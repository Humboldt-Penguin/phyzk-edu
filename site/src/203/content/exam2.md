---
title: "Exam 2 Practice Problems"
# hide:
#     - toc
---

^^TIPS:^^

- If you want to print these questions, simply press `Ctrl + P` while on this page, and it should come out formatted nicely.
- If any of the math content isn't rendering properly, please refresh the page and it should be fixed.
    - *(e.g. you see something like `$v=\sqrt{2gh}$` instead of $v=\sqrt{2gh}$)*

---

**Difficulty key:**

- ★☆☆ = beginner
- ★★☆ = standard
- ★★★ = challenging / multi-step

<!--
---

## Table of Contents

- [[1] Energy, Work, and Conservation](#1-energy-work-and-conservation)
    - [[1.1] Work and Kinetic Energy](#11-work-and-kinetic-energy)
    - [[1.2] Potential Energy and Springs](#12-potential-energy-and-springs)
    - [[1.3] Mixed Energy Problems](#13-mixed-energy-problems)
- [[2] Momentum, Impulse, and Collisions](#2-momentum-impulse-and-collisions)
    - [[2.1] Momentum and Impulse](#21-momentum-and-impulse)
    - [[2.2] One-Dimensional Collisions](#22-one-dimensional-collisions)
    - [[2.3] Two-Dimensional Collisions and Explosions](#23-two-dimensional-collisions-and-explosions)
- [[3] Rotation](#3-rotation)
    - [[3.1] Rotational Kinematics](#31-rotational-kinematics)
    - [[3.2] Rotational Energy and Rolling](#32-rotational-energy-and-rolling)
    - [[3.3] Angular Momentum](#33-angular-momentum)
- [[4] Torque and Static Equilibrium](#4-torque-and-static-equilibrium)
    - [[4.1] Torque Basics](#41-torque-basics)
    - [[4.2] Static Equilibrium: Beams and Cables](#42-static-equilibrium-beams-and-cables)
- [[5] Springs and Simple Harmonic Motion](#5-springs-and-simple-harmonic-motion)
    - [[5.1] Spring Constants and Basic SHM Quantities](#51-spring-constants-and-basic-shm-quantities)
    - [[5.2] Energy in SHM](#52-energy-in-shm)
- [[6] Mixed Exam-Style / Multi-Concept Review](#6-mixed-exam-style--multi-concept-review)
-->

&nbsp;

---

## [1] Energy, Work, and Conservation

&nbsp;

### [1.1] Work and Kinetic Energy

1. ★☆☆ <br> A 0.40-kg stone is dropped from rest from a cliff 11.0 m high. Neglect air resistance. What is its speed just before it hits the ground?

    ??? success "Solution"
        Use energy conservation: $\frac12 mv^2 = mgh$.

        So $v=\sqrt{2gh}=\sqrt{2(9.8)(11.0)}=14.7\ \text{m/s}$.


        <br>**Answer:** $14.7\ \text{m/s}$ downward.

1. ★☆☆ <br> An 18.0-kg sled starts from rest on a horizontal frictionless surface. A constant 48.0-N force pulls it through 7.50 m. What is the sled’s final speed?

    ??? success "Solution"
        By the work-energy theorem, $W=\Delta K$:

        $$Fd=\frac12 mv^2.$$

        So $v=\sqrt{\frac{2Fd}{m}}=\sqrt{\frac{2(48.0)(7.50)}{18.0}}=6.32\ \text{m/s}$.


        <br>**Answer:** $6.32\ \text{m/s}$.

1. ★★☆ <br> A 10.0-kg crate is pulled up a 6.00-m incline at 25.0° above the horizontal by a force of 95.0 N parallel to the incline. The coefficient of kinetic friction is 0.18. The crate starts from rest. What is its speed at the top?

    ??? success "Solution"
        Net work on the crate is

        $$W_{\text{net}} = Fd - mgd\sin\theta - \mu_k mgd\cos\theta.$$

        Plugging in:

        $$W_{\text{net}} = 225.6\ \text{J}.$$

        Then $\frac12 mv^2 = W_{\text{net}}$, so

        $$v=\sqrt{\frac{2W_{\text{net}}}{m}}=\sqrt{\frac{2(225.6)}{10.0}}=6.72\ \text{m/s}.$$


        <br>**Answer:** $6.72\ \text{m/s}$.

&nbsp;

### [1.2] Potential Energy and Springs

1. ★★☆ <br> A 2.50-kg block is pressed against a horizontal spring with spring constant 320 N/m, compressing the spring by 0.180 m. The surface is frictionless. What is the maximum speed of the block after it is released?

    ??? success "Solution"
        Spring energy becomes kinetic energy:

        $$\frac12 kx^2 = \frac12 mv^2.$$

        So $v = x\sqrt{\frac{k}{m}} = 0.180\sqrt{\frac{320}{2.50}} = 2.04\ \text{m/s}$.


        <br>**Answer:** $2.04\ \text{m/s}$.

1. ★★☆ <br> A 5.0-kg block is released from rest at a height of 2.40 m above a horizontal surface. The curved ramp is frictionless, but the horizontal surface has coefficient of kinetic friction 0.30. How far does the block slide along the horizontal surface before coming to rest?

    ??? success "Solution"
        Gravitational potential energy is dissipated by friction:

        $$mgh = \mu_k mg\,d.$$

        The mass cancels, so

        $$d=\frac{h}{\mu_k}=\frac{2.40}{0.30}=8.0\ \text{m}.$$


        <br>**Answer:** $8.0\ \text{m}$.

1. ★★★ <br> A 4.00-kg block starts from rest and slides 5.00 m down a 30.0° incline. The coefficient of kinetic friction between the block and the incline is 0.10. At the bottom of the incline there is a spring with spring constant 900 N/m aligned along the incline. How much does the spring compress before the block momentarily stops?

    ??? success "Solution"
        From start to maximum compression, the block moves a total distance $(5.00+x)$ along the incline. Energy gives

        $$mg(\sin\theta-\mu_k\cos\theta)(5.00+x)=\frac12 kx^2.$$

        With $\theta=30.0^\circ$:

        $$(4.00)(9.8)(\sin30.0^\circ-0.10\cos30.0^\circ)(5.00+x)=450x^2.$$

        Solving,

        $$x \approx 0.443\ \text{m}.$$


        <br>**Answer:** $0.443\ \text{m}$.

&nbsp;

### [1.3] Mixed Energy Problems

1. ★★★ <br> A 65.0-kg snowboarder starts with a speed of 4.0 m/s at the top of a hill that is 18.0 m above the bottom. During the descent, friction dissipates 6.0 × 10^3 J of mechanical energy. What is the snowboarder’s speed at the bottom?

    ??? success "Solution"
        Use

        $$\frac12 mv_f^2 = \frac12 mv_i^2 + mgh - E_{\text{fric}}.$$

        So

        $$\frac12 (65.0)v_f^2 = \frac12(65.0)(4.0)^2 + (65.0)(9.8)(18.0) - 6000.$$

        This gives $v_f = 13.6\ \text{m/s}$.


        <br>**Answer:** $13.6\ \text{m/s}$.

1. ★★★ <br> A 1.20-kg cart is released from rest at the top of a frictionless track 1.50 m above the bottom. It then crosses a 0.80-m rough patch with coefficient of kinetic friction 0.25 before compressing a horizontal spring with spring constant 250 N/m. What is the maximum compression of the spring?

    ??? success "Solution"
        Initial gravitational potential becomes spring energy minus the work done by friction:

        $$mgh - \mu_k mgL = \frac12 kx^2.$$

        So

        $$(1.20)(9.8)(1.50) - (0.25)(1.20)(9.8)(0.80) = \frac12(250)x^2.$$

        This gives

        $$x = 0.350\ \text{m}.$$


        <br>**Answer:** $0.350\ \text{m}$.

&nbsp;

&nbsp;

---

## [2] Momentum, Impulse, and Collisions

&nbsp;

### [2.1] Momentum and Impulse

1. ★☆☆ <br> A 0.145-kg baseball is moving 18.0 m/s east when it is struck by a bat and leaves moving 32.0 m/s west. What is the ball’s change in momentum? Give magnitude and direction.

    ??? success "Solution"
        Take east as positive. Then

        $$\Delta p = m(v_f-v_i)=0.145(-32.0-18.0)=-7.25\ \text{kg·m/s}.$$

        The negative sign means west.


        <br>**Answer:** $7.25\ \text{kg·m/s}$ west.

1. ★☆☆ <br> A 2.0-kg hockey puck moving 6.0 m/s on frictionless ice is brought to rest in 0.20 s by a constant force. What are the impulse delivered to the puck and the magnitude of the average force?

    ??? success "Solution"
        Impulse is the change in momentum:

        $$J=\Delta p=m(v_f-v_i)=2.0(0-6.0)=-12.0\ \text{N·s}.$$

        So the impulse has magnitude $12.0\ \text{N·s}$ opposite the initial motion.

        The average force magnitude is

        $$F_{\text{avg}}=\frac{|J|}{\Delta t}=\frac{12.0}{0.20}=60.0\ \text{N}.$$


        <br>**Answer:** impulse $=12.0\ \text{N·s}$ opposite the motion; average force magnitude $=60.0\ \text{N}$.

&nbsp;

### [2.2] One-Dimensional Collisions

1. ★★☆ <br> A 1.20-kg cart moving 3.5 m/s to the right collides and sticks to a 0.80-kg cart initially at rest. What is their common speed immediately after the collision? How much kinetic energy is lost?

    ??? success "Solution"
        Momentum conservation gives

        $(1.20)(3.5) + (0.80)(0) = (1.20+0.80)v_f$,

        so

        $v_f = \frac{4.2}{2.0}=2.10\ \text{m/s}$ to the right.

        Initial kinetic energy:

        $$K_i=\frac12(1.20)(3.5)^2=7.35\ \text{J}.$$

        Final kinetic energy:

        $$K_f=\frac12(2.00)(2.10)^2=4.41\ \text{J}.$$

        Lost kinetic energy:

        $$\Delta K = K_i-K_f = 2.94\ \text{J}.$$


        <br>**Answer:** $2.10\ \text{m/s}$ to the right; $2.94\ \text{J}$ lost.

1. ★★☆ <br> A 0.020-kg bullet embeds in a 4.0-kg wooden block resting on a frictionless table. Immediately after the collision, the block and bullet move together at 1.5 m/s. What was the bullet’s speed just before impact?

    ??? success "Solution"
        This is a perfectly inelastic collision, so

        $$m_b v_b = (m_b+M)v_f.$$

        Therefore

        $$v_b = \frac{(0.020+4.0)(1.5)}{0.020}=301.5\ \text{m/s}.$$


        <br>**Answer:** $3.02\times 10^2\ \text{m/s}$.

&nbsp;

### [2.3] Two-Dimensional Collisions and Explosions

1. ★★☆ <br> A 70.0-kg runner moving east at 6.0 m/s is tackled by an 80.0-kg runner moving north at 5.0 m/s. They stick together. What are the magnitude and direction of their velocity immediately after the collision?

    ??? success "Solution"
        Conserve momentum in components.

        $$p_x=(70.0)(6.0)=420$ and $p_y=(80.0)(5.0)=400.$$

        Total mass is $150.0\ \text{kg}$, so

        $$v_x=\frac{420}{150}=2.80\ \text{m/s}, \qquad v_y=\frac{400}{150}=2.67\ \text{m/s}.$$

        Magnitude:

        $$v=\sqrt{v_x^2+v_y^2}=3.87\ \text{m/s}.$$

        Direction:

        $\theta=\tan^{-1}\!\left(\frac{v_y}{v_x}\right)=43.6^\circ$ north of east.


        <br>**Answer:** $3.87\ \text{m/s}$ at $43.6^\circ$ north of east.

1. ★★★ <br> Identical billiard balls are used on a frictionless table. A cue ball moves east at 2.4 m/s and strikes a stationary target ball. After the collision, the target ball moves at 1.6 m/s at 40.0° south of east. What is the velocity of the cue ball immediately after the collision?

    ??? success "Solution"
        Since the masses are identical, conserve momentum using velocities directly.

        Initial velocity of cue ball: $(2.4,\,0)$.

        Target ball after collision:

        $v_{tx}=1.6\cos40.0^\circ=1.226\ \text{m/s}$,

        $$v_{ty}=-1.6\sin40.0^\circ=-1.028\ \text{m/s}.$$

        Therefore the cue ball velocity is

        $v_{cx}=2.4-1.226=1.174\ \text{m/s}$,

        $$v_{cy}=0-(-1.028)=1.028\ \text{m/s}.$$

        Magnitude:

        $$v_c=\sqrt{(1.174)^2+(1.028)^2}=1.56\ \text{m/s}.$$

        Direction:

        $\theta=\tan^{-1}\!\left(\frac{1.028}{1.174}\right)=41.2^\circ$ north of east.


        <br>**Answer:** $1.56\ \text{m/s}$ at $41.2^\circ$ north of east.

1. ★★★ <br> A 4.0-kg cart moving east at 5.0 m/s explodes into two pieces. One 1.5-kg piece moves west at 2.0 m/s immediately after the explosion. What are the magnitude and direction of the velocity of the other piece?

    ??? success "Solution"
        Take east as positive. Initial momentum:

        $$p_i=(4.0)(5.0)=20.0\ \text{kg·m/s}.$$

        The 1.5-kg piece has momentum

        $$p_1=(1.5)(-2.0)=-3.0\ \text{kg·m/s}.$$

        So the other piece must have

        $$p_2=20.0-(-3.0)=23.0\ \text{kg·m/s}.$$

        Its mass is $4.0-1.5=2.5\ \text{kg}$, so

        $v_2=\frac{23.0}{2.5}=9.2\ \text{m/s}$ east.


        <br>**Answer:** $9.2\ \text{m/s}$ east.

1. ★★★ <br> A 6.0-kg firework shell is initially at rest and explodes into three pieces. Two 2.0-kg pieces fly off symmetrically, each moving at 8.0 m/s and 30.0° below the horizontal, one to the left and one to the right. What is the velocity of the third piece?

    ??? success "Solution"
        Initial momentum is zero. The horizontal momenta of the first two pieces cancel by symmetry.

        Each of those pieces has downward vertical momentum

        $p_y = (2.0)(8.0)\sin30.0^\circ = 8.0\ \text{kg·m/s}$ downward.

        Together they have $16.0\ \text{kg·m/s}$ downward, so the third piece must have $16.0\ \text{kg·m/s}$ upward.

        Its mass is $2.0\ \text{kg}$, so

        $v_3 = \frac{16.0}{2.0}=8.0\ \text{m/s}$ upward.


        <br>**Answer:** $8.0\ \text{m/s}$ straight upward.

&nbsp;

&nbsp;

---

## [3] Rotation

&nbsp;

### [3.1] Rotational Kinematics

1. ★☆☆ <br> A disk starts from rest and rotates with a constant angular acceleration of 2.5 rad/s^2 for 4.0 s. Find its final angular speed and angular displacement.

    ??? success "Solution"
        Use constant-angular-acceleration kinematics:

        $$\omega = \omega_0 + \alpha t = 0 + (2.5)(4.0)=10.0\ \text{rad/s}.$$

        $$\theta = \omega_0 t + \frac12 \alpha t^2 = \frac12(2.5)(4.0)^2 = 20.0\ \text{rad}.$$


        <br>**Answer:** $\omega_f=10.0\ \text{rad/s}$ and $\theta=20.0\ \text{rad}$.

1. ★☆☆ <br> A wheel initially rotating at 12.0 rad/s slows uniformly to 4.0 rad/s in 6.0 s. Find its angular acceleration and the number of revolutions it makes during that interval.

    ??? success "Solution"
        Angular acceleration:

        $$\alpha=\frac{\omega_f-\omega_i}{t}=\frac{4.0-12.0}{6.0}=-1.33\ \text{rad/s}^2.$$

        Angular displacement:

        $$\theta=\frac{\omega_i+\omega_f}{2}t=\frac{12.0+4.0}{2}(6.0)=48.0\ \text{rad}.$$

        Revolutions:

        $N=\frac{\theta}{2\pi}=\frac{48.0}{2\pi}=7.64$ revolutions.


        <br>**Answer:** $\alpha=-1.33\ \text{rad/s}^2$ and $7.64$ revolutions.

1. ★★☆ <br> A rotor speeds up uniformly from 3.0 rad/s to 15.0 rad/s while turning through 54 rad. What are the angular acceleration and the time required?

    ??? success "Solution"
        Use

        $$\omega_f^2=\omega_i^2+2\alpha\theta.$$

        So

        $$\alpha=\frac{15.0^2-3.0^2}{2(54)}=\frac{216}{108}=2.00\ \text{rad/s}^2.$$

        Then

        $$t=\frac{\omega_f-\omega_i}{\alpha}=\frac{15.0-3.0}{2.00}=6.0\ \text{s}.$$


        <br>**Answer:** $\alpha=2.00\ \text{rad/s}^2$ and $t=6.0\ \text{s}$.

1. ★★★ <br> A platform starts from rest, accelerates uniformly until it reaches 18.0 rad/s, and then continues rotating at that constant speed for 5.0 s. During the entire motion it turns through 126 rad. How long did the platform spend accelerating?

    ??? success "Solution"
        Let $t$ be the acceleration time.

        During acceleration from rest to $18.0\ \text{rad/s}$, the average angular speed is $9.0\ \text{rad/s}$, so

        $$\theta_1 = 9.0t.$$

        During the constant-speed part,

        $$\theta_2 = (18.0)(5.0)=90.0\ \text{rad}.$$

        Total angle:

        $$9.0t + 90.0 = 126.$$

        Thus

        $$t = 4.0\ \text{s}.$$


        <br>**Answer:** $4.0\ \text{s}$.

&nbsp;

### [3.2] Rotational Energy and Rolling

1. ★☆☆ <br> A 3.0-kg solid cylinder of radius 0.20 m rolls without slipping at 4.0 m/s. What is its total kinetic energy?

    ??? success "Solution"
        For a solid cylinder, $I=\frac12 mr^2$ and $\omega=v/r$.

        Total kinetic energy:

        $K = \frac12 mv^2 + \frac12 I\omega^2
        = \frac12 mv^2 + \frac12\left(\frac12 mr^2\right)\left(\frac{v}{r}\right)^2
        = \frac34 mv^2$.

        So

        $$K=\frac34(3.0)(4.0)^2=36.0\ \text{J}.$$


        <br>**Answer:** $36.0\ \text{J}$.

1. ★★☆ <br> A uniform solid sphere starts from rest and rolls without slipping down a 5.0-m ramp inclined at 25.0° above the horizontal. What is its speed at the bottom?

    ??? success "Solution"
        The vertical drop is

        $$h=(5.0)\sin25.0^\circ=2.11\ \text{m}.$$

        For a solid sphere, $I=\frac25 mr^2$, so

        $mgh=\frac12 mv^2+\frac12\left(\frac25 mr^2\right)\left(\frac{v}{r}\right)^2
        =\frac{7}{10}mv^2$.

        Hence

        $v=\sqrt{\frac{10}{7}gh}
        =\sqrt{\frac{10}{7}(9.8)(2.11)}
        =5.44\ \text{m/s}$.


        <br>**Answer:** $5.44\ \text{m/s}$.

1. ★★☆ <br> A hoop and a solid disk have the same mass and radius and are released from rest from the same height $h$. Which one reaches the bottom first? For each object, express the speed at the bottom in terms of $g$ and $h$.

    ??? success "Solution"
        Use

        $$mgh=\frac12 mv^2+\frac12 I\omega^2$ with $\omega=v/r.$$

        For the hoop, $I=mr^2$:

        $mgh=\frac12 mv^2+\frac12 mv^2=mv^2$,

        so

        $$v_{\text{hoop}}=\sqrt{gh}.$$

        For the solid disk, $I=\frac12 mr^2$:

        $mgh=\frac12 mv^2+\frac14 mv^2=\frac34 mv^2$,

        so

        $$v_{\text{disk}}=\sqrt{\frac{4gh}{3}}.$$

        Since $\sqrt{\frac{4gh}{3}} > \sqrt{gh}$, the disk is faster and reaches the bottom first.


        <br>**Answer:** the **solid disk** reaches first; $v_{\text{hoop}}=\sqrt{gh}$ and $v_{\text{disk}}=\sqrt{\frac{4gh}{3}}$.

1. ★★★ <br> A 3.0-kg solid sphere is rolling without slipping at 5.0 m/s on a level floor and then starts up a hill. Neglect losses. What maximum vertical height does it reach before coming momentarily to rest?

    ??? success "Solution"
        Initial total kinetic energy becomes gravitational potential energy:

        $$mgh = \frac12 mv^2 + \frac12 I\omega^2.$$

        For a solid sphere, $I=\frac25 mr^2$ and $\omega=v/r$, so

        $mgh = \frac12 mv^2 + \frac12\left(\frac25 mr^2\right)\left(\frac{v}{r}\right)^2
        = \left(\frac12+\frac15\right)mv^2
        = \frac{7}{10}mv^2$.

        Therefore

        $$h=\frac{7v^2}{10g}=\frac{7(5.0)^2}{10(9.8)}=1.79\ \text{m}.$$


        <br>**Answer:** $1.79\ \text{m}$.

&nbsp;

### [3.3] Angular Momentum

1. ★☆☆ <br> A student on a frictionless swivel stool has an initial moment of inertia of 2.8 kg·m^2 and is rotating at 1.6 rad/s. After pulling two dumbbells inward, the student’s moment of inertia decreases to 1.9 kg·m^2. What is the new angular speed?

    ??? success "Solution"
        Angular momentum is conserved:

        $$I_i\omega_i = I_f\omega_f.$$

        So

        $$\omega_f=\frac{I_i\omega_i}{I_f}=\frac{(2.8)(1.6)}{1.9}=2.36\ \text{rad/s}.$$


        <br>**Answer:** $2.36\ \text{rad/s}$.

1. ★★☆ <br> For the situation in the previous problem, by what factor does the student’s rotational kinetic energy change?

    ??? success "Solution"
        Since angular momentum $L$ is conserved, $K=\frac{L^2}{2I}$, so

        $$\frac{K_f}{K_i}=\frac{I_i}{I_f}=\frac{2.8}{1.9}=1.47.$$


        <br>**Answer:** the rotational kinetic energy increases by a factor of **1.47**.

1. ★★☆ <br> Disk A has moment of inertia 1.50 kg·m^2 and angular velocity +8.0 rad/s. Disk B has moment of inertia 0.80 kg·m^2 and angular velocity −5.0 rad/s. They are gently pressed together and rotate as one unit. What is their common final angular velocity?

    ??? success "Solution"
        Conserve angular momentum:

        $$I_A\omega_A + I_B\omega_B = (I_A+I_B)\omega_f.$$

        So

        $\omega_f = \frac{(1.50)(8.0)+(0.80)(-5.0)}{1.50+0.80}
        = \frac{12.0-4.0}{2.30}
        = 3.48\ \text{rad/s}$.

        Positive means the direction of Disk A’s original rotation.


        <br>**Answer:** $3.48\ \text{rad/s}$.

1. ★★★ <br> A 0.050-kg lump of clay moving tangentially at 12.0 m/s strikes and sticks to the rim of a turntable of radius 0.30 m. The turntable is initially at rest and has moment of inertia 0.20 kg·m^2. What is the angular speed of the turntable-clay system just after the collision?

    ??? success "Solution"
        Initial angular momentum of the clay about the axis is

        $$L_i = mvr = (0.050)(12.0)(0.30)=0.180\ \text{kg·m}^2/\text{s}.$$

        Final moment of inertia is

        $$I_f = 0.20 + mr^2 = 0.20 + (0.050)(0.30)^2 = 0.2045\ \text{kg·m}^2.$$

        Using $L_i=I_f\omega_f$:

        $$\omega_f=\frac{0.180}{0.2045}=0.880\ \text{rad/s}.$$


        <br>**Answer:** $0.880\ \text{rad/s}$.

&nbsp;

&nbsp;

---

## [4] Torque and Static Equilibrium

&nbsp;

### [4.1] Torque Basics

1. ★☆☆ <br> A mechanic applies a 40.0-N force perpendicular to the end of a 0.30-m wrench. What is the magnitude of the torque about the bolt?

    ??? success "Solution"
        Since the force is perpendicular,

        $$\tau = rF = (0.30)(40.0)=12.0\ \text{N·m}.$$


        <br>**Answer:** $12.0\ \text{N·m}$.

1. ★☆☆ <br> A meter stick is pivoted at its center. A 15.0-N upward force is applied 0.30 m to the right of the pivot, and a 10.0-N downward force is applied 0.20 m to the left of the pivot. What is the net torque on the stick? State magnitude and direction.

    ??? success "Solution"
        Taking counterclockwise as positive:

        Right-side upward force: $\tau_1=(0.30)(15.0)=4.50\ \text{N·m}$ CCW.

        Left-side downward force also produces CCW torque:

        $\tau_2=(0.20)(10.0)=2.00\ \text{N·m}$ CCW.

        So

        $\tau_{\text{net}}=4.50+2.00=6.50\ \text{N·m}$ CCW.


        <br>**Answer:** $6.50\ \text{N·m}$ counterclockwise.

&nbsp;

### [4.2] Static Equilibrium: Beams and Cables

1. ★★☆ <br> A uniform 6.0-m beam of mass 40.0 kg is hinged to a wall at its left end and held horizontal by a vertical cable attached at the right end. A 25.0-kg sign hangs 4.5 m from the hinge. What is the tension in the cable?

    ??? success "Solution"
        Take torques about the hinge.

        Counterclockwise torque from the cable:

        $$T(6.0).$$

        Clockwise torques from the beam and sign:

        $$(40.0)(9.8)(3.0) + (25.0)(9.8)(4.5).$$

        Equilibrium gives

        $$T(6.0)=(40.0)(9.8)(3.0)+(25.0)(9.8)(4.5).$$

        So

        $$T=379.75\ \text{N}\approx 3.80\times10^2\ \text{N}.$$


        <br>**Answer:** $380\ \text{N}$.

1. ★★☆ <br> A 5.0-m uniform beam of mass 120 kg is hinged to a wall and makes a 30.0° angle above the horizontal. It is supported by a cable attached to the far end of the beam and perpendicular to the beam. An 80.0-kg crate hangs from the far end. What is the tension in the cable?

    ??? success "Solution"
        Take torques about the hinge.

        Since the cable is perpendicular to the beam, its torque is simply $TL$.

        The weights act vertically, so their lever arms are the horizontal distances:

        beam: $\left(\frac{L}{2}\right)\cos30.0^\circ$,

        crate: $L\cos30.0^\circ$.

        Thus

        $$T(5.0) = (120)(9.8)\left(2.5\cos30.0^\circ\right) + (80)(9.8)\left(5.0\cos30.0^\circ\right).$$

        Solving gives

        $$T = 1.19\times10^3\ \text{N}.$$


        <br>**Answer:** $1.19\times10^3\ \text{N}$.

1. ★★★ <br> A 5.0-m ladder of mass 12.0 kg leans against a frictionless wall, making a 60.0° angle with the floor. The floor is rough enough to prevent slipping. A 70.0-kg person stands 3.0 m up the ladder as measured along the ladder from the bottom. Find the horizontal force exerted by the wall on the ladder and the friction force at the floor.

    ??? success "Solution"
        Let $F_w$ be the horizontal force from the wall. Take torques about the bottom of the ladder.

        The wall force acts at height $L\sin60.0^\circ$.

        The ladder’s weight acts at horizontal distance $\left(\frac{L}{2}\right)\cos60.0^\circ$.

        The person’s weight acts at horizontal distance $(3.0)\cos60.0^\circ$.

        So

        $$F_w(5.0\sin60.0^\circ) = (12.0)(9.8)\left(2.5\cos60.0^\circ\right) + (70.0)(9.8)\left(3.0\cos60.0^\circ\right).$$

        This gives

        $$F_w = 271.6\ \text{N}.$$

        Horizontal force balance then gives the floor friction force the same magnitude:

        $$f = 271.6\ \text{N}.$$


        <br>**Answer:** wall force $=272\ \text{N}$ horizontally; floor friction $=272\ \text{N}$ in the opposite horizontal direction.

1. ★★★ <br> A uniform 4.0-m beam of mass 50.0 kg is hinged to a wall at its left end and held horizontal by a cable attached to its right end. The cable makes a 35.0° angle above the beam. A 20.0-kg bucket hangs from the far end. Find the cable tension and the horizontal and vertical components of the hinge force.

    ??? success "Solution"
        Take torques about the hinge:

        $$T\sin35.0^\circ(4.0) = (50.0)(9.8)(2.0) + (20.0)(9.8)(4.0).$$

        So

        $T=\frac{(50.0)(9.8)(2.0)+(20.0)(9.8)(4.0)}{4.0\sin35.0^\circ}
        =768.9\ \text{N}$.

        Horizontal force balance:

        $$H_x - T\cos35.0^\circ = 0 \Rightarrow H_x = 629.8\ \text{N}.$$

        Vertical force balance:

        $H_y + T\sin35.0^\circ - (50.0+20.0)9.8 = 0$,

        so

        $H_y = 245\ \text{N}$ upward.


        <br>**Answer:** $T=769\ \text{N}$, $H_x=630\ \text{N}$ to the right, $H_y=245\ \text{N}$ upward.

&nbsp;

&nbsp;

---

## [5] Springs and Simple Harmonic Motion

&nbsp;

### [5.1] Spring Constants and Basic SHM Quantities

1. ★☆☆ <br> A 0.250-kg mass hangs from a vertical spring and stretches it 0.040 m from its natural length. What is the spring constant?

    ??? success "Solution"
        At equilibrium, $kx=mg$.

        So

        $$k=\frac{mg}{x}=\frac{(0.250)(9.8)}{0.040}=61.25\ \text{N/m}.$$


        <br>**Answer:** $61.3\ \text{N/m}$.

1. ★☆☆ <br> A 0.80-kg block attached to a spring with spring constant 200 N/m oscillates on a frictionless horizontal surface. Find its period and frequency.

    ??? success "Solution"
        For a mass-spring oscillator,

        $$T=2\pi\sqrt{\frac{m}{k}}=2\pi\sqrt{\frac{0.80}{200}}=0.397\ \text{s}.$$

        Then

        $$f=\frac{1}{T}=2.52\ \text{Hz}.$$


        <br>**Answer:** $T=0.397\ \text{s}$ and $f=2.52\ \text{Hz}$.

1. ★★☆ <br> The position of an oscillator is given by $x(t)=0.12\cos(4\pi t)$ with $x$ in meters and $t$ in seconds. Find the amplitude, period, and maximum speed.

    ??? success "Solution"
        Compare with $x(t)=A\cos(\omega t)$.

        So

        $$A=0.12\ \text{m}, \qquad \omega=4\pi\ \text{rad/s}.$$

        Then

        $T=\frac{2\pi}{\omega}=\frac{2\pi}{4\pi}=0.50\ \text{s}$,

        and

        $$v_{\max}=A\omega=(0.12)(4\pi)=1.51\ \text{m/s}.$$


        <br>**Answer:** amplitude $=0.12\ \text{m}$, period $=0.50\ \text{s}$, maximum speed $=1.51\ \text{m/s}$.

1. ★★☆ <br> A 0.40-kg block attached to a horizontal spring with spring constant 160 N/m oscillates with amplitude 0.10 m. What are its maximum speed and maximum acceleration?

    ??? success "Solution"
        Angular frequency:

        $$\omega=\sqrt{\frac{k}{m}}=\sqrt{\frac{160}{0.40}}=20\ \text{rad/s}.$$

        Then

        $v_{\max}=A\omega=(0.10)(20)=2.0\ \text{m/s}$,

        $$a_{\max}=A\omega^2=(0.10)(20)^2=40.0\ \text{m/s}^2.$$


        <br>**Answer:** $v_{\max}=2.0\ \text{m/s}$ and $a_{\max}=40.0\ \text{m/s}^2$.

&nbsp;

### [5.2] Energy in SHM

1. ★★☆ <br> A 0.50-kg block hangs from a vertical spring with spring constant 80 N/m. It is pulled 0.15 m below equilibrium and released from rest. What is its speed when it is 0.05 m above equilibrium?

    ??? success "Solution"
        Measure displacement from equilibrium. Then the amplitude is $A=0.15\ \text{m}$ and the position of interest has $|x|=0.05\ \text{m}$.

        Use SHM energy:

        $$\frac12 kA^2 = \frac12 kx^2 + \frac12 mv^2.$$

        So

        $v=\sqrt{\frac{k}{m}(A^2-x^2)}
        =\sqrt{\frac{80}{0.50}\left((0.15)^2-(0.05)^2\right)}
        =1.79\ \text{m/s}$.


        <br>**Answer:** $1.79\ \text{m/s}$.

1. ★★★ <br> A 0.300-kg mass is attached to a spring hanging from the ceiling and is released from rest when the spring is unstretched. The mass falls 0.180 m before momentarily coming to rest for the first time. What is the spring constant?

    ??? success "Solution"
        At the first turning point, the speed is zero again, so the lost gravitational potential equals the spring energy:

        $$mgy = \frac12 ky^2.$$

        Therefore

        $$k=\frac{2mg}{y}=\frac{2(0.300)(9.8)}{0.180}=32.7\ \text{N/m}.$$


        <br>**Answer:** $32.7\ \text{N/m}$.

1. ★★★ <br> A 1.20-kg block rests on a frictionless incline at 20.0° and is attached to a spring of constant 90.0 N/m oriented along the incline. The block is displaced 0.12 m from equilibrium and released from rest. What are the period of the motion and the maximum speed?

    ??? success "Solution"
        Motion about equilibrium is SHM with

        $$\omega=\sqrt{\frac{k}{m}}=\sqrt{\frac{90.0}{1.20}}=8.66\ \text{rad/s}.$$

        So

        $$T=2\pi\sqrt{\frac{m}{k}}=2\pi\sqrt{\frac{1.20}{90.0}}=0.726\ \text{s}.$$

        The incline angle only shifts the equilibrium point; it does not change the period.

        With amplitude $A=0.12\ \text{m}$,

        $$v_{\max}=A\omega=(0.12)(8.66)=1.04\ \text{m/s}.$$


        <br>**Answer:** $T=0.726\ \text{s}$ and $v_{\max}=1.04\ \text{m/s}$.

&nbsp;

&nbsp;

---

## [6] Mixed Exam-Style / Multi-Concept Review

1. ★★☆ <br> A 3.0-kg block on a horizontal surface is connected over a pulley to a hanging 2.0-kg block. The coefficient of kinetic friction between the 3.0-kg block and the table is 0.20. The pulley has mass 1.5 kg and moment of inertia $I=\frac{1}{2}MR^2$. The string does not slip. Find the acceleration of the system and the tension on each side of the pulley.

    ??? success "Solution"
        Let $m_1=3.0\ \text{kg}$ on the table and $m_2=2.0\ \text{kg}$ hanging. Friction on $m_1$ is

        $$f_k=\mu_k m_1 g=(0.20)(3.0)(9.8)=5.88\ \text{N}.$$

        Equations of motion:

        $T_1 - f_k = m_1 a$,

        $$m_2 g - T_2 = m_2 a.$$

        For the pulley,

        $(T_2-T_1)R = I\alpha = \frac12 MR^2\frac{a}{R}$,

        so

        $$T_2-T_1 = \frac12 Ma = 0.75a.$$

        Solving gives

        $a=2.39\ \text{m/s}^2$,

        $T_1 = m_1 a + f_k = 13.0\ \text{N}$,

        $$T_2 = m_2 g - m_2 a = 14.8\ \text{N}.$$


        <br>**Answer:** $a=2.39\ \text{m/s}^2$; tension on the 3.0-kg side $=13.0\ \text{N}$; tension on the 2.0-kg side $=14.8\ \text{N}$.

1. ★★★ <br> A 0.80-kg cart is launched from rest by a spring with spring constant 200 N/m compressed 0.20 m on a frictionless track. It collides and sticks to a 1.20-kg cart initially at rest. The combined carts then move up a frictionless incline. What maximum vertical height do they reach?

    ??? success "Solution"
        First, spring energy becomes kinetic energy of the 0.80-kg cart:

        $$\frac12 kx^2 = \frac12 m_1 v_1^2.$$

        So

        $$v_1 = x\sqrt{\frac{k}{m_1}} = 0.20\sqrt{\frac{200}{0.80}} = 3.16\ \text{m/s}.$$

        After the perfectly inelastic collision,

        $m_1 v_1 = (m_1+m_2)v_f$,

        so

        $$v_f=\frac{(0.80)(3.16)}{2.00}=1.265\ \text{m/s}.$$

        Then all of that kinetic energy becomes gravitational potential:

        $$\frac12 (m_1+m_2)v_f^2 = (m_1+m_2)gh.$$

        Thus

        $$h=\frac{v_f^2}{2g}=\frac{(1.265)^2}{2(9.8)}=0.0816\ \text{m}.$$


        <br>**Answer:** $8.16\times10^{-2}\ \text{m}$.

1. ★★★ <br> A uniform 3.0-m beam of mass 18.0 kg is hinged to a wall at one end and held horizontal by a cable attached at the free end. The cable suddenly snaps. What is the beam’s initial angular acceleration just after the cable breaks?

    ??? success "Solution"
        Just after the cable breaks, the only torque about the hinge is due to gravity acting at the center of mass:

        $$\tau = mg\left(\frac{L}{2}\right).$$

        For a uniform beam about one end,

        $$I=\frac13 mL^2.$$

        So

        $\alpha=\frac{\tau}{I}
        =\frac{mg(L/2)}{(1/3)mL^2}
        =\frac{3g}{2L}
        =\frac{3(9.8)}{2(3.0)}
        =4.90\ \text{rad/s}^2$.


        <br>**Answer:** $4.90\ \text{rad/s}^2$ clockwise.

1. ★★★ <br> A 0.50-kg block attached to a horizontal spring with spring constant 100 N/m oscillates with amplitude 0.12 m. As it passes through equilibrium, it collides and sticks to a 0.25-kg block initially at rest on the same frictionless surface. What is the amplitude of the motion immediately after the collision?

    ??? success "Solution"
        At equilibrium, the 0.50-kg block has maximum speed:

        $\omega=\sqrt{\frac{k}{m_1}}=\sqrt{\frac{100}{0.50}}=14.14\ \text{rad/s}$,

        $$v_{\max}=A\omega=(0.12)(14.14)=1.70\ \text{m/s}.$$

        During the collision, momentum is conserved:

        $m_1 v_{\max} = (m_1+m_2)v'$,

        so

        $$v'=\frac{(0.50)(1.70)}{0.75}=1.13\ \text{m/s}.$$

        Right after the collision the system is still at equilibrium ($x=0$), so the new amplitude is

        $A'=\frac{v'}{\omega'}$,

        where

        $$\omega'=\sqrt{\frac{k}{m_1+m_2}}=\sqrt{\frac{100}{0.75}}=11.55\ \text{rad/s}.$$

        Therefore

        $$A'=\frac{1.13}{11.55}=0.0980\ \text{m}.$$


        <br>**Answer:** $0.0980\ \text{m}$.
