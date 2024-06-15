# Blog by mkdocs-material

[![Built with Devbox](https://jetpack.io/img/devbox/shield_galaxy.svg)](https://jetpack.io/devbox/docs/contributor-quickstart/)


## How to run

Install `direnv` & `devbox`

```shell
curl -fsSL https://get.jetpack.io/devbox | bash
devbox install

brew install direnv  # Will take times, be patients
# This command is only for zsh
# The other shell hook, pls refer to: https://direnv.net/docs/hook.html
cat <<EOF >> ~/.zshrc
export DIRENV_LOG_FORMAT=''
eval "\$(direnv hook zsh)"
EOF

sudo chown -R "$USER" /nix
source ~/.zshrc
```

## TODO

* [x] pre-commit
* [x] commitizen
* [x] command alias
* [x] gitleaks
* [ ] badge
* [ ] renovate
