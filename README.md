<!-- badges: start (generate GitHub workflow status badges from the 'Actions' tab on github.com by selecting a workflow, clicking '...' then 'Create status badge'. See also https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge) -->

[![GitHub Actions Demo](https://github.com/rmgpanw/rmarkdown-basics/actions/workflows/github-actions-demo.yml/badge.svg)](https://github.com/rmgpanw/rmarkdown-basics/actions/workflows/github-actions-demo.yml)
[![pages-build-deployment](https://github.com/rmgpanw/rmarkdown-basics/actions/workflows/pages/pages-build-deployment/badge.svg?branch=main)](https://github.com/rmgpanw/rmarkdown-basics/actions/workflows/pages/pages-build-deployment)
[![Launch RStudio Cloud](https://img.shields.io/badge/RStudio-Cloud-blue)](https://rstudio.cloud/project/4700482)

<!-- badges: end -->

A basic template repository showcasing R Markdown using GitHub Actions (minimally adapted from this [example](https://docs.github.com/en/actions/quickstart)) and a simple GitHub Pages website at https://rmgpanw.github.io/rmarkdown-basics/. 

To activate GitHub Pages, go to repository 'Settings' on github.com, select the 'Pages' tab, then under 'Branch' select either `main` or `gh-pages` with `/ (root)` folder (the latter option relies on GitHub Actions to copy `index.html` and any other selected website files to a `docs` directory, also creating a new file [`GithubActionsOnly.md`](https://rmgpanw.github.io/rmarkdown-basics/GithubActionsOnly.md)).

Click on the RStudio badge above to experiment.
