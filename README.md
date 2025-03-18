# Klipper Macros
Various macros used in Klipper.

Descriptions:

exercise_axis; Run an axis repeatedly. Modified from the [TEST_SPEED macro by Andrew Ellis][test_speed]. I use this to check belt alignment or after greasing a rail carriage.

part_cooling_override; Override the Part Cooling Fan calls. Cap the maximum speed with `MAX_FAN`, create an offset of all calls with `OFFSET_PERCENT`, or lock the fan at a set speed with `MANUAL_FAN`.



Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
[test_speed]: https://github.com/AndrewEllis93/Print-Tuning-Guide/blob/main/macros/TEST_SPEED.cfg
