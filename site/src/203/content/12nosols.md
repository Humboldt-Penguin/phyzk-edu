---
title: "Week 12: Thermodynamics"
hide:
  - toc
---

==$\Delta$ ← if you see the word "Delta" instead of a triangle, please refresh the page! Thanks :)==

NOTE: this page was updated Friday, April 17, ~12pm to add more problems :)

&nbsp;

---

## Overview

I recommend reviewing the following concepts, they will probably come up in recitation:

- ^^The first law of thermodynamics^^
    - *$\Delta U = Q - W$*
    - *taking $W$ to mean work done by the gas*
    - *keeping track of signs carefully*

- ^^Internal energy and heat capacities for a monatomic ideal gas^^
    - *$U = \tfrac32 nRT$*
    - *so $\Delta U = \tfrac32 nR\Delta T$*
    - *$C_V = \tfrac32 R$ and $C_P = \tfrac52 R$*
    - *internal energy depends only on temperature*

- ^^Special thermodynamic processes^^
    - *isothermal: $\Delta T = 0$, so $\Delta U = 0$*
    - *constant volume: $W = 0$*
    - *adiabatic: $Q = 0$*
    - *constant pressure: $Q = nC_P\Delta T$*

- ^^Work from a $PV$ diagram^^
    - *area under the curve*
    - *positive for expansion*
    - *negative for compression*
    - *for straight-line segments, using trapezoid areas*

- ^^Using $PV=nRT$ to compare states on a diagram^^
    - *if $n$ is fixed, then $T \propto PV$*
    - *using endpoint states to find temperature changes*
    - *for a monatomic gas, $\Delta U = \tfrac32 (P_fV_f - P_iV_i)$*

- ^^Heat engines and thermal efficiency^^
    - *$e = \dfrac{W}{Q_H}$*
    - *$W = Q_H - Q_C$*
    - *power is work per time*
    - *keeping track of whether quantities are per cycle or per second*

- ^^Carnot efficiency^^
    - *$e_{\mathrm{Carnot}} = 1 - \dfrac{T_C}{T_H}$*
    - *reservoir temperatures must be in Kelvin*
    - *real engines must have efficiency below Carnot*

&nbsp;

&nbsp;

---

## Practice Problems

- If you're comfortable with the "★★★" problems, you should do great during recitation.
- To print these questions, simply press `Ctrl + P` while on this page, and it should come out formatted nicely -- just make sure to refresh first so all the math renders properly.
    <!-- - For a copy *without* solutions, [click here](./12nosols.md){ target="_blank" rel="noopener noreferrer" }. -->

<!--
regex for all solution admonition blocks:

^ {4}\?\?\?\s+success\s+"Solution"\r?\n(?: {8}.*\r?\n|\r?\n)*

-->

---

**Difficulty key:**

- ★☆☆ = beginner
- ★★☆ = standard
- ★★★ = challenging / multi-step

!!! info "Thermodynamics Constants / Reminders"

    - $R = 8.31 \ \mathrm{J/(mol \cdot K)}$
    - For a monatomic ideal gas: $U = \tfrac32 nRT$
    - $C_V = \tfrac32 R$
    - $C_P = \tfrac52 R$
    - First law: $\Delta U = Q - W$
    - Isothermal ideal-gas process: $\Delta U = 0$
    - Constant-volume process: $W = 0$
    - Adiabatic process: $Q = 0$
    - Heat-engine efficiency: $e = \dfrac{W}{Q_H}$
    - Carnot efficiency: $e_{\mathrm{Carnot}} = 1 - \dfrac{T_C}{T_H}$
    - Useful conversion: $1\,\mathrm{kPa \cdot L} = 1\,\mathrm{J}$
    - Latent heat of vaporization of water: $L_v = 2.26 \times 10^6\,\mathrm{J/kg}$
    - Power: $1\,\mathrm{W} = 1\,\mathrm{J/s}$

&nbsp;

---

### [1] First Law, Internal Energy, and Special Processes

1. ★☆☆ <br> A rigid container holds $0.200 \ \mathrm{mol}$ of a monatomic ideal gas. The gas is heated from $310 \ \mathrm{K}$ to $370 \ \mathrm{K}$.
    - (a) Find the change in internal energy.
    - (b) Find the work done by the gas.
    - (c) Find the heat added to the gas.

1. ★☆☆ <br> During an isothermal expansion of an ideal gas, the gas does $680 \ \mathrm{J}$ of work on its surroundings.
    - (a) What is the change in internal energy of the gas?
    - (b) How much heat flows into or out of the gas?

1. ★★☆ <br> A sample of $0.350 \ \mathrm{mol}$ of a monatomic ideal gas is compressed isothermally at $300 \ \mathrm{K}$ from $3.60 \ \mathrm{L}$ to $1.20 \ \mathrm{L}$.
    - (a) Find the change in internal energy.
    - (b) Find the work done by the gas.
    - (c) Find the heat flow into or out of the gas.

1. ★★☆ <br> A closed rigid container holds $0.240 \ \mathrm{mol}$ of a monatomic ideal gas at $290 \ \mathrm{K}$. The gas is heated until its pressure is $2.50$ times its initial value.
    - (a) What is the final temperature?
    - (b) What is the change in internal energy?
    - (c) How much heat is added to the gas?

1. ★★★ <br> In an adiabatic process, the temperature of $3.20 \ \mathrm{mol}$ of a monatomic ideal gas drops from $500^\circ\mathrm{C}$ to $140^\circ\mathrm{C}$.
    - (a) How much heat is exchanged with the surroundings?
    - (b) What work does the gas do?
    - (c) What is the change in internal energy of the gas?

1. ★★★ <br> The temperature of a $2.80 \ \mathrm{mol}$ sample of a monatomic ideal gas is initially $320 \ \mathrm{K}$. Its internal energy is doubled by the addition of heat.
    - (a) How much heat is needed if the gas is heated at constant volume?
    - (b) How much heat is needed if the gas is heated at constant pressure?

---

### [2] $PV$ Diagrams, Work, and Heat

1. ★☆☆ <br> A gas expands at constant pressure $P = 180 \ \mathrm{kPa}$ from $1.40 \ \mathrm{L}$ to $4.10 \ \mathrm{L}$. What is the work done by the gas?

1. ★☆☆ <br> A fixed amount of an ideal gas goes from state $A$ to state $B$.

    $$A: (P=150 \ \mathrm{kPa},\ V=2.00 \ \mathrm{L},\ T=300 \ \mathrm{K})$$

    $$B: (P=250 \ \mathrm{kPa},\ V=3.00 \ \mathrm{L})$$

    What is the temperature at point $B$?

1. ★★☆ <br> A monatomic ideal gas goes from state $A$ to state $C$ in two steps on a $PV$ diagram:
    - $A \to B$: constant volume from $(1.50 \ \mathrm{L},\ 200 \ \mathrm{kPa})$ to $(1.50 \ \mathrm{L},\ 350 \ \mathrm{kPa})$
    - $B \to C$: constant pressure from $(1.50 \ \mathrm{L},\ 350 \ \mathrm{kPa})$ to $(4.50 \ \mathrm{L},\ 350 \ \mathrm{kPa})$

    If the temperature at point $A$ is $200 \ \mathrm{K}$, find:

    - (a) the temperature at point $C$
    - (b) the total work done by the gas
    - (c) the change in internal energy
    - (d) the total heat added to the gas

1. ★★☆ <br> A monatomic ideal gas moves from state $A$ to state $B$ along a straight-line path on a $PV$ diagram.

    $$A: (V=2.00 \ \mathrm{L},\ P=120 \ \mathrm{kPa},\ T=280 \ \mathrm{K})$$

    $$B: (V=5.00 \ \mathrm{L},\ P=300 \ \mathrm{kPa})$$

    Find:

    - (a) the temperature at point $B$
    - (b) the work done by the gas
    - (c) the change in internal energy
    - (d) the heat added to the gas


1. ★★★ <br> A monatomic ideal gas moves along the following four-segment path on a $PV$ diagram:
    - from $A=(2.00 \ \mathrm{L},\ 100 \ \mathrm{kPa})$ horizontally to $(3.00 \ \mathrm{L},\ 100 \ \mathrm{kPa})$
    - then linearly to $(5.00 \ \mathrm{L},\ 250 \ \mathrm{kPa})$
    - then horizontally to $(7.00 \ \mathrm{L},\ 250 \ \mathrm{kPa})$
    - then linearly to $B=(9.00 \ \mathrm{L},\ 150 \ \mathrm{kPa})$

    If the temperature at point $A$ is $240 \ \mathrm{K}$, find:

    - (a) the temperature at point $B$
    - (b) the total work done by the gas
    - (c) the change in internal energy
    - (d) the total heat added to the gas

1. ★★★ <br> A monatomic ideal gas is taken from state $A$ to state $C$, where

    $$A: (V=2.00 \ \mathrm{L},\ P=150 \ \mathrm{kPa},\ T=300 \ \mathrm{K})$$

    $$C: (V=6.00 \ \mathrm{L},\ P=300 \ \mathrm{kPa}).$$

    Compare the following two paths between the same endpoints:

    - **Path 1:** a straight-line path from $A$ directly to $C$
    - **Path 2:** first go vertically to $(2.00 \ \mathrm{L},\ 300 \ \mathrm{kPa})$, then horizontally to $C$

    For each path, find:

    - (a) the work done by the gas
    - (b) the heat added to the gas

    Also find:

    - (c) the change in internal energy between $A$ and $C$
    - (d) which path requires more heat input

---

### [3] Heat Engines and Carnot Efficiency

1. ★☆☆ <br> A heat engine absorbs $2.20 \times 10^3 \ \mathrm{J}$ of heat each cycle and exhausts $1.50 \times 10^3 \ \mathrm{J}$ each cycle.
    - (a) How much work is done per cycle?
    - (b) What is the engine's efficiency?

1. ★☆☆ <br> A heat engine does $480 \ \mathrm{J}$ of work in each cycle, and each cycle lasts $0.250 \ \mathrm{s}$. What is the power output of the engine?

1. ★★☆ <br> A heat engine operates at three-quarters of the efficiency of a Carnot engine working between a hot reservoir at $525^\circ\mathrm{C}$ and a cold reservoir at $75^\circ\mathrm{C}$.

    What is the operating efficiency of the engine?

1. ★★☆ <br> The efficiency of a heat engine is $55.0\%$ of the efficiency of a Carnot engine operating between $45^\circ\mathrm{C}$ and $245^\circ\mathrm{C}$. If the engine absorbs heat at a rate of $20.0 \ \mathrm{kW}$, at what rate is heat exhausted?

1. ★★★ <br> A heat engine has a thermal efficiency of $34.0\%$. Its heat input each cycle is supplied by the condensation of $4.20 \ \mathrm{kg}$ of steam at $100^\circ\mathrm{C}$.
    - (a) How much heat is absorbed each cycle?
    - (b) How much work is done each cycle?
    - (c) How much heat is lost to the surroundings each cycle?

1. ★★★ <br> A proposed ocean-thermal power plant would operate between warm surface water at $24^\circ\mathrm{C}$ and deep water at $7^\circ\mathrm{C}$.

    - (a) What is the maximum possible efficiency of such a plant?
    - (b) If the electrical power output is $80.0 \ \mathrm{MW}$, how much heat must be absorbed from the warm reservoir each hour, assuming the plant operates at that maximum efficiency?

