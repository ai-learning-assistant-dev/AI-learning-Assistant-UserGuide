# Changelog

All notable changes to the AI Learning Assistant User Guide will be documented in this file.

## [Unreleased] - 2025-01-07

### Removed
- **Duplicate Documentation Files** - Cleaned up redundant markdown files after merge
  - Removed `AI学习助手1.1版本_使用文档.md` (merged into complete guide)
  - Removed `AI学习助手使用说明-软件版本V1.01.md` (merged into complete guide)  
  - Removed duplicate `media/` folder (images consolidated in `images/`)

### Changed
- **Enhanced .gitignore** - Added comprehensive ignore patterns for:
  - Operating system files (.DS_Store, Thumbs.db)
  - IDE/editor temporary files
  - Backup and temporary files
  - Development/testing directories
  - Obsidian workspace files
- **Improved README.md** - Restructured with clear navigation, feature overview, and quick start guide

## [1.0.0] - 2025-01-07

### Added
- **Complete User Documentation** - Merged V1.01 and V1.1 documentation into comprehensive guide
- **Unified Image Management** - Consolidated images from `media/` and `images/` folders into single `images/` directory
- **Version-based Structure** - Organized documentation by version chapters:
  - Part 1: Basic Features (V1.01) - Installation, configuration, basic AI functionality
  - Part 2: New Features (V1.1) - Custom personas, multi-text reference, ASR, TTS
  - Part 3: Additional Features - LM Studio, SiliconFlow integration
- **Enhanced AI Features Documentation**:
  - Custom AI persona creation with tag-based design
  - Multi-document text reference functionality  
  - Voice recognition (ASR) with CPU/CUDA deployment
  - Text-to-speech (TTS) with multiple model options
- **Configuration Guides**:
  - LM Studio local model setup and usage
  - SiliconFlow cloud API integration
  - Obsidian plugin configuration details
- **Development Documentation** - Added CLAUDE.md for Claude Code guidance

### Changed
- **Image Path Standardization** - Updated all image references to use unified `./images/` path
- **Document Structure** - Reorganized content from separate version docs into cohesive chapters
- **Table Formatting** - Converted complex tables to markdown format for better readability

### Technical Details
- Converted Word document (`.docx`) to Markdown using pandoc with media extraction
- Merged image assets from multiple sources into centralized folder
- Updated all image references to maintain consistency across documentation
- Preserved Obsidian-specific syntax and formatting throughout

### Files Added
- `AI学习助手完整使用文档.md` - Complete merged documentation
- `CLAUDE.md` - Development guidance for Claude Code
- `images/` - Unified image directory with 80+ screenshots and diagrams
- `media/` - Extracted images from Word document conversion

### Files Included
- `AI学习助手使用说明-软件版本V1.01.md` - Original V1.01 documentation
- `AI学习助手1.1版本 使用文档.docx` - Original V1.1 Word document
- `AI学习助手1.1版本_使用文档.md` - Converted V1.1 markdown