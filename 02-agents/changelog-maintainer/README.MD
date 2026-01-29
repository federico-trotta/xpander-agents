# Weekly Changelog Maintainer

This AI agent that automatically creates release notes for your software documentation and pushes them on a new PR.

It analyzes a target repository, searches for merged PRs, and creates a summary of the merged PRs and regroup the content in the following categories:
- New features.
- Enhancements.
- Bux fixes.

It will write this content in a changelog file. Then, it will open a new branch on the repository and open a new PR. When the process is complete, it will send you a notification via email.

[Read how to set it up and how to use it in the documentation](https://docs.xpander.ai/Examples/12-changelog-maintainer).