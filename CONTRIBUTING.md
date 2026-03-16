# Contributing to Amdox AI-Powered Task Optimizer

Thank you for your interest in contributing to the Amdox AI-Powered Task Optimizer! We welcome contributions from the community.

## Contact

For questions or support, email: support@amdox.in

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Environment details (OS, Python version, etc.)
- Screenshots if applicable

### Suggesting Features

We love new ideas! To suggest a feature:
1. Check if it's already been suggested
2. Create an issue with the "enhancement" label
3. Describe the feature and its benefits
4. Provide use cases

### Pull Requests

1. **Fork the repository**
   ```bash
   git clone https://github.com/1234-ad/amdox-emotion-task-optimizer.git
   cd amdox-emotion-task-optimizer
   ```

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow the existing code style
   - Add tests for new features
   - Update documentation as needed
   - Ensure all tests pass

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of your changes"
   ```

5. **Push and create PR**
   ```bash
   git push origin feature/your-feature-name
   ```
   Then create a Pull Request on GitHub

## Development Setup

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Download models**
   ```bash
   python scripts/download_models.py
   ```

3. **Initialize database**
   ```bash
   python scripts/init_db.py --sample-data
   ```

4. **Run tests**
   ```bash
   pytest tests/ -v
   ```

## Code Style

- Follow PEP 8 guidelines
- Use type hints where appropriate
- Write docstrings for functions and classes
- Keep functions focused and modular
- Add comments for complex logic

### Example:

```python
def analyze_emotion(text: str) -> Dict[str, any]:
    """
    Analyze emotion from text input
    
    Args:
        text: Input text to analyze
        
    Returns:
        Dictionary with emotion analysis results
    """
    # Implementation
    pass
```

## Testing

- Write unit tests for new features
- Ensure existing tests pass
- Aim for >80% code coverage
- Test edge cases

```bash
# Run all tests
pytest tests/

# Run with coverage
pytest --cov=src tests/

# Run specific test file
pytest tests/test_text_analyzer.py -v
```

## Documentation

- Update README.md for major changes
- Add docstrings to new functions/classes
- Update API documentation if adding endpoints
- Include examples in docstrings

## Privacy & Security

When contributing, please:
- Never commit sensitive data (API keys, passwords)
- Follow privacy best practices
- Ensure data anonymization is maintained
- Review security implications of changes

## Code Review Process

1. All PRs require review before merging
2. Address reviewer feedback promptly
3. Keep PRs focused and reasonably sized
4. Update PR description if scope changes

## Areas for Contribution

We especially welcome contributions in:

- **New emotion detection modalities**
- **Improved ML models**
- **Additional task categories**
- **Dashboard enhancements**
- **Performance optimizations**
- **Documentation improvements**
- **Test coverage**
- **Bug fixes**

## Questions?

Feel free to:
- Open an issue for discussion
- Email us at support@amdox.in
- Check existing issues and PRs

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to Amdox AI-Powered Task Optimizer!**

Made with ❤️ by the Amdox Team
