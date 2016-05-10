This is a LaTeX class for creating scientific presentations in the corporate
design of the
[Institute for Web Science and Technologies (WeST)](http://west.uni-koblenz.de/).
It's style was adapted by Lukas from the
`WeST - Presentation Template - 2015-07-17.potx` powerpoint template.
It is implemented as a theme for LaTeX poster class
[beamer](https://www.ctan.org/pkg/beamer), so you should probably
have a look at its manual.

## Usage

Have a look at the [example_presentation.tex](example_presentation.tex) file for
how to use this class.

Currently the code can only be build using
[LuaLaTeX](https://www.ctan.org/pkg/lualatex-doc), so make sure you have that
installed.
For compilation [latexmk](https://www.ctan.org/pkg/latexmk/) is recommended, if
you have it installed you just have to perform:

    git clone https://github.com/Institute-Web-Science-and-Technologies/WeSTpresentation.git
    cd WeSTpresentation
    latexmk

Of course you can also compile this class by calling `lualatex` manually.

## ToDo

There is a lot left to be done before this thing can be considered stable,
pull requests are always welcome.

Bugs:

- Have better example content.

Additional Features:

- Support Beamer's Handout feature.
- Support other latex engines (`pdftex`, etc).
