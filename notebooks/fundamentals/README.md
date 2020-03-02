# Fundamentals

## Kinematic Equations based on Constant Acceleration
* v2 = v1 + at
* v2<sup>2</sup> = v1<sup>2</sup> + 2a(s2 - s1)
* s2 = s1 + v1t + (at<sup>2</sup>)/2

## Cross Product & Dot Product
* u . (v x w) = v . (w x u) = w . (u x v)
* u x (v x w) = (u . w)v - (u . v)w 

## Translation as a Matrix Operation
<p float="left">
  <img src="./pix/translation.png" width="700">
</p>

## Rotation as a Matrix Operation
<p float="left">
  <img src="./pix/rotation-2.png" width="450">
  <img src="./pix/rotation-1.png" width="250">
</p>

## Definiteness of a Matrix
<p float="left">
  <img src="./pix/definiteness.png" width="700">
</p>

## Scalar Field
<p float="left">
  <img src="./pix/scalar-field.png" width="700">
</p>

## Vector Field
<p float="left">
  <img src="./pix/vector-field.png" width="700">
</p>

## Angular Velocity - Rigid Body
<p float="left">
  <img src="./pix/circular-path.png" width="700">
</p>

* c = r Ω
* dc/dt = r dΩ/dt
* v = r w (direction of angular velocity w is determined by **right hand rule**) -> <mark>**v** = **w** x **r**</mark>
* dv/dt = r dw/dt
* a<sub>t</sub> = r α (a<sub>t</sub> is tangential acceleration) -> <mark>**a<sub>t</sub>** = **α** x **r**</mark>
* a<sub>n</sub> = v<sup>2</sup>/r = r w<sup>2</sup> (a<sub>n</sub> is centripetal acceleration) -> <mark>**a<sub>n</sub>** = **w** x (**w** x **r**)</mark>

<p float="left">
  <img src="./pix/linear-angular-velocity.png" width="700">
</p>

<p float="left">
  <img src="./pix/tangential-centripetal-acceleration.png" width="700">
</p>

* **v<sub>R</sub>** = **v<sub>cg</sub>** + **v<sub>t</sub>** -> **v<sub>R</sub>** = **v<sub>cg</sub>** + (**w** x **r**)

<p float="left">
  <img src="./pix/relative-velocity.png" width="700">
</p>

* **a<sub>R</sub>** = **a<sub>cg</sub>** + **a<sub>n</sub>** + **a<sub>t</sub>** -> **a<sub>R</sub>** = **a<sub>cg</sub>** + (**w** x (**w** x **r**)) + (**α** x **r**)

<p float="left">
  <img src="./pix/relative-acceleration.png" width="700">
</p>

## Quaternions
<p float="left">
  <img src="./pix/quaternions.png" width="700">
</p>

## Quaternions to describe Rotation
<p float="left">
  <img src="./pix/quaternion-rotation.png" width="700">
</p>

## Analogs
<p float="left">
  <img src="./pix/analogs.png" width="700">
</p>

## Moment of Inertia = Rotational Inertia
<p float="left">
  <img src="./pix/angular-momentum.png" width="700">
</p>

<p float="left">
  <img src="./pix/mass.png" width="700">
</p>

<p float="left">
  <img src="./pix/moment-of-inertia.png" width="700">
</p>

## Parallel Axis Theorem
<p float="left">
  <img src="./pix/transfer-of-axes.png" width="700">
</p>

<p float="left">
  <img src="./pix/parallel-axis-theorem.png" width="700">
</p>

## Torque
<p float="left">
  <img src="./pix/torque.png" width="700">
</p>

## Forces on Free Rigid Bodies
<p float="left">
  <img src="./pix/forces-on-free-rigid-body.png" width="700">
</p>

## Work done by Forces on Rigid Bodies
<p float="left">
  <img src="./pix/work.png" width="700">
</p>

## References
* https://en.wikipedia.org/wiki/Trigonometric_functions
* https://en.wikipedia.org/wiki/Right-hand_rule
* https://en.wikipedia.org/wiki/Cross_product
* https://en.wikipedia.org/wiki/Partial_derivative
* https://en.wikipedia.org/wiki/Total_derivative
* https://en.wikipedia.org/wiki/Scalar_field
* https://en.wikipedia.org/wiki/Vector_field
* https://en.wikipedia.org/wiki/Mechanical_energy
* http://www.chrishecker.com/Rigid_Body_Dynamics
