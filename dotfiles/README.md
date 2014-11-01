dotfiles
========

 * synchronizing configuration between multiple computers
  * store it in git (or your favorite VCS)
   * ...and upload to GitHub (or somewhere else)
   * hide *secret* stuff in submodules
  * create a script which will perform initial installation (so you can easily `curl $URL | sh`)
  * define a list of required packages for your configuration

## stow

 * symlink manager
 * `stow -v $app`
 * `~/.gitconfig -> ~/.dotfiles/git/.gitconfig`

## alternatives

 * [there is just too many...](https://www.google.com/search?q=dotfiles%20manager)
