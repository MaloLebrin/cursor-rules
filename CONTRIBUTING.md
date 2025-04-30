# Contributing to Cursor AI Rules

Thank you for your interest in contributing to the Cursor AI Rules project! This document provides guidelines and instructions for contributing.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## How to Contribute

### 1. Fork and Clone

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/cursor-rules.git
   ```
3. Add the original repository as upstream:
   ```bash
   git remote add upstream https://github.com/ORIGINAL-OWNER/cursor-rules.git
   ```

### 2. Branching

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Keep your branch up to date:
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

### 3. Making Changes

#### Adding New Rules

1. Place new rules in the appropriate directory:
   - `nuxt/` for Nuxt.js specific rules
   - `typescript/` for TypeScript rules
   - `seo/` for SEO related rules

2. Follow the existing file naming conventions:
   - Use `.mdc` extension

3. Include in your rule:
   - Clear description
   - Examples (both positive and negative)
   - Rationale
   - Related rules (if applicable)

#### Updating Existing Rules

1. Maintain the existing format
2. Document the reason for changes
3. Update related rules if necessary
4. Ensure backward compatibility

### 4. Documentation

1. Update the README.md if your changes affect the project structure
2. Keep documentation clear and concise
3. Use proper Markdown formatting
4. Include examples where appropriate

### 5. Testing

1. Test your rules with Cursor AI
2. Verify rule effectiveness
3. Document edge cases
4. Update rules based on testing results

### 6. Committing Changes

1. Write clear, descriptive commit messages
2. Reference issues and pull requests in commit messages
3. Keep commits focused and atomic
4. Follow the commit message format:
   ```
   type(scope): description

   [optional body]

   [optional footer]
   ```

### 7. Pull Request Process

1. Update the README.md with details of changes if needed
2. Update the documentation with any new rules or changes
3. The PR will be merged once you have the sign-off of at least one maintainer

## Style Guide

### Markdown Files

1. Use proper Markdown formatting
2. Keep lines under 100 characters
3. Use proper heading hierarchy
4. Include a table of contents for long documents

### Code Examples

1. Use proper code blocks with language specification
2. Keep examples simple and clear
3. Include comments where necessary
4. Follow the language's style guide

## Review Process

1. All submissions require review
2. We use GitHub pull requests for this purpose
3. Check the automated checks
4. Address any feedback from maintainers

## Getting Help

If you need help:
1. Check the existing documentation
2. Open an issue
3. Contact the maintainers

## Recognition

Contributors will be:
1. Listed in the README.md
2. Acknowledged in release notes
3. Given proper credit for their work

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License. 
