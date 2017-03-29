.vim
====

This is my .vim configuration files.

It uses these plugins:
- Pathogen for runtimepath managment.
- ack.vim
- gitv
- nerdtree
- vim-fugitive
- vim-fuzzyfinder
- vim-git
- vim-l9
- vim-rooter
- Command-T

Compiling Command-T:

  cd ~/.vim/bundle/command-t/ruby/command-t
  ruby extconf.rb
  make

NOTE: same ruby version for vim must be used & make sure ruby-dev package is installed on your system.
