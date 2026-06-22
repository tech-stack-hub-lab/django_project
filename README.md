# django_project
Optimized tool selection

I’ll check the workspace setup first so I can give you the exact steps that match this project and VS Code.

In VS Code on macOS, the usual way is:

Open the integrated terminal
Activate the environment from the project folder
If your virtual environment is named .venv:

source .venv/bin/activate
If it is named venv:

You should then see something like:

Also set it in VS Code
After activating once, open the Command Palette and run:

Python: Select Interpreter
Then choose the interpreter that points to your environment (the one inside .venv or venv).

Quick check
Run:

which python
python --version
If the path points inside your environment folder, it is active correctly.

If VS Code still uses the wrong Python, restart the terminal after selecting the interpreter.