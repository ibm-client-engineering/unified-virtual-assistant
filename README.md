# IBM Client Engineering Solutions Documentation Template

## What is this?
This is a template used to quickly and effectively document assets and solutions created by Client Engineers at IBM. The template outlines the bare minimum requirements that must be documented when publishing your work.

## Install Quarto
To be able to build and view changes locally for these docs you will need to install the appropriate version of Quarto from [here](https://quarto.org/docs/get-started/) and ensure one of the tools below is installed:
* VS Code
* Jupyter
* RStudio
* Neovim
* Text Editor

## How do I use it?
1. Change line 9 of the `_quarto.yml` file to the appropriate Project Name of the solution doc.
2. Change line 19 of the `_quarto.yml` file to the reflect the link to the repo of the newly created solution doc. Ex. https://github.com/ibm-client-engineering/[repo-name]
3. Assuming that Quarto is already installed, navigate to the appropriate directory with the cloned solution doc repository and run `quarto preview index.qmd` to preview your build locally.