# Tilt-Based Virtual Navigation

This project explores moving control input away from the hands by using
body tilt as an interaction method.

## Hardware
- Arduino Nano
- ADXL345 Accelerometer

## Interaction Mapping
- Lean Forward / Back → Move Camera Forward
- Tilt Left / Right → Rotate Camera

## Concept
The accelerometer is worn on the body and sends tilt data to Unity via
serial communication, allowing navigation without keyboard or mouse.

## Output
A virtual space navigated using body movement only.
