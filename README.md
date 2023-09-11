# verilogPath

When learning FPGA design, there are two languages to choose from, Verilog or VHDL. They are called HDLs, or hardware design languages. Unlike a language like C, where they define what you want the circuit to do, HDLs define how the hardware needs to be configured.
If companies around you where you might want to work use VHDL, learn VHDL! <-- This is my case.
But it will be 

Here's some of the common concepts of Verilog:
1.Module declaration: module <module_name> (<list_of_ports>);

2.Data types: wire, reg, integer, real, etc.

3.Continuous assignments: assign <wire_name> = ;

4.Port declaration: input <port_name>, <port_name>; or output <port_name>, <port_name>;

5.Behavioral modeling: initial and always blocks for concurrent and sequential logic respectively.

6.Loops: for, while, repeat loops.

7.Conditional statements: if (condition) begin end

8.Case statements: case (expression) <case_item> : <case_item> : endcase

9.Function and Task: function <function_name>; <function_body> endfunction and task <task_name>; <task_body> endtask

10.Timing control: # for delaying the execution of a statement.

11.Structural modeling: instantiation of modules and use of parameter to pass values.

12.Preprocessor directives: define, include, ``ifdef, ``endif, etc.
