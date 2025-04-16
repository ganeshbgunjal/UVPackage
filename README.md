UV is a modern Python package manager created by Astral, the team behind Ruff.

Think of it as a super fast alternative to:

    pip (installing packages)

    virtualenv (creating isolated environments)

    pip-tools (dependency resolution)

It’s kind of like Poetry, but focused more on speed, simplicity, and modern tooling.

Commands for installing UV: 
    1. pip install uv
    2. uv init uvdemo       #this is folder in project.
    it will create necessory files bydefault. this is so fast.
    3. uv venv              #to create virtul environment
    4. .venv\Scripts\activate    #activate venv.. link is given there after creating venv.
    5. uv add pandas     #adding necessory files.
    6. uv add numpy
    7. uv add -r requirements.txt     #if you want to execute requirements.txt
    8. uv run main.py
    uv.lock file contains all the references from where all the packages are installed. it keeps all the track.