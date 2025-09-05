
 Observations
- During the 60-minute sunlight period, the battery voltage rises as it charges.
- During the 30-minute eclipse, the battery voltage falls as it powers the loads.
- Turning on additional loads (TT&C, ADCS) causes sharp drops in voltage because of higher power demand.

 Component Mapping
| Circuit Component      | Real-World Equivalent | Function |
|------------------------|------------------------|----------|
| Pulse Current Source   | Solar Panels + MPPT   | Provides 6W during sunlight, 0W during eclipse |
| 5F Capacitor           | Battery               | Stores energy; voltage shows SOC |
| 50Ω Resistor           | OBC + Housekeeping    | Constant load that is always on |
| 200Ω Resistor + Switch | TT&C Radio            | Intermittent high-power load |
| 150Ω Resistor + Switch | ADCS Thruster         | Periodic medium-power load |
