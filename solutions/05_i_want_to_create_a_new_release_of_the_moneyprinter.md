# I want to create a new release of the MoneyPrinterV2 tool, but I don't know how to use the GitHub Actions workflow.

_Create a new release of the MoneyPrinterV2 tool using the GitHub Actions workflow._

## Steps

1. First, create a new branch for the release by running the command `git checkout -b release/v1.0`.
2. Next, update the version number in the `__init__.py` file to match the new release version.
3. Commit the changes by running the command `git add .` and then `git commit -m 'Bump version to v1.0'`.
4. Push the changes to the remote repository by running the command `git push origin release/v1.0`.
5. Create a new release on GitHub by clicking the 'Releases' tab and then clicking the 'New release' button, and select the `release/v1.0` branch as the target.

## Pitfalls

- Forgetting to update the version number can result in the wrong version being released.