
# FCL self-interpreter
This repository contains an FCL-self interpreter. Since FCL only supports integers, lists (nested aswell) and qoute values ('value) the programs need to be encoded in a special way. The programs in ```test_programs/``` are programs following such encodings. This readme maybe updated in the future show the encoding is done.  

# Interpreter  
The interpreter is implemented in int.fcl and expects two inputs.  
 - An encoded fcl program.
 - A list of inputs. If there are none an empty list must be passed.

 ### standard_fcl_examples  
 In the folder ```standard_fcl_examples/``` are a few ordinary FCL programs that were used while I learned how the FCL language worked. Or things I needed to test at a small scale before using them in the interpreter implementation.

 # Cogen
 This project was made with the purpose of using the code generator in [Cogen](https://github.com/svbrodersen/cogen/tree/main).  
 Likewise the interpreter was written with the focus of working with the implementations of evaluator/cogen that Cogen implements which is why it uses things like ```call```.

 The folder ```cogens/``` contains outputs from the code generator.
