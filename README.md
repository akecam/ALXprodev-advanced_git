# ALXprodev-advanced_git

This repository demonstrates GitFlow workflow implementation as part of the ALX Professional Development Advanced Git course.

## GitFlow Structure

This project follows the GitFlow branching model with the following branch types:

- `main` - Production-ready code
- `develop` - Integration branch for features
- `feature/*` - Feature development branches
- `release/*` - Release preparation branches
- `hotfix/*` - Critical bug fixes

## Project Structure

- `login-page/` - Login feature implementation
- `signup-page/` - Signup feature implementation

## Getting Started

1. Clone the repository
2. Check out the develop branch for ongoing development
3. Create feature branches from develop
4. Merge completed features back to develop
5. Create release branches for production deployment

## Workflow Commands

```bash
# Create feature branch
git checkout develop
git checkout -b feature/feature-name

# Create release branch
git checkout develop
git checkout -b release/version-number

# Merge to main and tag
git checkout main
git merge release/version-number
git tag -a v1.0.0 -m "Release version 1.0.0"
```
# Test
