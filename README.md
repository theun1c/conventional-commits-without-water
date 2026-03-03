# Conventional commits without water 💦

This repository is created as a brief reminder of how to name your commits. A collection of commonly accepted rules.

# Type of change

First, you need to specify the type of your change.

- ***feat***: Adding new functionality.
- ***fix***: Fixing an error.
- ***docs***: Changing the documentation.
- ***style***: Style edits (formatting, spacing, commas, etc.).
- ***refactor***: Refactoring the code without fixing errors or adding new functionality.
- ***perf***: Optimizing performance.
- ***test***: Adding or updating tests.
- ***build***: Changes related to building the project.
- ***ci***: Configure or modify CI/CD.
- ***chore***: Other tasks (such as changes to .gitignore).
- ***revert***: Revert a previous commit.

# Specify the scope of the changes

Specify the areas where the changes were made.

- ***auth***: Authorization and authentication.
- ***ui***: User interface.
- ***api***: Server or client APIs.
- ***core***: Core application functionality.
- ***config***: Configuration files.
- ***deps***: Dependency updates.
- ***tests***: Unit, integration, or e2e tests.
- ***docs***: Documentation.
- ***db***: Changes to the database.
- ***build***: Build scripts or build files.

# Description 

Write a short description. it should be brief and complete

- ***ui***: "Fix button display on small screens"
- ***api***: "Add endpoint for file uploads"
- ***core***: "Optimize cost calculation logic"
- ***docs***: "Update project setup section"
- ***tests***: "Add e2e tests for login feature"
- ***deps***: "Upgrade dependencies to latest versions"
- ***build***: "Configure build to support new plugins"

# Specify the breaking changes

If the change is critical, important, or incompatible with previous versions, etc., specify this in the message.

Use an exclamation mark (!) after the main commit signature: ``` type(area)!: ```

> P.S. I'm having some trouble with (!). I think it's because of my terminal. To indicate breaking changes, I write (BC) 

# Examples 

Take a look at these examples

```
# type(area): desc
fix(ui): fix button alignment issue

# type: desc
docs: update API documentation

# type(area): desc
feat(api): remove support for old endpoints

# type(area)!: desc (BREAKING CHANGES!)
feat!: send an email to the customer when a product is shipped

# type: desc
revert: revert commit c12345
```
