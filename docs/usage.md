
## Usage / Help

`gimme --help` will output the main help output, with commands available
and list of possible options.

`--help` works too for subcommands, eg running `gimme <cmd> --help` (or
`--usage`).

It'll output the help or usage definition of the appropriate command.


Here's a few examples:

    $ gimme list --help
    list - List available packages
    ==============================

    gimme list


    $ gimme install --help
    install <name ...> - Installs the lib(s) <name ...>
    ===================================================

    gimme install <asset>
    gimme install <asset> <asset ...>

    $ gimme docs --help
    docs <name> - Tries to open package's documentation using default browser
    =========================================================================

    gimme docs <pkgname>


    $ gimme readme --help
    readme <name> - Show the appropriate documentation manpage generated from readme file
    =====================================================================================

    gimme readme <pkgname>


## Help command

The `help` subcommand is the one to use for further information and
documentation on the appropriate command.

    gimme help install


The way the `help` command outputs the help is based on the `viewer`
option. Valid options for `viewer` are:

* **man** (Defaults for Posix) Output the documutentation using man.

* **browser** (Defaults for Windows) Output the documentation as HTML
  page

* **markdown** Simply output the markdown file to stdout.

The only available implemented viewer is markdown for now.


