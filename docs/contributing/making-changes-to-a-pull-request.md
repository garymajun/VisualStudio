# Making changes to a Pull Request

When a Pull Request branch is [checked out](review-a-pull-request-in-visual-studio.md) you can commit changes to it and push and pull like any other branch. If the Pull Request branch is located in a fork and was checked out from the GitHub Pull Request details pane, then a remote to that fork will be created automatically and the branch set to track the fork branch.

## Pulling Changes

If a Pull Request is checked out and the author adds new commits to the branch, then the option will be given to pull the changes locally. This works both for Pull Requests from the same repository and from a fork.

TODO: screenshot

## Pushing Changes

If you make commits locally to a Pull Request branch then you can push the changes to the remote branch. You can also do this from `git` itself or from the Visual Studio Team Explorer **Sync** view.

> Note: for this to work with Pull Requests that come from forks, then you must be a maintainer on the repository and the Pull Request submitter must have checked [Allow edits from maintainers](https://help.github.com/articles/allowing-changes-to-a-pull-request-branch-created-from-a-fork/) when submitting the Pull Request.

If there are remote changes to the pull request branch then they must be pulled before you can push your changes.