# example-module
This is an example CJR module. 

# Requirements
The only requirement is that you have an index.cjr file, you can have submodules and these also need an index.cjr file. 
For a submodule example check out [here](https://github.com/CJR-Org/websocket) (the serve folder is the submodule) for implementation and [here](https://github.com/CJR-Org/ccjr/blob/master/examples/websocket.cjr) for usage. 

# Scripts
If your module requires a script to be run after the repository is cloned, you must add a `postinstall.sh` script to the root folder of your repository. This file must have execute permissions as PCJR will not do this for you.

# Distribution
To add the repository to Moduland, go [here](https://moduland.ml/add_module).