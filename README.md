### Python Environment
python3 -m venv starknet source

### Pip dependencies
pip install cairo-nile
pip install openzeppelin-cairo-contracts

### Compiling contracts 
nile compile

### Deploying contracts
nile deploy <contract_name> <constructor_argument> <constructor_argument> <...> --network <deployment_network>

### Other commands
If you have problems with any nile commands, don't forget the --help option. 
Use nile --help to see all nile commands
