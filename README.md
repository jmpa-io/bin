<!-- markdownlint-disable MD041 MD010 -->
[![depot](https://github.com/jmpa-io/depot/actions/workflows/local-cicd.yml/badge.svg)](https://github.com/jmpa-io/depot/actions/workflows/local-cicd.yml)
[![depot](https://github.com/jmpa-io/depot/actions/workflows/local-README.yml/badge.svg)](https://github.com/jmpa-io/depot/actions/workflows/local-README.yml)

<p align="center">
  <img src="docs/logo.png"/>
</p>

# `depot`

```diff
+ 📦 A monorepo used to store org-wide resources used by other repositories in
+ this org, such as pipelines, scripts, mechanisms to deploy, and templates. Used
+ in conjunction with https://github.com/jmpa-io/root-template.
```

## 🧰 Scripts

Script|Description
:---|:---
[bin/10-lint.sh](bin/10-lint.sh) | Lints everything!
[bin/20-test.sh](bin/20-test.sh) | Tests everything!
[bin/30-deploy.sh](bin/30-deploy.sh) | Deploys the given cloudformation template to the authed AWS account.
[bin/40-sync.sh](bin/40-sync.sh) | Uploads the dist directory to an expected S3 bucket in the authed AWS account.
[bin/clear-action-runs.sh](bin/clear-action-runs.sh) | Clears all GitHub Action runs for a given GitHub repository.
[bin/commit.sh](bin/commit.sh) | As the GitHub Actions user, this script commits back to the git repository it is executed in.
[bin/dispatch.sh](bin/dispatch.sh) | Trigger a repository_dispatch event in ALL repositories in a given GitHub org.
[bin/invalidate-cloudfront-distribution.sh](bin/invalidate-cloudfront-distribution.sh) | Invalidates files in the CloudFront cache, for the repostitory this script is execututed in - best to be run in a website repository.
[bin/list-repository-topics.sh](bin/list-repository-topics.sh) | Lists ALL topics for a given GitHub repository in a given GitHub org.
[bin/README.sh](bin/README.sh) | Generates a README.md, using a found README.md template.

