Dot files for various tools. 

Managed with gnu stow, idea from this blog post: https://alexpearce.me/2016/02/managing-dotfiles-with-stow/

So far I have my hammerspoon and emacs configs.

stow hammerspoon
stow emacs

Each application gets a folder and stow will make a symlink for each file in that folder a level above.
