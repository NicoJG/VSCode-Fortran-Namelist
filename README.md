# Fortran Namelist Syntax Highlighting

VS Code extension for syntax highlighting in Fortran Namelist (`.nml`, `.namelist`) files.

My personal use case: Parameter files for the [GENE Code](https://genecode.org/)

## Features

- Syntax highlighting for variables, numbers, strings, booleans, and comments
- Folding for namelist blocks (`&name ... /`)
- Supports `.nml` and `.namelist` file extensions

## Usage

Just clone or download this repository and copy the folder into your VS Code extensions directory:

```sh
git clone https://github.com/NicoJG/VSCode-Fortran-Namelist.git ~/.vscode/extensions/fortran-namelist
```

Then restart VS Code.

Optional tip: If you want to highlight this syntax in other files you can either select it on the bottom right of VSCode or add the following in your VSCode `settings.json` :
```json
"files.associations": {
	"<file-pattern>": "fortran-namelist",
},
```
For example, for parameter files in GENE I use `parameters*` as `<file-pattern>`.

## Issues

Report bugs or suggestions
