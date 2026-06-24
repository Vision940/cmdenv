# cmdenv
## Install
Source cmdenv in .bashrc to make the `cmdenv` command and the `ce` alias available locally.

The cmdenv file can also be made executable and added to your PATH to be run like a normal command.

## Documentation
**cmdenv** CMD

- cmdenv will create a terminal environment with history support for any CMD given
- cmdenv will attempt to provide completion for CMD
- everything run in cmd env is equivalent to running `CMD "$@"`
- type "help" while in cmd env to run CMD --help
- cmdenv can also be run with the alias `ce`

## Examples
The `ce git` command is a useful demo for this function. This use case allows you to run status/commit/push/etc without typing git first.

## Note
The features cmdenv provides (completion/history in nested env) could probably be done better in bash 5.3+ using `read -E`. This approach provides a more backwards compatible method of attempting these features in bash, however, so it will remain as-is.

