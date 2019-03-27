---
layout: single
classes: wide
mathjax: true
title: "A test gone right. Also, notes on Quantum Sensing"
categories: ["Quantum Sensing Notes"]
tags: ["quantum", "sensing", "notes"]
read_time: true
---
## Non-sequitur Intro
I cannot believe that I was able to get that to work so quickly! In my first post
I did not cite any sources (oops) and figured that would change moving forward.
So now I sit here listening to a chill-hop study beats stream like the nerd
I am, writing (more accurate: typing) this post.

## A Brief Summary [^Degen2017]
The paper I will be reviewing is <i>Quantum Sensing</i>,
by C. L. Degen [^Degen2017]. It does not focus on specific devices such as superconducting
sensors, NV centers, etc., but instead centers around the general principles of
quantum sensing. It covers such topics as the qualifications to be a quantum sensor,
noise spectroscopy, sensitivity, and protocols. Each of these topics are deep enough
to have stand-alone books and perhaps in future posts we can explore them
further. But for now we'll stick to the task at hand and review <i>Quantum Sensing</i>.
<br>
<br>
Let's begin.

## What is a Quantum Sensor?
What is a quantum sensor? To answer that question let's first answer the question,
"What is a sensor?". Merriam-Webster defines sensor as "a device that responds to
a physical stimulus (such as heat, light, sound, pressure, magnetism, or a particular
motion) and transmits a resulting impulse (as for measurement or operating a
control)"[^sensor]. Okay, so what is a quantum sensor? Well we can borrow the
definition from Merriam-Webster and replace "a device that responds to a physical
stimulus" with "a <i>quantum</i> device that responds to a stimulus". The main
difference being that we are restricting the <i>type</i> of sensor to be quantum.
But what makes a sensor quantum? Conveniently, the paper we are reviewing has a
list of necessary conditions:
<ol>
  <li>The system has to have discrete, resolvable energy levels.</li>
  <li>You can initialize the sensor and you can perform readout (turn on
    and get answer).</li>
  <li>You can coherently manipulate the sensor.</li>
  <li>The sensor interacts with a physical quantity and has some response to that
  quantity.</li>
</ol>
Conditions 2 and 4 apply to all sensors and condition 3 is not strictly required.
Condition 1 might seem like a quality that only quantum systems have but in actuality
classical systems can be quantized as well (i.e. vibrations on a string).
There are some examples of sensors that most everyone would call quantum.
For example, a sensor that utilizes entanglement. But there are other sensors which
are a bit in the gray area, not exactly quantum, not exactly classical. Interference
experiments are a great example (is light quantum mechanical?). However, these
questions quickly devolve into philosophical debate and leaves practical physics
as an afterthought. For now we will move on and call a quantum sensor a sensor
that is not classical.
<br><br>
## Stopping point
I feel this a good place to stop. Mostly for me because I have other work to do,
such as prepare for my candidacy exam. However, the series will continue, so look
forward to that.

<br>
<br>
## References
[^Degen2017]: Degen, C. L., Reinhard, F., & Cappellaro, P. (2017). Quantum sensing. Reviews of Modern Physics, 89(3), 1–39. http://doi.org/10.1103/RevModPhys.89.035002
[^sensor]: sensor. 2019. In Merriam-Webster.com. Retrieved March 20, 2019, from https://www.merriam-webster.com/dictionary/sensor
