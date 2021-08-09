---
layout: default
title:  "Vibrotactile Insoles"
excerpt: "Vibrotactile Insoles (Ph.D. Thesis)"
featured-image: img/2015-Shoes/cover.jpg
---

<h1>Vibrotactile Insoles</h1>
<span class="image left"><a class="gallery" href="img/2015-Shoes/trog_v2_front-small.jpg"><img src="img/2015-Shoes/trog_v2_front-small.jpg" alt="tacTiles second generation" /></a></span>

With the goal to eventually support tactile feedback on balance and locomotion tasks, such as dancing, I developed two generations of instrumented insoles. 
In contrast to previous systems, were located below the points of highest contact with the ground, heel, big toe, and 1st/5th metatarsal head. 

Skills: PCB Design + Manufacturing, Embedded Development (Arduino), Mobile Development (Evothings/Cordova), Study Design and Execution, Data Analysis (R), Scientific Writing

<br/>

<h2>First Prototype</h2>
<div class="box alt">
	<div class="row uniform">
		<div class="5u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/trog-small.jpg"><img src="img/2015-Shoes/trog-small.jpg" alt="" /></a></span></div>
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/haptic_croc.jpg"><img src="img/2015-Shoes/haptic_croc.jpg" alt="" /></a></span></div>
		<div class="5u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/pilot_compact.png"><img src="img/2015-Shoes/pilot_compact.png" alt="" /></a></span></div>
	</div>
</div>


I evaluated the ability of users to distinguish between 14 tactons, spatio-temporal activation sequences of three tactors, while standing, with promising results highlighting the importance of actuator coupling.

<h2>Developing a suitable actuator integration</h2>

We evaluated a number of materials and integrations to ensure good coupling of the actuators to the feet, while decoupling them from another. 

<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/silicon_samples.jpg"><img src="img/2015-Shoes/silicon_samples.jpg" alt="" /></a></span></div>
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/vibtest.jpg"><img src="img/2015-Shoes/vibtest.jpg" alt="" /></a></span></div>
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/troggendock-side.jpg"><img src="img/2015-Shoes/troggendock-side.jpg" alt="" /></a></span></div>
		<div class="3u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/troggendock-module-pink2.jpg"><img src="img/2015-Shoes/troggendock-module-pink2.jpg" alt="" /></a></span></div>
	</div>
</div>

<h2>Second Prototype</h2>
The result was a robust insert. We also designed a custom PCB for a more robust and capable on-shoe electronics, and sensors: force-sensing resistors under the actuators to measure their loading, and a time-of-flight proximity sensor to measure step height.

<div class="box alt">
	<div class="row uniform">
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/tn-200.jpg"><img src="img/2015-Shoes/tn-200.jpg" alt="" /></a></span></div>
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/trog_v2_front-small.jpg"><img src="img/2015-Shoes/trog_v2_front-small.jpg" alt="" /></a></span></div>
		<div class="3u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/trog_v2-back.jpg"><img src="img/2015-Shoes/trog_v2-back.jpg" alt="" /></a></span></div>
		<div class="3u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/DSCF1462-shoetronics-populated-crop-small.jpg"><img src="img/2015-Shoes/DSCF1462-shoetronics-populated-crop-small.jpg" alt="" /></a></span></div>
	</div>
</div>

<h3>Study: Tacton Recognition Rates</h3>

In a study we evaluated this integration and we asked participants to distinguish between six tactons and found that detection was nearly perfect during stance and still remained high (~75%) during gait.

<div class="box alt">
	<div class="row uniform">
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/trog_v2_sole-letters.jpg"><img src="img/2015-Shoes/trog_v2_sole-letters.jpg" alt="" /></a></span></div>
		<div class="4u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/patterns_3x2-lines.png"><img src="img/2015-Shoes/patterns_3x2-lines.png" alt="" /></a></span></div>
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/recognition_total.png"><img src="img/2015-Shoes/recognition_total.png" alt="" /></a></span></div>
		<div class="4u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/recognition_patterns_total.png"><img src="img/2015-Shoes/recognition_patterns_total.png" alt="" /></a></span></div>
	</div>
</div>

I developed a mobile phone web app, connected to the shoe through Bluetooth Low Energy, for participants entered their responses on and as general interface to the shoe hardware.

<div class="box alt">
	<div class="row uniform">
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/app_connect.png"><img src="img/2015-Shoes/app_connect.png" alt="" /></a></span></div>
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/app_pressure.png"><img src="img/2015-Shoes/app_pressure.png" alt="" /></a></span></div>
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/app_choice.png"><img src="img/2015-Shoes/app_choice.png" alt="" /></a></span></div>
		<div class="2u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/app_notice.png"><img src="img/2015-Shoes/app_notice.png" alt="" /></a></span></div>
		<div class="2u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/app_hapticman.png"><img src="img/2015-Shoes/app_hapticman.png" alt="" /></a></span></div>
	</div>
</div>

Published as: <a href="https://ieeexplore.ieee.org/abstract/document/7989977/">Anlauff, J., Fung, J., & Cooperstock, J. R. (2017, June). VibeWalk: Foot-based tactons during walking and quiet stance. In 2017 IEEE World Haptics Conference (WHC) (pp. 647-652). IEEE.</a>

<h3>Study: Angular Menu Feedback</h3>
Foot-based interface control may present an appealing option when the hands are occupied, such as in the control of machines and instrumentation by doctors, for example. We compared two types of vibrotactile pulses against an auditory click for indicating steps in an angular menu of 3, 6, or 9 items (shown below) and found that while not as good as auditory, vibrotactile feedback allowed still enabled good user performance, with the directional feedback not being significantly better than simultaneous activation of the L/R tactor.

<div class="box alt">
	<div class="row uniform">
		<div class="4u"><span class="image fit"><a class="gallery" href="img/2015-Shoes/jan_menue_final_171023.png"><img src="img/2015-Shoes/jan_menue_final_171023.png" alt="" /></a></span></div>
		<div class="8u$"><span class="image fit"><a class="gallery" href="img/2015-Shoes/attempts.png"><img src="img/2015-Shoes/attempts.png" alt="" /></a></span></div>
	</div>
</div>

Published as: <a href="https://ieeexplore.ieee.org/abstract/document/8357172/">Anlauff, J., Kim, T., & Cooperstock, J. R. (2018, March). Feel-a-bump: Haptic feedback for foot-based angular menu selection. In 2018 IEEE Haptics Symposium (HAPTICS) (pp. 175-179). IEEE.</a>
