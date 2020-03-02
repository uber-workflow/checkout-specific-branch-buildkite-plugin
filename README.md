# checkout-specific-branch-buildkite-plugin

> Buildkite plugin to override default checkout script and checkout a specific branch

## Usage

```yaml
steps:
  - command: "echo hi"
    plugins:
      - "uber-workflow/checkout-specific-branch":
        branch: "next"
```

If `branch` is not provided, the default branch of the pipeline is used.
