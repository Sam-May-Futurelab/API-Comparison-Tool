# API Documentation Comparison Tool

A modern, single-file web application for comparing different versions of API documentation with advanced commenting and diff visualization capabilities.

![API Comparison Tool](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-TailwindCSS-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

## 🚀 Features

### Core Functionality
• **Side-by-side comparison** - Two panels showing different API versions
• **Automatic difference highlighting** - Added (green), removed (red), and changed (yellow) content
• **Unified/Split view toggle** - Switch between side-by-side and unified diff views
• **Floating header** - Fixed position with version selectors
• **Responsive design** - Panels stack vertically on mobile (using Tailwind's grid system)
• **Line number clicking** - Click any line number to add comments
• **Comment indicators** - Blue circles show comment count per line
• **Version selection** - Dropdown menus to select different versions
• **Syntax preservation** - Maintains formatting and structure of API documentation

### Advanced Features
• **Custom Documentation Loading** - Paste and load your own API documentation with custom version naming instead of being limited to hardcoded samples
• **Interactive Comment Management** - View, add, edit, and delete comments with timestamps, plus quick comment addition directly from the comment viewer modal
• **Modern UI/UX Design** - Beautiful gradient backgrounds, glass-effect header, custom fonts (Inter + JetBrains Mono), and smooth animations throughout
• **Smart Notification System** - Elegant custom notifications with slide animations replace jarring browser alerts, featuring different styles for warnings, success, and errors
• **Enhanced Visual Feedback** - Improved hover states, selection highlighting, custom scrollbars, and professional color schemes for better user experience
• **Advanced Comment Viewing** - Click comment indicators to see all comments for a line, with version-specific filtering in unified view and bulk comment management
• **Seamless Modal Experience** - Multiple modals with backdrop blur effects, keyboard shortcuts (ESC to close), and click-outside-to-close functionality
• **Live Version Management** - Real-time version name updates in headers and comparison panels as you type in the input fields
• **Professional Code Highlighting** - Robust syntax highlighting with error handling and monospace font consistency across all code displays
• **Accessibility Features** - Keyboard navigation support, proper focus management, and screen reader friendly interface elements

## 🎯 Use Cases

- **API Version Migration** - Compare different versions of your API documentation to identify breaking changes
- **Documentation Review** - Add comments and notes to specific lines for team collaboration
- **Change Tracking** - Visualize what's been added, removed, or modified between API versions
- **Documentation Quality Assurance** - Review and annotate API documentation before publication
- **Developer Onboarding** - Help new team members understand API evolution and changes

## 🚀 Quick Start

1. **Download or Clone**
   ```bash
   git clone https://github.com/Sam-May-Futurelab/API-Comparison-Tool.git
   cd API-Comparison-Tool
   ```

2. **Open in Browser**
   Simply open `index.html` in any modern web browser. No installation or build process required!

3. **Load Your Documentation**
   - Click "Load Documentation" button
   - Paste your API documentation in the text areas
   - Set custom version names
   - Click "Load Documentation" to start comparing

## 📖 How to Use

### Loading Documentation
1. Click the **"Load Documentation"** button in the header
2. Paste your API documentation content in the provided text areas
3. Set custom version names (e.g., "v1.2.0", "v2.0.0")
4. Click **"Load Documentation"** to apply changes

### Viewing Differences
- **Split View**: Side-by-side comparison (default)
- **Unified View**: Git-style unified diff format
- Toggle between views using the **"Switch to Unified/Split View"** button

### Adding Comments
1. Click on line numbers to select them (they'll highlight in blue)
2. Click **"Add Comment"** button
3. Type your comment and click **"Save"**
4. Comments appear as numbered blue circles next to line numbers

### Managing Comments
- Click on comment indicators (blue circles) to view all comments for that line
- Add new comments directly in the comment viewer
- Delete comments using the delete button
- Comments include timestamps and version information

### Keyboard Shortcuts
- **ESC** - Close any open modal
- **Click outside modal** - Close modal
- **Enter** - Submit comment (when in comment input field)

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic markup
- **TailwindCSS** - Modern utility-first CSS framework
- **Vanilla JavaScript** - No external dependencies
- **Highlight.js** - Syntax highlighting for code blocks
- **Google Fonts** - Inter and JetBrains Mono fonts

### Browser Compatibility
- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with ES6+ support

### File Structure
```
api-comparison/
├── index.html          # Single-file application
├── README.md          # This file
└── LICENSE            # MIT License
```

## 🎨 Customization

The tool is designed to be easily customizable:

### Styling
- Modify the CSS variables in the `<style>` section
- Change gradient colors, fonts, or spacing
- TailwindCSS classes can be updated for different themes

### Functionality
- Add new diff algorithms in the `computeDiff()` function
- Extend comment features in the comment management functions
- Add export/import functionality for comments

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Ideas
- Export comments to JSON/CSV
- Import documentation from URLs
- Dark mode theme
- Additional syntax highlighting languages
- Print-friendly view
- Keyboard navigation improvements

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TailwindCSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Highlight.js](https://highlightjs.org/) for syntax highlighting
- [Google Fonts](https://fonts.google.com/) for the beautiful typography
- The open-source community for inspiration and best practices

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/Sam-May-Futurelab/API-Comparison-Tool/issues) page
2. Create a new issue with detailed information
3. Include browser version and steps to reproduce

## 🔄 Version History

- **v1.0.0** - Initial release with core comparison and commenting features

---

Made with ❤️ by [Sam May](https://github.com/Sam-May-Futurelab)
