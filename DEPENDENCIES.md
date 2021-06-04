# Installation

This project was developed using Python 3.9.1.

You may want to install Python and the libraries in `requirements.txt` using `pyenv` and `pipenv`.

 - There is a command-line JSON processor called [**jq**](https://stedolan.github.io/jq/) that could help you extract and work with the `Pipfile.lock`. You may want to check out [this blog by Zebradil](https://zebradil.me/post/2019-04-24-pipfile-lock-to-requirements-txt/) to understand how to create `requirements.txt` from `Pipfile.lock`. I've also included `create_requirements.sh` for this matter.


### Known issues:

Bash scripts may not run if you do not have an execution permission. To grant execution permission to the current user, execute this command in the `gutenberg-project` directory: 

`chmod u+x ./create_requirements.sh`