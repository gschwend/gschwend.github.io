# gschwend.github.io

Julia Gschwend's personal website built with [Hugo](https://gohugo.io/) and the [Toha theme](https://github.com/hugo-toha/hugo-toha.github.io). 


## Requirements

We use [jdx/mise](https://github.com/jdx/mise) to manage dependencies. Mise takes care of installing `hugo`, `go`, `nodes` and other tools to appropriate versions. Please, install it following the instruction from [here](https://mise.jdx.dev/getting-started.html).

## Running Locally
- Install dependencies
```
mise install
```
- Run hugo server
```
mise run server
```

## Updating theme
- To update theme to latest release, run:
```
mise run update
```
- To update theme to latest commit from `main` brnach, run:
```
mise run update-to-main
```