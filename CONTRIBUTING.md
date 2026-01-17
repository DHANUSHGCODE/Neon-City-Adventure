# Contributing to Neon City Adventure

Thank you for your interest in contributing to Neon City Adventure! We welcome contributions from everyone.

## How to Contribute

### Reporting Bugs

If you find a bug, please open an issue with:
- A clear, descriptive title
- Steps to reproduce the problem
- Expected behavior vs actual behavior
- Screenshots if applicable
- Your environment details (browser, OS, etc.)

### Suggesting Enhancements

We love new ideas! To suggest an enhancement:
1. Check if a similar suggestion already exists
2. Open an issue with the "enhancement" label
3. Describe the feature and why it would be useful
4. Provide examples if possible

### Pull Requests

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Neon-City-Adventure.git
   ```

2. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Write clean, maintainable code
   - Follow existing code style
   - Add comments where necessary
   - Test your changes

4. **Commit your changes**
   ```bash
   git commit -m "feat: add your feature description"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request**
   - Provide a clear description
   - Reference any related issues
   - Wait for review

## Development Setup

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your GEMINI_API_KEY to .env.local

# Start development server
npm run dev
```

## Code Style

- Use TypeScript for type safety
- Follow ESLint rules
- Use meaningful variable and function names
- Keep functions small and focused
- Write self-documenting code

## Commit Message Guidelines

Use conventional commits:
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting)
- `refactor:` Code refactoring
- `test:` Adding tests
- `chore:` Maintenance tasks

## Questions?

Feel free to open an issue for any questions about contributing!

---

Thank you for making Neon City Adventure better! 🌟
