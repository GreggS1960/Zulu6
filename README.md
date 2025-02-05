# Zulu6

Zulu is a library of routines for creating ultra-realistic combat simulations using the Unity 3D game engine.

Features include, but are not limited to.

- Support for extra-terrestrial missions.
	- Orbital data for the worlds ensures that local sun appearance and location in sky appropriate for time of day and date.
	- Atmospheric gas mix controls speed of sound - affecting ballistics, blast wave travel and overall sound pitch.
	- Local surface gravity appropriate for planet - affecting travel and ballistics.
- Explosive effects vary by material.
- Fragments from blasts are simulated, no stochastic calculations. Objects will provide proper cover from shrapnel.
- Fatigue model uses physiology. Carbon dioxide and lactic acid levels build up and decay according to activity
  and determine player fatigue affects.
- Player damage based on physiology. Blood volume determines health status.
- Universal trauma system. Projectiles and blast waves relay force data to objects they encounter. Those objects process the data into the
  correct type of damage along with appropriate effects.
- Multiple rag-dolls are available for player models. The dolls are used for increasingly more severe damage effects.
