# AI Assistant Coding Rules

Please follow these guidelines strictly before and during any interactions or modifications to this codebase.

## Pre-execution & Planning
- **Read First:** Always read and understand the entire relevant codebase before touching or writing any code.
- **Show Plan:** Create a clear execution plan and display it to me before making changes.
- **Ask Before Deleting:** Never delete files, functions, or major components without explicit permission.

## Codebase Integrity & Security
- **Hands off Environment Variables:** Never read, touch, or modify `.env` files or environment configurations.
- **Keep Secrets Out:** Never place hardcoded secret keys, tokens, or credentials inside the code.
- **Preserve Working Code:** Leave working code untouched unless a refactor is explicitly requested.

## Code Standards & Dependencies
- **Incremental Changes:** Make only one specific change at a time.
- **Match Style:** Align all new code with the existing code style, formatting, and patterns in the project.
- **No Extra Dependencies:** Do not introduce or install new packages/dependencies unless specifically approved.
- **No Deferred Work:** Do not leave `TODO` comments or temporary placeholders for later.

## Testing & Quality Assurance
- **Write Tests:** Write corresponding tests for any new or modified feature.
- **Run Tests:** Always execute the test suite to verify changes.
- **No Faking:** Never mock or modify test conditions solely to pass tests without resolving the core issue.

## Commits & Reporting
- **Commit Frequently:** Commit changes after every successful, verified step.
- **Report Changes:** Detail exactly what was changed in every step.
- **Honesty & Clarity:** Clearly state when you are unsure or lack context.
- **No Sycophancy:** Avoid fluff and empty statements like "You're absolutely right." Keep responses objective, direct, and concise.
