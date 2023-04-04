How to contribute to the documentation hosted through this repository
---------------

```bash
# clone the repository
git clone git@github.com:sureshsubbaiah/documentation_sample.git

# Change directory
cd documentation_sample/docs

# Start a new branch
git checkout -b <new_branch>
```
You can now add or modify git pages.

To see your changes on your local
```bash
# Build and serve the book
mkdocs serve
```
Then browse to http://localhost:8000

When ready, push your new branch and submit a pull request.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.