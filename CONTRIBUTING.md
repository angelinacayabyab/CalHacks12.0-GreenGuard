# Contributing to GreenGuard

First off, thank you for considering contributing to GreenGuard! 🛡️💚

This document provides guidelines for contributing to this project. Following these guidelines helps communicate that you respect the time of the developers managing and developing this open source project.

## 🌟 Ways to Contribute

### 1. Report Bugs
Found a bug? Please open an issue with:
- Clear, descriptive title
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable
- Your environment (browser, OS)

### 2. Suggest Enhancements
Have an idea? Open an issue tagged as "enhancement" with:
- Clear description of the enhancement
- Why it would be useful
- Potential implementation approach

### 3. Submit Pull Requests
Want to code? Great! Please:
- Fork the repository
- Create a feature branch
- Make your changes
- Test thoroughly
- Submit a PR with clear description

### 4. Improve Documentation
- Fix typos or clarify instructions
- Add examples or tutorials
- Translate documentation

### 5. Share Sample Reports
Help improve accuracy by sharing:
- Real corporate sustainability reports (public domain)
- Edge cases that the analysis misses
- Examples of good vs bad reports

## 🔧 Development Setup

```bash
# Fork and clone the repository
git clone https://github.com/yourusername/greenguard.git
cd greenguard

# Install dependencies
npm install

# Start development server
npm start

# Run tests (when available)
npm test
```

## 📝 Pull Request Guidelines

### Before Submitting
- [ ] Code follows existing style
- [ ] Comments added for complex logic
- [ ] Tested with multiple sample reports
- [ ] README updated if needed
- [ ] No console errors or warnings

### PR Description Should Include
- What changes were made and why
- Which issue it addresses (if applicable)
- Screenshots/GIFs of UI changes
- Any breaking changes

### Code Style
- Use meaningful variable names
- Add comments for non-obvious logic
- Keep functions focused and small
- Follow React best practices
- Maintain accessibility (WCAG 2.1)

## 🎯 Priority Areas for Contribution

### High Priority
- [ ] PDF upload support
- [ ] Improved analysis accuracy
- [ ] Additional language support
- [ ] Mobile optimization
- [ ] Performance improvements

### Medium Priority
- [ ] Export to PDF feature
- [ ] Historical tracking
- [ ] Industry benchmarks
- [ ] API development
- [ ] Test coverage

### Documentation Needed
- [ ] Video tutorials
- [ ] API documentation
- [ ] Analysis methodology details
- [ ] Translation to other languages

## 🐛 Bug Report Template

```markdown
**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Upload file '...'
3. Click on '...'
4. See error

**Expected behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**Environment:**
 - OS: [e.g. iOS, Windows]
 - Browser: [e.g. chrome, safari]
 - Version: [e.g. 22]

**Sample Report**
If relevant, attach or describe the report that caused the issue.
```

## 💡 Feature Request Template

```markdown
**Is your feature request related to a problem?**
A clear description of the problem.

**Describe the solution you'd like**
A clear description of what you want to happen.

**Describe alternatives you've considered**
Other solutions or features you've considered.

**Additional context**
Any other context, mockups, or examples.
```

## 🧪 Testing Guidelines

When contributing code changes:

1. **Test with Multiple Reports**
   - High greenwashing (score <40)
   - Medium greenwashing (score 40-69)
   - Low greenwashing (score >70)

2. **Test Edge Cases**
   - Very short reports (<100 words)
   - Very long reports (>5000 words)
   - Reports with special characters
   - Empty or corrupted files

3. **Browser Testing**
   - Chrome/Edge
   - Firefox
   - Safari
   - Mobile browsers

4. **Accessibility Testing**
   - Keyboard navigation
   - Screen reader compatibility
   - Color contrast

## 🤝 Code of Conduct

### Our Standards
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Gracefully accepting constructive criticism
- Focusing on what's best for the community
- Showing empathy towards others

### Unacceptable Behavior
- Harassment, trolling, or derogatory comments
- Personal or political attacks
- Public or private harassment
- Publishing others' private information
- Other unethical or unprofessional conduct

## 📜 License

By contributing, you agree that your contributions will be licensed under the MIT License. See [LICENSE](LICENSE) for details.

## ❓ Questions?

Don't hesitate to ask questions! You can:
- Open an issue with the "question" label
- [Email](acayabyab3@gatech.edu)
- Join discussions in the Issues tab

## 🙏 Recognition

All contributors will be recognized in:
- README.md Contributors section
- Release notes
- Project documentation

Thank you for making GreenGuard better! 🌟
