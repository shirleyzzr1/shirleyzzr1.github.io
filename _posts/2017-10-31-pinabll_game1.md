---
layout: post
title:  "Pinball Game"
date:   2017-10-31
excerpt: "Python; Euler-Lagrange Equations; Impacts"
image: "/images//blog/PinBall/Pinball Game.gif"
---

This coordiate system of this pinball game is shown below:
<div style="text-align: center"><img src="/images/blog/PinBall/general_idea.png" /></div>
here is the transformation between different coordinates
The Pinball Game system consists of 2 bumpers, a pair of slippers and a rotating box. The box can be seen as a rigid body with 3 degrees of freedom(position x,y and angle β).Only the initial position and angle of the box is given, no external force. Each Slipper has length L and 1 degree of freedom(angle α), and an external force of 1000 N exerts on slippers to change direction constantly. No Extra constraints  for the system. The goal of the system is to generate the trajectory of the box after multiple impacts.
Initially, we set g = - 9.8\
[mbox,mslipper1,msplipper2] = [1,1,1]\
[lsquare,rcircle,lpedal1,lpedal2] = [2,2,7,7]\
[xsquare,ysquare] = [4,-4],[xcircle,ycircle] = [15,-6]

The lagrangian for box is:\
$$L_b = \frac{1}{2}V^T_bdiag(m_b,m_b,m_b,0,0,1)V_b-m_bgy_b$$

The lagrangian for the rotating pedals is:\
$$L_r = \frac{1}{2}V^T_rdiag(m_r,m_r,m_r,0,0,J)V_r-m_rgy_r$$

And this is the forced euler-lagrange equations when applying an external force
on the system.\
$$\frac{d}{dt}\frac{\partial L}{\partial \dot{q}}-\frac{\partial L}{\partial q}=F$$\
Next, we will analyze the impact of the system.\
1) 12 impacts for 3 walls. \
$$box_1 = [x-\sqrt{2}sin(\frac{\pi}{4}-b),y+\sqrt{2}cos(\frac{\pi}{4}-b)]\\phi_1 = box_1[y] - y_{wall}$$

2) 16 impacts for 4 edges in square bumper\
$$phi = box[y] - y_{square} \ \ if\ \ x_{s1,min} < box[x] < x_{s1,max}$$

3) 1 impact for circle bumper\
$$phi = (x - x_r)^2 + (y-y_r)^2 - (2+\sqrt(2))^2$$

4) 8 impacts for rotating pedals
the start and end point of rotating pedals are (x0,y0) ,(x2,y2), one vertex of the box is 
(x1,y1)\
$$phi = (y_1-y_0)(x_2-x_0)-(y_2-y_0)(x_1-x_0)\\$$