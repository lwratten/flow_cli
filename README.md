# Flow CLI
Productivity tracker and time management application

## dev instructions
1. `git clone https://github.com/lwratten/flow_cli.git`
2. `cd flow_cli`
3. `python3 -m venv env` create a python virtual environment if you haven't already
4. `source env/bin/activate`  activate / go into the virtual environment
5. `pip install --editable .` 


### Files
* Directory `flow` contains the core code of the tool.
* Directory `commands` contains Click commands, e.g. save. 
* File `falcon_megaqc/cli.py` sets up Click so it will automatically search the `commands` directory for commands. After installing, run `flow` and see the commands available.
* File `setup.py` allows you to use `pip install --editable .` or `pip install .`.


## User Instructions
1. The above dev instructions + `flow` command.


test git config