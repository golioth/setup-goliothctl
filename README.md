> :warning: This project is considered experimental and is not recommended for production use. Functionality may break at any time.

# setup-goliothctl

Use [`goliothctl`](https://docs.golioth.io/reference/command-line-tools/goliothctl/goliothctl/), the Golioth CLI, from GitHub Actions. This action can be used to directly call the CLI as well as use in other actions.

# ✨ Quickstart

To install the latest version of the Golioth CLI:

```yaml
- name: Setup Golioth CLI
  uses: goliothlabs/setup-goliothctl@main
  with:
    apiKey: ${{ secrets.APIKEY }}
    projectId: ${{ secrets.PROJECTID }}
```

The action requires a Golioth API Key and Project ID. Refer to the Golioth [documentation](https://docs.golioth.io/) for to generate an API Key and retrieve a Project ID. Settings these values as [repository secrets](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions) is recommended.

# Inputs

| Parameter | Description | Required |
| --- | --- | --- |
| apiKey | The API Key generated via goliothctl or web console | Yes | 
| projectId | Project ID to use | Yes |