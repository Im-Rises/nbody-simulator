# nbody-simulator

Work in progress do not use it !!!

## Todo

- [x] Move the position update in a different function to prevent the first particle to move before the calculation of
  the next particles which will cause a wrong calculation for the distance and the direction (so create two function,
  one to calculate the current applied force and one to update the position)
- [ ] Do a base form of donut/torus with particles oriented to go in the same direction according to the center (rotate
  position by 90°)
- [ ] Add a quadree to reduce the number of calculation (Barnes-Hut algorithm)
- [ ] Add a parameter to display the barnes-hut quadree or not

<https://www.youtube.com/watch?v=GjbKsOkN1Oc>
