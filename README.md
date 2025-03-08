# PIR_for_ASL_SU2C

This repository is part of the paper:

 *Delay-Based Control of a High Gain Transformerless DC-DC Converter* by E. Moreno-Negrete, J. A. Hernández Gallardo, A. Ramirez, & C.-F. Mendez-Barrios (to be on the 5th Modeling, Estimation and Control Conference (MECC 2025) October 5-8, 2025 Pittsburgh, Pennsylvania, USA)
 
 Recognizing that the controller parameters algebraic functions are *big enough* to attach in the paper, here we attach the MATLAB functions for the elimination produced polinomial, and the PIR controller gains. The user's have to look at the running test section as a demo to get the numerical value of controllers' parameters.


## Running Tests

To run the function for the PIR controller, the user must run the following command

```bash
  [hsol] = solvability_curve([s0max:stepS0:s0min]);
```

To run the function for the PR controller, the user must run the following command

```bash
  [kp, ki, kr, h] = f_PIR_controller(s0, a, b, c, d, e, f, g, z);
```

## Feedback

If you have any feedback, please reach out to us at emone@ieee.org


## Acknowledgements

 - E. Moreno-Negrete thanks CONAHCYT for his PhD scholarship number (CVU: 990591)

