### Marcelo's Personal Configurations!

The bulk of this project should operate on symlinks, in order to have a source of truth across all your projects:

# Example Symlink
1. Ensure nvim .config file exists:
  `mkdir ~/.config/nvim`
2. Create symlink:
  `ln -s init.lua ~/.config/nvim/init.lua`

  NOTE: It's important to use absolute paths with symlinks, otherwise you will receive a `Too many levels of symbolic links` error.
