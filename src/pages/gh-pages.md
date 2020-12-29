---
layout: base
permalink: /gh-pages/
eleventyNavigation:
  key: GitHub Pages
---

# Using GitHub Pages

## Configure GitHub Pages

You will need to configure GitHub Pages on your project. That should just need enabling and selecting the **`gh-pages`** branch.

## Triggering build of "gh-pages" branch

The configuration in the github/workflows folder will trigger [GitHub Actions](https://github.com/features/actions) deploy to a branch called **`gh-pages`** whenever a change is detected on the **`main`** branch.

## Other things

Pathprefix in eleventy.js needs to match the repo name.
