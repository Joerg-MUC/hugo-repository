---
title: "Creality Ender 5 pro"
date: 2022-01-06T12:06:47+01:00
draft: true

type: printer
---

## Beschreibung

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Umbauten

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Einstellungen

### aktuelle steps

### UBL Einrichten
Temperatur setzen auf 200° / 60°
M109 S190
M140 S60

G28
G29 P1
G29 P3 T
G29 P3 T
G29 P3 T

G29 S0
G29 F 10.0
G29 A
M500


### aktuelle steps

+ Extruder:  137.78 (steps/mm)
+ z-Achse:   800.00 (steps/mm)
+ x-Achse:   080.00 (steps/mm)
+ y-Achste:  080.00 (steps/mm)



#### Status M503
Send: M503
Recv: echo:  G21    ; Units in mm (mm)
Recv: echo:  M149 C ; Units in Celsius
Recv: 
Recv: echo:; Filament settings: Disabled
Recv: echo:  M200 S0 D1.75
Recv: echo:; Steps per unit:
Recv: echo: M92 X80.00 Y80.00 Z800.00 E137.78
Recv: echo:; Maximum feedrates (units/s):
Recv: echo:  M203 X500.00 Y500.00 Z5.00 E25.00
Recv: echo:; Maximum Acceleration (units/s2):
Recv: echo:  M201 X500.00 Y500.00 Z100.00 E5000.00
Recv: echo:; Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P500.00 R500.00 T500.00
Recv: echo:; Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> J<junc_dev>
Recv: echo:  M205 B20000.00 S0.00 T0.00 J0.08
Recv: echo:; Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:; Unified Bed Leveling:
Recv: echo:  M420 S1 Z10.00
Recv: 
Recv: Unified Bed Leveling System v1.01 active
Recv: 
Recv: echo:; Active Mesh Slot: 0
Recv: echo:; EEPROM can hold 1 meshes.
Recv: 
Recv: echo:; Material heatup parameters:
Recv: echo:  M145 S0 H185 B45 F255
Recv: echo:  M145 S1 H240 B70 F255
Recv: echo:; PID settings:
Recv: echo:  M301 P22.21 I1.64 D75.20
Recv: echo:  M304 P257.88 I50.26 D882.04
Recv: echo:; Z-Probe Offset (mm):
Recv: echo:  M851 X-40.00 Y-12.00 Z-1.75
Recv: ok