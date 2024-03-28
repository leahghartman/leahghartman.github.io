---
title: Writing a Particle-In-Cell (PIC) Plasma Simulation Code
author: Leah
date: 2024-03-12 14:33:00 -0500
categories: [Physics, Code]
pin: true
math: true
mermaid: true
---

Over the past, around a year now, I've been working in the field of Plasma Wakefield Acceleration. This field relies heavily on efficient codes that can simulate the physics behind these new accelerator systems, which are based on plasmas rather than conventional metallic RF (radio-frequency) accelerators.

This is just my journey through creating my own, small, particle-in-cell (PIC) code for simulating simple situations. I am by no means an expert, this is simply what I have learned along the way. With that, let's get started :D!

## Why Attempting to Do Plasma Physics Via Simulation _Makes Sense_ 

At first glance, a 




## Important Theory (Physics)

Unfortunately, there is some important math and physics theory that we need to know in order to create a PIC code (I know, I know, I just want to code as well, but we'll get to the fun part later). This isn't necessarily *hard*, and if you have any experience with physics at the undergraduate level, all of this should be understandable. Therefore, I'm going to go over it somewhat quickly.



$$
\begin{equation}
  \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6}
  \label{eq:series}
\end{equation}
$$

We can reference the equation as \eqref{eq:series}.

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

## Important Theory (Code)

## Implementing a Yee Grid and Yee Solver

## Implementing a Particle Pusher

## Sources

