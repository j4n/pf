---
layout: default
title:  "tacTiles"
excerpt: "Low-Cost, Room-Scale Tactile Sensing"
featured-image: img/2009-tacTiles/tacTiles-module_top-crop.jpg
---

<h1>tacTiles - Low-Cost, Room-Scale Tactile Sensing</h1>
<span class="image left"><a href="img/2009-tacTiles/tacTiles-module_top-crop.jpg"><img src="img/2009-tacTiles/tacTiles-module_top-crop.jpg" alt="tacTiles second generation" /></a></span>

My Master's thesis in computer science at the Ambient Intelligence Group, Bielefeld University, was the development of a modular, low-cost tactile sensing system to detect user's presence and activity in a smart environment through pressure-sensing floor tiles. With a spatial resolution of 5 cm, it could detect steps and their ground-force characteristics. The goals was to substitute or complement visual tracking, often problematic due to visual occlusion and due to privacy implications. The system outputs its reading through a USB-Video-Stream (UVC, like a webcam), allowing analysis through with a computer vision toolchain. The modules are based on a custom AVR 8-Bit microcontroller board, read out by an AVR32 master controller (based on [Carsten Schürmann's myrmex project](https://pub.uni-bielefeld.de/record/2711704)). The sensor grid is based on conductive paper, laser-cut to form a force sensing resistor matrix, making it very cheap to reproduce materials-wise.

<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/paperFSR.png"><img src="img/2009-tacTiles/paperFSR.png" alt="FSR Principle (all layers from paper)" /></a></span></div>
		<div class="4u"><span class="image fit"><a href="img/2009-tacTiles/amilab.png"><img src="img/2009-tacTiles/amilab.png" alt="Smart environment with example module placements" /></a></span></div>
		<div class="5u$"><span class="image fit"><a href="img/2009-tacTiles/feet_dark.png"><img src="img/2009-tacTiles/feet_dark.png" alt="Smart environment with example module placements" /></a></span></div>
	</div>
</div>

Published as Diplomarbeit, and at NordiCHI'10: <a href="https://www.techfak.de/ags/ami/publications/media/AnlauffGrosshauserHermann2010-TAL.pdf">Anlauff, J., Großhauser, T., & Hermann, T. (2010, October). tacTiles: a low-cost modular tactile sensing system for floor interactions. In Proceedings of the 6th Nordic Conference on Human-Computer Interaction: Extending Boundaries (pp. 591-594).</a>

Skills: Embedded programming (AVR-C), Processing for Visualization. G-Code for Linear Table. Lasercutting, PCB design and, assembly for second generation.

<h2>Paper-FSR Construction</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_paper.jpg"><img src="img/2009-tacTiles/tacTiles_paper.jpg" alt="Conductive Art Paper" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_squares.jpg"><img src="img/2009-tacTiles/tacTiles_squares.jpg" alt="Cut to squares" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_line.jpg"><img src="img/2009-tacTiles/tacTiles_line.jpg" alt="Layed out in Lines" /></a></span></div>
		<div class="3u$"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_layers.jpg"><img src="img/2009-tacTiles/tacTiles_layers.jpg" alt="and layers." /></a></span></div>
	</div>
</div>

The operating principle of the sensor cells is based similar to that of a force sensing resistor, with all layers made from conductive, carbon art paper of two different resistances.

<h2>First two 8x8 Prototypes</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_v1_top.jpg"><img src="img/2009-tacTiles/tacTiles_v1_top.jpg" alt="V1 top" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_v1_bot.jpg"><img src="img/2009-tacTiles/tacTiles_v1_bot.jpg" alt="V1 bot" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_v1_standing.jpg"><img src="img/2009-tacTiles/tacTiles_v1_standing.jpg" alt="User standing on two V1" /></a></span></div>
		<div class="3u$"><div class="image fit"><a href="img/2009-tacTiles/tacTiles_v1_eval.jpg"><img src="img/2009-tacTiles/tacTiles_v1_eval.jpg" alt="Evaluation force response and durability with linear table and strain gauge." /></a></span></div>
	</div>
</div>

The first prototypes were completely hand-built and connected directly to a PC. We evaluated force response and durability with a linear table and a strain gauge. Mechanical adapters were CNC-milled.

<h2>Second, fully modular Prototypes</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles-module_top-crop.jpg"><img src="img/2009-tacTiles/tacTiles-module_top-crop.jpg" alt="Top" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_v2_top_detail.jpg"><img src="img/2009-tacTiles/tacTiles_v2_top_detail.jpg" alt="Bottom" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2009-tacTiles/tacTiles-module_bot-crop.jpg"><img src="img/2009-tacTiles/tacTiles-module_bot-crop.jpg" alt="Top Detail" /></a></span></div>
		<div class="3u$"><span class="image fit"><a href="img/2009-tacTiles/tacTiles_v2_bot_detail.jpg"><img src="img/2009-tacTiles/tacTiles_v2_bot_detail.jpg" alt="Bottom Detail" /></a></span></div>
	</div>
</div>

The goal of the second generation was a modular setup, that could be arranged freely and reproduced more easily. We laser-cut the paper and CNC-milled the support "puzzle" pieces, and designed and manufactured a PCB for the sensor readout for each module.
