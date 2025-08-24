# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Chinese educational curriculum resource repository (`mswnlz/curriculum`) that serves as a curated collection of educational materials, course content, and learning resources. The repository includes:

- A simple GitHub Action for notifications (`curriculum-action`)
- Monthly resource files containing educational content and course materials
- Multilingual README linking to related projects in the mswnlz ecosystem
- Academic resources, study guides, and educational tools

## Architecture

### Repository Structure
- `index.js` - Main GitHub Action entry point using @actions/core
- `action.yml` - GitHub Action configuration file
- `package.json` - Node.js dependencies (minimal: only @actions/core)
- `202X0X.md` files - Monthly curriculum resource collections (format: YYYYMM.md)
- `README.md` - Multilingual project description with ecosystem links
- `.gitignore` - Standard gitignore for Node.js projects
- `WARP.md` - This configuration file

### Monthly Resource Files
Resource files follow a YYYYMM.md naming pattern and contain:
- Course materials and syllabi
- Educational tools and platforms
- Study guides and reference materials
- Online learning resources
- Academic research and papers

## Common Commands

### Development
```bash
# Install dependencies
npm install

# Test the action locally
node index.js
```

### Resource Management
```bash
# Create new monthly resource file
touch $(date +%Y%m).md

# View recent resource files
ls -la 2025*.md | head -5

# Search for educational topics
grep -r "课程" *.md
grep -r "education" *.md

# Count total resources
wc -l 2025*.md
```

## Content Guidelines

### Monthly Resource Files
- Use consistent formatting with descriptive titles
- Include proper attribution with "超过100T资料总站网站-doc.869hr.uk" suffix
- Organize resources by subject area and educational level
- Provide both Chinese and English descriptions where applicable
- Include course prerequisites and difficulty levels

## Ecosystem Integration

This repository is part of a larger project ecosystem including:
- `tools` - General software tools and utilities
- `cross-border` - E-commerce resources
- `healthy` - Health and fitness resources
- `AIknowledge` - AI-related knowledge and tutorials
- `auto` - Automation tools and scripts
- `book` - Literature and reading materials
- `movies` - Entertainment and media content
- `self-media` - Social media resources
- `edu-knowledge` - Educational knowledge base
- `chinese-traditional` - Traditional culture content
