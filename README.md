<h3>This project is abandoned!</h3>

<p>
I've given up on the CC3000, it's just too buggy and problematic.
</p>


<p>TI themselves say this on the CC3000 page:</p>

<pre>
TI recommends CC3200 & CC3100 for all new and existing embedded Wi-Fi & Internet of Things applications.
</pre>

<p>And they've removed references to the CC3000 on their SimpleLink WiFi page at
<a href="http://www.ti.com/ww/en/simplelink_embedded_wi-fi/home.html">http://www.ti.com/ww/en/simplelink_embedded_wi-fi/home.html</a>
</p>

<p>
I'm going to leave these pages here so people searching the web for help don't find dead links,
but I recommend you abandon your quest to make this half-baked module work. Best of luck to you.
</p>

<hr/>
<hr/>
<hr/>



CC3000 Breakout
=============

<p>Version 1.4</p>

<p>Yet another breakout board for the TI CC3000 WiFi module</p>

<p>Based on a design & library by Matt Bigarani, http://www.centerblack.com</p>

<p>This design is licensed under the Creative Commons CC by NC SA (http://creativecommons.org/licenses/by-nc-sa/3.0/us/). OK to share & remix for any noncommercial purpose</p>

<p>The antenna used by Matt from the SparkFun-RF library was the wrong size. SparkFun had one that was close (ANTENNA-CHIP5) but wasn't exactly right so I modified the part in their library. The modified library is included in this project as SparkFun-RF-Modified.lbr</p>
 
<p>Changes:</p>
<ul>
<li>1.4 - Changed antenna trace from 20 mil to 50 mil & antenna trace gap from 12 mil to 10 mil based on calculations from http://chemandy.com/calculators/coplanar-waveguide-with-ground-calculator.htm</li>
<li>1.3 - First board design to be manufactured. Fixed antenna footprint from V1.2</li>
<li>1.2 - Fixed antenna gap per antenna datasheet</li>
<li>1.1 - Revised BOM to use the same parts as TI whenever possible</li>
<li>1.0 - Initial prototype</li>
</ul>