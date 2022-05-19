# multitank-matbal-tutorial

*Read this in other languages: [English](README.md), [Русский](README.ru.md)*

Designed to better understand the structure and the implementation of the [MultiTankMaterialBalance](https://github.com/sidelkin1/MultiTankMaterialBalance.jl) package.

## Quick installation

Requires `Jupyter` to work. The easiest way to do this is to install [Anaconda](https://www.anaconda.com/), as follows:

- Download the installer (https://www.anaconda.com/download/) and follow the instructions for your platform.

- After installation, check the box to add `Python` to the `PATH` environment variable.

Also, [Julia](http://julialang.org/downloads/) and [Git Bash](https://git-scm.com/downloads) must be installed. Further you require

- Download repository using command

```
git clone https://github.com/sidelkin1/multitank-matbal-tutorial
```

- Start `Julia REPL` and run the command

```julia
using Pkg; Pkg.add("IJulia")
```

- Next run the command
 
```julia
cd("path/to/multitank-matbal-tutorial")
```

where you need to specify the correct path to the downloaded repository.

- Install additional required packages via `Julia REPL` with the command
 
```julia
Pkg.activate("."); Pkg.instantiate()
```

- Run command in terminal

```
jupyter lab path/to/multitank-matbal-tutorial
```

- In the folder `tutorial` open the notebook `tutorial.ipynb`