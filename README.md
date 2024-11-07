After cloning this project, it is recommended you use pyenv to switch to the relevant version of the python interpreter used for this project by running the following command: pyenv local 3.10.6
Should this specific version of the python interpreter not being available from your machine, then set it up by using pyenv
You will then need to use poetry to build the Virtual Environment from the toml file, to this end, run the following command: poetry install
Activate the Virtual Environment using poetry, therefore executing the following command: poetry shell
Make sure you can run your program by executing the following command: python3 main.py
If you want to run the code from inside Visual Studio Code then select the appropriate project from the left panel, open a terminal (within Visual Studio Code) and run the following command to get the path of the virtual environment: poetry env info -p
Copy the path of the virtual environment to your clipboard, then Cmd + Shit + P to open the palette in Visual Studio Code, hit enter interpreter path, and paste the path.
You should now be good to run your project from Visual Studio Code !!
