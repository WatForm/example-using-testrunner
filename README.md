# README.md

This repo contains a simple example and documentation of how to use the testrunner scripts in the repo.

The example-using-testrunner repo is not needed to run testrunner on your own application.

Documentation on how to use testrunner is supplied within the example.py file.

# Running the example

1) Put the testrunner directory as a subdirectory of this one

`git clone https://github.com/WatForm/testrunner.git`

testrunner should be a subdirectory of example-using-testrunner now.

2) Set up the venv in the example-using-testrunner directory

`python3 -m venv venv`

`source ./venv/bin/activate`

`python -m pip install --upgrade pip`  # if you want to upgrade pip

`python -m pip install -r requirements.txt`

`deactivate`

3) Run the example

`./example.py`  # to execute the command with options as described in example.py in venv

example.py will generate a log file called log-date-time.txt listing the commands run and showing all their option value combinations plus their stdout and stderr output.

Input files (inputstrings.py, test.csv) are provided to run example-simple.py.

4) Now, let's say you want to do performance evaluation in a directory called `fortress-eval`.  Check out testrunner within `fortress-eval` (step 1 above).  Copy example.py, requirements.txt from here into `fortress-eval`.  Run step 2 above within `fortress-eval`. Modify example.py to suite your purpose.

More complicated examples of how to use testrunner can be found in other evaluation repos of Watform.
   
## Acknowledgements

These scripts were mainly written by Owen Zila with modifications by Nancy Day.
