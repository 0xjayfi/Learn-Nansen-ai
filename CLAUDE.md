# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a documentation repository for Nansen AI tutorials. The project aims to create a public wiki-style documentation site using GitHub Pages to help users get started with Nansen AI features including Token Screener, Smart Money, and Token God Mode.

## Repository Structure

The planned documentation structure follows this pattern:

```
docs/
├── index.md           # Home page
├── getting-started.md # Getting started guide
├── tutorials/
│   ├── token-screener.md
│   ├── smart-money.md
│   └── token-god-mode.md
└── faq.md
```

## Common Development Tasks

### Setting up GitHub Pages

1. Create the `docs/` folder structure in the root directory
2. Enable GitHub Pages in repository settings to publish from `main` branch `/docs` folder
3. Implement a Jekyll-based documentation theme (recommended: "Just the Docs" theme)

### Creating Documentation Pages

When creating new documentation pages:
- Use Markdown format (.md files)
- Include inter-page linking for wiki-style navigation (e.g., `[See Token Screener tutorial](tutorials/token-screener.md)`)
- Keep the initial version simple and iterate based on user feedback

### Jekyll Configuration

When setting up Jekyll for GitHub Pages:
1. Create a `docs/_config.yml` file for Jekyll configuration
2. Include theme configuration (e.g., `remote_theme: just-the-docs/just-the-docs`)
3. Configure navigation structure and sidebar

### Documentation Guidelines

- Focus on practical tutorials for Nansen AI features
- Structure content for easy navigation and discovery
- Use clear headings and sections
- Include examples and screenshots where helpful
- Link between related topics to build interconnected documentation

## GitHub Actions

The repository includes Claude Code Review workflows that:
- Automatically review pull requests using Claude
- Provide feedback on documentation quality and structure
- The workflow is configured in `.github/workflows/claude-code-review.yml`

## Python Environment

The project uses a Python virtual environment named `nansen-ai` (as specified in `.python-version`). This may be used for any documentation build scripts or automation tools in the future.

## Key Focus Areas

When working on this repository, prioritize:
1. Creating clear, user-friendly documentation for Nansen AI features
2. Building an intuitive navigation structure
3. Ensuring documentation is accessible via GitHub Pages
4. Maintaining consistency in documentation style and format