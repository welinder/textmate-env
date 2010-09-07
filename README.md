To install, first make sure that the `~/Library/Application\ Support/TextMate` directory is empty. Then do the following:

    rmdir ~/Library/Application\ Support/TextMate
    cd ~/Library/Application\ Support
    git clone git@github.com:welinder/textmate-env.git "TextMate"

Since the repository depends on submodules (for bundles etc), you have to do the following to get them loaded:

    git submodule init
    git submodule update

