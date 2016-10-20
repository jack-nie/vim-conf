# vim-conf

My personal vimrc files

## Install

```
   git clone --recursive https://github.com/jack-nie/vim-conf.git ~/.vim
   ln -s  ~/.vim/.vimrc ~/.vimrc
```

then open vim, `:PluginInstall`

## vim-go support

Please be sure all necessary binaries are installed (such as gocode, godef, goimports, etc.). You can easily install them with the included `:GoInstallBinaries` command. If invoked, all necessary binaries will be automatically downloaded and installed to your `$GOBIN` environment (if not set it will use `$GOPATH/bin`). Note that this command requires git for fetching the individual Go packages. Additionally, use `:GoUpdateBinaries` to update the installed binaries.

## know issues

Please update your vim to 7.4 to erase `vim-ruby` errors, for mac os, just type `brew install vim`, and reopen terminal.
