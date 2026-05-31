# Contributing

Thank you for contributing!

## Workflow

1. Sync your local repository:

```bash
git checkout main
git pull origin main
```

2. Create a feature branch:

```bash
git checkout -b feature/short-description
```

Examples:

```bash
feature/user-authentication
feature/order-api
bugfix/login-validation
```

3. Make your changes and commit them with clear commit messages:

```bash
git commit -m "Add user authentication endpoint"
```

4. Push your branch:

```bash
git push origin feature/short-description
```

5. Open a Pull Request (PR) against `main`.

6. Request a review from another team member.

7. Address any review comments and update the PR if needed.

8. After approval and passing checks, merge the PR .

9. Delete the branch after merging.

## Rules

* Do not commit directly to `main`.
* Keep pull requests focused on a single task.
* Write meaningful commit messages.
* Ensure the project builds and tests pass before creating a PR.
* Review teammates' code before approving.

## Branch Naming

* `feature/...` – New functionality
* `bugfix/...` – Bug fixes
* `refactor/...` – Code improvements without behavior changes
* `docs/...` – Documentation updates
