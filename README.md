# Base packages & utilities

## Homebrew

Run `brew bundle` in this repository to install all homebrew packages.

Symlink the `.Brewfile` to the home directory by running `ln -s ~/path/to/Brewfile ~/.Brewfile` in the repository root to keep it up to date.

To purge all temporary packages, run `brew bundle cleanup --global --force`.

Check which packages have been manually installed (instead of as dependencies) by running `brew leaves`.
