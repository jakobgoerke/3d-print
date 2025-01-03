# 3D-Printing

Configs etc.

Initial printer calibration steps:

- 1. E-steps: https://teachingtechyt.github.io/calibration.html#esteps
- 2. Initial z-offset via PROBE_CALIBRATE
- 3. Manual bed leveling via SCREWS_TILT_CALCULATE https://www.klipper3d.org/Manual_Level.html
- 4. Print first layer while micro adjusting z-offset
- 5. Flow calibration: https://teachingtechyt.github.io/calibration.html#flow -> Make sure to also set initial layer flow!
- 6. Re-calibrate z-offset
- 7. BED_MESH_CALIBRATE
- 8. Temperature: https://teachingtechyt.github.io/calibration.html#temp
- 9. Retraction: https://www.printables.com/model/236366-klipper-stringing-test-with-firmware-retraction
  - make sure to add a default firmware retraction configuration to your klipper configuration to enable it
  - for cura: install "Printer Settings" by fieldOfView via marketplace
  - enable firmware retraction in print profile
- 10. Pressure advance: https://www.klipper3d.org/Pressure_Advance.html
- 11. Enjoy
