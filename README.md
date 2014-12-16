OpenCPN 3.2.2 Patches
===============
<div align="justify">
A set of useful patches for <a href="https://github.com/OpenCPN/OpenCPN">OpenCPN 3.2.2</a>, aiming small boats, running in low performance devices and small screens.
To use these patches just copy the desired patches to the OpenCPN source folder and run:</div>
```
patch -p0 -i <file>.patch
```
<br>
#### Waypoint Arrival Radius
From OpenCPN website:
>OpenCPN automatically shifts to the next waypoint in the route using an arrival radius of 0.05 miles (= 92.6 m). This is all automatic and not user configurable or "signal-able".

Great, but not for small boats. <a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/arrival_radius.patch">This</a> patch reduce the arrival radius to 0.001 miles (~1.8 m) and increase the dashboard digits to allow see this new third digit precision.

<br>
#### Start in Fullscreen
<a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/fullscreen.patch">This</a> patch just do it start in fullscreen mode.
<table>
  <tr>
    <th>Before</th>
    <th>After</th>
  </tr>
   <tr>
    <th><img src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/full_b.png"></th>
    <th><img src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/full_a.png"></th>
  </tr>
</table>

<br>
#### Remove Watermarks
<a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/overzoom.patch">This</a> patch remove the "Overzoom" and "Meters" text/watermark from screen.</a>
<div align="center"><img width="50%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/overzoom.png"></div>

<br>
#### Max Zoomout
<div align="justify">
<a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/zoomout.patch">This</a> patch set the max zoomout level, this is necessary if you run OpenCPN in low performance devices. The zoomout level can be changed directly in the patch before apply it.</div>
<table>
  <tr>
    <th>Before</th>
    <th>After</th>
  </tr>
   <tr>
    <th><img width="100%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/zoom_b.png"></th>
    <th><img width="100%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/zoom_a.png"></th>
  </tr>
</table>

<br>
#### Basic Toolbar
<div align="justify">
<a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/toolbar.patch">This</a> patch remove some buttons from toolbar, to fit in small screens only with the basic: zoom in/out, draw route, boat, configuration and route manager. Anyway if you want keep something, just edit the patch.</div>
<table>
  <tr>
    <th>Before</th>
    <th>After</th>
  </tr>
   <tr>
    <th><img width="100%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/toolbar_b.png"></th>
    <th><img width="100%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/toolbar_a.png"></th>
  </tr>
</table>

<br>
#### No Annoying Screens!
<div align="justify"><a href="https://github.com/themrleon/OpenCPN_Patches/blob/master/patches/screens.patch">This</a> patch remove two annoying screens, first is that about no charts installed and other about log file size when it's big.</div>
<div align="center"><img width="40%" src="https://raw.githubusercontent.com/themrleon/OpenCPN_Patches/master/images/screen.png"></div>
