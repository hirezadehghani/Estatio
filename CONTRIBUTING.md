# Contributing to Estatio

First of all, thank you for considering contributing to Estatio ❤️

Every contribution, whether it's fixing a typo or implementing a major feature,
helps make the project better.

---

# Ways to Contribute

You can help by:

- Reporting bugs
- Suggesting new features
- Improving documentation
- Fixing bugs
- Writing tests
- Improving performance
- Reviewing pull requests

---

# Before You Start

Please:

- Search existing Issues before opening a new one.
- Search existing Pull Requests before creating a duplicate.
- Be respectful and constructive.
- Keep discussions focused.

---

# Development Setup

Clone the repository

```bash
git clone https://github.com/hirezadehghani/Estatio.git

cd Estatio
```

Install dependencies

```bash
composer install
npm install
```

Copy environment

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Run migrations

```bash
php artisan migrate
```

Start the development server

```bash
php artisan serve
npm run dev
```

---

# Coding Standards

Please follow:

- PSR-12
- Laravel coding conventions
- SOLID principles
- Clean Architecture where applicable

Keep methods small and readable.

Avoid unnecessary complexity.

---

# Branch Naming

Examples:

```
feature/property-search
feature/dashboard

fix/login-bug

docs/readme-update

refactor/user-service
```

---

# Commit Messages

Use meaningful commit messages.

Good examples:

```
Add property image uploader

Fix tenant registration validation

Refactor booking service

Update README
```

Avoid:

```
update

fix

changes

asdf
```

---

# Pull Requests

Before opening a PR:

- Ensure the project builds successfully.
- Run the test suite.
- Update documentation if necessary.
- Keep PRs focused on a single change.
- Link related Issues when possible.

---

# Reporting Bugs

Include:

- Laravel version
- PHP version
- Database
- Operating System
- Steps to reproduce
- Expected behavior
- Actual behavior
- Error logs

---

# Feature Requests

Describe:

- The problem
- Your proposed solution
- Possible alternatives
- Additional context

---

# Documentation

Documentation improvements are always welcome.

Examples:

- README improvements
- Examples
- API documentation
- Architecture documentation

---

# Questions

If you're unsure how to implement something, feel free to open a GitHub Discussion before starting work.

We'd be happy to help.

---

Thank you for helping make Estatio better!
