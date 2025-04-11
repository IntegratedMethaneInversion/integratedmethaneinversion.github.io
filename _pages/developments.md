---
layout: single
title: In Development
permalink: /developments/
---

<h3>IMI 2.1.0 - expected April 2025</h3>
<table style="width:100%">
	<tr>
    	<th style="width=70%">Feature</th>
    	<th>Developer(s)</th>
    </tr>
	<tr>
    	<td>Automatic ensemble generation for uncertainty calculation</td>
    	<td>Lucas Estrada (Harvard University)</td>
    </tr>
    <tr>
    	<td>Independent validation of the IMI using NOAA Observation Package (ObsPack) data</td>
    	<td>Melissa Sulprizio and James East (Harvard University)</td>
    </tr>
    <tr>
		<td>Breakdown of sectoral emissions in plots</td>
		<td>John Thomas (Harvard University)</td>
	</tr>
	<tr>
    	<td>Minor bug fixes</td>
    	<td> </td>
   	</tr>
</table>

<h3>IMI 2.2.0 - expected May 2025</h3>
<table style="width=100%">
	<tr>
    	<th style="width=70%">Feature</th>
    	<th>Developer(s)</th>
    </tr>
	<tr>
	    <td>Enable inversions at 12-km resolution</td>
	    <td>Xiaolin Wang and Melissa Sulprizio (Harvard University)</td>
	</tr>
	<tr>
	    <td>Update to GEOS-Chem 14.6.0, which includes:
    	   <ul>
             <li>Mass conservation fix in mixing scheme (Nick Balasus, Harvard University)</li>
             <li>Seasonality of hydropower reservoir emissions (Melissa Sulprizio, Harvard University)</li>
       	     <li>Fix for double counting of agricultural burning emissions (Nick Balasus, Harvard University)</li>
            <li>Update rice emissions to GRPI (Zichong Chen, Harvard University)</li>
            <li>Update to GFEI v3 (Tia Scarpelli, CarbonMapper)</li>
            <li>Option to use TCR-2 OH fields (Kazu Miyazaki, NASA JPL)</li>
          </ul>
        </td>
        <td>Melissa Sulprizio (Harvard University)</td>
	</tr>
</table>

<h3>Looking Forward<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/arrow-trend-up.svg" style = "height: 25px; width: 25px; margin-bottom: 5px; margin-left: 10px;"></span></h3>
<table style="font-size:0.9em width=100%">
	<tr>
    	<th style="width=70%">Feature</th>
    	<th>Developer(s)</th>
    </tr>
	<tr>
	    <td>Near-real-time / low-latency capability</td>
	    <td>Lucas Estrada (Harvard University)</td>
	</tr>
    <tr>
    	<td>Automated benchmarking of IMI</td>
    	<td>(Melissa Sulprizio (Harvard University)</td>
	</tr>
    <tr>
    	<td>Use GEOS-Chem carbon simulation instead of the CH4 simulation
    	   <ul>
             <li>Single species or joint carbon (CO2, CO, CH4, OCS) simulations</li>
             <li>Step toward expanding the IMI into the Integrated Carbon Inversion (ICI)</li>
           </ul>
    	</td>
    	<td>Melissa Sulprizio (Harvard University)</td>
    </tr>
    <tr>
    	<td>Incorporation of point sources</td>
    	<td>James East (Harvard University)</td>
    </tr>
    <tr>
    	<td>Regional BC error diagnostic</td>
    	<td>Hannah Nesser (NASA JPL)</td>
    </tr>
    <tr>
 	 	<td>ObsPack observation operator</td>
 	 	<td>TBD</td>
 	</tr>
    <tr>
    	<td>Integration of MethaneSAT data into the IMI</td>
    	<td>Jack Bruno (Harvard University)</td>
    </tr>
    <tr>
    	<td>Extend the IMI to CO<sub>2</sub>
    	  <ul>
    	     <li>Options for OCO-2/3, GOSAT-GW, CO2M</li>
             <li>IMI will be renamed to Integrated Carbon Inversion (ICI)</li>
          </ul>
        </td>
    	<td>Hannah Nesser (NASA JPL)</td>
    </tr>
    <tr>
    	<td>Enable GEOS-Chem High Performance (GCHP) in the IMI</td>
    	<td>Dandan Zhang (Harvard University)</td>
</table>
