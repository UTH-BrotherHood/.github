# Commit Rules

## General Guidelines

1. **Write clear and concise commit messages**: Ensure your commit messages are easy to understand and clearly describe the changes made.
2. **Use English**: Write commit messages in English to maintain consistency and ensure everyone on the team can understand them.
3. **Reference issues**: If your commit is related to a specific issue, reference it in the commit message using the issue number.

## Commit Message Structure

Each commit message should consist of three parts:

1. **Header**: A brief summary of the changes (up to 50 characters).
2. **Body**: A more detailed explanation of the changes (optional).
3. **Footer**: References to any related issues or PRs (optional).

### Example:

Header: [Type] Short description (50 characters or less)

Body:
Explanation of what and why.
Explain the motivation behind the changes, if necessary.

Footer:
References to issues or pull requests (e.g., Closes #123, Fixes #456).

## Types of Commits

Use the following prefixes to categorize your commits:

> - **`feat`**: A new feature for the user.
> - **`fix`**: A bug fix.
> - **`docs`**: Documentation only changes.
> - **`style`**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
> - **`refactor`**: A code change that neither fixes a bug nor adds a feature.
> - **`perf`**: A code change that improves performance.
> - **`test`**: Adding missing or correcting existing tests.
> - **`chore`**: Changes to the build process or auxiliary tools and libraries such as documentation generation.

## Examples

### Feature:

feat: add user login functionality

Added user login functionality to allow users to log in with their email and password.

### Bug Fix:

fix: resolve login issue on mobile devices

Fixed an issue where users could not log in on mobile devices due to a viewport scaling problem.

### Documentation:

docs: update README with setup instructions

Updated the README file to include instructions on how to set up the development environment.

### Style:

tyle: format code with Prettier

Formatted all JavaScript files using Prettier to maintain code consistency.

### Refactor:

refactor: optimize authentication logic

Refactored the authentication logic to improve code readability and maintainability.

### Performance:

perf: improve database query performance

Optimized database queries to reduce load times and improve overall performance.

### Test:

test: add tests for user login functionality

Added unit tests for the user login functionality to ensure reliability and correctness.

### Chore:

chore: update dependencies

Updated project dependencies to the latest versions to ensure security and compatibility.

By following these commit rules, we can maintain a clean and understandable project history, making collaboration easier and more efficient.
