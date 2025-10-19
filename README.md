[![Copr build status](https://copr.fedorainfracloud.org/coprs/aldantanneo/jj-vcs/package/jj-cli/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/aldantanneo/jj-vcs/package/jj-cli/)
# COPR repository for `jj`

This repo contains the base spec file and a Github action to check for updates automatically.

No source code is stored here, it is fetched from the base [`jj-vcs/jj`](https://github.com/jj-vcs/jj) repo at build time.

To add the repository ([link](https://copr.fedorainfracloud.org/coprs/aldantanneo/jj-vcs)):

```sh
sudo dnf copr enable aldantanneo/jj-vcs
```

To install the `jj` CLI tool:

```sh
sudo dnf install jj-cli
```
