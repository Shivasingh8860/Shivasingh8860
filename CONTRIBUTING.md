# Contributing Guidelines

## 🎯 Before You Start

- Check existing issues and pull requests
- Create an issue for new features/bugs
- Discuss major changes first

## 📝 Commit Convention

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <subject>
<blank line>
<body>
<blank line>
<footer>
```

### Commit Types

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation
- `style`: Code style changes
- `refactor`: Code refactoring
- `perf`: Performance improvement
- `test`: Testing changes
- `chore`: Build, dependencies
- `ci`: CI/CD configuration

### Examples

```
feat(auth): add JWT token refresh mechanism
fix(api): handle null pointer in user service
docs(setup): update installation instructions
```

## 🔄 Pull Request Process

1. **Fork & Branch**
   ```bash
   git checkout -b feature/meaningful-name
   ```

2. **Code Quality**
   ```bash
   npm run lint:fix
   npm run format
   npm run typecheck
   ```

3. **Testing**
   ```bash
   npm run test:coverage
   # Ensure 80%+ coverage
   ```

4. **Commit & Push**
   ```bash
   git commit -m "feat(module): description"
   git push origin feature/meaningful-name
   ```

5. **Create Pull Request**
   - Clear title and description
   - Link related issues
   - Add screenshots for UI changes

## ✅ PR Requirements

- All tests pass
- Code coverage maintained
- No linting errors
- Updated documentation
- TypeScript types are correct

## 📚 Code Standards

### TypeScript
- Strict mode enabled
- Explicit return types
- No `any` type usage
- Proper error handling

### File Naming
- camelCase for files
- PascalCase for classes
- kebab-case for directories

### Function Guidelines
- Keep functions small (< 20 lines)
- Single responsibility principle
- Clear naming conventions
- Proper JSDoc comments

## 🐛 Bug Reports

Include:
- Clear description
- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details

## 💡 Feature Requests

Provide:
- Use case description
- Proposed solution
- Alternatives considered
- Implementation complexity estimate

## 📞 Questions?

Open a Discussion or reach out via Issues.
