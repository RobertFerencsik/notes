# How To Write Commit Messages

## Commit Message Structure

\<type\>\<(scope)\>: \<short summary\> [optional longer description]

## Common Commit Types

| Type | Description |
|------|-------------|
| **feat** | A new feature |
| **fix** | A bug fix |
| **docs** | Documentation changes only |
| **style** | Code style changes (formatting, whitespace, etc.) |
| **refactor** | Code changes that don't fix a bug or add a feature |
| **perf** | Performance improvements |
| **test** | Adding or updating tests |
| **chore** | Maintenance tasks (build process, dependencies, etc.) |

## Scope

The scope is an optional part that indicates which part of the codebase is affected by the change. It helps provide more context about where the change occurred.

**Common scopes:**

- `api` - Backend API changes
- `ui` or `components` - Frontend UI changes
- `auth` - Authentication related changes
- `db` - Database changes
- `config` - Configuration changes
- `docs` - Documentation changes
- `test` - Test-related changes

## Writing The Short Summary

- Use the **imperative mood** (as if giving an order)

    1. Add search bar

- Keep it **under 50 characters** if possible

## Optional Longer Description

- Leave one blank line after the summary
- Explain what and why in detail
- Use bullet points for clarity
