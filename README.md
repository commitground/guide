# Welcome to join as a contributor

Thanks for contributing to the Commitground project. This document is about general conventions for Commitground project. However each sub projects may have their own conventions or policie.


If you want to be a full time contributor for Commitground, please contact [Commitplay team](https://commitplay.io). Click [here](mailto:join@commitplay.io) to send an email.

# Branching Convention

Use [Git flow](https://nvie.com/posts/a-successful-git-branching-model/)

- `master`: Latest released versions.
- `pre-release`: Beta versions. This branch is for preparing a release and does not mean a released version.
- `develop`: Alpha versions
- `group/title`: Branches to merge into `develop`, `pre-release`, or `master`.
  - groups
    - feature: Branch to develop a specific feature. If they are planned for a specific release version, merge them into the `release/version`. Otherwise, merge them into the develop branch.
    - `bug/`: Branches to fix bugs which are related to the registered issues.
    - `hotfix/`: Branches to fix a released version. Merge them into `master` branch & `develop` branch
    - `release/`: Branches to prepare a specific release version. Merged them into `pre-release` & `develop` branch
  - examples
    Branch name should be descriptive
    - `feature/reward-contract-for-contributor`
    - `bug/issue-32-selection-error`

**Please work with your forked repository. And sync the forked repo's each branches to the origin(commitground)**
