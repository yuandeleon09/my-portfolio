---
title: "Git and GitHub: A Practical Workflow for Student Developers"
date: "2026-08-15T09:00:00"
excerpt: "How I use Git and GitHub to keep development work organized and recoverable."
tags: ["Git", "GitHub", "Software Development", "IT"]
---

# Git and GitHub: A Practical Workflow for Student Developers

When a project starts becoming larger, manually keeping copies of folders can become confusing. Git solves part of this problem by tracking changes to a project.

GitHub provides a remote place where Git repositories can be stored and shared.

## A simple workflow

A basic workflow I use is:

```bash
git status
git add .
git commit -m "Update portfolio"
git push
```

`git status` helps me understand what changed before I commit anything.

`git add` stages the changes.

`git commit` creates a checkpoint with a message.

`git push` sends the committed changes to the remote repository.

## Branches

Branches are useful when I want to work on something without immediately changing the main version.

For example:

```bash
git checkout -b feature/projects
```

After testing the feature, the changes can be merged into the appropriate branch.

## GitHub Pages

GitHub can also be used to publish static websites. This is useful for portfolios because a React application can be built into static files and deployed through a Pages branch.

The important lesson is that the source project and the generated production files can have different purposes.

## What I learned

Git is not only a backup system. It gives a project a history. When something breaks, previous commits can help identify what changed and provide a recovery point.

For student projects, learning Git early makes collaboration and project management much easier.
