# E100 assembly for Sublime Text
This is a Sublime Text package that provides syntax highlighting for E100 Assembly language. In the future, it may provide some other convenience features for working with the simple E100 microprocessor. 

Syntax highlighting will be triggered for any file ending in *.e, *.easm, or *.e100, and will look something like this, depending on your theme:
![Syntax Highlighting Features](http://alexanderhouse.me/Syntax Highlighting Demo.png)

Also, due to the way I've written the syntax definition file, Sublime won't highlight a statement until it's valid, so you know when you've written something that will assemble:
![Dynamic Highlighting](http://alexanderhouse.me/E100 Syntax Highlighting Demo.gif)

## Installation Instructions
#### Via Package Control *(recommended)*
You can now get E100 assembly support directly through Package Control! Installing through package control will also keep the extension up-to-date, such as when syntax highlighting is improved or snippets are added.

1. Install [Package Control](https://sublime.wbond.net/installation) (if you haven't already)
2. Run the “Package Control: Install Package” command 
  1. Use `Ctrl+Shift+P` to open the command palette.
  2. Type `pcip` and press `Enter` to run the command.
3. Search for and install the `E100 Assembly` plugin.
4. Restart Sublime Text if syntax highlighting doesn't start automatically.

#### Manually *(with git)*
*NOTE: If you do it this way, there's no auto-update, and you'll have to use `git pull` to keep the package up-to-date.*

Clone the repository in your Sublime Text "Packages" directory:

    git clone https://github.com/ahouse101/SublimeE100Assembly.git

For Sublime Text 3, the "Packages" directory is located at:

* OS X: `~/Library/Application Support/Sublime Text 3/Packages/`
* Linux: `~/.config/sublime-text-3/Packages/`
* Windows: `%APPDATA%\Sublime Text 3\Packages\`


#### Manually *(without git)*
This is the hard way, if you don't have Package Control or git installed. *The only way to keep the package up-to-date with this method is to repeat all the steps.*

1. Download the `.zip` file from this page. 
2. Create a folder called `E100 Assembly` inside Sublime Text's "Packages" directory (location shown above).
3. Extract the contents of the zip into that folder.
4. Restart Sublime Text if syntax highlighting doesn't start automatically. 
