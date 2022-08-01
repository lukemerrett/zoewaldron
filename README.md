# Zoe Waldron

Personal website for Zoe Waldron

## Pre-requisites

* Hugo (`brew install Hugo`)

## Commands

```bash

# Create a new page 
hugo new pages/my-first-page.md

# Start server locally, show all draft pages as if published
hugo server -D

# Build the static pages, outputs to the ./public/ directory by default but we use ./docs/ for github pages
hugo -d docs
```
