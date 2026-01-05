# brown-cs500-mkdocs

This is the cs500 course page that uses the mkdocs static site generator with the material theme. 

## Setup

1. [Install mkdocs](https://www.mkdocs.org/user-guide/installation/)
    * `pip install mkdocs`
2. [Install mkdocs-material](https://squidfunk.github.io/mkdocs-material/getting-started/)
    * `pip install mkdocs-material`

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml         # The configuration file.
    docs/
        assets/        # Images probably
        stylesheets/   # Contains custom css config files
        index.md       # The documentation homepage.
        ...            # Other markdown pages, images and other files.
