# python-ci-static-analysis

[![Build Status](https://travis-ci.org/hugovk/python-ci-static-analysis.svg?branch=master)](https://travis-ci.org/hugovk/python-ci-static-analysis)

Static analysis on Travis CI for Python projects

## Instructions

1. Create a free [Travis CI](https://travis-ci.org) account
2. Enable your repo at https://travis-ci.org/profile (you may need to <i>Sync account</i> first)
3. Copy .travis.yml to your repo's root and commit it:

  ```bash
  wget https://raw.githubusercontent.com/hugovk/python-ci-static-analysis/master/.travis.yml
  git add .travis.yml && git commit -m "Run static analysis on Travis CI"
  ```

4. Push a commit to your repo, and Travis CI will run the static analysis
