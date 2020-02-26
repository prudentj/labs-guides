# Labs Guides

![Publish docs via GitHub Pages](https://github.com/Lambda-School-Labs/labs-guides/workflows/Publish%20docs%20via%20GitHub%20Pages/badge.svg)

This repository contains the [Lambda School](https://lambdaschool.com/) Labs
Guides. The Guides are in [MarkDown](https://daringfireball.net/projects/markdown/)
format and structured to be converted into a static HTML website using the [MkDocs](https://www.mkdocs.org/)
site generator.

[Generated Website](https://lambda-school-labs.github.io/labs-guides/)

## Contributions

Contributions, suggestions and comments are welcome from anyone in the form of a
PR and github issues. The Pull Request will be reviewed by Lambda Labs
Engineering staff and if approved, will become part of the Labs Guides.

## Getting Started with local dev

- install pipenv
    - `> brew install pipenv`
- `> pipenv install --dev`
- `> pipenv shell`
    - start a shell with a virtual environment
- Build the site
    - `#> mkdocs build`
- install markdown linter
    - `> npm install -g markdownlint-cli`
- run the linter
    - `> markdownlint -c .markdownlint.json .`

> All python packages should be added to the Pipfile and requirements.txt
