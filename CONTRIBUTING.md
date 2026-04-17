# Contributing

Thank you for your interest in contributing! This project welcomes contributions that improve functionality, documentation, or user experience.

## How to Contribute

### Bug Reports
1. Check [existing issues](../../issues) to avoid duplicates
2. Open a new issue with:
   - Clear description
   - Steps to reproduce
   - Expected vs. actual behavior
   - Python version and OS
   - Relevant logs or screenshots

### Feature Requests
1. Open an issue with the `enhancement` label
2. Describe:
   - The feature and its purpose
   - Use case scenarios
   - Expected behavior
   - Why it would benefit users

### Pull Requests
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes with clear, descriptive commits
4. Test thoroughly
5. Update documentation if needed
6. Submit PR with:
   - Clear description of changes
   - Reference to related issues
   - Screenshots if UI changes

## Code Standards

### Python Style
- Python 3.10+ compatible
- PEP 8 compliance (100-character line limit)
- Type hints where practical
- Descriptive variable names

### Documentation
- Docstrings for all public functions
- Inline comments for complex logic
- Update README.md for user-facing changes
- Update CHANGELOG.md for notable changes

### Testing
- Test all new features manually
- Ensure existing functionality unchanged
- Include edge cases

## Development Setup

```bash
# Clone your fork
git clone https://github.com/Hridoypk/AAMVA-PDF417-Generator----Telegram-Bot.git
cd aamva-pdf417-generator

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create test bot token
# Get from @BotFather

# Set environment variables
export TG_TOKEN="your_test_bot_token"
export ADMIN_IDS="your_telegram_id"

# Run bot
python bot.py

Community
Be respectful and inclusive
Follow Code of Conduct
Help others in discussions
Share knowledge and experience
License
By contributing, you agree your work will be licensed under the MIT License.

Questions?
Open a discussion or comment on relevant issues.

Thank you for contributing! 🎉
