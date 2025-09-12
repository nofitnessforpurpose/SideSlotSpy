# Side Slot Spy
PSION Organiser I & II - Side Slot Monitoring

This repository holds files needed to create a Side Slot monitoring point for the Organiser 1 & 2 devices for device development. The related Organiser II Top Slot Spy is located <a href="https://github.com/nofitnessforpurpose/TopSlotSpy">here</a>.  

As detailed in the <a href="https://www.jaapsch.net/psion/tech04.htm">Technical Reference Manual</a>, hardware interfaces can be included in the side slots, with the Top Slot of Organiser II devices preferred for ergonomic reasons. On the Organiser I device the Top Slot is not available, hence the '<a href="https://www.jaapsch.net/psion/p1manlink2.htm">Link-Up</a>' packs utilised the side slots to implement hardware interfaces.  

In addition to supporting development of side slot hardware interfaces the Side Slot Spy will suport use and development of <a href="https://www.jaapsch.net/psion/tech09.htm">Data Pack</a> memory modules, co-processors or other hardware.  

<div align="center">
  <div style="display: flex; align-items: flex-start;">
    
  <img src="https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/images/Assembly 01.jpg?raw=true" width="400px" alt="PSION Organiser II Side Slot Case. Image copyright (c) 18 August 2025 nofitnessforpurpose All Rights Reserved">
  </div>
</div>
<BR>

[![Organiser](https://img.shields.io/badge/gadget-Organiser_II-blueviolet.svg?%3D&style=flat-square)]([https://en.wikipedia.org/wiki/Psion_Organiser])
[![GitHub License](https://img.shields.io/github/license/nofitnessforpurpose/TopSlotSpy?style=flat-square)](https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/LICENSE) 
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg?style=flat-square)](https://github.com/nofitnessforpurpose/SideSlotSpy/graphs/commit-activity)
![GitHub repo size](https://img.shields.io/github/repo-size/nofitnessforpurpose/SideSlotSpy?style=flat-square)
[![Static Badge](https://img.shields.io/badge/format-STEP%20Solid%20Model-blue?style=flat-square)](https://en.wikipedia.org/wiki/ISO_10303)
[![Static Badge](https://img.shields.io/badge/format-GERBER%20PCB-blue?style=flat-square)](https://en.wikipedia.org/wiki/Gerber_format)
<br>  
  All the files are required.  <br>
  The default repository format for 3D files is STEP (<a target="_blank" rel="noopener noreferrer" href="https://en.wikipedia.org/wiki/ISO_10303"> ISO 10303</a> ) due to its high fidelity.  { STL files are surface geometry as opposed to solid model representations, often containing export processing artifacts }. 
<br>  
  The default repository format for PCB files is <a targer="_blank" rel="noopener noreferrer" href="https://en.wikipedia.org/wiki/Gerber_format">GERBER</a> .
<br>

<br>  
<a target="_blank" rel="noopener noreferrer" href="https://www.freecad.org/" > FreeCAD </a> may prove suitable for viewing, handling and, if desired modifying STEP files.
<br>
<a target="_blank" rel="noopener noreferrer" href="https://www.kicad.org/" >KiCad </a> may prove suitable for viewing GERBER files.  
<br>
<br>

### On-Line Preview   
Models might be viewed on line using the following links. Noting display of any mesh lines is a feature of the renderer and are not contained in the source STEP model. It is strongly recommended to use the source STEP file where ever possible, as any export process will introduce artifacts.  
 - Assembly - <a target="_blank" href="https://3dviewer.net/#model=https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/CAD/ass-sss-01.stp">here</a>.
 - Outer - <a target="_blank" href="https://3dviewer.net/#model=https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/CAD/Outer%2003%20-%20No%20Grips%20-%20Slot.stp">here</a>.
 - Cover - <a target="_blank" href="https://3dviewer.net/#model=https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/CAD/Top-Cover%2003%20-%20No%20Hole.stp">here</a>.  
<BR>
<BR>

The internal connector of the Side Slot is brought out to two external connections. The PCB is marked with Slot Pin out details and the case does not have friction grips so as to assist reading of the details through transparent cases. One of the connections can be used to probe signals on the Side <a href="https://www.jaapsch.net/psion/tech04.htm#p4.2">Slot Control Bus<a> whilst the other connection connected to the target hardware. Making more practicable development on <a href="https://en.wikipedia.org/wiki/Breadboard">Solderless Bread Boards<a/>.   

As there are two identical external connections provided by the Side Slot Spy makes it practicable to use a traditional data pack whilst developing hardware in the same Side Slot port. As the control logic needed for hardware will, when correctly implemented, select the appropriate hardware.  

The PCB is 4 layer to provide a screening for signals and ensure a low impedance power distribution to an externally connected target system.  

Note:  
As the internal signals of the host Organiser are exposed via the Side Slot Spy connection pins, care must be exercised to protect from unsuitable signal connection(s) or static electricity. Any incorrect connection or voltage will lead to irreversible degradation!

<div align="center">
  <div style="display: flex; align-items: flex-start;">
    
  <img src="https://github.com/nofitnessforpurpose/SideSlotSpy/blob/main/images/SSS-Rear-View.jpg?raw=true" width="400px" alt="PSION Organiser II Side Slot Case. Image copyright (c) 18 August 2025 nofitnessforpurpose All Rights Reserved">
  </div>
</div>
<BR>

<br>

## Considerations
The 3D models make no accomodation for manufacturing tolerances, process or material - see Notes below.  
The PCB has been tested, it remains your responsiblity to asses suitability!  
The assembly of PCB and case has been tested, it remains your responsiblity to asses suitability!  
See all notes  

<br>

## Questions / Discussion
See <a target="_blank" rel="noopener noreferrer" href="https://www.organiser2.com/"> Organiser 2 Hardware </a> forum, though see note below first.  

<br>

## Please note:  
All information is For Indication Only.  
No association, affiliation, recommendation, suitability, fitness for purpose should be assumed or is implied.  
Registered trademarks are owned by their respective registrants.  
