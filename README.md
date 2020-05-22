
# Installation instructions 

## Theme downloaded form the VSC Marketplace

1. Click on the `install` button.
2. Click Reload
3. File > Preferences > Color Theme > Secuoyas-code

Yo can access the Theme with the Color Theme Picker 
Mac Shortcut: `[cmd-K cmd-T]`


## Github Repo

### Option 1
1. Clone the repo https://github.com/Secuoyas-Experience/secuoyas-theme.git
2. Symlink the generated package directory into the VS Code extensions directory.
3. Load the Theme
4. Then reload or restart VS Code.

From the Terminal:
```
$ cd ~/your.path.to.repo.folder/
$ git clone https://github.com/Secuoyas-Experience/secuoyas-theme.git
$ ln -s ~/your.path.to.repo.folder/secuoyas-theme/ ~/.vscode/extensions/secuoyas-code
```

### Option 2
Copy the generated package directory into the VS Code extensions directory.
To copy the theme:

1. go to the clone folder
2. copy with:

> `cp -R 'secuoyas-theme/secuoyas-code' ~/.vscode/extensions/`

Option 1 is preferred as you wold be able to get the updates with a `git pull`command.


The generated theme package should be in the list of installed extensions, and "Secuoyas code" will be available in the list of themes.

---- 

Secuoyas Code theme is loosely based on the [VS Code template](https://github.com/mjswensen/themer/tree/master/cli/packages/themer-vscode) for [themer](https://github.com/mjswensen/themer) and [citylights](http://citylights.xyz/) by yummygum