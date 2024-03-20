---
title: "uFluidic Device"
excerpt: "Creating a microfluidic device to mix two fluids."
header:
  teaser: /assets/img/syringe.jpg
gallery:
  - image_path: /assets/img/pic1.jpg
  - image_path: /assets/img/pic3.jpg
  - image_path: /assets/img/pic4.jpg
   
---

<br>

# Introduction

Microfluidic (uFluidic) devices refer to systems with small liquid channels. Microfluidic devices can be used in fluid mixing, droplet generation, and fluid separation. There are many possible applications including medical diagnostics, DNA sequencing, tissue engineering, and
environmental testing. By leveraging precise control over small volumes of liquids, microfluidic devices enable efficient and accurate processes, revolutionizing traditional methods and opening avenues for rapid, cost-effective, and portable solutions in a multitude of applications.

In microfluidics, achieving effective mixing poses a significant challenge due to the absence of turbulent mixing commonly observed in macro-scale fluid systems. Instead, microfluidic devices typically operate under laminar flow conditions within small chambers, where conventional mixing mechanisms are inefficient. To overcome this limitation, the next solution is chaotic advection, which leverages geometric intricacies or external perturbations to induce chaotic flow patterns within the laminar regime, thereby enhancing mixing efficiency. This necessitates innovative design approaches and precise control strategies to harness chaotic advection for homogeneous mixing.


<br>

# Parts

| Item                                           | Quantity |
|------------------------------------------------|----------|
| 250 mm lead screw with 2 mm pitch and 2 mm lead  | 1        |
| 250 mm lead screw with 2 mm pitch and 8 mm lead  | 1        |
| 1/4" x 8mm Flexible Coupling                     | 1        |
| 200 mm linear rod with 8 mm diameter            | 2        |
| LM8UU Linear bearing for 8 mm diameter rod      | 2        |
| 2040 Aluminum Extrusion 1' Length               | 1        |
| Nema 17 Stepper Motor                           | 1        |
| MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp | 1 |
| Arduino Uno                                     | 1        |
| A4988 Stepper Driver                            | 1        |
| Small Breadboard                                | 1        |
| Panel Mount Latching Push Buttons               | 1        |
| Limit Switch                                    | 1        |
| RGB Common Cathode LED                          | 1        |
| Monetary Buttons                                | 1        |
| Potentiometer (Not Incorporated)                | 1        |

# Custom Designed Parts

| Custom Part                    |
|--------------------------------|
| Carriage (Syringe Plunger Support) |
| Syringe Tip End Support        |
| LED Mount                      |
| Syringe Body Middle Mounting Plate |
| NEMA 17 Motor Mounting Plate   |
| Left End Mount                 |
| Electronics Enclosure Lid      |
| Electronics Enclosure Box      |

<br>

# Code

<script src="https://gist.github.com/mariusschueller/2ad81b6cef701bb5aa797111ca2e98c5.js"></script>

Code On [Github](https://github.com/mariusschueller/Syringe/blob/master/main/main.ino). 

<br>

# Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e10515e96ce3f04fe?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>

# Operating Instructions

1. **Loading the Syringe:**
   - Place the syringe in the pump with its outward extrusions fitting into the middle support.
   - Ensure the syringe tip faces away from the motor, and the plunger end is in the carriage's top extrusion.

2. **Powering On:**
   - Plug in the syringe pump to an outlet. 

3. **Starting Operation:**
   - Once powered on, press the latching button to start the pump. The LED will turn green, indicating the pump is running.

4. **Pausing Operation:**
   - Press the latching button once more to pause the pump. The LED will turn yellow, signaling a pause in operation.

5. **Completing Operation:**
   - When the syringe is empty, and the carriage hits the limit switch on the middle mount, the pump stops, and the LED turns red.

6. **Directional Control:**
   - Use additional buttons to change the motor's direction.
   - Hold the left button to move the syringe back for refilling, and hold the right button to empty the syringe at a constant rate.

<br>


{% include gallery caption="uFluidic Device Photos" %}
