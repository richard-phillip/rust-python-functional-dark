# Marketplace

Publisher ID: `RichardPhillip`
Publisher name: eigenform
Account: richard@eigenform.art
Extension: `rust-python-functional-dark-theme`

The same publisher also publishes `the-fold-pdf`.

Manage: https://marketplace.visualstudio.com/manage/publishers/RichardPhillip

The `publisher` field in `package.json` must stay `RichardPhillip`. The Marketplace display name is eigenform.

Publish with Trusted Publishing, not a personal access token. Global tokens stop working on January 27, 2027.

On https://marketplace.visualstudio.com/manage/publishers/RichardPhillip open Trusted Publishing and create a policy:

- Policy name: `Publish theme`
- Repository owner: `richard-phillip`
- Repository: `rust-python-functional-dark`
- Workflow: `publish.yaml`
- Environment: leave empty

The workflow is `.github/workflows/publish.yaml`. Run it with Actions, then Run workflow.
