# HALF_SUBTRACTOR
# Aim:
To simulate and synthesis half subtractor using vivado.

# Apparatus Required:
vivado software.

# Procedure:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed. 

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it. 

STEP:5 Select the run simulation adn then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table. 

STEP:7 Select the Implementation in the Sources Window and select the required file in the Processes Window.

STEP:8 Compare the output with logic truth table. 


# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![Half-Subtractor-in-Digital-Logic](https://github.com/Shaiksushma123/HALF_SUBTRACTOR/assets/159005642/882d1a9f-1e86-4a8f-9d87-b466cbd9eff3)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)

# Program
module half_sub(a,b,diff,borrow);

input a,b; 

output diff,borrow; 

xor g1(diff,a,b);

and g2(borrow,~a,b);

endmodule

# Output
![image](https://github.com/Shaiksushma123/HALF_SUBTRACTOR/assets/159005642/b0c2211b-2828-4b2a-9cf8-e69f82356a6b)

# Result:
Thus the verilog program for half subtractor has been simulated and verified successfully using logic truth table.
