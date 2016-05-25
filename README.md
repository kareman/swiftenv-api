# swiftenv API

API for [swiftenv](https://swiftenv.fuller.li/) to return the available
versions of Swift.

## Development Environment

You can configure a development environment with the following:

**NOTE**: *These steps assume you have Python 3 along with
[pip](https://pip.pypa.io/en/latest/installing.html) and
[virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)
installed.*

```bash
$ virtualenv -p python3 venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

### Running the tests

```shell
$ python -m unittest
```

### Running the development server

```shell
$ python api.py
```
