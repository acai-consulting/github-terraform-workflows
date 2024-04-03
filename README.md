# GitHub Actions - Reusable Terraform Workflows

<!-- LOGO -->
<a href="https://acai.gmbh">    
  <img src="https://github.com/acai-consulting/acai.public/raw/main/logo/logo_github_readme.png" alt="acai logo" title="ACAI" align="right" height="75" />
</a>

<!-- SHIELDS -->
[![Latest Release][release-shield]][release-url]

<!-- DESCRIPTION -->
Leverage [GitHub Workflows][github_workflows_link] for implementing advanced Terraform pipelines efficiently.
This setup conducts various static code analyses directly within GitHub Actions, including formatting checks, documentation verification, linting, and adherence to security best practices. Additionally, Terraform Plan and Apply operations are seamlessly integrated with [Terraform Cloud][tfe_intro] through API calls. The workflows also support Terraform module testing using [Terratest](terratest) and facilitate the automatic release of new module versions.


## Referenced Github Actions

The reusable Github Workflows include the following public Github Actions:

- [`@terraform-docs/gh-actions`](https://github.com/terraform-docs/gh-actions)
- [`@actions/checkout`](https://github.com/actions/checkout)
- [`@actions/setup-go`](https://github.com/actions/setup-go)
- [`@ad-m/github-push-action`](https://github.com/ad-m/github-push-action)
- [`@cycjimmy/semantic-release-action`](https://github.com/cycjimmy/semantic-release-action)
- [`@hashicorp/setup-terraform`](https://github.com/hashicorp/setup-terraform)
- [`@octokit/request-action`](https://github.com/octokit/request-action)
- [`@reviewdog/action-tflint`](https://github.com/reviewdog/action-tflint)
- [`@reviewdog/action-trivy`](https://github.com/reviewdog/action-trivy)
- [`@terraform-linters/tflint-load-config-action`](https://github.com/terraform-linters/tflint-load-config-action)

## Leveraged Repos

https://github.com/nuvibit/github-terraform-workflows

<!-- AUTHORS -->
## Authors
This repository is maintained by [acai][acai-url].

<!-- LICENSE -->
## License
This repository is licensed under Apache 2.0
<br />
See [LICENSE][license-url] for full details.

<!-- COPYRIGHT -->
<br />
<br />
<p align="center">Copyright &copy; 2024 ACAI GmbH</p>

<!-- MARKDOWN LINKS & IMAGES -->
[acai-shield]: https://img.shields.io/badge/maintained%20by-acai.com-%235849a6.svg?style=flat&color=1c83ba
[acai-url]: https://acai.com
[release-shield]: https://img.shields.io/github/v/release/acai/github-terraform-workflows?style=flat&color=success
[release-url]: https://github.com/acai-consulting/github-terraform-workflows/releases
[contributors-url]: https://github.com/acai-consulting/github-terraform-workflows/graphs/contributors
[license-url]: https://github.com/acai-consulting/github-terraform-workflows/tree/master/LICENSE
[terraform-workflow]: https://github.com/acai-consulting/github-terraform-workflows/blob/main/docs/terraform-workflow.png?raw=true

[github_workflows_link]: https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions
[tfe_intro]: https://www.terraform.io/cloud-docs
[terratest]: https://terratest.gruntwork.io/
