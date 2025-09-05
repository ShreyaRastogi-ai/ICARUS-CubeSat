Minimal CubeSat EPS Simulation

Approach  
I created a simple Electrical Power System (EPS) model in CircuitJS to show how the battery charges and discharges during a 90-minute orbit, which includes 60 minutes of sunlight and 30 minutes of eclipse. I modeled the solar source as a pulsed current source, the battery as a large capacitor, and the loads as resistors with manual switches.

Assumptions  
- The solar panel with MPPT operates at an ideal efficiency, providing 6W.  
- The battery is treated as an ideal capacitor without complex chemistry.  
- The loads are purely resistive for simplicity.  
- EPS losses are ignored in this basic model.  

Tools Used  
- **CircuitJS1** (web version) for the simulation.  
- I used manual switches to simulate timed loads because of tool limitations.  

How to Run  
1. Open [CircuitJS](https://www.falstad.com/circuit/circuitjs.html).  
2. Copy and paste the circuit code from `src/satellite-eps-circuit.txt` into the simulator.  
3. Run the simulation and observe the scope.  
