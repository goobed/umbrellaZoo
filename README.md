# Jenkins Multibranch Pipeline

This repository is designed to be used with a Jenkins Multibranch Pipeline. It contains the necessary configuration files and code for automating builds and deployments for multiple branches.

## Table of Contents
- [Pipeline Overview](#pipeline-overview)
- [Repository Structure](#repository-structure)
- [Jenkinsfile](#jenkinsfile)

## Pipeline Overview

The Jenkins Multibranch Pipeline is a project type that automatically detects branches in the repository and creates a pipeline for each branch. This allows for continuous integration and delivery (CI/CD) on multiple branches with minimal setup.

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

### Key Features:
- Automated pipeline creation for new branches.
- Separate build and test jobs for each branch.
- Supports feature, development, and production branches.
- Integration with source control to trigger builds on code changes.

## Repository Structure

```bash
├── Jenkinsfile               # Main Jenkins pipeline script.
├── src/                      # Source code directory.
├── tests/                    # Test files for the project.
├── README.md                 # Project documentation.
└── .jenkins/                 # Optional Jenkins-specific configuration.
