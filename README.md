# Neovim-bundle
Meta repository with submodules for each vim plugin I'm currently using.

Basically,

```sh
git clone https://github.com/glentner/Neovim-bundle ~/.vim/bundle
cd ~/.vim/bundle
git submodule update --init --recursive
```

Youcompleteme needs to be compiled, `cd ~/.vim/bundle/youcompleteme && ./install.py --clang-completer`.
