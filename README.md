# dotfiles
Portable Configuration Files

These can be downloaded to new machines and used with symlinks

from the $HOME directory, run
```
git pull https://github.com/rericsson/dotfiles
```

Then, symlink the .vimrc

```
ln -s ~/dotfiles/.vimrc .vimrc
```

The first time you run vim, the plugins will be loaded and it's ready to go.

You can also do a symlink for the .tmux.conf file:
```
ln -s ~/dotfiles/.tmux.conf .tmux.conf
```

That doesn't have much in it right now except some very basic screen configs.


