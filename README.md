Localisation in 2D plane:
This program finds out the location of a robot kept in known space using probabilistic approach. If a robot is randomly placed in plane with green and red tiles, this program will calculate the location by using the sensor data and direction of motion data. This algothim is known as histogram filtering.

Kalman Filters in 2D plane:
This program estimates the velocity of the robot using the data of its position collected in regular time intervals. The algorithm used in this program in called as Kalman Filtering.

Particle Filters in 2D plane:
This code first randomly spreads 1000 particles in a 2D plane. Next, it finds out how similar the position of the randomly spread particle is to the actual position of the particle. Based on the similarity, it assigns a probability to that particle. Finally, it removes the particles with a lower probability from the set of particles. This algorithm is called as Particle filtering.
