# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML presentation website about Claude Code implementation, written in Japanese. It's designed to be deployed on GitHub Pages and contains a single-page interactive slideshow with 8 slides covering Claude Code features, installation, and use cases.

## Architecture

- **Technology Stack**: Pure HTML, CSS, and JavaScript (no external dependencies)
- **Structure**: Single-page application with all styles and scripts embedded inline
- **Main File**: `index.html` - contains the complete presentation with embedded CSS and JavaScript
- **Deployment**: GitHub Pages static site

## Key Features

The presentation includes:
- Interactive slideshow with keyboard navigation (arrow keys, spacebar)
- Responsive design with CSS Grid and Flexbox
- Smooth animations and transitions
- Slide counter and navigation controls
- Japanese content about Claude Code implementation

## Development

Since this is a static HTML file with no build process:

- **No build commands** - the site is ready to deploy as-is
- **No dependencies** - everything is self-contained in index.html
- **No tests** - static presentation content
- **No linting setup** - pure HTML/CSS/JavaScript

## File Structure

- `index.html` - Main presentation file (contains all HTML, CSS, and JavaScript)
- `README.md` - Basic project description
- `.claude/settings.local.json` - Claude Code configuration with restricted permissions

## Making Changes

When editing the presentation:
- All modifications should be made directly to `index.html`
- The file contains three main sections: HTML structure, CSS styles (in `<style>` tags), and JavaScript functionality (in `<script>` tags)
- Preserve the existing slide structure and navigation functionality
- Content is in Japanese - maintain language consistency