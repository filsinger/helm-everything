# THIS PACKAGE IS DEPRECATED

[Voidtools Everything](http://www.voidtools.com) now provides a command line interface [es.exe](https://www.voidtools.com/support/everything/command_line_interface/) which is somewhat compatable with the Linux `locate` command.  I recommend using `es.exe` via `helm-locate` which is part of the [Helm](https://github.com/emacs-helm/helm) package.

You can use `M-x customize-variable` to set the `helm-locate-command` to the path where `es.exe` is installed along with any commandline params you might want that are listed in the [Voidtools command line interface documentation](https://www.voidtools.com/support/everything/command_line_interface/).

***

# helm-everything.el

helm-everything.el is a [Helm](https://github.com/emacs-helm/helm) interface for [Voidtools Everything search engine](http://www.voidtools.com)

## Requirements
* [helm](https://github.com/emacs-helm/helm) 1.0 or higher
* [Voidtools Everything](http://www.voidtools.com) (version >= 1.3.3.658b Beta) for Windows
