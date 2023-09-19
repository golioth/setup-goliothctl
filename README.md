> :warning: This project is considered experimental and is not recommended for production use. Functionality may break at any time.

# ✨ Quickstart

To install the latest version of the Golioth CLI:

```yaml
- name: Setup Golioth CLI
  uses: goliothlabs/setup-goliothctl@main
  with:
    apiKey: ${{ secrets.APIKEY }}
    projectId: ${{ secrets.PROJECTID }}
```

Currently the Action requires a Golioth API Key and Project ID. Refer to the Golioth [documentation](https://docs.golioth.io/) for to generate an API Key and retrieve a Project ID. We recommend settings these values as [repository secrets](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions).