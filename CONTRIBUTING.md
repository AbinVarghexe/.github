# Contributing to [Project Name]

First off, thank you for considering contributing to [Project Name]! It's people like you that make [Project Name] such a great tool.

## 🤝 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to [your.email@example.com].

## 🎯 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed and what you expected**
- **Include screenshots or animated GIFs if relevant**
- **Include your environment details** (OS, browser, version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **List examples of how it would be used**

### Pull Requests

1. Fork the repo and create your branch from `main`
2. If you've added code that should be tested, add tests
3. If you've changed APIs, update the documentation
4. Ensure the test suite passes
5. Make sure your code lints
6. Issue that pull request!

## 🚀 Development Process

### Setting Up Development Environment

```bash
# Fork and clone the repository
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME

# Install dependencies
pnpm install  # or npm install / yarn install

# Create a branch
git checkout -b feature/your-feature-name
```

### Making Changes

1. **Write clear, concise commit messages**
   ```bash
   git commit -m "Add feature: brief description"
   ```

2. **Follow the coding style of the project**
   - Use consistent indentation
   - Follow naming conventions
   - Add comments for complex logic

3. **Test your changes**
   ```bash
   pnpm test
   ```

4. **Run linter**
   ```bash
   pnpm lint
   ```

### Submitting Changes

1. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Open a Pull Request**
   - Fill in the PR template
   - Link any relevant issues
   - Add screenshots for UI changes
   - Request review from maintainers

## 📝 Coding Conventions

### Style Guide

- Use 2 spaces for indentation
- Use camelCase for variables and functions
- Use PascalCase for components and classes
- Write meaningful variable and function names
- Add JSDoc comments for functions
- Keep functions small and focused

### Example

```javascript
/**
 * Calculate the sum of two numbers
 * @param {number} a - First number
 * @param {number} b - Second number
 * @returns {number} Sum of a and b
 */
function calculateSum(a, b) {
  return a + b;
}
```

## 🧪 Testing

- Write tests for new features
- Update tests when changing existing code
- Ensure all tests pass before submitting PR

```bash
# Run all tests
pnpm test

# Run tests in watch mode
pnpm test:watch

# Run tests with coverage
pnpm test:coverage
```

## 📖 Documentation

- Update README.md if you change functionality
- Add JSDoc comments to new functions
- Update API documentation for API changes
- Include examples for new features

## 🏷️ Commit Message Guidelines

### Format
```
type(scope): subject

body

footer
```

### Types
- **feat**: New feature
- **fix**: Bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, etc.)
- **refactor**: Code refactoring
- **test**: Adding or updating tests
- **chore**: Maintenance tasks

### Examples
```bash
feat(auth): add OAuth2 authentication
fix(api): resolve rate limiting issue
docs(readme): update installation instructions
```

## 🔍 Review Process

1. Maintainers will review your PR
2. Address any requested changes
3. Once approved, maintainers will merge your PR

## ✅ Checklist

Before submitting your contribution, make sure:

- [ ] Code follows the project's style guidelines
- [ ] Self-review of code completed
- [ ] Comments added for complex code
- [ ] Documentation updated
- [ ] Tests added/updated and passing
- [ ] No new warnings generated
- [ ] Dependent changes merged/published

## 💬 Questions?

Feel free to:
- Open an issue for questions
- Join our [Discord/Slack community] (if applicable)
- Email maintainers at [your.email@example.com]

## 🎉 Recognition

Contributors will be:
- Added to the README contributors section
- Mentioned in release notes
- Given credit in relevant commits

---

<div align="center">
  <sub>Thank you for contributing! 🙌</sub>
</div>
