# Pythontex Tikzplotlib Project Template

Generate tikz diagrams with Python directly in .tex files using [pythontex](https://ctan.org/pkg/pythontex) and [tikzplotlib](https://github.com/nschloe/tikzplotlib).

## Getting Started

You will need a working latex install as well as [pipenv](https://pypi.org/project/pipenv/).

```shell
pipenv install # install python dependencies
pipenv run dev # start latexmk in watch mode
pipenv run build # run latexmk once
pipenv run clean # run latexmk -c
```