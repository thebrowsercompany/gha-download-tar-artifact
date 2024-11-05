# `@thebrowsercompany/gha-download-tar-artifact`

Download and untar [Action Artifacts](https://docs.github.com/en/actions/using-workflows/storing-workflow-data-as-artifacts) from your Workflow Runs. Internally powered by GitHub's [@actions/download-artifact](https://github.com/actions/download-artifact) action. This action uses [@actions/download-artifact](https://github.com/actions/download-artifact) to download the tar file and untar it, preserving permissions on non-Windows platforms.

See also [gha-upload-tar-artifact](https://github.com/thebrowsercompany/gha-upload-tar-artifact). For further documentation, refer to the [@actions/download-artifact](https://github.com/actions/download-artifact) documentation.

- [`@thebrowsercompany/gha-download-tar-artifact`](#thebrowsercompanygha-download-tar-artifact)
  - [Usage](#usage)
    - [Inputs](#inputs)
    - [Outputs](#outputs)

## Usage

### Inputs

```yaml
- uses: thebrowsercompany/gha-upload-tar-artifact@main
  with:
    # Name of the artifact to download. If unspecified, defaults to `artifact`.
    name:

    # Destination path.
    # Required.
    path:
```

### Outputs

| Name | Description | Example |
| - | - | - |
| Name | Description | Example |
| - | - | - |
| `download-path` | Absolute path where the artifact(s) were downloaded | `/tmp/my/download/path` |
