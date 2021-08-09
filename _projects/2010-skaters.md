[[---]]
layout: default
title:  "Push N900: Solderin' Skaters / Tilt'n'Roll"
excerpt: "Solderin' Skaters: Tilt'n'Roll Augmented Skateboarding Game"
featured-image: img/2010-solderin_skaters/cover.jpg
---

<div class="box alt">
	<div class="row uniform">
		<div class="12$"><span class="image fit"><img src="img/2010-solderin_skaters/header.jpg" alt="header" /></span></div>
	</div>
</div>
<h1>PUSH N900 / Solderin' Skaters: Tilt'n'Roll Augmented Skateboarding Game</h1>
<span class="image left"><a href="img/2010-solderin_skaters/skateboard_and_n900.jpg"><img src="img/2010-solderin_skaters/skateboard_and_n900.jpg" alt="tacTiles second generation" /></a></span>

Created to raise awareness of the "hackability" of the Nokia N900 Linux smartphone, the PUSH challenge asked for teams to create novel uses within a good two months. I was part of the team "Solderin' Skaters", and our entry was an augmented skateboarding game, controlled by performing real tricks on a skateboard, equipped with motion sensors.
Our project aimed to contrast the video game skateboard controllers introduced at the time and to bring skaters back on the streets.
My part was the electronic hardware and the embedded programming of the highly integrated circuit board, called Diptera.
We integrated two Diptera boards, one in each truck, capturing the high acceleration, angular velocity of the board, and pressure distribution during tricks and relaying it to the N900 phone via Bluetooth. There, a machine learning classified tricks and gave users points, encouraging remarks, and an increasingly up-beat soundtrack, as well as the option to tweet highscores. 
With a team of 9 in total, we manages to go from idea to functional prototype in just under two months, exceeding expectations and demonstrating what open soft and hardware could enable, back in 2010.
The skateboard was exhibited in a the V&A DECODE showcase at the Victoria &amp; Albert museum in London.
We reimplemented the machine learning for the subsequent Nokia N9 campaign by Wieden and Kennedy, reaching impressive recognition rates and becoming part of a global campaign to advertise Linux phones by Nokia - unfortunately, not becoming a widespread reality.

A demo video can be found on <a href="https://youtu.be/SFTRoslKSOE">Youtube</a>, and we published a paper at ACE'10 on the sytem: <a href="http://www.techfak.uni-bielefeld.de/ags/ami/publications/media/AnlauffWeitnauerLehnhardtSchirmerZeheTonekaboni2010-AMF.pdf">Anlauff, J., Weitnauer, E., Lehnhardt, A., Schirmer, S., Zehe, S., & Tonekaboni, K. (2010, November). A method for outdoor skateboarding video games. In Proceedings of the 7th International Conference on Advances in Computer Entertainment Technology (pp. 40-44).</a>

Skills: Embedded programming (AVR-C), PCB design and assembly for second generation, photography.

<h2>Operating Principle</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="6u"><span class="image fit"><a href="img/2010-solderin_skaters/principle.jpg"><img src="img/2010-solderin_skaters/principle.jpg" alt="high level principle" /></a></span></div>
		<div class="6u$"><span class="image fit"><a href="img/2010-solderin_skaters/architecture.png"><img src="img/2010-solderin_skaters/architecture.png" alt="architecture" /></a></span></div>
	</div>
</div>

<h2>Diptera Development</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-proto.jpg"><img src="img/2010-solderin_skaters/diptera-proto.jpg" alt="diptera-proto" /></a></span></div>
		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-closeup.jpg"><img src="img/2010-solderin_skaters/diptera-closeup.jpg" alt="diptera-closeup.jpg" /></a></span></div>
		<div class="4u$"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-top.jpg"><img src="img/2010-solderin_skaters/diptera-top.jpg" alt="diptera-top" /></a></span></div>
		
		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-programming.jpg"><img src="img/2010-solderin_skaters/diptera-programming.jpg" alt="diptera-programming" /></a></span></div>
		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-n900.jpg"><img src="img/2010-solderin_skaters/diptera-n900.jpg" alt="diptera-n900" /></a></span></div>
		<div class="4u$"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-truck-straight.jpg"><img src="img/2010-solderin_skaters/diptera-truck-straight.jpg" alt="diptera-truck-straight" /></a></span></div>

		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/diptera-mounting.jpg"><img src="img/2010-solderin_skaters/diptera-mounting.jpg" alt="diptera-mounting" /></a></span></div>
		<div class="4u"><span class="image fit"><a href="img/2010-solderin_skaters/board-bench.jpg"><img src="img/2010-solderin_skaters/board-bench.jpg" alt="board-bench" /></a></span></div>
		<div class="4u$"><span class="image fit"><a href="img/2010-solderin_skaters/highscore_and_blurred_board.jpg"><img src="img/2010-solderin_skaters/highscore_and_blurred_board.jpg" alt="highscore_and_blurred_board" /></a></span></div>
	</div>
</div>

The diptera modules were mounted under the trucks in a CNC-milled foam insert that absorbed the worst impacts. 
Diptera was built around an ATMega328, a Bluegiga Bluetooth module, an ADXL345 and high-rate gyrometers, and was also sampling FSR strips under the grip tape. Before long, the extra boards were used by collegues at the Ambient Intelligence Group at Bielefeld University for Human-Computer Interaction research, as compact and extensible wireless sensor boards were hard to get back then.

<h2>Test Session</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a href="img/2010-solderin_skaters/n900-laptop.jpg"><img src="img/2010-solderin_skaters/n900-laptop.jpg" alt="N900 and Laptop"/></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2010-solderin_skaters/skate-flip.jpg"><img src="img/2010-solderin_skaters/skate-flip.jpg" alt="skate-flip" /></a></span></div>
		<div class="3u"><span class="image fit"><a href="img/2010-solderin_skaters/skate-jump.jpg"><img src="img/2010-solderin_skaters/skate-jump.jpg" alt="skate-jump" /></a></span></div>
		<div class="3u$"><span class="image fit"><a href="img/2010-solderin_skaters/skate-flip.jpg"><img src="img/2010-solderin_skaters/skate-flip.jpg" alt="skate-flip" /></a></span></div>
	</div>
</div>

Our team's test skater putting the system to the test.
