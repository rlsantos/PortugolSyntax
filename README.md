# PortugolSyntax

**Portugol syntax highlight to sublime text. This syntax is based on Manzano and Oliveira (2019) "Algoritmos: Lógica Para Desenvolvimento de Programação de Computadores"**

## Installation

The easiest way to install the package is through the [Package Control](https://packagecontrol.io/installation). Once you have Package Control installed, type `Ctrl` + `Shift` + `P` (`Cmd` + `Shift` + `P` on Mac) and select the Package Control: Install Package command. Select the [Portugol Syntax](https://github.com/rlsantos/PortugolSyntax/) package and wait for it to install.

To facilitate the use of Portugol Syntax, I recommend the installation of [Unicode Math Package](https://github.com/mvoidex/UnicodeMath). This package enables you to use `\uparrow` and `\<-` for the most common symbols to ↑ (exponential) and ← (attribution).


## Usage

Once the package is installed, there will be a language option for `Portugol (Manzano)` (located in the bottom right corner of the window). The file extension to this syntax is `.portugol`, `.ptg`, or `ptgol`. In the case of the syntax is not working,  you can change this to `Portugol (Manzano)`, simply click in the bottom right corner of the window where it says `Plain Text` (or other) and select `Portugol (Manzano)` from the dropdown.

## Bug Reporting

This syntax highlighter is still in development. If you discover an issue with the highlighter, please report it in the issues section of this repository. Feel free to fork and pull request if you would like to fix a bug/add a feature yourself.

## Contributing

If you would like to contribute to the repository (either via bugfixes or added features), you can fork the repository and submit a pull request with your changes. The highlighter is written using the [Syntax Definitions](http://www.sublimetext.com/docs/syntax.html) from [Sublime Text](http://www.sublimetext.com/), so take a look there if you want to learn how to edit the highlighter. There is a tutorial in the first link that can help you.

Whatever you decide to do, please make changes to the portugol-manzano.sublime-syntax. Any pull requests that change portugol-manzano.sublime-syntax without commenting the changes will be rejected. Thanks for your help!

## Features

- [x] Initial commands and syntax
- [ ] Restrictions to var and program names
- [ ] Blocks constraints
