# Snippet Converter

### Description
---------------
This is a CLI tool designed to convert snippets from Sublime Text into VS Code usable snippets. 

The reason for the development of this app was two fold:
1) To assist in the transition from Sublime Text to VS Code.
2) Submlime Text has a better format for creating snippets (in my opinion).

### Installation
----------------
To install the CLI clone the repository -> cd into the root of the repository -> run `npm i -g` to install the tool globally.


### Usage
--------------
The usage of the app is pretty straight forward. 

Using the following command should transform your Sublime snippets into usable VS Code snippets:

`snp <command> <option>`


### Commands
---------------

**help** Displays help information.

**convert** Converts sublime snippets to vscode snippets.

### Options
--------------
**-h, --help** Displays help information.

**\<Sublime Snippet Directory\>** Optional (first arg) that will accept a file path. Used to input the file path to your Sublime snippet files if they have been moved from the defaut location.

**\<VS Code Snippet Directory\>** Optional (second arg) that will accept a file path. Used to input the file path to your VS Code snippet files if they have been moved from the defaut location.
