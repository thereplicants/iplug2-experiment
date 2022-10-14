# arp2

- Created from [iPlug2OOS template](https://github.com/iPlug2/iPlug2OOS)
- See [iPlug2 wiki on out of source builds](https://github.com/iPlug2/iPlug2/wiki/Out-of-source-builds)
- See [iPlug2 doc on containerized WAM development](https://docs.google.com/document/d/e/2PACX-1vT6lYZ3vtYKWAty2g6DL994IO0_pfyGctDdKfPxF6MZwOgFWENfLuVtBW9J0-KzLsfPSKKN055UnAmj/pub)

This iPlug2 project builds "out of source", allowing project dependencies to be synchronised with version control. It also enables "containerized development" with VS Code and GitHub Codespaces. Instead of using the `common-mac.xcconfig` and `common-win.xcconfig` in the `iPlug2` folder, it uses copies, meaning the iPlug2 submodule itself does not have to be modified.
