# Documentation

## Installation 

### Sphinx 

https://www.sphinx-doc.org
https://www.sphinx-doc.org/en/master/usage/quickstart.html

#### Windows 

https://www.sphinx-doc.org/en/master/tutorial/getting-started.html

`choco install sphinx`

In the root folder:

`python -m venv .venv`
`.venv\Scripts\activate`
`python -m pip install sphinx`
`python -m pip install sphinx-rtd-theme`

Validate: 

`sphinx-build --version`

## Publish documentation

`sphinx-build -b html docs/source/ docs/build/html`