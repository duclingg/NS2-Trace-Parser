# READ ME

## NS2 Trace File Parser
This program parses through an NS2 **.tr** file, to find to total degradation ratio of packets between all users.  

This program calculates: 
- Total percentage of packets dropped per second for each user.
- Total percentage of packets dropped per second for all users combined.  

Based on the output data **out.tr** from the simulation.  

## How to run
1. Run on either a Windows OS or Debian system, with NS2 and nam installed
2. Navigate to the resources folder using cmd
3. Run the script `ns test.tcl`
4. Once the simulation completes, you can open the visualizer using the script `nam out.nam`
5. Extract the **out.tr** file into the root program directory
6. Install **numpy** in the program directory using `py -m pip install numpy`
7. Install **matplotlib** in the program directory using `py -m pip install matplotlib` 
6. Run the program