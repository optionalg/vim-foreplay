# foreplay.vim is now fireplace.vim

The world wasn't ready for a plugin named foreplay.vim, so check out
[fireplace.vim][].

## Migrating

You'll need to blow away all references to foreplay and start over.  Note
that [classpath.vim][] is no longer included, so get that if you haven't
already.  With the standard [pathogen.vim][] setup:

    cd ~/.vim/bundle
    rm -rf vim-foreplay
    git clone git://github.com/tpope/vim-fireplace.git
    git clone git://github.com/tpope/vim-classpath.git
    git clone git://github.com/guns/vim-clojure-static.git

[fireplace.vim]: https://github.com/tpope/vim-fireplace
[classpath.vim]: https://github.com/tpope/vim-classpath
[pathogen.vim]: https://github.com/tpope/vim-pathogen

## License

Copyright © Tim Pope.  Distributed under the same terms as Vim itself.
See `:help license`.
