# achaea_sea_mapping
<i>"This is amazing. How sailing should be."</i> - <a href="http://forums.achaea.com/profile/Vadimuses">@Vadimuses</a><br><br><i>"Awesome. It's a really cool script, definitely something that will make sailing a lot less tedious."</i> - <a href="http://forums.achaea.com/profile/Xer">@Xer</a><br><br><i>"Oh my friggin' god ... this takes the headache out of sailing."</i> - <a href="http://forums.achaea.com/profile/Nizaris">@Nizaris</a><br><br>---------------------------------------<br><br><b><span style="font-size: x-large; font-size: x-large;">MAP-BUILDING</span></b><br><br>This script will build and append the sea map to an interactive Mudlet mapper window on-the-fly. All you need to do is sail. The map looks like this when you start (the red regions are water, where your ship can go):<b><br><br><img src="http://i2.minus.com/iNWoxLHyYOPTG.png" alt="image"><br></b><br>As you sail to new places, your map will grow:<br><br><img src="http://i2.minus.com/i5N8xxcQm8c8S.png" alt="image" width="737" height="488"><br><br>As was mentioned in this thread: forums.achaea.com/discussion/884/meropis-sea-map-via-mudlet-mapper, there are some challenges related to accurately tracking the movement of a ship. The map builder will try to match the new sea map to your existing mudlet map on each movement to account for silent drifting and to detect where you moved on a non-cardinal non-ordinal direction (NNE, for example).<br><br>For the utilitarians among us, there is an option to remove the printing of chops and land such that only the red (water) rooms appear. This speeds up processing.<br><br><span style="font-size: x-large; font-size: x-large;"><b>PATH-FINDING</b></span><br>The map that is built is fully interactive. You can double-click on any connected water room and your ship will sail there.<br><br><img src="http://i3.minus.com/ibyiuuyLxiWZz5.png" alt="image" width="745" height="515"><br><br>The path profile is calculated using the A* pathfinding algorithm and tries to avoid turning and going too close to chops. Advanced users who want to change the shape of their path can read below for details on how to customize pathfinding and ship turning.<br><br><span style="font-size: x-large; font-size: x-large;"><b>WHAT YOU NEED</b></span><br><ul><li>Mudlet 2.1</li><li>GMCP turned on</li><li>Download the script (see below)</li></ul><p><span style="font-size: x-large; font-size: x-large;"><b>BASIC USER INSTRUCTION<span style="font-size: x-large; font-size: x-large;">S</span></b></span></p><ul><li><span style="font-size: small; font-size: small;">Download the script.</span></li><li><span style="font-size: small; font-size: small;">Click on Package Manager, then click on Install. Select the entire .<span style="font-size: small; font-size: small;">zip file you downloaded.</span></span></li><li><span style="font-size: small; font-size: small;">Get on a ship.</span></li><li><span style="font-size: small; font-size: small;">Type "ymap on".</span></li><li><span style="font-size: small; font-size: small;">Start sailing. You can start auto-sailing when the map appears.</span></li></ul><p><span style="font-size: x-large; font-size: x-large;"><b>BASIC USER ALIASES</b></span></p><p><b>ymap &lt;on|off&gt;</b>: this either turns on the sea mapper or returns Mudlet mapper control back to your regular maps. The normal Mudlet mapper will be inaccessible while the sea mapper is on.<br><b>ystop</b>: this stops auto-sailing (you'll still need to "all stop").<br><b>clearmap</b>: this deletes your current sea map and allows you to start over.<br><b>yconfig shiptype &lt;cutter|strider&gt;</b>: this gives the system an estimate of what your ship turning speed is.<br><b>yconfig print &lt;on|off&gt;</b>: this allows you to choose whether or not to print the non-water rooms.</p><p><span style="font-size: x-large; font-size: x-large;"><b>DOWNLOAD: </b></span><a rel="nofollow" href="https://github.com/vadi2/achaea_sea_mapping/releases"><span style="font-size: x-large; font-size: x-large;"><b>https://github.com/vadi2/achaea_sea_mapping/releases</b></span></a></p><p><br></p><p>Shout out to <a href="http://forums.achaea.com/profile/Vadimuses">@Vadimuses</a> for a great deal of idea-bouncing and Mudlet help.<br></p><p><span style="font-size: x-large; font-size: x-large;"><b><a rel="nofollow" href="denied:DOWNLOAD: https://sourceforge.net/projects/achaeaseamappin/files/?source=navbar"><br></a></b></span></p><p><span style="font-size: small; font-size: small;"><b>Happy <span style="font-size: small; font-size: small;">sailing!</span></b></span></p><p><br></p><p><br></p>                
