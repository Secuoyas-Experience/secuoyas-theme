
<a href="https://secuoyas.com"><img src="https://brand.secuoyas.com/img/repository-hero.png" title="theme-repository-hero" alt="Secuoyas"></a>

![header](/assets/repository-hero.jpg)

# Secuoyas Code

Dark theme designed with care for better coding and improved developer experience.

This theme is optimized for Front End development, and has been optimized to have a uniied experience with html, css, js, md, json, and react files.

![screenshot-html](/assets/html.png)

> Secuoyas code works better with SF Mono and the Icon Theme form [City Lights](https://github.com/Yummygum/city-lights-icons-vsc)



## Screenshots
![screenshot-css](/assets/css.png)
![screenshot-react](/assets/react.png)
![screenshot-php](/assets/php.png)

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

### Bonus - iTerm2 ColorSet
Secuoyas-code theme adds a bautiful color theme to your terminal window. If you are using iTerm and want to pair those enviroments with the right ANSI colors, just load [this file](/assets/secuoyas-20.itermcolors) in iTerm2::Preferences>Profles>Colors>Color Presets...

# License
The following licensing applies to City Lights Syntax Theme: Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0). For more information go to https://creativecommons.org/licenses/by-nc-nd/4.0/


---- 

Secuoyas Code theme is loosely based on the [VS Code template](https://github.com/mjswensen/themer/tree/master/cli/packages/themer-vscode) for [themer](https://github.com/mjswensen/themer) and [citylights](http://citylights.xyz/) by yummygum