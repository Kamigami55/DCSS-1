# DCSS-1 - Debris Collecting Space Ship

Our great work for NASA hackathon 2018 Taipei

![](https://imgur.com/7tYi4eZ.png)

## 1. Project related links
- [Github repo](https://github.com/Kamigami55/DCSS-1/)
- [2018 NASA Hackathon team page](https://2018.spaceappschallenge.org/challenges/can-you-build/design-based-nature-fusion/teams/whatarewedoinghereohohohoh-oh/project)
- [Orbital Debris Visualization live demo](https://whatarewedoinghereohohoh.github.io/OrbitalDebrisVisualization/index.html)
- [Presentation in 2018 NASA Hackathon Taipei 20181021 (powerpoint)](https://drive.google.com/file/d/1DceDTZ9Sdh7Bcu7WrRrVSJb9wR8Y28c-/view?usp=sharing)

## 2. What we want to solve - Orbital Debris problem

Since the debris on space increase year by year. Some satellites are therefore being damaged by these garbage. Resulting in a considerable amount of loss. But the technology nowadays can not solve such a problem. In this case, we think a space ship with sustainabillity might be a good direction to improve the problem as Boyan Slat did. 

## 3. Basic Idea of DCSS-1

DCSS-1 is a new type of spacecraft designed to cleanup orbital debris around Earth.

It contains the following key components:

- Spacecraft body ( a 10km long rope with heavy loads on 2 side )
- Solar sails
- Debris capture web ( can be stored in the rope )
- 5 Movable heavy loads
- Tidal power generator

we try to obtain the orbit debris data and converse them into the longitude and latitude data. 
And display these information on a web using javascript and webGL. 
Also, with these data, we designed a new type of space ship to collect these debris. 
The importance of our design is that we only need to supply the fuel once and for all. 
The space ship will move by itself automatically. 
We illustrate such a model using 3D modeling.

## 4. Technology details

### (1) Visualization of Orbital Debris

By visualizing orbital debris, we can easily know how important the problem of orbital debris is.

And can help us to find the best path to deploy our DCSS-1 to clean more debris

**Live demo: http://makereallabs.com/Cesium_with_SGP.html**

Result: 

![](https://github.com/Kamigami55/DCSS-1/blob/master/orbital-debris-visualization.gif)

Technologies we used:
- Satellite.js: Converting TLE data format to SGP4
- Cesium.js: Visualizing objects on virtual globe

Data resource: [NORAD & NASA TLE](https://celestrak.com/NORAD/elements/)

### (2) Characteristic of DCSS-1 spacecraft

1. use the gravity of earth to implement semi-automatic self-generating electric power
2. provide a new solution to clean the space debris
3. reusable
4. less fuel
5. use solar sails as power source to fix the latitude
6. positioning with tle of space debris

### (3) Design of DCSS-1 spacecraft

It contains the following key components:

- Spacecraft body ( a 10km long rope with heavy loads on 2 side )
- Solar sails
- Debris capture web ( can be stored in the rope )
- 5 Movable heavy loads
- Tidal power generator

![](https://imgur.com/bEQ1YXw.png)

### (4) Operation of DCSS-1 spacecraft

DCSS-1 spacecraft workflow:

![](https://imgur.com/lzhTtBQ.png)

Simulation of DCSS-1 spacecraft:

![](https://imgur.com/JfG3Wr9.gif)

## 5. Team members
- [Chi Sheng, Chen ( Michael )](https://github.com/ChiShengChen)
- [Chi Lin, Lu ( James )](https://github.com/lujames13)
- [Shu Ming, Chang ( Eric )](https://github.com/ericz7000nolan)
- [Yin Hsiang, Chang ( Eason )](https://github.com/Kamigami55/)

## 6. References

- [daoneil/spacemission](https://github.com/daoneil/spacemission)
- [USA Space Debris Environment, Operations, and Policy Updates](http://www.unoosa.org/pdf/pres/stsc2011/tech-31.pdf)
- [CelesTrak: Current NORAD Two-Line Element Sets](https://celestrak.com/NORAD/elements/)

