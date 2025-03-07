# Beacon Unifier & Documentation Tools

This directory contains some tools for schema conversion and testing as well as for
the generation of readable schema representations in the ReadTheDocs-style documentation.

## Repository Unification & Conversion

At this time the source for the Beacon framework and models still is maintained in
separate repositories, while YAML and JSON versions are generated by pulling changes there
and performing a local conversion.

A conversion run currently is performed in a local setting with:

```
./yamlerRunner.sh
```

However, paths etc. depend on the local setup and can be modified in the shell
script.

## Documentation for Automatic Generation of Markdown Tables from Schemas

See this [link](SCHEMAS2MD.md).
