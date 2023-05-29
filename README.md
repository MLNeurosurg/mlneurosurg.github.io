# mlneurosurg.github.io

## Getting started
1. Install bundler
2. Set bundle install path to be local
   ```console
   bundle config set --local path 'vendor/bundle'
   ```
2. Install dependencies
   ```console
   bundle install
   ```
4. Serve locally
   ```console
   bundle exec jekyll serve --incremental
   ```

## Version control and source code formatting
`main` is a long-running branch. All work should be done in branches derived
from `main`, and will be rebased onto `main` once they are completed.
Spaces are used for indentation, and snake\_case is used to name variables
and functions.
