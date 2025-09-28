# VSCode Forest Pro 🌲

> **Premium Professional Nature-Inspired VS Code Theme**

[![Version](https://img.shields.io/badge/version-2.0.0-brightgreen)](https://marketplace.visualstudio.com/items?itemName=akashbadole.VSCode-forest-pro)

[![Downloads](https://img.shields.io/badge/downloads-100+-blue)](https://marketplace.visualstudio.com/items?itemName=akashbadole.VSCode-forest-pro)

[![Rating](https://img.shields.io/badge/rating-5%E2%AD%90-yellow)](https://marketplace.visualstudio.com/items?itemName=akashbadole.VSCode-forest-pro)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

VSCode Forest Pro transforms your coding environment into a sophisticated, nature-inspired workspace with professional-grade syntax highlighting and premium UI styling. Built for developers who demand both beauty and functionality.

## Share your suggestion

- https://docs.google.com/forms/d/e/1FAIpQLSd4jS2XuGAUl0aw-ou0viisV6s_DD2Mm6RVjw7HbV-6ANtwSQ/viewform?usp=preview

## ✨ Key Features

### 🎨 **Premium Visual Design**

- **Ultra-dark background** (`#0A1F15`) - Reduces eye strain during long coding sessions
- **Enhanced function visibility** (`#7FDB81`) - Bright green for improved readability
- **Neon nature accents** - Vibrant greens, golden highlights, sky blues
- **7:1+ contrast ratios** - Professional accessibility standards
- **Smooth gradients & glows** - Modern, premium aesthetic

### ⚡ **Advanced Semantic Highlighting**

- **Smart variable recognition** - Different colors for readonly, static, and library variables
- **Method intelligence** - Static methods, constructors, destructors get unique styling
- **Type system mastery** - Generics, interfaces, enums, type parameters
- **Decorator detection** - Python `@decorators`, TypeScript decorators, Rust macros

### 🚀 **Professional Language Support**

#### **Frontend Technologies**

- **JavaScript/TypeScript** - ES6+, JSX, TSX, React components
- **HTML5** - Web components, custom elements, semantic tags
- **CSS3/SCSS/LESS** - Modern properties, pseudo-selectors, CSS-in-JS
- **JSON/YAML** - Configuration files, API responses

#### **Backend & Systems**

- **Python** - Magic methods, decorators, self/cls, type hints
- **Rust** - Lifetimes, ownership, macros, traits
- **Go** - Interfaces, goroutines, channels, modules
- **C/C++** - Preprocessor directives, templates, STL
- **Java/C#** - OOP concepts, generics, LINQ

#### **Data & Query Languages**

- **SQL** - Advanced queries, stored procedures, functions
- **GraphQL** - Schema definitions, queries, mutations
- **MongoDB** - Aggregation pipelines, document queries

#### **DevOps & Scripting**

- **Shell/Bash** - Variable interpolation, built-in commands
- **Docker** - Dockerfile syntax, multi-stage builds
- **Kubernetes** - YAML manifests, custom resources

### 💎 **Luxury UI Components**

#### **Terminal Excellence**

- **16-color ANSI palette** - Nature-inspired terminal colors
- **Smart cursor styling** - Golden highlight with smooth animations
- **Selection theming** - Consistent with editor selections
- **Command decorations** - Success/error visual feedback

#### **Professional Interface**

- **Premium status bar** - Debugging states, git info, extensions
- **Elite activity bar** - Smooth hover effects, badge styling
- **Smart sidebar** - File explorer, search, git integration
- **Advanced tabs** - Modified indicators, close button theming

### 🔧 **Developer Tools Integration**

#### **Git Workflow**

- **8 Git status colors** - Added, modified, deleted, ignored, conflicting, submodules
- **Merge conflict resolution** - Clear visual separation for conflicts
- **Blame annotations** - Subtle, non-intrusive styling
- **Diff highlighting** - Side-by-side and inline comparisons

#### **Debugging & Testing**

- **Breakpoint styling** - Clear, professional indicators
- **Debug console** - Themed output with syntax highlighting
- **Test results** - Pass/fail indicators with proper contrast
- **Error highlighting** - Squiggles, hovers, problem panel

## 🎯 Installation

### Method 1: VS Code Marketplace (Recommended)

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X`)
3. Search for "VSCode Forest Pro"
4. Click Install
5. Go to `File > Preferences > Color Theme`
6. Select "VSCode Forest Pro"

### Method 2: Manual Installation

1. Download the `.vsix` file from releases
2. Open VS Code
3. Run `Ctrl+Shift+P` and type "Extensions: Install from VSIX"
4. Select the downloaded file
5. Reload VS Code
6. Activate the theme
<!--

### Method 3: Development Setup

````bash
# Clone the repository
git clone https://github.com/akashsbadole/vscode-forest-pro.git
cd VSCode-forest-pro

# Install dependencies
npm install

# Package the theme
vsce package

# Install locally
code --install-extension VSCode-forest-pro-*.vsix
``` -->

<!-- ## 🌟 Screenshots

### JavaScript/TypeScript

![JavaScript Screenshot](./screenshots/javascript.png)
_Advanced syntax highlighting with enhanced function visibility_ -->

<!-- ### Python

![Python Screenshot](./screenshots/python.png)
_Decorators, magic methods, and type hints with improved readability_

### Dark Theme

![Dark Theme Screenshot](./screenshots/dark-theme.png)
_Enhanced dark theme with brighter function colors_ -->

## ⚙️ Recommended Settings

Add these to your VS Code `settings.json` for the optimal experience:

```json
{
  // Font settings for premium experience
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,

  // Enhanced syntax highlighting
  "editor.semanticHighlighting.enabled": true,
  "editor.semanticTokenColorCustomizations": {
    "[VSCode Forest Pro]": {
      "enabled": true
    }
  },

  // Bracket pair colorization
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",

  // Minimap enhancements
  "editor.minimap.enabled": true,
  "editor.minimap.showSlider": "always",
  "editor.minimap.renderCharacters": false,

  // Terminal theming
  "terminal.integrated.fontFamily": "'Fira Code', monospace",
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.lineHeight": 1.4,

  // Workbench theming
  "workbench.iconTheme": "material-icon-theme",
  "workbench.tree.indent": 16,
  "workbench.tree.renderIndentGuides": "always"
}
```

## 🎨 Color Palette

### Primary Colors

| Color                                                    | Hex       | Usage         |
| -------------------------------------------------------- | --------- | ------------- |
| ![#0A1F15](https://via.placeholder.com/20/0A1F15/0A1F15) | `#0A1F15` | Background    |
| ![#E8F5E8](https://via.placeholder.com/20/E8F5E8/E8F5E8) | `#E8F5E8` | Foreground    |
| ![#7FDB81](https://via.placeholder.com/20/7FDB81/7FDB81) | `#7FDB81` | Functions     |
| ![#7ED321](https://via.placeholder.com/20/7ED321/7ED321) | `#7ED321` | Primary Green |
| ![#F5A623](https://via.placeholder.com/20/F5A623/F5A623) | `#F5A623` | Golden Orange |
| ![#4A90E2](https://via.placeholder.com/20/4A90E2/4A90E2) | `#4A90E2` | Sky Blue      |

### Accent Colors

| Color                                                    | Hex       | Usage      |
| -------------------------------------------------------- | --------- | ---------- |
| ![#FFD700](https://via.placeholder.com/20/FFD700/FFD700) | `#FFD700` | Highlights |
| ![#50E3C2](https://via.placeholder.com/20/50E3C2/50E3C2) | `#50E3C2` | Strings    |
| ![#9013FE](https://via.placeholder.com/20/9013FE/9013FE) | `#9013FE` | Keywords   |
| ![#E91E63](https://via.placeholder.com/20/E91E63/E91E63) | `#E91E63` | Decorators |
| ![#FF6B35](https://via.placeholder.com/20/FF6B35/FF6B35) | `#FF6B35` | Errors     |

## 🛠️ Customization

### Override Theme Colors

Add to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[VSCode Forest Pro]": {
      "editor.background": "#0A1F15",
      "editor.foreground": "#E8F5E8"
      // Add more customizations...
    }
  },
  "editor.tokenColorCustomizations": {
    "[VSCode Forest Pro]": {
      "comments": "#6B8E73",
      "strings": "#40D3B2",
      "functions": "#7FDB81"
      // Add more token customizations...
    }
  }
}
```

## 🐛 Known Issues

- **Issue #1**: Some semantic tokens might not appear in older TypeScript versions
  - **Solution**: Update TypeScript to 4.5+ and restart VS Code
- **Issue #2**: Terminal colors might appear different on some systems
  - **Solution**: Ensure true color support is enabled in your terminal

## 🔄 Changelog

### Version 2.0.0

- 🎉 Enhanced dark theme with improved function visibility
- ✨ Updated function colors to brighter greens for better readability
- 🎨 Darker editor background (#0A1F15) for improved contrast
- 🖥️ Enhanced terminal color palette
- 🔧 Improved UI component styling

### Version 1.0.0

- 🎉 Initial release
- ✨ Premium semantic highlighting for 15+ languages
- 🎨 Complete UI theming with 200+ color tokens
- 🖥️ Advanced terminal color palette
- 🔧 Git integration with 8 status colors

[View full changelog](CHANGELOG.md)

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Reporting Issues
https://docs.google.com/forms/d/e/1FAIpQLSd4jS2XuGAUl0aw-ou0viisV6s_DD2Mm6RVjw7HbV-6ANtwSQ/viewform?usp=preview


## 📄 License

This theme is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Nature Photography** - Color inspiration from forest ecosystems
- **VS Code Team** - For the extensible theming system
- **Community** - For feedback and suggestions
- **Contributors** - Thank you for making this theme better

## 📞 Support

- 📧 **Email**: skywebsitedev@gmail.com
<!-- - 💬 **Discord**: [Join our community](https://discord.gg/VSCode-forest-pro) -->
- 🐛 **Issues**: [GitHub Issues](https://github.com/akashsbadole/vscode-forest-pro/issues)
- 📖 **Documentation**: [Wiki](https://github.com/akashsbadole/vscode-forest-pro/wiki)

## 🌟 Show Your Support

If you love VSCode Forest Pro, please:

- ⭐ **Star** the repository
- 📝 **Leave a review** on the VS Code Marketplace
- 🐦 **Share** on social media with `#VSCodeForestPro`
<!-- - ☕ **Buy us a coffee** on [Ko-fi](https://ko-fi.com/VSCodeforestpro) -->

---
````
