# Automation with Docker for CI Workflows | Updated

[![Lint Code Base](https://github.com/aravindgshanthi/docker-ci-automation/actions/workflows/call-super-linter.yaml/badge.svg)](https://github.com/aravindgshanthi/docker-ci-automation/actions/workflows/call-super-linter.yaml)

> For Docker Community All Hands 2022

[![All-Hands Automation with Docker](https://user-images.githubusercontent.com/792287/160971371-0ae75c14-1ea4-4a11-82dc-f35f96184fa3.gif)](https://www.youtube.com/watch?v=aZzV6X7XhyI)

Watch the walkthrough of this repo: [https://www.youtube.com/watch?v=aZzV6X7XhyI](https://www.youtube.com/watch?v=aZzV6X7XhyI)

See this repositories' [`.github/workflows`](.github/workflows) directory for the below example workflows, ordered by number, simple to complex.

These examples are focused on five of Docker's [official GitHub Actions](https://github.com/marketplace?type=actions&query=publisher%3Adocker+).

These examples are based on three workflow diagrams on progressively more complex automation pipelines:

1. [Basic code PR automation workflow](diagrams/basic-code-pr.png)
2. [Intermediate code PR automation workflow](diagrams/intermediate-code-pr.png)
3. [Advanced code PR automation workflow](diagrams/advanced-code-pr.png)

I also have a [LIVE course on learning GitHub Actions for DevOps automation and Argo CD](https://bret.courses/autodeploy) for GitOps-style deployments.

## Example Workflows

1. Basic Docker build
2. Adding BuildKit cache
3. Adding multi-platform builds
4. Adding metadata to images
5. Adding comments with image tags to PRs
6. Adding CVE scanning
7. Adding CVE security reporting
8. Adding unit testing
9. Adding integration testing
10. Adding Kubernetes smoke tests
11. Adding job parallelizing for mucho speed

## GitHub Actions shown in these examples

- [Docker Login](https://github.com/marketplace/actions/docker-login)
- [Docker Setup Buildx](https://github.com/marketplace/actions/docker-setup-buildx)
- [Docker Setup QEMU](https://github.com/marketplace/actions/docker-setup-qemu)
- [Docker Metadata](https://github.com/marketplace/actions/docker-metadata-action)
- [Docker Build and Push](https://github.com/marketplace/actions/build-and-push-docker-images)
- [Aqua Security Trivy CVE Scan](https://github.com/marketplace/actions/aqua-security-trivy)
- [Super-Linter](https://github.com/marketplace/actions/super-linter)
- [Setup k3d](https://github.com/marketplace/actions/absaoss-k3d-action)
- [Find Comment](https://github.com/marketplace/actions/find-comment)
- [Create or Update Comment](https://github.com/marketplace/actions/create-or-update-comment)

## This repository is part of my example DevOps repos on GitHub Actions

- [aravindgshanthi/github-actions-templates](https://github.com/aravindgshanthi/github-actions-templates) - Main reusable templates repository
- [aravindgshanthi/super-linter-workflow](https://github.com/aravindgshanthi/super-linter-workflow) - Reusable linter workflow
- [aravindgshanthi/docker-build-workflow](https://github.com/aravindgshanthi/docker-build-workflow)- Reusable docker build workflow
- (you are here) [aravindgshanthi/docker-ci-automation](https://github.com/aravindgshanthi/docker-ci-automation) - Step by step video and example of a Docker CI workflow
- [My full list of container examples and tools](https://github.com/aravindgshanthi)

## More reading

[Docker Build/Push Action advanced examples](https://github.com/docker/build-push-action/tree/master/docs/advanced)
[My full list of container examples and tools](https://github.com/aravindgshanthi)

## 🎉🎉🎉 Join my container DevOps community 🎉🎉🎉

- [My "Vital DevOps" Discord server](https://devops.fan)
- [My weekly YouTube Live show](https://bret.live)
- [My courses and coupons](https://www.aravindgshanthi.com/courses)
