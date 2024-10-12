# Gitflow Workflow Simulator

This project demonstrates the Gitflow workflow, showcasing best practices for managing version control in a team environment. The repository simulates a real-world project with multiple branches, including feature development, bug fixes, and release management.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Gitflow Workflow](#gitflow-workflow)
- [Branching Strategy](#branching-strategy)
- [Key Features](#key-features)

## Overview

This repository is a simulation of a version-controlled project using the **Gitflow workflow**. It demonstrates the proper use of branches for development, releases, and hotfixes. Through this project, you will learn how to:
- Create and manage branches for features, releases, and hotfixes.
- Merge changes using fast-forward and merge commits.
- Resolve merge conflicts when they arise.
- Tag releases and ensure smooth version management.

### GitHub URL:
You can find the repository here: [GitHub Project](https://github.com/MohamadAbdelmoniem/GitHub_Project).

## Installation

1. **Clone the repository using GitHub Desktop**:
   - Open GitHub Desktop.
   - Click on `File > Clone Repository`.
   - Paste the repository URL: `https://github.com/MohamadAbdelmoniem/GitHub_Project`.
   - Choose a local directory to save the project.

2. **Ensure Git is installed**: 
   Verify you have Git installed by running:
   ```bash
   git --version
   ```

## Gitflow Workflow

This project follows the **Gitflow branching model**, which includes the following key branches:

- **master**: Holds the production-ready code.
- **develop**: Active development happens here, and it is the default branch for integrating features.
- **feature/**: Feature branches are created off `develop` to work on new features.
- **release/**: Release branches are created to finalize the version for production.
- **hotfix/**: Used for critical fixes applied directly to `master` and merged back into `develop`.

## Branching Strategy

Here’s how the different types of branches work:

1. **Feature Branches**:
   - Naming: `feature/feature-name`
   - Created from `develop` and merged back into `develop` when the feature is complete.

2. **Release Branches**:
   - Naming: `release/vX.X`
   - Created when preparing a new production release. It allows for last-minute bug fixes and version updates.

3. **Hotfix Branches**:
   - Naming: `hotfix/bug-name`
   - Created when an issue is found in production (`master`). Fixed and merged back into `master` and `develop`.

### Example Workflow

1. Start a feature using GitHub Desktop:
   - In GitHub Desktop, create a new branch based on `develop`.
   - Make your changes, then commit them to the feature branch.

2. Merge the feature back into `develop` using GitHub Desktop:
   - In GitHub Desktop, switch to the `develop` branch and select `Branch > Merge into current branch` to merge your feature branch.

3. Prepare for release using GitHub Desktop:
   - Create a new release branch from `develop`, fix any bugs, and merge the release branch into `master` using the same merging process.

## Key Features

- **Branching Strategy**: Simulates real-world feature development and bug fixing using Gitflow.
- **Merge Conflicts**: Learn how to resolve merge conflicts and understand the significance of merge commits.
- **Tagging Releases**: Proper version tagging (`v1.00`, `v1.01`) ensures smooth version control for releases.
- **Hotfix Management**: Manage production fixes and ensure they’re integrated into active development.
