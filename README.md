<!-- markdownlint-disable MD041 MD010 -->
[![cicd-local](https://github.com/jmpa-io/root-template/actions/workflows/cicd-local.yml/badge.svg)](https://github.com/jmpa-io/root-template/actions/workflows/cicd-local.yml)
[![cicd](https://github.com/jmpa-io/root-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/jmpa-io/root-template/actions/workflows/cicd.yml)
[![README-local](https://github.com/jmpa-io/root-template/actions/workflows/README-local.yml/badge.svg)](https://github.com/jmpa-io/root-template/actions/workflows/README-local.yml)
[![README](https://github.com/jmpa-io/root-template/actions/workflows/README.yml/badge.svg)](https://github.com/jmpa-io/root-template/actions/workflows/README.yml)

<div align="center">

# `root-template`

</div>

```diff
+ 🌱 The root template used by all other repositories in this org.
```

## How do I use this template?

1. Using a <kbd>terminal</kbd>, download the child repository locally.

2. From the root of that child repository, run:
```bash
git remote add template https://github.com/jmpa-io/root-template.git
git fetch template
git merge template/main --allow-unrelated-histories
# then fix any merge conflicts as required & 'git push' when ready.
```
