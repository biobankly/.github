# Contributing to Biobankly

Thank you for your interest in contributing to Biobankly! We value the contributions of each community member and want to make the contribution process as easy and transparent as possible.

## Table of Contents
1. [Code of Conduct](#code-of-conduct)
2. [Development Process](#development-process)
3. [Repository Structure](#repository-structure)
4. [Pull Request Process](#pull-request-process)
5. [Style Guidelines](#style-guidelines)
6. [Testing](#testing)
7. [Documentation](#documentation)
8. [Security](#security)

## Code of Conduct
This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Development Process

### Getting Started
1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

### Working with Biobank Data
- Never commit real biobank data or personally identifiable information
- Use mock data for testing and examples
- Follow UK Biobank data usage guidelines
- Report any potential data breaches immediately

## Repository Structure
```
repository/
├── src/                # Source code
├── tests/              # Test files
├── docs/              # Documentation
├── examples/          # Example code and usage
└── README.md         # Project documentation
```

## Pull Request Process
1. Update documentation as needed
2. Add tests for new features
3. Ensure all tests pass
4. Update the README.md if needed
5. Follow the pull request template
6. Get at least one code review

### Pull Request Template
```markdown
## Description
[Describe your changes]

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Other (specify)

## Testing
- [ ] Tests added/updated
- [ ] All tests passing

## Checklist
- [ ] Code follows style guidelines
- [ ] Documentation updated
- [ ] No sensitive data included
```

## Style Guidelines

### Python Code Style
- Follow PEP 8 guidelines
- Use type hints for function parameters and return values
- Use descriptive variable names
- Add docstrings for all functions and classes

### Documentation Style
- Use clear, concise language
- Include code examples where appropriate
- Keep README.md files up to date
- Document any configuration options

## Testing
- Write unit tests for new features
- Maintain test coverage above 80%
- Use pytest for testing
- Include integration tests where appropriate

### Running Tests
```bash
pytest tests/
```

## Documentation
- Update documentation with any changes
- Include docstrings for all public functions
- Provide usage examples
- Document any breaking changes

## Security
- Report security vulnerabilities privately
- Never commit sensitive data
- Follow security best practices
- Use secure dependencies

## Questions or Need Help?
- Open a GitHub issue
- Check existing documentation
- Contact maintainers directly for sensitive issues

## License
By contributing, you agree that your contributions will be licensed under the project's license.
