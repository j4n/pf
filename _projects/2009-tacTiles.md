---
layout: default
title:  "tacTiles"
excerpt: "Low-Cost, Room-Scale Tactile Sensing"
featured-image: img/2010-tacTiles/tacTiles-module_top-crop.jpg
---

My Master's thesis in computer science at the Ambient Intelligence Group, Bielefeld University, was the development of a modular, low-cost tactile sensing system to detect user's presence and activity in a smart environment through pressure-sensing floor tiles. With a spatial resolution of 5 cm, it could detect steps and their ground-force characteristics. The goals was to substitute or complement visual tracking, often problematic due to visual occlusion and due to privacy implications. The system outputs its reading through a USB-Video-Stream (UVC, like a webcam), allowing analysis through with a computer vision toolchain. The modules are based on a custom AVR 8-Bit microcontroller board, read out by an AVR32 master controller (based on [Carsten Schürmann's myrmex project](https://pub.uni-bielefeld.de/record/2711704)). The sensor grid is based on conductive paper, laser-cut to form a force sensing resistor matrix, making it very cheap to reproduce materials-wise.

Published as Diplomarbeit, and at ACE'10: Anlauff, J., Großhauser, T., & Hermann, T. (2010, October). Tactiles: a low-cost modular tactile sensing system for floor interactions. In Proceedings of the 6th Nordic Conference on Human-Computer Interaction: Extending Boundaries (pp. 591-594).
