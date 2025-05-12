# skip-checkout-windows-buildkite-plugin

Skips the checkout in a Buildkite step in Windows agent, by setting BUILDKITE_REPO to an empty string.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - skip-checkout-windowst#v1.0.0: ~
```

## Configuration

This plugin requires no configuration.

## Contributing

1. Fork the repo
2. Make the changes
3. Run the tests
4. Commit and push your changes
5. Send a pull request
