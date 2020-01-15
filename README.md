# Fuzzer
For example, a calculator script might not correctly handle an input of a string. The fuzzer outputs which arguments failed and which ones did not. 

## How it works

The fuzzer takes in the path to an XML file that specifies a program and a filepath to the program. 

## How to run it 
$ ./fuzzer [path to XML configuration file] [path to the target program]
