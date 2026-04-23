---
title: "Week 13: Radioactive Decay & Nuclear Reactions -- NO SOLUTIONS"
hide:
  - toc
---

For solutions, please visit: [edu.phyzk.net/206/rec/13/](./13.md)

==$\Delta$ ← if you see the word "Delta" instead of a triangle, please refresh the page! Thanks :)==

&nbsp;

---

## [1] Overview

I recommend reviewing the following concepts, they will probably come up in recitation:

- ^^Radioactive decay and half-life^^
    - *$N(t)=N_0e^{-\lambda t}$*
    - *$A(t)=A_0e^{-\lambda t}$*
    - *$\lambda=\dfrac{\ln 2}{T_{1/2}}$*
    - *after one half-life, the activity is cut in half*

- ^^Activity units^^
    - *$1\ \mathrm{Bq}=1\ \text{decay/s}$*
    - *$1\ \mathrm{Ci}=3.70\times10^{10}\ \mathrm{Bq}$*
    - *$1\ \mathrm{mCi}=3.70\times10^7\ \mathrm{Bq}$*
    - *activity is proportional to the number of undecayed nuclei*

- ^^Balancing nuclear reactions^^
    - *mass number $A$ must be conserved*
    - *atomic number $Z$ must be conserved*
    - *the missing particle or nuclide can usually be found by balancing $A$ and $Z$ separately*

- ^^Common decay modes^^
    - *alpha decay: emits $^4_2\mathrm{He}$*
    - *beta-minus decay: emits $^0_{-1}\mathrm{e}$ and increases $Z$ by 1*
    - *beta-plus decay: emits $^0_{+1}\mathrm{e}$ and decreases $Z$ by 1*
    - *electron capture: absorbs an inner electron and decreases $Z$ by 1*

- ^^Reaction energy / Q-values^^
    - *$Q=(m_{\mathrm{reactants}}-m_{\mathrm{products}})c^2$*
    - *$1\ \mathrm{u}=931.5\ \mathrm{MeV}/c^2$*
    - *positive $Q$ means energy is released*
    - *negative $Q$ means energy is absorbed / required*

- ^^Using atomic masses carefully^^
    - *for most balanced nuclear reactions, neutral atomic masses can be used directly if the same total number of electrons appears on both sides*
    - *for $\beta^-$ decay, atomic masses can be used as $Q=(M_{\mathrm{parent}}-M_{\mathrm{daughter}})c^2$*
    - *for $\beta^+$ decay, atomic masses require subtracting $2m_e$: $Q=(M_{\mathrm{parent}}-M_{\mathrm{daughter}}-2m_e)c^2$*

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

!!! info "Useful Constants"

    - $\ln 2 = 0.693$
    - $1\ \mathrm{Bq}=1\ \mathrm{s^{-1}}$
    - $1\ \mathrm{Ci}=3.70\times10^{10}\ \mathrm{Bq}$
    - $1\ \mathrm{mCi}=3.70\times10^7\ \mathrm{Bq}$
    - $m_n = 1.008665\ \mathrm{u}$
    - $m_e = 0.00054858\ \mathrm{u}$
    - $1\ \mathrm{u}=931.5\ \mathrm{MeV}/c^2$

&nbsp;

---

### [2.1] Radioactive Decay, Half-Life, and Activity

1. ★☆☆ <br> A radioactive isotope has a half-life of $12.0\ \mathrm{min}$ and an initial activity of $4.80\times10^5\ \mathrm{Bq}$.
    - (a) Find the decay constant in $\mathrm{min^{-1}}$.
    - (b) Find the decay constant in $\mathrm{s^{-1}}$.
    - (c) What is the activity after $12.0\ \mathrm{min}$?
    - (d) What is the activity after $24.0\ \mathrm{min}$?

1. ★☆☆ <br> A sample of a radioactive tracer has an activity of $18.0\ \mathrm{mCi}$ at noon. Its half-life is $6.00\ \mathrm{h}$.
    - (a) What is the activity at 6:00 p.m.?
    - (b) What is the activity at midnight?
    - (c) What percentage of the original activity remains at midnight?

1. ★★☆ <br> A radioisotope has a half-life of $4.20\ \mathrm{h}$ and an initial activity of $2.50\ \mathrm{mCi}$.
    - (a) Find the activity after $10.5\ \mathrm{h}$.
    - (b) Convert your answer to becquerels.

1. ★★☆ <br> A radioactive sample has a half-life of $2.50\ \mathrm{days}$. Its activity is initially $1600\ \mathrm{Bq}$.
    - (a) How long will it take for the activity to fall to $100\ \mathrm{Bq}$?
    - (b) How many half-lives have passed during this time?

1. ★★★ <br> A sample of fluorine-18 has a half-life of $110\ \mathrm{min}$. At 7:30 a.m., its activity is $12.0\ \mathrm{mCi}$. A patient is scheduled to receive the sample at 9:40 a.m.
    - (a) What will the activity be at 9:40 a.m.?
    - (b) If the patient needs at least $5.00\ \mathrm{mCi}$ at injection time, is this sample sufficient?
    - (c) What activity would the sample need to have at 7:30 a.m. in order to have exactly $5.00\ \mathrm{mCi}$ at 9:40 a.m.?

1. ★★★ <br> A sample initially contains $6.40\times10^6$ undecayed nuclei of a radioactive isotope with half-life $3.00\ \mathrm{h}$.
    - (a) Find the decay constant in $\mathrm{s^{-1}}$.
    - (b) Find the initial activity of the sample.
    - (c) How many undecayed nuclei remain after $7.50\ \mathrm{h}$?
    - (d) What is the activity after $7.50\ \mathrm{h}$?

---

### [2.2] Balancing Nuclear Reactions and Identifying Decay Modes

1. ★☆☆ <br> Complete the following nuclear reaction and identify the decay mode:

    $$^{226}_{88}\mathrm{Ra}\rightarrow X+{}^4_2\mathrm{He}$$

1. ★☆☆ <br> Complete the following nuclear reaction and identify the decay mode:

    $$^{14}_{6}\mathrm{C}\rightarrow X+{}^0_{-1}\mathrm{e}$$

1. ★★☆ <br> Complete the following reaction:

    $$^{27}_{13}\mathrm{Al}+{}^4_2\mathrm{He}\rightarrow X+{}^1_0\mathrm{n}$$

    - (a) Find the mass number of $X$.
    - (b) Find the atomic number of $X$.
    - (c) Identify the nuclide $X$.

1. ★★☆ <br> Complete the following decay reaction and classify the decay:

    $$^{64}_{29}\mathrm{Cu}\rightarrow{}^{64}_{28}\mathrm{Ni}+X$$

1. ★★★ <br> Complete the following reaction and classify the missing particle:

    $$^{23}_{11}\mathrm{Na}+{}^2_1\mathrm{H}\rightarrow{}^{24}_{12}\mathrm{Mg}+X$$

    - (a) Find $A_X$.
    - (b) Find $Z_X$.
    - (c) What particle is $X$?
    - (d) Explain why this is not an alpha particle or a proton.

1. ★★★ <br> A uranium nucleus $^{238}_{92}\mathrm{U}$ undergoes two alpha decays followed by one beta-minus decay.
    - (a) What is the final mass number?
    - (b) What is the final atomic number?
    - (c) What is the final nuclide?
    - (d) Would the final answer change if the beta-minus decay occurred between the two alpha decays instead?

---

### [2.3] Nuclear Reaction Energetics and Q-Values

1. ★☆☆ <br> Consider the fusion reaction

    $$^2_1\mathrm{H}+{}^3_1\mathrm{H}\rightarrow{}^4_2\mathrm{He}+{}^1_0\mathrm{n}.$$

    Use the following atomic masses:

    $$m(^2_1\mathrm{H})=2.014102\ \mathrm{u},\quad m(^3_1\mathrm{H})=3.016049\ \mathrm{u},$$

    $$m(^4_2\mathrm{He})=4.002603\ \mathrm{u},\quad m_n=1.008665\ \mathrm{u}.$$

    - (a) Find the total mass of the reactants.
    - (b) Find the total mass of the products.
    - (c) Find the reaction energy $Q$ in MeV.
    - (d) Is energy released or absorbed?

1. ★☆☆ <br> Tritium can beta-minus decay according to

    $$^3_1\mathrm{H}\rightarrow{}^3_2\mathrm{He}+{}^0_{-1}\mathrm{e}+\bar\nu.$$

    The atomic mass of $^3_1\mathrm{H}$ is $3.016049\ \mathrm{u}$, and the atomic mass of $^3_2\mathrm{He}$ is $3.016029\ \mathrm{u}$.

    - (a) Using atomic masses, find the mass difference.
    - (b) Find the energy released in MeV.

1. ★★☆ <br> Consider the reaction

    $$^7_3\mathrm{Li}+{}^1_1\mathrm{H}\rightarrow{}^4_2\mathrm{He}+{}^4_2\mathrm{He}.$$

    Use the following atomic masses:

    $$m(^7_3\mathrm{Li})=7.016004\ \mathrm{u},\quad m(^1_1\mathrm{H})=1.007825\ \mathrm{u},$$

    $$m(^4_2\mathrm{He})=4.002603\ \mathrm{u}.$$

    - (a) Find the total reactant mass.
    - (b) Find the total product mass.
    - (c) Find $Q$ in MeV.
    - (d) Is this reaction exothermic or endothermic?

1. ★★☆ <br> Consider the reaction

    $$^{14}_{7}\mathrm{N}+{}^4_2\mathrm{He}\rightarrow{}^{17}_{8}\mathrm{O}+{}^1_1\mathrm{H}.$$

    Use the following atomic masses:

    $$m(^{14}_{7}\mathrm{N})=14.003074\ \mathrm{u},\quad m(^4_2\mathrm{He})=4.002603\ \mathrm{u},$$

    $$m(^{17}_{8}\mathrm{O})=16.999132\ \mathrm{u},\quad m(^1_1\mathrm{H})=1.007825\ \mathrm{u}.$$

    - (a) Find the mass of the reactants.
    - (b) Find the mass of the products.
    - (c) Find $Q$ in MeV.
    - (d) Is energy released or absorbed?

1. ★★★ <br> Sodium-22 can decay by positron emission:

    $$^{22}_{11}\mathrm{Na}\rightarrow{}^{22}_{10}\mathrm{Ne}+{}^0_{+1}\mathrm{e}+\nu.$$

    The atomic mass of $^{22}_{11}\mathrm{Na}$ is $21.994436\ \mathrm{u}$, and the atomic mass of $^{22}_{10}\mathrm{Ne}$ is $21.991385\ \mathrm{u}$.

    - (a) Why is this classified as beta-plus decay?
    - (b) When using atomic masses, what mass difference should be used for a beta-plus decay?
    - (c) Find the energy released in MeV.

1. ★★★ <br> Consider the reaction

    $$^{11}_{5}\mathrm{B}+{}^1_1\mathrm{H}\rightarrow3\left({}^4_2\mathrm{He}\right).$$

    Use the following atomic masses:

    $$m(^{11}_{5}\mathrm{B})=11.009305\ \mathrm{u},\quad m(^1_1\mathrm{H})=1.007825\ \mathrm{u},$$

    $$m(^4_2\mathrm{He})=4.002603\ \mathrm{u}.$$

    - (a) Verify that mass number and atomic number are conserved.
    - (b) Find the total mass of the reactants.
    - (c) Find the total mass of the products.
    - (d) Find $Q$ in MeV and state whether energy is released or absorbed.

