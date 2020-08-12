# VSCode-LaTeX-Devcontainer
Devcontainer template for working with LaTeX in VSCode. This uses [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) for LaTeX editing, so refer to its manual for proper usage.
Note, the built-in PDF viewer for LaTeX Workshop is currently broken for remote connections; progress on this bug can be seen in the [relevant LaTeX Workshop GitHub issue](https://github.com/James-Yu/LaTeX-Workshop/issues/2206) (there is a [workaround](https://github.com/James-Yu/LaTeX-Workshop/issues/2206#issuecomment-659042978))).

The devcontainer Docker image is [tianon/latex](https://hub.docker.com/r/tianon/latex/dockerfile), which is quite bulky since it contains `texlive-full`.



