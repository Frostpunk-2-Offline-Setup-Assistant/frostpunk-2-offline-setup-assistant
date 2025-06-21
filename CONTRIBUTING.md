# Contributing to Frostpunk 2 Offline Setup Assistant

🎉 Thank you for your interest in contributing to the Frostpunk 2 Offline Setup Assistant! We welcome contributions from the community and are grateful for your help in making this tool better for everyone.

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create** a new branch for your feature
4. **Make** your changes
5. **Test** your changes thoroughly
6. **Submit** a pull request

## 📋 Ways to Contribute

### 🐛 Bug Reports
Found a bug? Help us fix it by:
- Checking if the bug has already been reported
- Creating a detailed issue with reproduction steps
- Include your system specifications
- Attach logs or screenshots if applicable

### 💡 Feature Requests
Have an idea for improvement?
- Check if someone else has suggested it
- Open an issue with the "enhancement" label
- Describe the feature and its benefits
- Explain why it would be useful for other users

### 🔧 Code Contributions
Ready to write some code?
- Start with "good first issue" labeled issues
- Follow our coding standards
- Write tests for new features
- Update documentation as needed

### 📝 Documentation
Help improve our docs:
- Fix typos or unclear explanations
- Add missing documentation
- Create tutorials or guides
- Translate to other languages

### 🌍 Translations
Help make the assistant accessible worldwide:
- Translate UI text to your language
- Review existing translations
- Add cultural adaptations where needed

## 🛠️ Development Setup

### Prerequisites
- **Git** - Version control
- **Node.js** v18+ - JavaScript runtime
- **Python** 3.8+ - Backend scripts
- **7-Zip** - Archive handling
- **Visual Studio Code** (recommended)

### Installation
```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/frostpunk-2-offline-setup-assistant
cd frostpunk-2-offline-setup-assistant

# Install dependencies
npm install
pip install -r requirements.txt

# Setup development environment
npm run setup-dev

# Start development server
npm run dev
```

### Project Structure
```
frostpunk-2-offline-setup-assistant/
├── src/                    # Source code
│   ├── installer/         # Installation scripts
│   ├── ui/               # User interface
│   ├── config/           # Configuration management
│   └── utils/            # Utility functions
├── docs/                 # Documentation
├── tests/                # Test files
├── assets/               # Images, icons, etc.
├── locales/              # Translation files
└── build-tools/          # Build scripts
```

## 🎯 Development Guidelines

### Code Style
- **JavaScript**: Use ESLint configuration
- **Python**: Follow PEP 8 standards
- **Indentation**: 2 spaces for JS, 4 for Python
- **Line Length**: Max 100 characters
- **Comments**: Write clear, concise comments

### Naming Conventions
- **Variables**: camelCase (JS) / snake_case (Python)
- **Functions**: camelCase (JS) / snake_case (Python)
- **Classes**: PascalCase
- **Constants**: UPPER_SNAKE_CASE
- **Files**: kebab-case for components

### Git Workflow
1. **Branch Naming**:
   - `feature/add-new-feature`
   - `fix/resolve-bug-issue`
   - `docs/update-readme`
   - `refactor/improve-code-structure`

2. **Commit Messages**:
   ```
   feat: add automatic graphics optimization
   fix: resolve controller detection issue
   docs: update installation instructions
   style: improve UI spacing and colors
   refactor: reorganize configuration modules
   test: add unit tests for save management
   ```

3. **Pull Request Process**:
   - Use the PR template
   - Link related issues
   - Request reviews from maintainers
   - Ensure CI passes
   - Update documentation if needed

## 🧪 Testing

### Running Tests
```bash
# Run all tests
npm test

# Run specific test suite
npm test -- --grep "installer"

# Run with coverage
npm run test:coverage

# Run integration tests
npm run test:integration
```

### Writing Tests
- Write unit tests for new functions
- Include integration tests for complex features
- Test error handling and edge cases
- Maintain test coverage above 80%

### Test Structure
```javascript
describe('Feature Name', () => {
  beforeEach(() => {
    // Setup test environment
  });

  it('should perform expected behavior', () => {
    // Test implementation
    expect(result).toBe(expected);
  });

  afterEach(() => {
    // Cleanup
  });
});
```

## 📚 Documentation Standards

### Code Documentation
- Document all public APIs
- Include usage examples
- Explain complex algorithms
- Update docs when changing functionality

### User Documentation
- Write clear, step-by-step instructions
- Include screenshots where helpful
- Test all documented procedures
- Keep documentation up to date

### README Updates
When adding features:
- Update feature list
- Add configuration examples
- Include troubleshooting info
- Update installation instructions

## 🌍 Internationalization (i18n)

### Adding New Languages
1. Create new locale file: `locales/[lang_code].json`
2. Copy structure from `locales/en.json`
3. Translate all strings
4. Add language option to UI
5. Test UI layout with translated text

### Translation Guidelines
- Keep text concise but clear
- Consider cultural context
- Test text length in UI
- Use consistent terminology
- Include plural forms where needed

### Example Translation File
```json
{
  "ui": {
    "buttons": {
      "install": "Install",
      "cancel": "Cancel",
      "next": "Next"
    },
    "messages": {
      "installing": "Installing Frostpunk 2...",
      "complete": "Installation complete!"
    }
  }
}
```

## 🐛 Issue Templates

### Bug Report Template
```markdown
**Bug Description**
A clear description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. See error

**Expected Behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**System Information:**
- OS: [e.g. Windows 11]
- Assistant Version: [e.g. v2.1.0]
- Game Version: [e.g. v1.0.5]

**Additional Context**
Any other context about the problem.
```

### Feature Request Template
```markdown
**Feature Description**
A clear description of what you want to happen.

**Problem Statement**
What problem does this feature solve?

**Proposed Solution**
How do you envision this feature working?

**Alternatives Considered**
Other approaches you've considered.

**Additional Context**
Any other context or screenshots.
```

## 🔍 Code Review Process

### For Contributors
- Ensure your code follows the style guide
- Write comprehensive commit messages
- Include tests for new functionality
- Update documentation as needed
- Be responsive to feedback

### For Reviewers
- Check code quality and standards
- Verify functionality works as intended
- Test on different platforms if possible
- Provide constructive feedback
- Approve when ready for merge

### Review Checklist
- [ ] Code follows style guidelines
- [ ] Tests pass and coverage maintained
- [ ] Documentation updated
- [ ] No breaking changes (or properly documented)
- [ ] Performance considerations addressed
- [ ] Security implications considered

## 🏆 Recognition

### Contributors
All contributors are recognized in:
- Repository README
- Release notes
- Hall of Fame section
- Annual contributor report

### Becoming a Maintainer
Regular contributors may be invited to become maintainers based on:
- Quality of contributions
- Community involvement
- Understanding of project goals
- Commitment to the project

## 📞 Getting Help

### Communication Channels
- 💬 **Discord**: [Join our server](https://discord.gg/frostpunk2) for real-time chat
- 📧 **Email**: maintainers@frostpunk2setup.com
- 🐛 **Issues**: Use GitHub issues for bugs and features
- 📝 **Discussions**: Use GitHub Discussions for questions

### Response Times
- **Critical bugs**: Within 24 hours
- **Regular issues**: Within 48 hours
- **Feature requests**: Within 1 week
- **Pull requests**: Within 3 days

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inclusive environment for all contributors.

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the same MIT License that covers the project.

---

Thank you for contributing to the Frostpunk 2 Offline Setup Assistant! Together, we can help more players enjoy this amazing survival city-builder game. 🎮❄️ 