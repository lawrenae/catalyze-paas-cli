# Catalyze PaaS CLI
Build status: [![Circle CI](https://circleci.com/gh/catalyzeio/catalyze-paas-cli.svg?style=svg&circle-token=0c5e5a36e771343a7ecc71990657378dcc0d2581)](https://circleci.com/gh/catalyzeio/catalyze-paas-cli)

CLI tool for interacting with environments hosted on [Catalyze](https://catalyze.io/)'s Platform-as-a-Service.

## Installing

Either of these methods requires python 2.7, [pip](https://pip.pypa.io/en/latest/installing.html), and setuptools (`pip install setuptools`). Also note: for now, `console` is not supported on Windows.

To verify installation: `catalyze --version`

### Missing Libraries

You may get an error about a missing `libffi.h` - if this is the case, use your OS's package manager to install libffi (for OS X, using [homebrew](http://brew.sh/) - `brew install libffi`) (for Ubuntu - `apt-get install libffi-dev`).

Likewise, you may get an error about missing libssl - this is fixed by `brew install openssl` on OS X, or `apt-get install libssl-dev` on Ubuntu.

### From PyPI

```
pip install catalyze
```

### From Source

1. Clone this repo
2. `python setup.py install` (see libffi note above)

## Usage

`catalyze --help`

## Issues, Support, and Help

For bugs with the CLI itself, please open github issues. For platform questions and problems, please [email Catalyze support](mailto:support@catalyze.io) (support@catalyze.io).

The same text available from `--help` is also available online at [https://resources.catalyze.io/paas/cli/](https://resources.catalyze.io/paas/cli/).
