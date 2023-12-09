# CI/CD with GitHub Actions

Welcome to my GitHub repository where I'm exploring Continuous Integration (CI) and Continuous Deployment (CD) using GitHub Actions.

## Overview

This repository serves as a playground to experiment with automating various aspects of the software development lifecycle, from building and testing to deploying applications.

## Workflows

### CI Workflow

The [action_1.yml](.github/workflows/ci.yml) workflow is triggered on every push to the `master` branch. It includes basic steps to check out the code, set up Node.js, install dependencies, and build the project.

### PR Created Workflow

The [action_1.yml](.github/workflows/pr_created.yml) workflow runs when a pull request is opened for the `master` branch. It's a starting point for exploring actions specific to pull request creation.

## How to Use

Feel free to explore the workflows and adapt them to your own projects. Experiment with different actions, customize the workflows, and see how GitHub Actions can streamline your development processes.

## Contributions

If you have suggestions or improvements, please open an issue or submit a pull request. This repository is a collaborative space for learning and sharing knowledge.

Happy coding!
