# fish

* [x] install fish using brew install fish
* [x] run this curl for fisher
* curl -Lo ~/.dotfiles/.config/fish/functions/fisher.fish --create-dirs https://git.io/fisher
* [x] put all the fish config files from .config, temp-config/.config/fish, into ~/.dotfiles/.config/fish
* [x] remove the .config/fish directory
* ... remove the entire thing and the symbolic link take its place *
* [ ] make the entire .config/fish directory a symbolic link to to the .dotfiles/.config/fish directory
* [ ] add the symbolic link creation for ~/.config/fish to ~/.dotfiles/.config/fish

# ??HOW can I set these in fish?

> # set -gx GOROOT "$(brew --prefix golang)/libexec"
> # set -gx PATH $PATH:${GOPATH}/bin:${GOROOT}/bin

* not that I need to anymore... the reason I was trying to install go was for that pdf readr... which I found out to be a pay for app... *
* That was from the REF: installing go from Medium... I think *
* ... oh well... it's in here just in case I want it *

* [x] all of the fish configuration is in ~/.dotfiles/.config/fish
* [x] there is a symbolic link from ~/.dotfiles/.config/fish to ~/.config/fish
**The functions are boing found in the example react app for typescript functions**
**... but it is only working in zsh and not fish**
**... in fish I get typescript-language-server not found error**
## the lsp is ??WHAT? ... that neovim lsm dep
*it is neovim/nvim-lspconfig*
*it is being installed by Packer*
* [ ] see if it is a packer problem
* [ ] ... or see if it is a fish problem
*it has something to do in fish since it is working in zsh and not fish*
*... unless I had installed something from the Wiesler tutorials that configured the typescript lsp to work...??*
"
