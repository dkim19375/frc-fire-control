# Changelog

## v1.0.0

Initial release. Three standalone fire control classes for FRC 2026 REBUILT.

- **ShotCalculator** - Newton-method SOTM solver with drag compensation, warm start, second-order pose prediction, speed/distance-scaled heading tolerance, tilt suppression, and confidence scoring
- **ProjectileSimulator** - RK4 projectile sim with drag and Magnus lift, generates 91-point shooter LUTs
- **FuelPhysicsSim** - Full-field ball physics simulation (2026 REBUILT field geometry)
