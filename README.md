# badreads

Minimal copy of Goodreads for tracking read books, want to read books, and basic
user profiles and authentication.

**MINIMAL README. WIP.**

## Contribution

How to contribute?

1. Fork this repository.
2. Add changes to your repository on a branch (`git checkout`).
3. Make a pull request.
4. Profit.

## Contribution Guidelines

- Git commits must be properly named. It does not have to follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/),
  but I encourage that format.
- Commits need to be traceable, with usually referenced issues in the commit message
  itself:
  - `References #4` for example, references the #4 object in this GitHub repository,
    which can be an issue or a pull request. Use this when your commit is related
    to it.
  - `Fixes #4` or `Closes #4`, same mechanism. Use this when your commit should make
    the project board consider the task as "Done" or "Closed".
- Try to keep pull requests one-topic only. It may be a giant issue such as "Implement
  Authentication", which is discouraged but not disallowed. Try to keep pull requests
  small, such as "Implement Login for Authentication" instead.
- All code needs to be formatted, and properly linted by Actions before it's considered
  fit for review.
