# GH actions as a subtree

This repository contains two branches: `master` (the main one) and `actions` which contain a sample GH workflow file. The `actions` branch is then subtree-merged to `master` at `.github/workflows` folder. This setup mocks-up sharing the action workflows across several repos.

https://github.com/mbojan/submodule-action tries similar approach, but through Git submodules.

