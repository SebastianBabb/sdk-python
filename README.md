## Virtual Env.
```python
virtualenv -p /usr/bin/python3 virtenv
source virtenv/bin/activate
python --version
```

## Install Dependencies
`pip install -r requirements.txt`

## Unit tests.
`python -m unittest tests/CSETests.py`

## Style Guide
https://google.github.io/styleguide/pyguide.html

## Documentation
https://www.sphinx-doc.org/en/master/

### Generating documentation
From docs/

#### Add any new modules.
`sphinx-apidoc -o source/ ./client` 

#### Build documentation.
`cd docs && make html`
