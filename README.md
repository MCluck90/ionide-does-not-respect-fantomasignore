# Reproduction

## From command-line

Run `dotnet fantomas Program.fs`

> `'Program.fs' was ignored`

## From VS Code with Ionide

Open this project in VS Code and save `Program.fs` with Ionide selected as the formatter.

- Expected: No changes to file as it is ignored
- Actual: File is formatted with Fantomas
