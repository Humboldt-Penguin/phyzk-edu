---
title: "Week 13: Waves & Sound -- NO SOLUTIONS"
hide:
  - toc
---

==$\Delta$ ← if you see the word "Delta" instead of a triangle, please refresh the page! Thanks :)==

&nbsp;

---

## Overview

I recommend reviewing the following concepts, they will probably come up in recitation:

- ^^Reading wave information from graphs^^
    - *from a displacement vs time graph: amplitude, period, frequency*
    - *from a displacement vs position graph: amplitude, wavelength*
    - *being careful about what each axis means*

- ^^Wave speed on a string^^
    - *$v = \dfrac{\lambda}{T} = f\lambda$*
    - *combining information from a time graph and a snapshot of the string*
    - *using fractions of a cycle or fractions of a wavelength when the graph does not show a full period directly*

- ^^Sound intensity and spherical spreading^^
    - *$I = \dfrac{P}{4\pi r^2}$ for a source radiating uniformly in all directions*
    - *intensity decreases like $1/r^2$*
    - *adding intensities from multiple independent sound sources*

- ^^Sound intensity level^^
    - *$\beta = 10\log_{10}\!\left(\dfrac{I}{I_0}\right)$*
    - *$I_0 = 1.0 \times 10^{-12}\ \mathrm{W/m^2}$*
    - *equal sources add in intensity, not in decibels*
    - *for $N$ identical sources: $I_{\mathrm{tot}} = NI_{\mathrm{one}}$*

- ^^Doppler effect^^
    - *for a moving source and stationary observer:*
    - *approaching: $f' = f\dfrac{v}{v-v_s}$*
    - *receding: $f' = f\dfrac{v}{v+v_s}$*
    - *for air near room temperature: $v \approx 331 + 0.60T_C \ \mathrm{m/s}$*

- ^^Interference from two in-phase speakers^^
    - *wavelength from $\lambda = v/f$*
    - *constructive interference: path difference $= m\lambda$*
    - *destructive interference: path difference $= \left(m+\tfrac12\right)\lambda$*
    - *on the line between the speakers, carefully writing each distance to the point*

&nbsp;

&nbsp;

---

## Practice Problems

- If you're comfortable with the "★★★" problems, you should do great during recitation.
- To print these questions, simply press `Ctrl + P` while on this page, and it should come out formatted nicely -- just make sure to refresh first so all the math renders properly.
    <!-- - For a copy *without* solutions, [click here](./13nosols.md){ target="_blank" rel="noopener noreferrer" }. -->

<!--
regex for all solution admonition blocks:

^ {4}\?\?\?\s+success\s+"Solution"\r?\n(?: {8}.*\r?\n|\r?\n)*

-->

---

**Difficulty key:**

- ★☆☆ = beginner
- ★★☆ = standard
- ★★★ = challenging / multi-step

!!! info "Waves and Sound Constants / Reminders"

    - $I_0 = 1.0 \times 10^{-12}\ \mathrm{W/m^2}$
    - For a spherical wave from a point source: $I = \dfrac{P}{4\pi r^2}$
    - Sound intensity level: $\beta = 10\log_{10}\!\left(\dfrac{I}{I_0}\right)$
    - Wave speed: $v = f\lambda = \dfrac{\lambda}{T}$
    - Frequency and period: $f = \dfrac{1}{T}$
    - Speed of sound in air: $v \approx 331 + 0.60T_C \ \mathrm{m/s}$
    - Moving source, stationary observer:
        - approaching: $f' = f\dfrac{v}{v-v_s}$
        - receding: $f' = f\dfrac{v}{v+v_s}$
    - Two-source interference:
        - constructive: $\Delta r = m\lambda$
        - destructive: $\Delta r = \left(m+\tfrac12\right)\lambda$

&nbsp;

---

### [1] Wave Graphs and Speed on a String

1. ★☆☆ <br> A displacement vs time graph is taken at one end of a string. The graph shows a maximum displacement of $+3.0\ \mathrm{cm}$, a minimum displacement of $-3.0\ \mathrm{cm}$, and the time between successive crests is $0.40\ \mathrm{s}$.
    - (a) What is the amplitude?
    - (b) What is the period?
    - (c) What is the frequency?

1. ★☆☆ <br> A snapshot of a sinusoidal wave on a string shows a maximum displacement of $2.5\ \mathrm{cm}$ and a distance of $1.8\ \mathrm{m}$ between two neighboring crests.
    - (a) What is the amplitude?
    - (b) What is the wavelength?

1. ★★☆ <br> At one point on a string, a displacement vs time graph shows that the wave has a period of $0.25\ \mathrm{s}$. A snapshot of the string shows a wavelength of $1.50\ \mathrm{m}$.
    - (a) Find the frequency.
    - (b) Find the wave speed.

1. ★★☆ <br> A displacement vs time graph at a fixed point on a string shows troughs at $t=0.10\ \mathrm{s}$ and $t=0.46\ \mathrm{s}$. A snapshot of the string at one instant shows that four full wavelengths occupy $2.40\ \mathrm{m}$ of the string.
    - (a) Find the period.
    - (b) Find the frequency.
    - (c) Find the wavelength.
    - (d) Find the wave speed.

1. ★★★ <br> A point on a string is observed as the wave passes by. A crest occurs at $t=0.18\ \mathrm{s}$, and the next time that same point passes through equilibrium moving downward is at $t=0.27\ \mathrm{s}$. In a snapshot of the string taken at one instant, a crest is located at $x=0.20\ \mathrm{m}$ and the nearest trough to its right is at $x=0.80\ \mathrm{m}$.
    - (a) Find the period.
    - (b) Find the frequency.
    - (c) Find the wavelength.
    - (d) Find the wave speed.

1. ★★★ <br> A displacement vs time graph for a point on a string shows that the point goes from $y=0$ moving upward to the next crest in $0.060\ \mathrm{s}$. A snapshot of the string shows that the distance from one zero crossing with positive slope to the next zero crossing with positive slope is $0.96\ \mathrm{m}$.
    - (a) Find the period.
    - (b) Find the frequency.
    - (c) Find the wavelength.
    - (d) Find the wave speed.
    - (e) How long does it take a crest to travel $7.2\ \mathrm{m}$ along the string?

---

### [2] Sound Intensity and Sound Level

1. ★☆☆ <br> A small speaker emits sound uniformly in all directions with a power output of $18.0\ \mathrm{W}$.
    - What is the sound intensity at a distance of $6.00\ \mathrm{m}$ from the speaker?

1. ★☆☆ <br> A sound wave has an intensity level of $72.0\ \mathrm{dB}$.
    - What is its intensity?

1. ★★☆ <br> At your location, one room fan produces a sound intensity level of $79.0\ \mathrm{dB}$. How many identical fans would be needed to produce a sound intensity level of $88.0\ \mathrm{dB}$ at that same location?

1. ★★☆ <br> One student speaking alone produces a sound intensity level of $56.0\ \mathrm{dB}$ at the back of a classroom. If $12$ students are all talking independently with the same intensity at that same location, what sound intensity level results?

1. ★★★ <br> Two identical outdoor speakers are separated by $24.0\ \mathrm{m}$. Each emits sound uniformly in all directions with a power output of $0.400\ \mathrm{W}$.
    - (a) Find the total sound intensity at the midpoint between the speakers.
    - (b) A person then walks $5.00\ \mathrm{m}$ directly toward one of the speakers. What total sound intensity do they hear there?

1. ★★★ <br> Thirty-six identical machines together produce a sound intensity level of $96.0\ \mathrm{dB}$ at a certain point in a workshop.
    - (a) Find the total sound intensity produced by all $36$ machines.
    - (b) Find the intensity produced by one machine.
    - (c) What sound intensity level would result if only $4$ of these machines were running?

---

### [3] Doppler Effect and Two-Speaker Interference

1. ★☆☆ <br> What is the speed of sound in air on a day when the temperature is $22.0^\circ\mathrm{C}$?

1. ★☆☆ <br> A sound wave in air has frequency $680\ \mathrm{Hz}$. If the speed of sound is $340\ \mathrm{m/s}$, what is the wavelength?

1. ★★☆ <br> A police car moves at $31.0\ \mathrm{m/s}$ while sounding a siren of frequency $720\ \mathrm{Hz}$. The air temperature is $25.0^\circ\mathrm{C}$.
    - What frequency is heard by a stationary observer when the police car is approaching?

1. ★★☆ <br> Two in-phase loudspeakers, $A$ and $B$, face each other and are separated by $1.50\ \mathrm{m}$. They emit sound of frequency $680\ \mathrm{Hz}$, and the speed of sound is $340\ \mathrm{m/s}$.
    - (a) What is the wavelength?
    - (b) Locate all points on the line between the speakers, measured from speaker $A$, where destructive interference occurs.

1. ★★★ <br> An ambulance travels at $27.0\ \mathrm{m/s}$ and emits a siren of frequency $950\ \mathrm{Hz}$. The air temperature is $15.0^\circ\mathrm{C}$.
    - (a) Find the speed of sound in air.
    - (b) What frequency is heard by a stationary observer as the ambulance approaches?
    - (c) What frequency is heard by the observer after the ambulance passes and is moving away?

1. ★★★ <br> Two in-phase loudspeakers, $A$ and $B$, face each other and are separated by $1.50\ \mathrm{m}$. They emit sound of frequency $660\ \mathrm{Hz}$, and the speed of sound is $330\ \mathrm{m/s}$.
    - (a) What is the wavelength?
    - (b) Locate all points on the line between the speakers, measured from speaker $A$, where constructive interference occurs.

