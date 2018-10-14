# python-ci-static-analysis

[![Build Status](https://travis-ci.org/hugovk/python-ci-static-analysis.svg?branch=master)](https://travis-ci.org/hugovk/python-ci-static-analysis)
[![Python: 2.7, 3.4+](https://img.shields.io/badge/python-2.7,_3.4+-blue.svg)](https://www.python.org/downloads/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

Static analysis on Travis CI for Python projects

## Instructions

1. Create a free [Travis CI](https://travis-ci.org) account
2. Enable your repo at https://travis-ci.org/profile (you may need to <i>Sync account</i> first)
3. Copy .travis.yml to your repo's root and commit it:

```bash
wget https://raw.githubusercontent.com/hugovk/python-ci-static-analysis/master/.flake8
wget https://raw.githubusercontent.com/hugovk/python-ci-static-analysis/master/.travis.yml
git add .flake8 .travis.yml && git commit -m "Run static analysis on Travis CI (https://github.com/hugovk/python-ci-static-analysis)"
```

4. Push a commit to your repo, and Travis CI will run the static analysis
