# Connection Configuration

Copy `connection.json.template` to a location outside the repository, fill in
the account values, and pass it to one command with `--config` or to a recipe's
`config` argument.

`cortex-training login` no longer takes this file. It sets up a Snowflake
connection profile instead; see [Set Up the Client](../../docs/getting-started/setup.md).

Do not commit programmatic access tokens.
