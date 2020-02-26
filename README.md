This repository contains the [Lambda School](https://lambdaschool.com/) Labs
Guides. The Guides are in [MarkDown](https://daringfireball.net/projects/markdown/)
format and structured to be converted into a static HTML website using the [MkDocs](https://www.mkdocs.org/)
site generator.

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
  - `> markdownlint docs`