# conda-agent
This library is a Python AI Agent for the conda ecosystem.

It should be considered unstable untile the release of v1.0

# Installing conda-agent

Using pip
`pip install -i https://test.pypi.org/simple/ test-agent==0.0.1`

# Using conda-agent

From any shell, call `conda-agent` then supply the message flag `-m` then your prompt in quotes.

`conda-agent -m "What is the difference between conda-forge and conda?"


# Testing
When testing this package, you should run with --all-features flag to ensure all tests are executed.

`grayskull pypi pytest`