# Contributing to VSCode Forest Pro 🌲

Thank you for your interest in contributing to VSCode Forest Pro! We welcome contributions from everyone and are grateful for every contribution.

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/akashsbadole/vscode-forest-pro.git`
3. **Install** dependencies: `npm install`
4. **Make** your changes
5. **Test** thoroughly
6. **Submit** a pull request

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Making Changes](#making-changes)
- [Testing](#testing)
- [Submitting Changes](#submitting-changes)
- [Style Guidelines](#style-guidelines)
- [Community](#community)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🤝 How to Contribute

### 🐛 Reporting Bugs

Before creating bug reports, please check existing issues as you might find out that you don't need to create one. When creating a bug report, include as many details as possible:

**Use this template:**

```markdown
**Describe the bug**
A clear description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Environment:**

- VS Code Version: [e.g. 1.85.0]
- Theme Version: [e.g. 1.0.0]
- OS: [e.g. macOS 14.0]
- Language: [e.g. JavaScript, Python]

**Additional context**
Add any other context about the problem here.
```

### ✨ Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Clear title** and description
- **Step-by-step description** of the suggested enhancement
- **Explain why** this enhancement would be useful
- **Screenshots or mockups** if applicable

### 🎨 Contributing to Theme Colors

When suggesting color changes:

1. **Provide hex values** for proposed colors
2. **Show before/after screenshots**
3. **Explain the reasoning** (accessibility, readability, aesthetic)
4. **Test with multiple languages**

### 📝 Improving Documentation

Documentation improvements are always welcome! This includes:

- README updates
- Code comments
- Wiki pages
- Examples and tutorials

## 🛠️ Development Setup

### Prerequisites

- **Node.js** 16+
- **npm** or **yarn**
- **VS Code** 1.74+
- **Git**

### Local Development

```bash
# Clone the repository
git clone https://github.com/akashsbadole/vscode-forest-pro.git
cd VSCode-forest-pro

# Install dependencies
npm install

# Install VS Code Extension Manager
npm install -g @vscode/vsce

# Create development build
npm run package

# Install locally for testing
code --install-extension VSCode-forest-pro-*.vsix
```

### Development Workflow

```bash
# Start development mode (watches for changes)
npm run dev

# Build production version
npm run build

# Run tests
npm test

# Lint code
npm run lint

# Format code
npm run format
```

## 🔄 Making Changes

### Branch Strategy

- **main** - Production ready code
- **develop** - Development branch
- **feature/\*** - New features
- **bugfix/\*** - Bug fixes
- **hotfix/\*** - Emergency fixes

<!-- ### Commit Convention
We use [Conventional Commits](https://www.conventionalcommits.org/):

```bash
# Features
git commit -m "feat: add support for PHP syntax highlighting"

# Bug fixes
git commit -m "fix: correct JavaScript string color in dark mode"

# Documentation
git commit -m "docs: update installation instructions"

# Refactoring
git commit -m "refactor: reorganize color token structure"

# Tests
git commit -m "test: add color contrast validation tests"

# Chores
git commit -m "chore: update dependencies"
``` -->

### Making Color Changes

#### 1. Understanding the Structure

```json
{
  "colors": {
    // UI colors for interface elements
    "editor.background": "#0D1B0F",
    "statusBar.foreground": "#7ED321"
  },
  "tokenColors": [
    // Syntax highlighting rules
    {
      "scope": ["comment"],
      "settings": {
        "foreground": "#6B8E73",
        "fontStyle": "italic"
      }
    }
  ]
}
```

#### 2. Color Guidelines

- **Maintain contrast ratios** ≥ 4.5:1 for normal text, ≥ 7:1 for professional use
- **Keep nature theme consistency** - earth tones, forest colors
- **Test with colorblind simulators**
- **Ensure readability** in both bright and dim environments

#### 3. Testing Colors

```bash
# Test with different languages
- JavaScript/TypeScript
- Python
- Rust/Go
- HTML/CSS
- JSON/YAML

# Test UI components
- Activity bar
- Sidebar
- Terminal
- Status bar
- Tabs
```

## 🧪 Testing

### Manual Testing Checklist

- [ ] **Languages**: Test syntax highlighting in 5+ languages
- [ ] **UI Elements**: Verify all interface components look correct
- [ ] **Terminal**: Check all 16 ANSI colors
- [ ] **Git Integration**: Test git decorations and diff views
- [ ] **Extensions**: Verify compatibility with popular extensions
- [ ] **Accessibility**: Use contrast checkers and screen readers

<!-- ### Automated Testing

```bash
# Run all tests
npm test

# Test color contrast
npm run test:contrast

# Validate JSON structure
npm run test:schema

# Check for missing tokens
npm run test:coverage
``` -->

## 📤 Submitting Changes

### Pull Request Process

1. **Update documentation** if needed
2. **Add/update tests** for your changes
3. **Ensure all tests pass**
4. **Follow the PR template**
5. **Request review** from maintainers

### PR Template

```markdown
## 🔍 Description

Brief description of changes

## 🎯 Type of Change

- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Refactoring

## 🧪 Testing

- [ ] Manual testing completed
- [ ] All automated tests pass
- [ ] Screenshots included (if UI changes)

## 📸 Screenshots

Before/after screenshots for visual changes

## 📋 Checklist

- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests added/updated
```

## 📏 Style Guidelines

### JSON Formatting

```json
{
  "colors": {
    // Group related colors together
    // Use descriptive comments
    "editor.background": "#0D1B0F",
    "editor.foreground": "#E8F5E8"
  }
}
```

### Color Naming

- Use **semantic names** over hex values
- Group **related colors** together
- Add **comments** for complex rules
- Maintain **consistent spacing**

### Documentation Style

- Use **clear headings** and structure
- Include **code examples**
- Add **screenshots** for visual changes
- Keep **language simple** and accessible

## 💬 Community

### Getting Help

- **GitHub Discussions** - Questions and ideas
- **GitHub Issues** - Bug reports and feature requests
- **Discord** - Real-time chat and support
- **Email** - Direct contact for sensitive issues

### Recognition

Contributors will be recognized in:

- **README.md** credits section
- **Release notes** for their contributions
- **Contributors** page
