# mkdocstrings-matlab-test

This is a test in reference to [#81](https://github.com/watermarkhu/mkdocstrings-matlab/issues/81) of the mkdocstrings-matlab handler. Reference documentation as well [here](https://watermarkhu.nl/mkdocstrings-matlab/latest/).

# Method

1. Download the Miniconda [here](https://repo.anaconda.com/miniconda/). Mine was the [Miniconda3-latest-MacOSX-arm64.sh](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh).
2. `bash Miniconda3-latest-MacOSX-arm64.sh` and follow those instructions. I installed within this temporary project directory so I will also not be creating a virtual environment either.
3. `source ./miniconda3/bin/activate` to activate the environment.
4. `python3 -m pip install mkdocstrings-matlab` which will install `mkdocstrings`, `mkdocs`, and the latest version of `mkdocstrings-matlab`.
5. `mkdocs serve` to fetch the documentation files and serve the pages as a local web server.
