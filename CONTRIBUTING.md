# Contributing to Geeks UI Website

🎉 **Thank you for your interest in contributing to the Geeks UI Framework website!** 🎉

We welcome contributions from the community and are excited to work with you to make the Geeks UI website even better. This document outlines the process for contributing to this project.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Contribution Guidelines](#contribution-guidelines)
- [Reporting Issues](#reporting-issues)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Testing](#testing)
- [Community](#community)

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](https://github.com/Geeks-UI-Css-Framework/Geeks_UI/blob/main/CODE_OF_CONDUCT.md). Please read it before contributing.

## 🚀 Getting Started

### Prerequisites

Before contributing, make sure you have:

- **Node.js** (version 14.0.0 or higher)
- **npm** (version 6.0.0 or higher)
- **Git** for version control
- A code editor (VS Code recommended)

### Fork and Clone

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/geeksui.github.io.git
   cd geeksui.github.io
   ```

3. **Add the upstream repository**:
   ```bash
   git remote add upstream https://github.com/Geeks-UI-Css-Framework/geeksui.github.io.git
   ```

## 🛠️ Development Setup

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the development server**:
   ```bash
   npm run dev
   ```
   This will start a live-reload server at `http://localhost:3000`

3. **Alternative development options**:
   ```bash
   npm start          # Start with http-server
   npm run serve      # Start with serve
   ```

## 🤝 How to Contribute

### Types of Contributions

We welcome several types of contributions:

- 🐛 **Bug fixes** - Fix broken links, layout issues, or functionality
- ✨ **Feature additions** - New sections, improved UI/UX, animations
- 📚 **Documentation** - Improve README, add code comments, update guides
- 🎨 **Design improvements** - Better styling, responsive design, accessibility
- 🔧 **Performance** - Optimize loading times, image compression, code optimization
- 🧪 **Testing** - Add validation tests, cross-browser testing

### What We're Looking For

- **Responsive design improvements**
- **Accessibility enhancements** (ARIA labels, keyboard navigation)
- **Performance optimizations**
- **Cross-browser compatibility fixes**
- **Mobile experience improvements**
- **Content updates** for new Geeks UI versions
- **Interactive component demos**
- **SEO improvements**

## 📝 Contribution Guidelines

### Before You Start

1. **Check existing issues** to see if your idea is already being worked on
2. **Create an issue** to discuss major changes before implementing
3. **Keep changes focused** - one feature or fix per pull request
4. **Follow our coding standards** (see Style Guide below)

### Commit Guidelines

We follow conventional commit format:

```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: CSS/styling changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```bash
git commit -m "feat: add dark mode toggle component"
git commit -m "fix: resolve mobile navigation overflow issue"
git commit -m "docs: update installation instructions"
git commit -m "style: improve hero section gradient animation"
```

## 🐛 Reporting Issues

When reporting bugs or requesting features:

### Bug Reports
```markdown
**Bug Description:**
Clear description of the issue

**Steps to Reproduce:**
1. Go to...
2. Click on...
3. See error

**Expected Behavior:**
What should have happened

**Screenshots:**
If applicable, add screenshots

**Environment:**
- Browser: [e.g., Chrome 122]
- Device: [e.g., iPhone 12, Desktop]
- Screen size: [e.g., 1920x1080]
```

### Feature Requests
```markdown
**Feature Description:**
Clear description of the proposed feature

**Use Case:**
Why would this feature be useful?

**Proposed Solution:**
How would you implement this?

**Alternatives:**
Any alternative solutions considered?
```

## 🔄 Pull Request Process

### 1. Prepare Your Changes

```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Make your changes
# ... edit files ...

# Test your changes
npm run lint:html
npm run validate

# Commit your changes
git add .
git commit -m "feat: add your feature description"
```

### 2. Sync with Upstream

```bash
# Fetch latest changes
git fetch upstream

# Merge upstream changes
git checkout main
git merge upstream/main

# Rebase your feature branch
git checkout feature/your-feature-name
git rebase main
```

### 3. Push and Create PR

```bash
# Push your branch
git push origin feature/your-feature-name

# Create a pull request on GitHub
```

### 4. PR Checklist

- [ ] ✅ **Tested locally** - Changes work as expected
- [ ] 📱 **Mobile responsive** - Tested on different screen sizes
- [ ] 🌐 **Cross-browser** - Tested in Chrome, Firefox, Safari, Edge
- [ ] ♿ **Accessibility** - Proper ARIA labels, keyboard navigation
- [ ] 📝 **Documentation** - Updated if necessary
- [ ] 🏷️ **Descriptive title** - Clear PR title and description
- [ ] 🔗 **Linked issues** - Reference related issues with `Fixes #123`

## 🎨 Style Guide

### HTML Standards
- Use **semantic HTML5** elements
- Include proper **meta tags** for SEO
- Ensure **accessibility** with ARIA labels
- Use **proper heading hierarchy** (h1 → h2 → h3)

### CSS Standards
- Follow **mobile-first** responsive design
- Use **CSS custom properties** for consistency
- Maintain **consistent spacing** using the framework's system
- Prefer **flexbox and grid** over floats
- Use **meaningful class names**

### JavaScript Standards
- Write **vanilla JavaScript** (no jQuery)
- Use **modern ES6+** syntax
- Include **proper error handling**
- Add **comments** for complex logic

### Performance Guidelines
- **Optimize images** (use WebP when possible)
- **Minimize HTTP requests**
- **Use efficient CSS selectors**
- **Defer non-critical JavaScript**

## 🧪 Testing

### Manual Testing Checklist

- [ ] **Desktop browsers**: Chrome, Firefox, Safari, Edge
- [ ] **Mobile devices**: iOS Safari, Chrome Mobile
- [ ] **Screen readers**: Test with VoiceOver or NVDA
- [ ] **Keyboard navigation**: Tab through all interactive elements
- [ ] **Print styles**: Check print preview

### Automated Testing

```bash
# HTML validation
npm run validate

# HTML linting
npm run lint:html

# Accessibility testing (if available)
npm run a11y
```

## 🌟 Recognition

Contributors will be recognized in:
- **GitHub contributors** list
- **Project documentation**
- **Community acknowledgments**

## 💬 Community

### Getting Help

- **GitHub Discussions**: [Project discussions](https://github.com/Geeks-UI-Css-Framework/Geeks_UI/discussions)
- **Issues**: For bug reports and feature requests
- **Email**: [joeycadieux161@gmail.com](mailto:joeycadieux161@gmail.com)

### Community Guidelines

- **Be respectful** and inclusive
- **Help others** learn and grow
- **Share knowledge** and best practices
- **Provide constructive** feedback

## 📄 License

By contributing, you agree that your contributions will be licensed under the [MIT License](https://github.com/Geeks-UI-Css-Framework/Geeks_UI/blob/main/LICENSE).

## 🙏 Thank You

Thank you for contributing to Geeks UI! Your efforts help make the web more beautiful and accessible for everyone.

---

**Questions?** Feel free to reach out by [creating an issue](https://github.com/Geeks-UI-Css-Framework/geeksui.github.io/issues) or contacting us at [joeycadieux161@gmail.com](mailto:joeycadieux161@gmail.com).

**Happy contributing! 🎉**
