# GitHub Actions Pipeline Templates

Reusable GitHub Actions workflows and composite actions for Terraform and more.


## Usage

### Composite Action (Step Template)

Use the composite action as a step in your workflow:


```yaml
steps:
  - name: Terraform Init and Validate
    uses: paragpratim/github-actions-pipeline-templates/.github/actions/terraform-validate@main
    with:
      terraform_version: 1.6.0
```

---

More pipeline templates coming soon!