# Documentation

Improving our documentation skills. Keys are our word skills, understanding intended readers, and purpose and context of code comments, external 
documentation, automated tests, git commit messages, pull request descriptions, automated documentation, and error 
messages. And an exercise in using docsify.

![Publish Documentation using MkDocs](https://github.com/tymyrddin/documentation/workflows/Publish%20Documentation%20using%20MkDocs/badge.svg?branch=main) Deployment: https://tymyrddin.github.io/documentation

Built with [MkDocs](https://www.mkdocs.org/) using a [theme](https://github.com/readthedocs/sphinx_rtd_theme) provided 
by [Read the Docs](https://readthedocs.org/). 

Installing mkdocs with `pip`, `pipenv` or `poetry` (example here is `pip`)
```bash
$ pip install mkdocs
```
Or by using the requirements file in the repo:
```bash
$ pip install -r requirements.txt
```
Launching the site in a local web server, running on port 8000 (in the directory where `mkdocs.yml` resides):
```bash
$ mkdocs serve
```
Using the built-in support for generating a static website by run the build command:
```bash
$ mkdocs build
```
This will generate an entire website in a new folder named `site`.

Deployment:
```bash
$ mkdocs gh-deploy
```