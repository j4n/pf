---
layout: default
title:  "tacTiles"
excerpt: "Low-Cost, Room-Scale Tactile Sensing"
featured-image: img/2010-tacTiles/tacTiles-module_top-crop.jpg
---

<div class="12u$"><span class="image fit"><img src="img/2010-tacTiles/tacTiles-module_top-crop.jpg" alt="tacTiles second generation" /></span></div>

My Master's thesis in computer science at the Ambient Intelligence Group, Bielefeld University, was the development of a modular, low-cost tactile sensing system to detect user's presence and activity in a smart environment through pressure-sensing floor tiles. With a spatial resolution of 5 cm, it could detect steps and their ground-force characteristics. The goals was to substitute or complement visual tracking, often problematic due to visual occlusion and due to privacy implications. The system outputs its reading through a USB-Video-Stream (UVC, like a webcam), allowing analysis through with a computer vision toolchain. The modules are based on a custom AVR 8-Bit microcontroller board, read out by an AVR32 master controller (based on [Carsten Schürmann's myrmex project](https://pub.uni-bielefeld.de/record/2711704)). The sensor grid is based on conductive paper, laser-cut to form a force sensing resistor matrix, making it very cheap to reproduce materials-wise.

Published as Diplomarbeit, and at ACE'10: Anlauff, J., Großhauser, T., & Hermann, T. (2010, October). Tactiles: a low-cost modular tactile sensing system for floor interactions. In Proceedings of the 6th Nordic Conference on Human-Computer Interaction: Extending Boundaries (pp. 591-594).

<h2>Idea and Principle</h2>
<div class="4u"><span class="image fit"><img src="paperFSR.png" alt="FSR Principle (all layers from paper)" /></span></div>
<div class="4u"><span class="image fit"><img src="amilab.png" alt="Smart environment with example module placements" /></span></div>
<div class="4u$"><span class="image fit"><img src="feet_dark.png" alt="Smart environment with example module placements" /></span></div>

<h2>Paper-FSR Construction</h2>
<div class="3u"><span class="image fit"><img src="tacTiles_paper.jpg" alt="Conductive Art Paper" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles_squares.jpg" alt="Cut to squares" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles_line.jpg" alt="Layed out in Lines" /></span></div>
<div class="3u$"><span class="image fit"><img src="tacTiles_layers.jpg" alt="and layers." /></span></div>

<h2>First two 8x8 Prototypes</h2>
<div class="3u"><span class="image fit"><img src="tacTiles_v1_top.jpg" alt="V1 top" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles_v1_bot.jpg" alt="V1 bot" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles_v1_standing.jpg" alt="User standing on two V1" /></span></div>
<div class="3u$"><span class="image fit"><img src="tacTiles_v1_eval.jpg" alt="Evaluation force respose and durability with linear table and straing gauge." /></span></div>

<h2>Second, fully modular Prototypes</h2>
<div class="3u"><span class="image fit"><img src="tacTiles-module_top-crop.jpg" alt="Top" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles_v2_top_detail.jpg" alt="Bottom" /></span></div>
<div class="3u"><span class="image fit"><img src="tacTiles-module_bot-crop.jpg" alt="Top Detail" /></span></div>
<div class="3u$"><span class="image fit"><img src="tacTiles_v2_bot_detail.jpg" alt="Bottom Detail" /></span></div>
