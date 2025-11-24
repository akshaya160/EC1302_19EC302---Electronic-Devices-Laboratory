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

<img width="1280" height="896" alt="image" src="https://github.com/user-attachments/assets/e94b1f21-25ae-41ff-ac7e-26109e106a6a" />

## AC INPUT WAVEFORM:

<img width="1280" height="848" alt="image" src="https://github.com/user-attachments/assets/04e29c1e-13d8-4c1c-ba22-557a830e7528" />

## MODELGRAPH:

<img width="1031" height="954" alt="image" src="https://github.com/user-attachments/assets/210ac412-2c69-4a5e-af4a-866b8b581d65" />

## SIGNAL OUTPUT(WITHOUT FILTER)

<img width="1280" height="959" alt="image" src="https://github.com/user-attachments/assets/d2e67649-39fa-45fb-b985-93d602791619" />

## SIGNAL OUTPUT(WITH FILTER)

<img width="1280" height="1140" alt="image" src="https://github.com/user-attachments/assets/fc750138-195b-4f47-9c58-d9d37a6caa6b" />

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
