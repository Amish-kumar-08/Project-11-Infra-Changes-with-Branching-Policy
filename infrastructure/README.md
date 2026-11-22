# Infrastructure Changes

## Overview

This directory contains documentation related to infrastructure changes made as part of Project 11: Infrastructure Changes with Branching Policy.

The purpose is to demonstrate how infrastructure-related modifications can be managed through Git feature branches and Pull Requests.

## Objective

- Maintain infrastructure-related documentation.
- Make changes separately from the main branch.
- Track modifications using Git commits.
- Submit changes through Pull Requests.

## Changes Made

The infrastructure update is documented in this directory to demonstrate the feature branching workflow.

## Git Workflow

### 1. Create Feature Branch

```bash
git checkout -b feature/infra-update
```

### 2. Make Infrastructure Changes

Update the infrastructure documentation or configuration files.

### 3. Stage Changes

```bash
git add .
```

### 4. Commit Changes

```bash
git commit -m "Add infrastructure updates"
```

### 5. Push Feature Branch

```bash
git push -u origin feature/infra-update
```

### 6. Create Pull Request

- Open the repository on GitHub.
- Select the Pull Requests tab.
- Click New Pull Request.
- Select `main` as the base branch.
- Select `feature/infra-update` as the compare branch.
- Review the changes and create the Pull Request.

### 7. Merge Changes

After reviewing the Pull Request, merge it into the main branch.

## Expected Outcome

Infrastructure-related changes are maintained separately in a feature branch and merged into the main branch through a Pull Request review process.

## Technologies

- Git
- GitHub
- Git Branching
- Pull Requests
