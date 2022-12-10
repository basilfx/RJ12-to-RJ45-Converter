# RJ12-to-RJ45 Converter
A converter for RJ12 to RJ45 for just a very specific use case.

## Introduction
My charge point connects to my Dutch Smart Meter (DSMR), to dynamically adjust
the maximum allowed current. It utillizes the P1 port, which uses a port with a
RJ12 connector. Between the charger and the DSMR, I installed a Cat 5e cable.

Crimping an RJ12 connector onto a Cat 5e cable will not make a durable
connection. I therefore designed this converter and 3D printed an enclosure for
it, just because I can.

I installed a normal RJ45 connector on both ends of the cable, installed two
converters and installed short 'telephone cables' (with RJ11 connectors) to
connect the charge point to the convert, and the DSMR to the converter.

## Contents
* The `3d/` folder contains a 3D-printable design for an enclosure.
* The `pcb/` folder contains the Kicad schema and board design.

## License
The work in this repository is covered by CC BY-NC-SA 4.0. See the `LICENSE.md`
file for more information.
