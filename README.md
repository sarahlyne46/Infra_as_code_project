# Infras_as_code_project
Udacity DevOps Course - Project 2

There are 2 files to be run, in order: network.yml then servers.yml

This can be done using the scripts included in the repository with the following inputs:
1. stack name - This can be anything.  Note: for the network & server scripts to work, the stack names will need to be different.
2. file name - network.yml or servers.yml
3. parameter file: network_params.json or servers_params.json

First creation, use create.sh
e.g. ./create.sh UdacityProject2 network.yml network_params.json

Updates can be done with the same inputs
e.g. ./update.sh UdacityProject2 network.yml network_params.json

To delete the stack, run the delete script:
./delete.sh UdacityProject2

To use the CLI rather than scripts, the instructions are available in CloudFormation CLI Info.txt

