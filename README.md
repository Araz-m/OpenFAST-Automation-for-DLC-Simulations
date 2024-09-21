# OpenFast_DLC_Autorun_Optimus_295_20_Hochschule Flensburg
This tool is capable of running a complete DLC with all the wind and hydroDyn files and in furthur steps a loop of different DLC simulations in openfast automatically
https://github.com/WindEnergyEngineering/Optimus-295-20/tree/master/OpenFAST/Optimus-295-20

A detailed *pdf manual* will be added as a guide



**running each DLC seperately:** 

1- Here I name the file DLC12.py but I recommend to change the name based on your prefered DLC

2- paste the file next to your openfast.exe and batch file

3- Wind and Wave files must be in a seperated directory before the main folder (or you have to define the path in the code)

4- Define the path of the batch file in the script

5- I recommend to run the code in VScode because in contrast with cmd it can be scrolled for furthure checks


**running all DLCs together:**

1- you have to copy and paste the DLC12.py in each DLC seperetely and edit it accordingly

2- Define the path on all those dlc.py files you have in this FullyAutomate.py

that's it

# I am aware of that this script does not fully automate the process of simulation with openfast, but I believe it would be a great help 
# I hope future students/developers participate in it's developing to make the steps more comperhensible for everyone
