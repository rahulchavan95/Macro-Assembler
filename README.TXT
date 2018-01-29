File folder contains:
macro_def_generate.py=> to generate the output
macro.asm => input file in this file i write some macroes



What is this ?
-------------	

	This is the program file to create MNT(Macro Name Table) & MDT(Macro Definition Table).This program will store the Macros from the assembly code.


How to use this programmes files ?



1)After run the following command to execute the code
	 
	  $ python macro_def_generate.py

    This command create the required output files that is 'macro_op.txt'
    and allmacro call get replaced by the definition



2)To see the result use following command
	

	To see the output of the program execute following command.
	
		$cat macro_op.txt
