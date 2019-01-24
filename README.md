# pcgen-custom
There isn't much to say, really. Sometimes the existing sources in PCGen don't have what I need for a character, so I make some myself. These are them. It's mainly homebrew, but occasionally I work up a couple items from an official or 3rd-party source if one of the official data monkeys hasn't already taken care of it.

If, for whatever reason, you actually want to *use* these, I recommending cloning this whole repository and then symlinking the individual sources you want into your PCGen data folder. This way, you can just keep the repo updated and not have to worry about copy and pasting folders back and forth.

## Symbolic linking
If you're most people, you have no reason to use symlinks, so you may not know what they are or how to make them. The short version is they're like Shortcuts (Windows) or Aliases (Mac), except programs that aren't Windows Explorer or Finder actually understand how to interact with them. However, Windows Explorer and Finder don't allow you to create symlinks. You either need to muck around in the terminal shell or download third party extensions. Since you (like me) probably don't want to use the terminal if you don't have to, so...

### Third-party extensions
Windows: [Link Shell Extension by Hermann Schinagl](http://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html)
Mac: [SymbolicLinker by Mick Zitzmann](https://github.com/nickzman/symboliclinker/releases)

Both of these do the same thing: they let you make symlinks by using the context/right-click menu. Quick and easy.