# Contributing Guidelines

Thank you for contributing to our project! To maintain a consistent and clean codebase, please follow these guidelines when working with Git.

## Branch Naming Conventions

Use the following naming conventions for your branches:

| **Branch Type**         | **Branch Name**            | **Description**                                  | **Example**                   |
|-------------------------|----------------------------|--------------------------------------------------|-------------------------------|
| **Feature Branches**    | `feature/featurename`     | Branch for implementing new features.            | `feature/pwm_module`          |
| **Bugfix Branches**     | `bugfix/bugname`           | Branch for fixing bugs.                          | `bugfix/fix_login_issue`      |
| **Hotfix Branches**     | `hotfix/hotfixname`        | Branch for urgent fixes in production.           | `hotfix/urgent_security_fix`  |
| **Release Branches**    | `release/releasename`      | Branch for preparing a new release.              | `release/v1.2.0`              |
| **Development Branch**  | `dev`                  | Branch containing the latest development changes.|                               |
| **Test Branch**         | `test`                     | Branch containing code that is currently in testing.|                           |
| **Staging Branch**      | `staging`                  | Branch containing code that is ready for staging before production deployment.|  |
| **Main/Production Branch**| `main` or `master`      | Branch containing stable, production-ready code. |                               |

Sure! Here is the information presented in a table format using Markdown:

### Commit Message Conventions

| **Format**                   | `type(scope): subject`                                                                                          |
|------------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Description**              | Follow the Conventional Commits specification for your commit messages. Each commit message should include a type, an optional scope, and a concise description of the changes. |

| **Type**       | **Description**                                                                                                                   | **Example**                                        |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **feat**       | A new feature                                                                                                                     | `feat(auth): add login functionality`              |
| **fix**        | A bug fix                                                                                                                          | `fix(auth): resolve login bug for special characters` |
| **docs**       | Documentation changes                                                                                                             | `docs(readme): update installation instructions`   |
| **style**      | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.)                           | `style(button): adjust button spacing`             |
| **refactor**   | A code change that neither fixes a bug nor adds a feature                                                                          | `refactor(user-service): optimize user data fetching` |
| **test**       | Adding missing tests or correcting existing tests                                                                                 | `test(auth): add tests for login validation`       |
| **chore**      | Changes to the build process or auxiliary tools and libraries such as documentation generation                                     | `chore(deps): update dependency versions`          |


## Git Workflow

We use a Git Flow-inspired workflow to manage our branches. Here's a simplified overview:


### Main Branches

| **Branch Name** | **Description**                                                      |
|-----------------|----------------------------------------------------------------------|
| **main**        | Contains stable, production-ready code.                              |
| **dev**         | Contains the latest development changes.                             |
| **test**        | Contains code that is currently in testing.                          |
| **staging**     | Contains code that is ready for staging before production deployment. |


### Workflow Diagram
![Git Flow Diagram](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*9yJY7fyscWFUVRqnx0BM6A.png)



### VS Code Extensions

Certainly! Here's the updated section with **SonarLint** included:

### VS Code Extensions

| **Extension**                               | **Description**                                           |
|---------------------------------------------|-----------------------------------------------------------|
| [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)               | Automatically formats code to ensure consistent style.    |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)                                  | Lints JavaScript and TypeScript code to enforce coding standards. |
| [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)                                 | Provides detailed Git insights and history in the editor. |
| [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)      | Detects and highlights spelling errors in code.    
| [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)                  | Colors matching brackets to make code easier to read.     |
| [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)                | Provides a set of icons to customize file and folder visuals. |
| [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)                     | Provides on-the-fly code quality and security feedback.    |


## Summary

Following these guidelines will help us keep our codebase clean and well-organized. We appreciate your contributions!

If you have any questions or need further clarification, please feel free to reach out to the project maintainers.

---

Happy coding!
