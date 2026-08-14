# Contributing to OpsNexus CLI

Keep the CLI an API client: do not import backend internals or duplicate server business logic. Describe command, authentication, output compatibility, and API version impact.

Run gofmt, go vet ./..., and go test ./.... Never commit tokens, local configuration, binaries, or captured infrastructure output.
