# Continuous Integration with AWS CodeBuild

## Introduction

- CodeBuild is a fully managed build service in the cloud.
- Compiles your source code, runs unit tests, and produces artifacts that are ready to deploy
- Eliminates the need to provision, manage, and scale your own build servers.
- It provides prepackaged build environments for the most popular programming languages and build tools such as Apache Maven, Gradle, and more.
- We can also customize build environments in CodeBuild to use ourown build tools.
- Scales automatically to meet peak build requests.

## How CodeBuild works?

### Step-01: Create CodeBuild Project

- Create a S3 bucket and folder
- Create CodeBuild project
- Start build, Verify build logs, Verify build phase details

### Step-02: Create a buildspec.yml & Start Build

- Create buildspec.yml and check-in code
- Start build, Verify build logs, Verify build phase details
- Download the artifacts from S3, unzip and review
- Run one more build and see versioning in S3.

### Step-03: Create Build Notifications
