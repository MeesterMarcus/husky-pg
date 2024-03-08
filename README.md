# husky-pg
This repo tests out some of the use cases we can use husky commit hooks for.

## Setup
1. Install the packages via `npm install`
2. Edit a file and perform a `git commit`
3. You should now see some behavior from husky. In this project, we verify the test suite and commit message to follow the conventional commits standard and meg-issues postfix.
4. For interactive rebases or scenarios where you don't need husky to run, append `--no-verify` to your `git` command.