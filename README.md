# skip-checkout-windows-buildkite-plugin

Skips the checkout in a Buildkite step in Windows agent, by setting BUILDKITE_REPO to an empty string.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - skip-checkout-windows#v1.0.0: ~
```

## Configuration

This plugin requires no configuration.

## Contributing

Raise PR with your changes!

