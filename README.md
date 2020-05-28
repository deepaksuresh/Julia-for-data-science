# Julia-for-data-science

Follow the steps below to get started with the notebooks

1. Install JuliaPro from [here](https://juliacomputing.com/products/juliapro). You can find instructions for installation in the [documentation](https://juliacomputing.com/docs/). 
    - In order to run in multi-threaded mode you will have to set number of threads Julia starts up with is controlled by an environment variable called JULIA_NUM_THREADS. On Linux/OSX, from Bash, execute `export JULIA_NUM_THREADS=10` or C shell on Linux/OSX, CMD on Windows, execute `set JULIA_NUM_THREADS=10` or Powershell on Windows execute `$env:JULIA_NUM_THREADS=10`
2. Launch Julia repl in JuliaPro
3. Switch to Pkg mode by pressing `]`
4. Install packages with the commands below
    - `add CSV@0.6.2`
    - `add BenchmarkTools@0.5.0`
    - `add CategoricalArrays@0.8.0`
    - `add DataFrames@0.21.0`
    - `add IJulia@1.21.2`
    - `add StatsPlots@0.14.5`
5. Exit Pkg mode by pressing backspace or ^C
6. Launch IJulia with `using IJulia`
7. Start notebook with `notebook()`
