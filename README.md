
# Awesome GitLab Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of open-source tools built specifically for GitLab.

## Contents

- [Configuration & Governance](#configuration--governance)
- [CI/CD](#cicd)
- [Monitoring & Analytics](#monitoring--analytics)
- [Migration](#migration)
- [Infrastructure & Operations](#infrastructure--operations)
- [CLI & API](#cli--api)
- [Utilities](#utilities)

## Configuration & Governance

- [GitLabForm](https://github.com/gitlabform/gitlabform) - Manage GitLab configurations as code using YAML.
- [GitLab Triage](https://gitlab.com/gitlab-org/ruby/gems/gitlab-triage) - Automate triage of GitLab issues, merge requests, and epics with YAML-defined policies.
- [MergeBot](https://github.com/Gasoid/merge-bot) - Automate GitLab merge request checks, merges, branch updates, pipeline reruns, and reviewer assignment.

## CI/CD

- [gitlab-auto-merge-request](https://gitlab.com/tmaier/gitlab-auto-merge-request) - Automatically open a GitLab merge request from CI when none exists for a feature branch.
- [gitlab-autopilot](https://github.com/vigohan95/gitlab-autopilot) - Gate merge requests on a written policy file, auto-merge when it holds, and roll back to the last release with a GitLab Incident when a scheduled health check fails.
- [gitlab-ci-local](https://github.com/firecow/gitlab-ci-local) - Run GitLab CI jobs locally.
- [glsec](https://gitlab.com/glsec-io/glsec) - Lint GitLab CI configuration for security issues.
- [PipeIntel](https://gitlab.com/gitlab-org/professional-services-automation/tools/utilities/pipeintel) - Scan GitLab CI pipelines for security and correctness issues with OPA policies and ShellCheck.
- [Pipeline Cleaner](https://gitlab.com/gitlab-org/professional-services-automation/tools/utilities/pipeline-cleaner) - Delete old completed pipelines, with dry-run and CI/CD component support.

## Monitoring & Analytics

- [Evaluate](https://gitlab.com/gitlab-org/professional-services-automation/tools/utilities/evaluate) - Assess GitLab instances for migration by reporting user and project data, feature usage, and potential migration issues.
- [GitLab CI Pipelines Exporter](https://github.com/mvisonneau/gitlab-ci-pipelines-exporter) - Export GitLab pipeline metrics for Prometheus.

## Migration

- [Congregate](https://gitlab.com/gitlab-org/professional-services-automation/tools/migration/congregate) - Orchestrate migrations from GitHub, Bitbucket, GitLab, Azure DevOps, and CodeCommit to GitLab.

## Infrastructure & Operations

- [GitLab Operator](https://gitlab.com/gitlab-org/cloud-native/gitlab-operator) - Manage the lifecycle of GitLab instances on Kubernetes or OpenShift.

## CLI & API

- [GitLab CLI (glab)](https://gitlab.com/gitlab-org/cli) - Manage GitLab issues, merge requests, pipelines, releases, and repositories from the command line.
- [python-gitlab](https://github.com/python-gitlab/python-gitlab) - Python library for the GitLab API.

## Utilities

- [Curate](https://gitlab.com/gitlab-org/professional-services-automation/tools/utilities/curate) - Organize GitLab project lists for migration planning.
- [GitLab RPS Analyzer](https://gitlab.com/gitlab-org/professional-services-automation/tools/utilities/gitlab-rps-analyzer) - Analyze GitLabSOS and KubeSOS logs to estimate reference architecture sizing and request load.
