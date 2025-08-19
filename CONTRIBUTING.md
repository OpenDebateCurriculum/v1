# Contributing to Open Debate Curriculum

Thank you for your interest in contributing to the Open Debate Curriculum! This project aims to provide a comprehensive, accessible guide for teaching and learning high school debate.

## How to Contribute

### Content Contributions

We welcome contributions that improve the educational content:

- **Fix errors or typos**: Help us maintain accuracy in our educational materials
- **Add examples**: Real-world applications and practice scenarios strengthen learning
- **Expand sections**: Some units are marked as "Coming Soon" and need development
- **Create supplementary materials**: Drills, exercises, and additional resources
- **Improve explanations**: Make complex concepts more accessible to students

### Types of Contributions

1. **Documentation improvements**: Better explanations, clearer examples, fixed typos
2. **New content**: Additional units, expanded sections, new practice materials  
3. **Structure enhancements**: Better organization, navigation, or formatting
4. **Accessibility**: Making content more inclusive and accessible to all learners

## Getting Started

### Prerequisites

- Basic familiarity with Markdown/MDX syntax
- Understanding of high school debate formats (Policy, Public Forum, Lincoln-Douglas)
- [Mintlify CLI](https://www.npmjs.com/package/mint) for local development (optional)

### Development Setup

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/v1.git
   cd v1
   ```

3. **Install Mintlify CLI** (optional, for local preview):
   ```bash
   npm i -g mint
   ```

4. **Preview locally** (if CLI installed):
   ```bash
   mint dev
   ```
   View at `http://localhost:3000`

### Making Changes

1. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/your-improvement-name
   ```

2. **Make your changes** to the relevant `.mdx` files in the unit folders

3. **Test your changes** by previewing locally (if possible) or carefully reviewing the markdown syntax

4. **Commit your changes** with a descriptive message:
   ```bash
   git add .
   git commit -m "Add practice exercises for impact calculus unit"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-improvement-name
   ```

6. **Create a pull request** on GitHub with:
   - Clear description of your changes
   - Rationale for the improvement
   - Any testing you've performed

## Content Guidelines

### Writing Style
- **Clear and accessible**: Write for high school students and coaches
- **Practical focus**: Include concrete examples and actionable advice
- **Format-inclusive**: Consider Policy, Public Forum, and Lincoln-Douglas formats
- **Evidence-based**: Support claims with reasoning or examples from debate practice

### Structure
- Follow existing patterns in similar files
- Use appropriate MDX components (Tips, Examples, etc.)
- Maintain consistent heading hierarchy
- Include practice exercises where appropriate

### Examples
- Use realistic but educational scenarios
- Avoid controversial political examples unless pedagogically necessary
- Include diverse perspectives and contexts
- Make examples accessible to students from various backgrounds

## Review Process

1. **Community review**: Other contributors may comment on your pull request
2. **Maintainer review**: Project maintainers will review for accuracy and fit
3. **Iteration**: Be prepared to make revisions based on feedback
4. **Merge**: Once approved, your contribution will be merged and deployed

## Recognition

Contributors are recognized through:
- GitHub contributor history
- Acknowledgment in major releases
- Community recognition for significant contributions

## Questions or Need Help?

- **Open an issue** on GitHub for questions about content or contributions
- **Join discussions** in existing issues and pull requests
- **Check existing content** for patterns and examples to follow

## Code of Conduct

We are committed to providing a welcoming and inclusive environment for all contributors. Please:

- Be respectful in all interactions
- Focus on constructive feedback
- Welcome newcomers and help them get started
- Report any inappropriate behavior to project maintainers

## License

By contributing to this project, you agree that your contributions will be licensed under the MIT License. Educational content should be freely accessible and shareable.

---

Thank you for helping make debate education more accessible and effective for students everywhere!