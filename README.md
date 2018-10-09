# dotfiles

## installation

1. clone to ~/dotfiles
2. add `for f in $(find ~/dotfiles -maxdepth 2 -not -path '*.git*' -not -path '*/dotfiles/bin/*' -not -type dir); do source $f; done` to ~/.bashrc
