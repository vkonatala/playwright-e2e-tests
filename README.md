# Instructions and Notes

## Install node project commands

- `npm init`

## Install

1. playwright
   - `npm init playwright@latest`
2. Check if installed correctly
   - `mpx playwright --help`

## Playwright Project Folder Structure

    |-- .github/
    |-- .vscode/
    |    |-- mcp.json
    |-- config/
    |-- data/
    |    |-- constants.json
    |-- debug/
    |-- logs/
    |-- node_modules/
    |-- playwright-report/
    |-- resources/
    |-- tests/
    |     |-- api/
    |     |-- demo/
    |     |-- devices/
    |     |-- e2e/
    |     |-- functional/
    |     |-- helpers/
    |     |-- page-objects/
    |-- tests-examples/
    |-- .env.example
    |-- .gitignore
    |-- package-lock.json
    |-- package.json
    |-- playwright.config.ts
    |-- README.md

## Recommended VSCode Extensions

    - vscode-icons
    - Prettier - Code formatter
    - Path Intellisense
    - npm Intellisense
    - DotENV
    - JAvascript (ES6) code snippets
    - .gitignore Generator

## Setup Git Repo

    1. Git commands
    - `git init`
    - `git status`
    - `git add .`
    - `git commit -m <commit-message> `

    2. Git ignores the following folders & files
    - debug/
    - logs/
    - .env
    - allure-results
    - test-examples/
    - example.*
    - *.log
