# DataFrames.jl-Exercises

This repository is inspired by the [Pandas exercises](https://github.com/guipsamora/pandas_exercises) repository. While the data and structure remain the same, the key distinction lies in this repository's focus on demonstrating how to perform data engineering, data cleaning, and data visualization tasks. All exercises are adapted for [Julia language](https://julialang.org/) using the [DataFrames.jl](https://dataframes.juliadata.org/stable/) library.


## File Types

There are three types of files included in this repository:

1. **Exercises.ipynb**: Detailed instructions for each exercise.
2. **Solutions.ipynb**: Solutions presented without accompanying code.
3. **Exercises_with_solutions.ipynb**: Solutions with detailed code and explanatory comments.

Feel free to explore and enhance your skills in data manipulation and visualization using Julia and DataFrames.jl.


## Environment Setup

This repository is tested using Julia Version 1.10.3. To get started, please ensure that you have the required libraries installed from the Project.toml file by running:

```julia
using Pkg
Pkg.instantiate()
```

Additionally, every file in Exercises_with_solutions.ipynb begins by importing the project environment with the following commands:

```julia
using DotEnv
using Pkg
DotEnv.load!()
Pkg.activate(ENV["ENV_PATH"])
```

This means you should install DotEnv globally in your Julia environment and add an .env file in your desired directory with the appropriate ENV_PATH. Set your environment path as follows:

```
ENV_PATH = "your_env_path"
```


