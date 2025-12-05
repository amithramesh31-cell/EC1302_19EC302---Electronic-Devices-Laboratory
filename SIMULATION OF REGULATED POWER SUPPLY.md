# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="903" height="412" alt="Screenshot 2025-11-26 223715" src="https://github.com/user-attachments/assets/d44730a4-c418-4c9c-afcb-406abb46c041" />

## AC INPUT WAVEFORM:
<img width="779" height="390" alt="Screenshot 2025-11-26 223727" src="https://github.com/user-attachments/assets/c0be6415-c179-477a-8788-005e6f0b773c" />

![WhatsApp Image 2025-11-29 at 13 24 19_7db82be1](https://github.com/user-attachments/assets/f8c56a6d-fa7e-42cf-b305-218f0ab9a417)

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="778" height="393" alt="Screenshot 2025-11-26 223738" src="https://github.com/user-attachments/assets/33e1b892-ae89-4568-9d93-4126b3f58724" />

![WhatsApp Image 2025-11-29 at 13 24 46_52431489](https://github.com/user-attachments/assets/1a03d143-ab68-4513-ae2b-d94fa74af04e)

## SIGNAL OUTPUT(WITH FILTER)
<img width="776" height="388" alt="Screenshot 2025-11-26 223746" src="https://github.com/user-attachments/assets/83f25ef9-8582-4571-a5bf-e0bee2798e49" />

![WhatsApp Image 2025-11-29 at 13 25 13_d246df81](https://github.com/user-attachments/assets/3377bd94-10bc-4bb2-b68f-37420cdf254d)

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
