# Example of Helm application for multiple environments

This is single application that has different configurations for 3 different environments

* For the [QA](values-qa.yaml) environment
* For the [Staging](values-staging.yaml) environment
* For the [Production](values-prod.yaml) environment

The repository also contains several Codefresh pipelines

* [Build only pipeline](pipelines/0_build_only.yml)
* [Basic deployment](pipelines/1_basic_deploy.yml)
* [Environment Board](pipelines/2_environment_board.yml)
* [Manual approval](pipelines/3_approval.yml)
* [Staging deployment](pipelines/4a_staging.yml)
* [Production deployment](pipelines/4b_production.yml)

See the [documentation page](https://codefresh.io/docs/docs/ci-cd-guides/environment-deployments/) for more details.

[![Codefresh build status]( https://g.codefresh.io/api/badges/pipeline/mikhail-klimko/helm%2Fhelm-promotion-deploy?type=cf-2&repoName=notreal&key=eyJhbGciOiJIUzI1NiJ9.NWYwNDhkODVlYjEwN2Q1MmIxNmM1M2Vh.r9DkHUm8oUeqLCwtNU9AyPwo5ScFIQUSY4xJUrcqab8)]( https://g.codefresh.io/pipelines/edit/new/builds?id=60460ee2e93681c312c85839&pipeline=helm-promotion-deploy&projects=helm&projectId=6045fe4a981f63a0de2cdbbb)
