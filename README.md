# testpyenv
This project is a test of demonstrating how I like to use pyenv and its pyenv-virtualenv plugin. It's about these things:

1. I'm exlcuding the file .python-version from version control, as I no longer use it to pin a project to a certain python version, but rather to an virtual environment name. The result of that is that pyenv-virtualenv automatically activates the virtual environment when navigating to the root directory in a terminal.
2. Any vscode task picks up on the the correct python executable if the correct pyenv environment is set.
3. If additonal environment variables are stored in .envrc it's picked up by the [direnv](https://direnv.net/) tool in a terminal
4. If using [this direnv extension] (https://github.com/direnv/direnv-vscode), any variable defined in .envrc is available in a vscode task.
