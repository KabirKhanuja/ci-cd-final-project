# CI/CD Tools and Practices Final Project

[![CI workflow](https://github.com/KabirKhanuja/ci-cd-final-project/actions/workflows/workflow.yml/badge.svg)](https://github.com/KabirKhanuja/ci-cd-final-project/actions/workflows/workflow.yml)

## Project Name

**ci-cd-final-project**: Hit Counter Service CI/CD Pipeline

## Project Details

* **Course:** CI/CD Tools and Practices (IBM, Coursera)
* **Author:** Kabir Singh Khanuja
* **Application:** Hit Counter Service, a Python Flask REST API
* **CI:** GitHub Actions workflow in `.github/workflows/workflow.yml` that lints with flake8 and runs unit tests with nose
* **CD:** Tekton tasks in `.tekton/tasks.yml` (cleanup and nose) and an OpenShift pipeline with the steps cleanup, git-clone, flake8, nose, buildah and deploy

This repository contains my Final Project for the Coursera course **CI/CD Tools and Practices**. It builds a CI pipeline with GitHub Actions (flake8 linting and nose unit tests) and a CD pipeline with Tekton tasks on OpenShift that clean the workspace, clone the code, lint, test, build the image and deploy the Hit Counter Service.

## Usage

This repository is to be used as a template to create your own repository in your own GitHub account. No need to Fork it as it has been set up as a Template. This will avoid confusion when making Pull Requests in the future.

From the GitHub **Code** page, press the green **Use this template** button to create your own repository from this template.

Name your repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks


## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>
