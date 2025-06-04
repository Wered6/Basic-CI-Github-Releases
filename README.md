# 🛠️ Automated GitHub Release Script for Unreal Engine C++ Projects

This Bash script automates the creation of GitHub releases whenever C++ source files (`.cpp` / `.h`) are pushed to the `main` or `dev` branches.

- Automatically checks for `.cpp` or `.h` file changes in each push.
- Creates a zip archive of `Binaries/Win64` using PowerShell.
- Tags the commit with a timestamped, commit-message-based tag.
- Publishes a GitHub release with the zipped binaries.
- Only runs when pushing to `main` or `dev`.
