# Contributing

## General Workflow
The repository has two main branches:

- The default `staging`-branch. This branch contains the latest version of the project, which might be incomplete or unstable, but builds successfully.
- The `production`-branch. This branch contains the latest stable release version of the project.

1. For each feature request, a feature request issue must be created.
2. For each bug report, a bug report issue must be created.
3. From the issue, a new branch must be created. The branch must start with the corresponding issue number.
4. For each issue, a pull request to staging must be created. If a pull request to another branch is necessary, there is an explanation in the pull request description.
5. The feature is implemented on the feature branch
6. The TODO-list in the issue is completed. The pull request must be marked as ready.
7. The changes of pull requests must be reviewed before merging can be completed.
8. If further changes are necessary, threads are opened on the corresponding code positions and the pull request is marked as draft. Once all threads are resolved, continue in Step 6.
9. If no further changes are necessary, all threads are resolved and the reviews are completed successfully, the pull request can be merged into staging.

- For releases, a release issue and a pull request are created. Code reviews are performed according to the above steps. For the releases, tags and releases in github are created.
- Issues (feature requests, bug reports) and pull requests must use the appropriate templates and should be as helpful as possible in their explanations.