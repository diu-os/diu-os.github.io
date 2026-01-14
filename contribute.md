# 🤝 Contributing to DIU OS

Thank you for your interest in contributing to DIU OS! We welcome contributions from the community.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Community](#community)

---

## 📜 Code of Conduct

### Our Standards

- **Be respectful** — Treat everyone with respect and kindness
- **Be constructive** — Provide helpful feedback and suggestions
- **Be inclusive** — Welcome newcomers and help them get started
- **Be patient** — Remember that everyone has different experience levels

### Unacceptable Behavior

- Harassment, discrimination, or offensive comments
- Trolling or deliberately inflammatory remarks
- Publishing others' private information
- Other conduct inappropriate in a professional setting

---

## 🚀 Getting Started

### Prerequisites

- Git installed on your machine
- Node.js 18+ (for frontend/MCP projects)
- Rust toolchain (for backend projects)
- GitHub account

### Finding Something to Work On

1. Check [open issues](https://github.com/diu-os/physics-tutorial/issues) for tasks
2. Look for issues labeled `good first issue` for beginner-friendly tasks
3. Browse `help wanted` labels for areas where we need assistance

### Issue Labels

| Label | Description |
|-------|-------------|
| `good first issue` | Great for newcomers |
| `bug` | Something isn't working |
| `enhancement` | New feature or improvement |
| `documentation` | Documentation improvements |
| `help wanted` | Community help needed |

---

## 💻 How to Contribute

### 1. Fork the Repository

Click the "Fork" button on the repository page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/physics-tutorial.git
cd physics-tutorial
```

### 3. Create a Branch

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

### 4. Make Your Changes

- Write clean, readable code
- Add tests if applicable
- Update documentation if needed

### 5. Commit Your Changes

We use [Conventional Commits](https://www.conventionalcommits.org/):

```bash
# Features
git commit -m "feat: add new quantum tunneling visualization"

# Bug fixes
git commit -m "fix: resolve rendering issue on mobile devices"

# Documentation
git commit -m "docs: update installation instructions"

# Tests
git commit -m "test: add unit tests for wave function calculator"
```

### 6. Push and Create PR

```bash
git push origin feature/your-feature-name
```

Then open a Pull Request on GitHub.

---

## 📝 Pull Request Process

### Before Submitting

- [ ] Code follows project coding standards
- [ ] Tests pass locally
- [ ] Documentation updated (if applicable)
- [ ] Commit messages follow conventional format
- [ ] Branch is up-to-date with `main`

### PR Template

When creating a PR, please include:

```markdown
## Description
Brief description of what this PR does.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Code refactoring

## Testing
Describe how you tested your changes.

## Screenshots (if applicable)
Add screenshots for UI changes.
```

### Review Process

1. A maintainer will review your PR
2. They may request changes or ask questions
3. Once approved, your PR will be merged
4. You'll be credited in the release notes!

---

## 🎨 Coding Standards

### TypeScript/JavaScript

```typescript
// Use meaningful variable names
const wavelengthInNanometers = 500;

// Use async/await over .then()
const result = await fetchSimulation();

// Document complex logic
/**
 * Calculates interference pattern for double-slit experiment
 * @param wavelength - Light wavelength in nanometers
 * @param slitDistance - Distance between slits in millimeters
 */
function calculateInterference(wavelength: number, slitDistance: number) {
  // ...
}
```

### Rust

```rust
// Use descriptive names
let wavelength_nm: f64 = 500.0;

// Document public functions
/// Calculates the de Broglie wavelength for a particle
/// 
/// # Arguments
/// * `momentum` - Particle momentum in kg·m/s
pub fn de_broglie_wavelength(momentum: f64) -> f64 {
    PLANCK_CONSTANT / momentum
}
```

### Git Commits

- Keep commits atomic (one logical change per commit)
- Write clear commit messages
- Reference issues when applicable: `fix: resolve #123`

---

## 🌐 Areas We Need Help

### High Priority

- [ ] Additional physics experiments
- [ ] Mobile responsiveness improvements
- [ ] Accessibility enhancements
- [ ] Performance optimizations

### Documentation

- [ ] Tutorials for new users
- [ ] API documentation improvements
- [ ] Translations (Russian, Spanish, Chinese)
- [ ] Video tutorials

### Testing

- [ ] Unit tests
- [ ] Integration tests
- [ ] End-to-end tests

---

## 💬 Community

### Get Help

- **Discord**: [Join our community](https://discord.gg/rXQDgpgaW8)
- **GitHub Discussions**: Ask questions and share ideas
- **Issues**: Report bugs or request features

### Stay Updated

- Watch the repository for updates
- Join Discord for announcements
- Follow our roadmap in the documentation

---

## 🏆 Recognition

Contributors are recognized in:

- Release notes
- Contributors page on the website
- Special Discord role

---

## ❓ Questions?

If you have questions about contributing:

1. Check existing issues and discussions
2. Ask in Discord #development channel
3. Open a new discussion on GitHub

---

**Thank you for helping build the Scientific Operating System! 🚀**

---

*Last updated: January 2025*
