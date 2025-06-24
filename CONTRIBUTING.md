# Contributing to API Documentation Comparison Tool

First off, thank you for considering contributing to the API Documentation Comparison Tool! 🎉

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our commitment to creating a welcoming and inclusive environment. By participating, you are expected to uphold these standards:

- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community
- Show empathy towards other community members

## How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the [existing issues](https://github.com/Sam-May-Futurelab/API-Comparison-Tool/issues) to avoid duplicates.

When filing a bug report, please include:
- A clear and descriptive title
- Steps to reproduce the behavior
- Expected behavior vs actual behavior
- Screenshots (if applicable)
- Browser version and operating system
- Any error messages from the browser console

### 💡 Suggesting Enhancements

Enhancement suggestions are welcome! Please provide:
- A clear and descriptive title
- A detailed description of the proposed feature
- Explanation of why this enhancement would be useful
- Examples of how the feature would work
- Any relevant mockups or examples

### 🔧 Code Contributions

#### Good First Issues
Look for issues labeled `good first issue` or `help wanted` if you're new to the project.

#### Popular Contribution Areas
- **UI/UX Improvements**: Better responsive design, animations, accessibility
- **New Features**: Export functionality, dark mode, additional file formats
- **Performance**: Optimizations for large documents, memory usage
- **Documentation**: Improving README, adding tutorials, code comments
- **Testing**: Adding test cases, improving browser compatibility

## Development Setup

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor or IDE
- Basic knowledge of HTML, CSS, and JavaScript

### Getting Started
1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/API-Comparison-Tool.git
   cd API-Comparison-Tool
   ```

2. **Open the project**
   Simply open `index.html` in your browser - no build process required!

3. **Make your changes**
   Edit the `index.html` file directly

4. **Test your changes**
   - Test in multiple browsers
   - Test responsive design on different screen sizes
   - Verify all features work as expected

### Project Structure
```
api-comparison/
├── index.html          # Main application file
├── README.md          # Project documentation
├── LICENSE            # MIT License
├── CHANGELOG.md       # Version history
└── CONTRIBUTING.md    # This file
```

### Architecture Overview
- **Single File Application**: Everything is contained in `index.html`
- **No Build Process**: Direct browser execution
- **Vanilla JavaScript**: No frameworks, minimal dependencies
- **TailwindCSS**: Utility-first CSS via CDN
- **Highlight.js**: Syntax highlighting via CDN

## Pull Request Process

### Before Submitting
1. **Test thoroughly** across different browsers
2. **Check responsive design** on mobile and desktop
3. **Verify accessibility** features still work
4. **Update documentation** if needed
5. **Follow code style guidelines**

### Submitting Your PR
1. **Create a descriptive title**
   - ✅ Good: "Add dark mode toggle functionality"
   - ❌ Bad: "Fix stuff"

2. **Write a clear description**
   - What changes were made and why
   - Any breaking changes
   - Screenshots for UI changes
   - Testing instructions

3. **Reference related issues**
   - Use "Fixes #123" to automatically close issues
   - Use "Relates to #456" for related discussions

### Review Process
- Maintainers will review your PR within a few days
- You may be asked to make changes
- Once approved, your PR will be merged
- Your contribution will be credited in the changelog

## Style Guidelines

### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Include appropriate ARIA labels for accessibility
- Keep the single-file structure

### CSS (TailwindCSS)
- Use existing Tailwind utility classes when possible
- Add custom CSS only when necessary
- Maintain responsive design principles
- Follow the existing color scheme and spacing

### JavaScript
- Use modern ES6+ features
- Maintain consistent indentation (4 spaces)
- Add comments for complex logic
- Follow existing naming conventions
- Keep functions focused and small
- Handle errors gracefully

### Example Code Style
```javascript
function renderCommentsList(commentList, container) {
    container.innerHTML = '';
    
    if (commentList.length === 0) {
        container.innerHTML = '<p class="text-gray-500 text-sm">No comments yet.</p>';
        return;
    }
    
    commentList.forEach(comment => {
        const commentDiv = document.createElement('div');
        commentDiv.className = 'bg-gray-50 rounded-lg p-3 border border-gray-200';
        // ... rest of implementation
    });
}
```

### Commit Messages
Use clear, descriptive commit messages:
- ✅ `feat: add dark mode toggle button`
- ✅ `fix: resolve comment deletion bug in unified view`
- ✅ `docs: update installation instructions`
- ❌ `update stuff`
- ❌ `fix bug`

## Community

### Getting Help
- **GitHub Issues**: For bugs and feature requests
- **GitHub Discussions**: For questions and general discussion
- **README**: For usage instructions and examples

### Recognition
Contributors will be:
- Listed in the project's contributor section
- Mentioned in release notes for significant contributions
- Credited in the changelog

## Thank You! 🙏

Your contributions help make this tool better for everyone. Whether it's:
- Reporting a bug
- Suggesting a feature
- Improving documentation
- Writing code
- Helping other users

Every contribution matters and is appreciated!

---

*Happy coding!* 🚀
