# Quote Comparison

Compare supplier offers for a common quantity, currency and delivery scope.

## Use in ChatGPT or Claude

Copy the instructions from [SKILL.md](SKILL.md) into a conversation and supply your material. In an Agent Skills environment, install the entire folder using that environment's skill loader.

## Try it

A offers 100 units for 500 delivered. B offers 100 for 460 plus delivery. All other terms match.

**Expected behavior**

A costs 5 per delivered unit. B ties A at a delivery charge of 40.

## Limitations

Results depend on the supplied material and the assistant's interpretation. Use the worked example to inspect the output before applying it to new material.

## Development

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup and test commands, and the [changelog](CHANGELOG.md) for project history.

## License

[MIT License](LICENSE). Copyright (c) 2026 quote-comparison contributors.
