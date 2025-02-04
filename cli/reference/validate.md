---
label: validate
---

# baselime validate

Use the `baselime validate` command to validate your ORL configuration files.

```bash :icon-terminal: terminal
baselime validate

Check whether the configuration is valid

Options:
      --profile    [string] [default: "default"]
      --quiet      [boolean] [default: false]
  -d, --debug      [boolean] [default: false]
      --format     Format to output the data in  [string] [choices: "table", "json"] [default: "table"]
  -c, --config     The configuration file to execute  [string] [default: ".baselime"]
      --variables  The variables to replace when doing the plan  [array]
  -h, --help       Show this help output, or the help for a specified command or subcommand  [boolean]
  -v, --version    Show the current Baselime CLI version  [boolean]

Examples:

        baselime validate
        baselime validate --config .baselime --profile prod

```
