# JSMN RPC #

This repository contains a JSON RPC implementation that is built on top of the JSMN parser. The RPC uses printf and some related string functions.

The API includes only 3 methods:    
`rpc_install_methods()` --- connects C methods to their RPC names.     
`rpc_handle_command()` --- parses and executes a JSON buffer.     
`workstatus_to_string()` --- converts error codes to readable messages.

### NOTE: This project uses my branch of JSMN - "First Child, Next Sibling", which can be found [here](https://bitbucket.org/azimoff/jsmn).     
      
See `example.c` for sample usage. Build example by running `build`.