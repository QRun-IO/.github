# Contributing to QQQ

Thank you for your interest in contributing to the QQQ framework! This document provides guidelines for contributing to any repository in the QRun-IO organization.

## Getting Started

1. **Fork the repository** you want to contribute to
2. **Clone your fork** locally
3. **Create a feature branch** from `main` (or `develop` for qqq-core)
4. **Make your changes** following our coding conventions
5. **Submit a pull request**

## Development Setup

### Java Projects (qqq, qbit-*)

```bash
# Requirements
- Java 21 LTS
- Maven 3.9+

# Build and test
mvn clean verify
```

### Frontend Projects (qqq-frontend-*)

```bash
# Requirements
- Node.js 18+ LTS
- npm 9+

# Install and test
npm ci
npm test
npm run build
```

## Branch Naming

Use the following prefixes:
- `feature/` - New features
- `fix/` - Bug fixes
- `docs/` - Documentation changes
- `chore/` - Maintenance tasks

Example: `feature/add-composite-key-support`

## Commit Messages

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <description>

[optional body]
```

### Types
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Documentation
- `style` - Formatting (no code change)
- `refactor` - Code restructuring
- `perf` - Performance improvement
- `test` - Adding tests
- `chore` - Maintenance

### Examples

```
feat(entity): add support for composite primary keys
fix(dashboard): resolve null pointer on empty query
chore(deps): upgrade Spring Boot to 3.2.0
```

## Pull Request Process

1. **Update documentation** if your change affects public APIs
2. **Add tests** for new functionality
3. **Ensure CI passes** - all checks must be green
4. **Request review** from a maintainer
5. **Address feedback** promptly

### PR Title Format

Use the same format as commit messages:
```
feat(entity): add composite key support
```

### PR Description

Include:
- Summary of changes
- Related issue numbers (e.g., "Fixes #123")
- Testing performed
- Breaking changes (if any)

## Code Style

### Java
- 4 spaces indentation
- 120 character line limit
- Follow existing patterns in the codebase
- Use meaningful variable names

### TypeScript/JavaScript
- 2 spaces indentation
- Single quotes for strings
- Semicolons required

## Testing

- Write tests for new functionality
- Maintain or improve code coverage
- Use descriptive test names: `methodName_condition_expectedResult`

## Reporting Issues

When reporting bugs:
1. Search existing issues first
2. Use the bug report template
3. Include steps to reproduce
4. Provide environment details

When requesting features:
1. Describe the use case
2. Explain expected behavior
3. Consider implementation approaches

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

- Open a [Discussion](https://github.com/orgs/QRun-IO/discussions) for questions
- Check existing documentation in each repository
- Review the [QQQ Wiki](https://github.com/QRun-IO/qqq/wiki) for framework docs

## License

By contributing, you agree that your contributions will be licensed under the same license as the project you're contributing to.

---

Thank you for contributing to QQQ!
