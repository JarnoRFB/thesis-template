# Thesis Template
A LaTeX template and some utilities for your Bachelor/Master thesis.
The template is specialized for Cognitive Science at Osnabrück University, but could easily be adapted.

## Installation
To use this template you first of all need to install [Visual Studio Code](https://code.visualstudio.com/).

### Using Devcontainer
If you have docker on your machine, you can easily write your thesis inside a container
that has all the necessary software already installed.
Install the [Remove Development Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
for VSCode. Then type <kbd>F1</kbd> > `Remote-Containers: Reopen in Container`.
A new instance of VSCode should open. Open `thesis.txt` and press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>b</kbd>
to build the latex document.

### Using Native Installation
First you will need to install LaTeX. Assuming that your machine is running an Ubuntu based distro run in your terminal

    sudo apt install texlive-full 

If you are on a different distro or operating system you will need to install LaTeX in a different way.

Install the following extensions into VSCode to enable processing of LaTeX documents and spell checking

    	James-Yu.latex-workshop
		tecosaur.latex-utilities
        streetsidesoftware.code-spell-checker


## General Guidelines
* Use American English. Cognitive Science is a discipline originating from the States. Also most research papers are written in American English.
* Use Latex and to make your life easier this template.
* Write one sentence per line in your editor.  While `synctex` is able to establish correspondence between the `.tex` document
  and the compiled PDF, it can only to so on the level of lines. If you rely on word wrapping in your editor and write entire
  paragraphs in a single line, you make the process of going from errors found in PDF back to the source unnecessarily hard.
  Writing only a single sentence per line also makes diffs more readable.
* Avoid errors early. Spellcheck your writing and put references where they belong.
* Keep your glossary up to date. Whenever you use and acronym add it to the `acronyms.txt` file.
* Use a citation manager. [Mendeley](https://www.mendeley.com/) is preferred. 
  If you have experience with it and want to stay open source you can also use [Zotero](https://www.zotero.org/).
* Use [`booktabs`](https://inf.ethz.ch/personal/markusp/teaching/guides/guide-tables.pdf) style for your tables. Tables can be conveniently 
  generated using [Tables Generator](http://www.tablesgenerator.com/latex_tables).
  The style should then be set to `Booktabs table style`.
* Get familiar with VSCode. https://github.com/Microsoft/vscode-tips-and-tricks is a good starting point.
* Use git and GitHub to manage your versions. Since `.tex` files are just text documents
  you can easily use git to manage your version and even sync them back to GitHub to back them up. 

## Contributing
Did you find any other resources, practices, instructions, LaTeX macros or VSCode extensions
that you found helpful for writing a thesis? Feel free to add them and make a pull
request. 