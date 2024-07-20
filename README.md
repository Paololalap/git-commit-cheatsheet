# Git Commit Message Cheatsheet

## Types
- feat: A new feature
- fix: A bug fix
- docs: Documentation changes
- style: Code style changes (formatting, missing semi colons, etc)
- refactor: Code refactoring
- perf: Performance improvements
- test: Adding or modifying tests
- chore: Maintenance tasks, build changes, etc.

## Scope
- Optional
- Describes the part of the codebase affected (e.g., ui, api, auth)

## Subject
- Short summary (50 chars or less)
- Use imperative mood ("Add feature" not "Added feature")
- Don't capitalize first letter
- No period at the end

## Body
- Optional
- Provide context and explain the "why" behind the changes
- Wrap at 72 characters

## Footer
- Optional
- Reference issue numbers or PRs
- Mention breaking changes

## Examples
```
feat(auth): add password reset functionality

fix(api): resolve null pointer exception in user service

docs: update README with new build instructions

style: format code according to style guide

refactor(database): optimize query performance

perf: improve load time of dashboard

test: add unit tests for payment gateway

chore: update dependencies to latest versions
```

## Best Practices
1. Be concise but descriptive
2. Use the imperative mood
3. Separate subject from body with a blank line
4. Limit the subject line to 50 characters
5. Capitalize the subject line
6. Do not end the subject line with a period
7. Wrap the body at 72 characters
8. Use the body to explain what and why vs. how
9. Reference issues and pull requests liberally

