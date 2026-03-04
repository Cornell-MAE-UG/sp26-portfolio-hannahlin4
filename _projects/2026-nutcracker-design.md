---
layout: project
title: Nutcracker Design
description: Design of a nutcracker based on physical values
---
**Problem Statement and Objective**\
Imagine you have a macadamia nut that you want to crack open by hand
using a simple lever nut cracker. Calculate the necessary dimensions of the nutcracker and come up with a design to make this task feasible. You can assume a very simple geometry for the nutcracker to make your calculations easier. You will need to find typical values for the inputs (e.g. size for macadamia nuts and maximum grip strength). Then, modify the design to use a linear actuator.\
**Constraints and Input Parameters**\
Diameter of macadamia nuts: 20 mm\
Maximum grip strength: 40 kg\
Average load to crack a macadamia nut: 222.18 kg\
IP65 Mini Linear Actuator: Model PA-01\
Force: 16-225 lbs\
Stroke: 1-40 in.\
Length: 5.13"\
**Approach to the Problem**\
First, I drew a free body diagram of a potential nutcracker. I made it very simple, with just two arms. Then, I found values for constants online. I used a momentum balance on A to find the proportion of lc over ln which was about 5.55. This was used to find the diameter of the nutcracker which was calculated to be 11.11 cm. Thus, the length of the nutcracker was 22 cm. \
<img width="259" height="117" alt="Screenshot 2026-03-04 at 12 50 08 AM" src="https://github.com/user-attachments/assets/5ae2cd80-218e-4883-b12f-3266f21d58c7" />\
Then, for the linear actuator I repeated the previous calculations but with different values. The proportion of lc/ln was 2.17, and the length was 11.59 cm with a diameter of 13 cm. \
**Usability of design**\
The design does not seem very usable, since the diameter was 11.11 cm for the first one which is large and hard to grip onto. For the linear actuator, it is still quite large and likely unwieldy. 
