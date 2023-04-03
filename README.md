# dotslashdash.github.io
This repo contains the code for my Github Pages blog.

The configuration for the Pages workflow is contained in
`.github/workflows/hugo.yaml`.

To add a new post, generate a markdown file with hugo:
```
$ hugo new content/2023-01-01-post-title.md
```

To run the development server (with drafts enabled), execute `run.sh`, or:
```
$ hugo server -D
```
