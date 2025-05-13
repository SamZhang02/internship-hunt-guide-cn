# Contributing

Thank you for your interest in contributing to this project! This guide outlines how to contribute to our static website built with MkDocs and deployed via GitHub Pages.

## Getting Started

1. Fork the repository
2. Install dependencies as specified in `requirements.txt`

```shell
pip install -r requirements.txt
```

3. Create a new branch: `git checkout -b feature/your-feature-name` or `fix/issue-description`

## Types of Contributions

### Small Changes (Typos, Minor Edits)

For small issues like typos, grammar corrections, or minor content updates:

- Feel free to open a Pull Request directly
- No need to create an issue first
- Please include a clear description of the change

### Large Changes (New Content, Restructuring)

For significant changes like:

- Adding new chapters/sections
- Restructuring content
- Major rewrites

Please:

1. Open a GitHub issue first to discuss the proposed changes
2. Wait for feedback from maintainers
3. Create a PR once the approach is agreed upon

## How to Contribute

1. Make your changes in your feature branch
2. Test locally by running: `mkdocs serve`
3. Ensure your changes don't break the build
4. Commit your changes with a clear, descriptive message
5. Push to your fork
6. Open a Pull Request

## Pull Request Guidelines

- Use a clear, descriptive title
- Include a detailed description of your changes
- Reference any related issues (e.g., "Fixes #123")
- Make sure your branch is up to date with the main branch
- Include screenshots for UI/formatting changes (If applicable)

## File Structure

```
docs/
├── index.md
├── chapter1.md
├── chapter2.md
└── assets/
└───── image1.png
└───── image2.png
```

Chapters are organized within `mkdocs.yaml`, and markdown files and assets are stored within `docs`.
