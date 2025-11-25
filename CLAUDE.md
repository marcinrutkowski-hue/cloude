# CLAUDE.md - AI Assistant Guide

> This file provides guidance for AI assistants working with this repository.

## Project Overview

**Repository:** cloude
**Status:** New/Initialized
**Last Updated:** 2025-11-25

This repository is newly initialized. Update this section with project purpose and description as the codebase develops.

---

## Repository Structure

```
cloude/
├── CLAUDE.md           # This file - AI assistant guidelines
└── (project files)     # Add as development progresses
```

### Recommended Structure (to be created)

```
cloude/
├── src/                # Source code
│   ├── index.ts        # Main entry point
│   ├── components/     # UI components (if applicable)
│   ├── utils/          # Utility functions
│   └── types/          # Type definitions
├── tests/              # Test files
├── docs/               # Documentation
├── scripts/            # Build/deployment scripts
├── package.json        # Dependencies and scripts
├── tsconfig.json       # TypeScript configuration
├── .gitignore          # Git ignore rules
├── README.md           # Project documentation
└── CLAUDE.md           # AI assistant guide (this file)
```

---

## Development Workflow

### Getting Started

```bash
# Clone the repository
git clone <repository-url>
cd cloude

# Install dependencies (when package.json exists)
npm install

# Start development (update command as needed)
npm run dev
```

### Git Workflow

1. **Branch Naming Convention:**
   - Feature branches: `feature/<description>`
   - Bug fixes: `fix/<description>`
   - Claude branches: `claude/<session-id>`

2. **Commit Messages:**
   - Use clear, descriptive commit messages
   - Start with a verb: "Add", "Fix", "Update", "Remove", "Refactor"
   - Keep the first line under 72 characters
   - Example: `Add user authentication module`

3. **Pull Requests:**
   - Create PRs against the main branch
   - Include description of changes
   - Reference any related issues

---

## Code Conventions

### General Guidelines

- Write clean, readable code with meaningful variable names
- Follow the principle of single responsibility
- Keep functions small and focused
- Add comments only where the logic isn't self-evident
- Avoid over-engineering - implement only what's needed

### TypeScript/JavaScript (if applicable)

- Use TypeScript for type safety
- Prefer `const` over `let`, avoid `var`
- Use async/await over raw promises
- Export types and interfaces explicitly
- Use meaningful names for functions and variables

### File Organization

- One component/module per file
- Group related functionality together
- Keep test files adjacent to source files or in a parallel `tests/` directory

---

## Testing

### Running Tests

```bash
# Run all tests (update when test framework is configured)
npm test

# Run tests in watch mode
npm run test:watch

# Run tests with coverage
npm run test:coverage
```

### Test Conventions

- Write tests for all new functionality
- Maintain test coverage for critical paths
- Use descriptive test names that explain the expected behavior
- Follow the Arrange-Act-Assert pattern

---

## Build & Deployment

### Build Commands

```bash
# Build for production (update as needed)
npm run build

# Type checking
npm run typecheck

# Linting
npm run lint
```

### Environment Configuration

- Use `.env` files for environment variables
- Never commit secrets or credentials
- Document required environment variables in `.env.example`

---

## AI Assistant Guidelines

### When Working on This Repository

1. **Before Making Changes:**
   - Read and understand existing code before modifying
   - Check for existing patterns and conventions
   - Look for related tests and documentation

2. **Making Changes:**
   - Follow existing code style and patterns
   - Keep changes focused and minimal
   - Update tests when modifying functionality
   - Update documentation when adding features

3. **Code Quality:**
   - Run linting and type checking before committing
   - Ensure all tests pass
   - Avoid introducing security vulnerabilities
   - Don't add unnecessary dependencies

4. **Git Operations:**
   - Make atomic commits with clear messages
   - Push to feature branches, not main directly
   - Create PRs for review when appropriate

### Common Tasks

| Task | Command/Action |
|------|----------------|
| Install dependencies | `npm install` |
| Run development server | `npm run dev` |
| Run tests | `npm test` |
| Build project | `npm run build` |
| Check types | `npm run typecheck` |
| Lint code | `npm run lint` |

---

## Troubleshooting

### Common Issues

1. **Dependencies not installing:**
   - Delete `node_modules` and `package-lock.json`
   - Run `npm install` again

2. **Type errors:**
   - Ensure TypeScript version matches project requirements
   - Check for missing type definitions

3. **Test failures:**
   - Check for environment-specific issues
   - Ensure test database/mocks are properly configured

---

## Resources

- [Project README](./README.md) (to be created)
- [Contributing Guide](./CONTRIBUTING.md) (to be created)
- [API Documentation](./docs/api.md) (to be created)

---

## Notes for AI Assistants

### This Repository

- This is a newly initialized repository
- Update this CLAUDE.md as the project structure develops
- Add specific conventions and patterns as they emerge
- Document any non-obvious decisions or architecture choices

### Key Principles

1. **Understand before modifying** - Always read existing code first
2. **Keep it simple** - Don't over-engineer solutions
3. **Be consistent** - Follow existing patterns
4. **Test thoroughly** - Ensure changes don't break existing functionality
5. **Document intentionally** - Update docs when making significant changes

---

*This file should be updated as the project evolves. Last reviewed: 2025-11-25*
