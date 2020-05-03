# Github Pages React Actions
Github actions for deploying Create React App to GitHub Pages.

## Features
* Run tests on PR
* Configues Github Pages
* Deploys on push to master branch

## Usage
Copy `.github` folder contents to your project.

Setup 

1. Create personal access token with `repo` permissions in `Settings > Developer Settings > Personal Access Tokens`
1. Add personal access token as secret with name  `ACCESS_TOKEN`

## Badges

![Lighthouse](https://github.com/briansunter/github-pages-react-actions/workflows/Lighthouse/badge.svg)
![Unit Tests](https://github.com/briansunter/github-pages-react-actions/workflows/Run%20npm%20tests%20on%20PR/badge.svg)
