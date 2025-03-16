---
layout: post
title: "A Dumb Smart Lock"
date: 2024-7-31
---

## Preamble

My girlfriend only has one key to her apartment.
Sometimes she has to leave for school or work when it would be inconvenient for me to leave at the same time, but I also need in-and-out privileges before she'd get back.

My first thought was to spoof the digital chip inside her key. I thought it'd be easy because I watched a video on copying a magstrip from an old-fashioned swipe pass using a read-write peripheral for mag strips.
(There were even lower-fidelity options such as picking up the barcode mag strip pattern using iron filings)

There's a reason they don't use swipe cards any more. They're easy to hack! So I guess it's a good thing that it's not easy for me to clone the key. 
The key coding is done with a commercial fob reader/writer that costs $9000 to get your hands on, and there's no way they'd let a sketchy guy like me get my hands on one.

Clearly, the apartment management doesn't want anyone to open doors from the outside if they don't have a legitimate key. So, I should try figuring out how to open the doors from the *inside*, given that I'm already allowed to be inside.
I have a mechanical engineering degree, I should be able to figure out how to turn a deadbolt!

## Mechanical Design

The door lock has a smooth shape, so theres no corners to grip onto. I made some measurements with the calipers I stole from my dad a couple years ago to make a model of the lock.
![image](https://github.com/user-attachments/assets/04a1ce57-1921-4c51-b8f5-a187f7605a53)

The next step was then to CAD up the rest of the doohickey.
![door cad](https://github.com/user-attachments/assets/2f7727d2-9fdb-4425-ad3f-984eaef458c5)
The main housing of the device is the black shell that wraps around the lock. I accounted for the print tolerance so you'd be able to slide it on. In practice, I also added some paper shims so it would fit snugly without having to screw some clamps into the lock.

The green standoff holds a NEMA-17 stepper motor. Thankfully I have enough torque with the bare stepper so I don't have to gear it down.

There are also some mounts for two limit switches, one in the locked position, and one in unlocked. I intended for them to act as sensors so the motor knows when to stop spinning, but we'll get to that later.

## Controlling the Motor

## Hosting a server

## Smart Lock in Action


<iframe width="560" height="315" src="https://www.youtube.com/embed/oAbyvY5lPGY?si=WB8qXuF_QAK8bNBn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

