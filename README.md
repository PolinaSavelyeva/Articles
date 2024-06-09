# Articles

This repository is dedicated to storing and organizing various reports, research papers, and related works. 

## Usage Features

If you are using online TeX editors, be sure for completing steps below.
- Upload the template files to your project, preserving the folder structure.
- Choose XeTeX (or LuaTeX) as the compiler (e.g., in [Overleaf](https://www.overleaf.com/), go to Menu &rarr; Compiler).

If you are using a TeX locally, the standard way to build is by using the following command:
```
make
```
By default, this command will compile the template using XeTeX. If you want to use LuaLaTeX instead, you can modify the `ENGINE` variable in the Makefile or use the following command:
```
make ENGINE=lualatex
```

## Template 
To find more options take a look at the original MatMech [template](https://github.com/spbu-se/matmex-diploma-template).
