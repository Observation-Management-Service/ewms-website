# Event Workflow Management Service Website

Website for Event Workflow Management Service (EWMS)

## Editing

After cloning the repo, you should set up a local environment:

```bash
./setupenv.sh
. env/bin/activate
mkdocs serve
```

This should start a live preview at [http://localhost:8000](http://localhost:8000).
It should automatically update whenever you save any file in the `docs`
directory.

The Markdown source exists in `docs` and uses [mkdocs](https://www.mkdocs.org/).

## Publishing

There is a GitHub action configured to deploy any changes to `main`.
Either commit directly to `main` or go through the PR process and your
changes will appear a minute or two after the merge.
