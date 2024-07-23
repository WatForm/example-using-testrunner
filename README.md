# README.md

This repo contains a simple example and documentation of how to use the testrunner scripts in the repo.

The example-using-testrunner repo is not needed to run testrunner on your own application.

# Running the example

Putting the testrunner directory as a subdirectory of this one:

`git clone https://github.com/WatForm/testrunner.git`

Setting up the venv:

`python3 -m venv venv`

`source ./venv/bin/activate`

`python -m pip install --upgrade pip`  # if you want to upgrade pip

`python -m pip install -r requirements.txt`

`deactivate`

Running the example:

`./example.py`  # to execute the command with options as described in example.py in venv

example.py will generate a log file called log-date-time.txt listing the commands run and showing all their option value combinations.

Input files (inputstrings.py, test.csv) are provided to run example-simple.py.

Documentation on how to use testrunner is supplied within the example.py file.

## Acknowledgements

These scripts were mainly written by Owen Zila with modifications by Nancy Day.
