# TITTLE
Design and simulate 1:8 De- MUX using Verilog.
# THEORY
De-multiplexer is also a device with one input and multiple output lines. It is used to send a signal to one of the many devices. The main difference between a multiplexer and a de- multiplexer is that a multiplexer takes two or more signals and encodes them on a wire, whereas a de-multiplexer does reverse to what the multiplexer does. In 1 to 8 De-multiplexer, there are total of eight outputs, i.e., Y0, Y1, Y2, Y3, Y4, Y5, Y6, and Y7, 3 selection lines, i.e., S0, S1and S2 and single input, i.e., A. On the basis of the combination of inputs which are present at the selection lines S0, S1 and S2, the input will be connected to one of these outputs. The block diagram and the truth table of the 1×8 de-multiplexer are given below.
# PROCEDURE
Step 1 Create a project with required entities.

Step 2 Create a module along with file name for DE MUX .

Step 3 Type the code in the created module and run the stimulation.

Step 4 After it get successfully runned get the respective RTL outputs.

Step 5 Create university program(VWF) for getting timing diagram.

Step 6 Give the respective inputs for timing diagram and get the results.

### PROGRAM
```
Developed by: RATHISH KUMAR C
RegisterNumber: 212222100043
```
#### De- MUX using Verilog programming.
```
module demux_1_8(y,s,a); output reg [7:0]y;
input [2:0]s; input a;
always @(*) begin y=0;
case(s) 3'd0: y[0]=a; 
3'd1: y[1]=a; 3'd2: y[2]=a; 
3'd3: y[3]=a; 3'd4: y[4]=a;
3'd5: y[5]=a; 3'd6: y[6]=a;
3'd7: y[7]=a; 
endcase 
end 
endmodule
```
# BLOCK DIAGRAM
![image](https://github.com/rathishc12/Simulation-project--Digital-Electronics/assets/120539398/9141f8dc-aefd-49d7-98c2-fdf71ce1220f)

# LOGIC DIAGRAM
![image](https://github.com/rathishc12/Simulation-project--Digital-Electronics/assets/120539398/c698afeb-5275-452c-9a9f-d5146f46bde7)

# NETLIST DIAGRAM
![image](https://github.com/rathishc12/Simulation-project--Digital-Electronics/assets/120539398/caaa0142-2172-414a-96ac-fe2a5d520381)

# TIMING DIAGRAM
![image](https://github.com/rathishc12/Simulation-project--Digital-Electronics/assets/120539398/e9e27332-b1e2-42fa-a2d2-1dd01744e0e3)

# RESULT
Thus Designed and simulated 1:8 De- MUX using Verilog programming.
