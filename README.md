## UTSM-PROTO-TELEMETRY-V2 BRANCH

Please refer back to main branch for important documentation.  This is just for fucking around, implementing new things, and testing data-preprocessing software without affecting the main branch.

**Things to Work On:**
- Implement wind, acceleration, driver weight resistance
- ~~Clean the data → remove spikes, fill gaps~~
- ~~Kalman filter → use GPS + IMU + wheel speed into one clean position/velocity/acceleration estimate~~
- ~~Re-index everything from time-domain → distance-domain (so lap 1 and lap 2 are comparable even if they took different amounts of time)~~
- ~~Calculate instantaneous and cumulative energy from power~~
- Complete accel_throttle sim

Output: A clean table where each row is a track position, with columns like: distance, speed, acceleration, slope, energy used, temperature, forces, etc.
