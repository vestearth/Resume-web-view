# Contributing to Resume Web View

Thank you for your interest in contributing to Resume Web View! We welcome contributions from the community.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/your-username/Resume-web-view.git`
3. Create a new branch: `git checkout -b feature/your-feature-name`

## Development Guidelines

### Code Style

- Use 2 spaces for indentation
- Follow semantic HTML structure
- Use SCSS for styling (compile to CSS before committing)
- Write meaningful commit messages
- Test your changes across different browsers

### SCSS Development

If you're working with styles:

1. Edit files in the `css/` directory:
   - Modify `_earth.scss` for main styles
   - Use `resume_cv.scss` as the entry point
2. Compile SCSS to CSS:
   ```bash
   sass css/resume_cv.scss css/resume_cv.css
   ```
3. Test your changes by opening `index.html` in a browser

### JavaScript Development

- Follow ES6+ standards
- Comment complex functions
- Test animations and interactions
- Ensure cross-browser compatibility

## Testing

Before submitting your contribution:

1. Test in multiple browsers (Chrome, Firefox, Safari, Edge)
2. Check responsive design on different screen sizes
3. Verify all animations work correctly
4. Ensure no console errors

## Submitting Changes

1. Commit your changes with a descriptive message
2. Push to your fork: `git push origin feature/your-feature-name`
3. Create a Pull Request with:
   - Clear description of changes
   - Screenshots if applicable
   - List of browsers tested

## Types of Contributions

We welcome:

- Bug fixes
- New features
- Improved documentation
- Performance optimizations
- Accessibility improvements
- Code refactoring

## Questions?

Feel free to open an issue if you have questions or need help getting started!