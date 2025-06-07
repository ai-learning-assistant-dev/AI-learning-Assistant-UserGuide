# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a documentation repository for the AI Learning Assistant (AI学习助手), a learning tool that integrates AI capabilities with Obsidian note-taking software. The repository contains user guides and documentation for different versions of the software.

## Key Files and Structure

- `AI学习助手使用说明-软件版本V1.01.md` - User guide for version 1.01, with images in `images/` folder
- `AI学习助手1.1版本 使用文档.docx` - Word document for version 1.1 
- `AI学习助手1.1版本_使用文档.md` - Converted markdown version of 1.1 documentation
- `images/` - Screenshots and diagrams for v1.01 documentation
- `media/` - Extracted images from Word document conversion (when using pandoc --extract-media)

## Common Tasks

### Converting Word Documents to Markdown
Use pandoc with media extraction to preserve images:
```bash
pandoc "filename.docx" --extract-media=. -o "output.md"
```

### Image Path Management
- V1.01 documentation uses `images/` folder with descriptive Chinese filenames
- Converted Word docs create `media/` folder with generic `image1.png`, `image2.png` names
- When merging documents, ensure image paths are consistent

### Documentation Merging
When combining multiple markdown files:
1. Align image folder structures (`images/` vs `media/`)
2. Ensure heading levels are consistent
3. Maintain table of contents structure used in existing docs
4. Preserve Obsidian-specific syntax like `![[filename.png]]` and table-of-contents blocks

## Content Structure

The documentation covers:
- AI plugin usage (Copilot integration, custom personas)
- Voice recognition (ASR) deployment and configuration
- Text-to-speech (TTS) setup
- Multi-platform deployment (Windows CPU/CUDA, macOS)
- Obsidian plugin configuration and workflows

## Language and Localization

All documentation is in Chinese. The software supports both Windows and macOS platforms with different deployment packages for CPU and CUDA environments.