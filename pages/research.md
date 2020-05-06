---
layout: page
title: Research Activities
permalink: /research/
---

# Athletic Balancing and Hopping Robots

From end 2015 to beginning 2019 I have worked on a project of the Italian Institute of Technology (Istituto Italiano di Tecnologia, IIT) on the design of a monopedal balancing and hopping robot, named Skippy, as part of my MSc and PhD project.

The project explored physical performance limits of legged robots, in terms of jumping height and other highly dynamic objectives such as 3D balancing. The main aim of the project was to show that legged robots can be designed to exhibit levels of physical performance that outperform present-day robots and even most animals through a simplistic, holistic and technology-inspired design strategy. Skippy in particular was tasked to jump to a height of 4m. The feasibility of this was tackled in my [MSc Thesis](/staticfiles/documents/driessen2015msc.pdf) through simulation studies, results of which are mostly summarized in a [once submitted conference paper](/staticfiles/documents/driessen2017.pdf). It is furthermore minimally simple in having only two actuators, as it is the minimum number of actuators required to have full controllability in 3D, both for hopping and balancing. I firstly designed and built a precursor balancing-only prototype of Skippy, called Tippy. The design of both robots and related studies are well-described in my [PhD thesis](/staticfiles/documents/driessen2019phd-compressed.pdf).

#### Tippy

<img src="/staticfiles/figures/tippy.jpg" alt="tippy" width="400" align="right" hspace="20"/>
Tippy was designed and built to precede the balancing and hopping robot Skippy for the purpose of investigating its balancing performance, testing new balancing algorithms for 2D and 3D balancing, and being a design exercise for Skippy. I have been responsible for all of its mechanical design, most of its electronical design, and some of the real-time software implementations. The below video demonstrates a 2D balancing routine.
<iframe width="736" height="414" src="https://www.youtube.com/embed/ZQdiOBikxVQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Skippy

<img src="/staticfiles/figures/skippy-render.jpg" alt="skippy" width="400" align="right" hspace="20"/>
The design of Skippy was not only challenged by the requirement for reaching a jumping height of almost 4 m, but also by the required ability to survive a fall from the same height, to be fully autonomous (by requiring it to be able to get up unaided after a fall), and to be affordable. The design is the result of simulation and optimization studies, considerations for weight reduction, physical robustness and manufacturability. The robot has relatively few parts, with frames mainly consisting of carbon-fibre tubes glued to aluminium end pieces. Electronics are tactically placed and shielded behind bumpers. The design furthermore features a four-bar linkage mechanism and lightweight glass fibre and rubber springs to modulate and optimize power flow.


#### Ring Screw

<img src="/staticfiles/figures/ringscrew-functional-prototype.jpg" alt="ringscrew" width="400" align="right" hspace="20"/>
During the Skippy project I've mentored Elco Heijmink for his [MSc thesis on the modelling, development and evaluation of the novel Ring Screw transmission](https://repository.tudelft.nl/islandora/object/uuid%3Ae7e28551-0410-4303-a10a-92ec88aa91a4), an invention by Dr R. Featherstone. The ring screw is a rotational-to-linear transmission with purely rolling (little friction) principles, similar to the ball screw, but without a ball return mechanism and fewer parts, for which it is faster and more reliable. The ring screw invention came forth from the Skippy project because of the need for a transmission with a higher speed limit and power throughput than a ball screw, as this is currently largely responsible for limiting Skippy's theoretical performance.


# Rehabilitation Robotics
After the PhD, my research interests branched out from fundamental legged robot dynamics, mechanics and control to more applied research and product development, in particular in the field of human-machine interaction and medical devices. I am currently employed as a postdoc at IIT's department of Rehabilitation Technologies (RTech). My main project concerns the design and higher level control of a conceptually new hybrid above-knee prosthetic leg. It is a difficult but satisfying challange to create robotic devices that can truly help people comfortably in their daily lives.