# CN Tower Shadow Simulator

An interactive 3D simulation of the shadow cast by the CN Tower based on time of day and time of year.

## Live URL

https://mskaura.github.io/classroom-tools/cn-tower-shadow/

## Features

- 3D scene built with Three.js
- Simplified CN Tower model (553 m) with observation deck and antenna spire
- Real-time shadow simulation based on solar position
- Controls: time-of-day slider, month + day selector
- Displays: sun elevation, azimuth, shadow length in metres
- Day animation (play through sunrise to sunset)
- Orbit camera: drag to rotate, scroll to zoom

## Solar Calculations

- Toronto coordinates: 43.64 N, 79.39 W
- Solar declination, hour angle, and elevation calculated from date/time
- Equation of time correction applied for accuracy
- Shadow length = 553 / tan(sun elevation), capped at 5000 m

## Created

March 2026
