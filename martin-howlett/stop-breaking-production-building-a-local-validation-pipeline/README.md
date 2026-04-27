# Stop Breaking Production: Building a local validation pipeline

## Abstract

Ever pushed code that failed its Pester tests? Or merged a PR that violated Script Analyzer rules? Or even forgotten to bump your module version, causing code conflicts?

In this talk, we will explore creating a local CI/CD pipeline using Invoke-Build that removes the manual work associated with preparing a PR for review. Automate validating PSSA linting, Pester testing, version validation, changelog verification, and JSON validation in a single CLI command. No AWS credits or GitHub Actions syntax is needed. Handle everything in your own shell, on your machine.

Writing PowerShell is the interesting part. The tedious work comes when validating your code passes tests and handling all the administrative tasks to polish your PR. Remove this repetitive, but important work and standardize it across your team with a fast, local validation pipeline.
