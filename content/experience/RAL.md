+++
title = 'Rehabilitation and Augmentation Lab'
date = 2025-03-31T20:15:31-07:00
draft = true
weight = 3

description= ""
summary = "Graduate Student Researcher working on robotic hardware for stroke rehabilitation"

toc= false
autonumber= false
math= true

readTime= false
hideBackToTop= true
hidePagination= true
showDate = false
showRange = true
dateRange = "September 2022 — Current"
+++

## Skills Utilized

{{< chips >}}SolidWorks, Experiment Design, MATLAB, Simulink Real-Time, HIL Testing, 3D Printing, Finite Element Analysis, Controller Design, Mentorship{{< /chips >}}

## Overview
Currently, I'm a third year PhD student working on developing robotic hardware for stroke rehabilitation. My research involves multiple domains from mechanical design, human-computer interaction, and controller design/tuning. During my time as a graduate student researcher, I have contributed to, as well as lead multiple projects.

My main project is to design, validate, and test a cable drive, bidirectional ankle exoskeleton. I own all parts of this project and have done extensive design, iteration, and prototyping to optimize on complexity and mass. Currently, I'm working on writing new controllers in MATLAB/Simulink Real-Time and testing them on people to collect gait metrics. Coupled with intrinsic capability measures, I aim to find correlations between physical attributes and robotic assisted therapy outcomes.
## At a Glance
{{< columns >}}

### Engineering Design Process

I was involved in all of the following steps:

1. Project ideation
1. Definition of requirements
1. Concept design
1. Iterative CAD design/drawings
1. Sensor selection and integration
1. Finite Element Analysis (hand calculations, static, impulse)
1. Prototyping
1. Controller design
1. Testing protocol (benchtop and on person)
1. Detailed design report
1. Iteration

<--->

### Detailed Design
I gained exposure into various facets of mechanical design including:

* System level FEA and subassembly analysis
* Controller design and debugging
* Sensor suite selection and testing
* Additive manufacturing and part tolerancing
* Design for human interaction
* Optimizing custom designs
* Rapid prototyping and iteration

{{< /columns >}}

## Background
Motor impairment affects roughly 18.6% of Americans. Existing therapies focus on retraining specific movements, but they often fail to translate to functional mobility in real-world settings. Robotic devices are a promising tool for adaptive and individualized therapy but are currently underutilized in clinical settings. 

Most exoskeletons provide assistance to the user by injecting torque at specific phases of the gait cycle to augment movement. Studies show that healthy individuals often benefit from this assistance through reduced energy expenditure and muscle activation. But individuals with motor impairment typically do not experience the same level of improvement. Additionally, there is still a large gap in our understanding of how motor learning occurs in impaired individuals and our ability to predict patient outcomes from therapies.

My research aims to address these questions by:

* Developing a bidirectionally actuating exoskeleton that can provide assistive and resistive torque at the ankle
* Building a library of controllers that can manipulate the user's gait to explore different therapeutic strategies
* Creating a model that can predict patient outcome from different exoskeleton therapies based on intrinsic capabilities

## Mechanical Design

### Defining Requirements

The requirements for the exoskeleton fell into two categories: functional requirements and performance requirements. The functional requirements were safety and comfort oriented. Performance requirements were defined so that the hardware did not limit the controller.


| Design Requirement             |              Metric       |
|--------------------------------|---------------------------|
| Mass                           | < 1 kg                    |
| Torque                         | > 60 Nm                   |
| Plantarflexion Range of Motion | 55 degrees                |
| Dorsiflexion Range of Motion   | 20 degrees                |


| Performance Requirement        |         Metric            |
|--------------------------------|---------------------------|
| Torque Resolution              | < 1 Nm                    |
| Angle Sensing Resolution       | < 0.1 degrees             |
| Bandwidth                      | > 10 Hz                   |


### Design

### Sensor Selection and Integration

### Analysis

## Validation

### Test Rig

### Results

## Controller Design

## Future Work

## Mentorship


