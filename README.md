# Github Pages React Actions
Github actions for deploying Create React App to GitHub Pages.

## Features
* Run tests on PR
* Runs Lighthouse tests on PR with test artifacts
* Runs Cypress tests with videos and screenshot test artifacts
* Configues Github Pages
* Deploys on push to master branch

## Usage
1. Copy `.github` folder contents to your project.
1. Setup `homepage` to GitHub Pages URL
1. Create personal access token with `repo` permissions in `Settings > Developer Settings > Personal Access Tokens`
1. Add personal access token as secret with name  `ACCESS_TOKEN`

## Badges

![Lighthouse](https://github.com/briansunter/github-pages-react-actions/workflows/Lighthouse/badge.svg)
![Unit Tests](https://github.com/briansunter/github-pages-react-actions/workflows/Run%20npm%20tests%20on%20PR/badge.svg)
