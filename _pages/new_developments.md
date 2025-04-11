---
layout: single
title: In Development
permalink: /new_developments/
---

<h3>IMI 2.1.0 - expected April 2025</h3>
<ul style = "font-size: 0.9em">
    <li>Automatic ensemble generation for uncertainty calculation (Lucas Estrada, Harvard University)</li>
    <li>Option to plot prior and posterior against NOAA Observation Package (ObsPack) data (Melissa Sulprizio and James East, Harvard University)</li>
    <li>Breakdown of sectoral emissions in plots (John Thomas, Harvard University)</li>
    <li>Minor bug fixes</li>
</ul>

<h3>IMI 2.2.0 - expected May 2025</h3>
<ul style = "font-size: 0.9em">
    <li>Update to GEOS-Chem 14.6.0, which includes:
       <ul>
         <li>Mass conservation fix in mixing scheme (Nick Balasus, Harvard University)</li>
         <li>Seasonality of hydropower reservoir emissions (Melissa Sulprizio, Harvard University)</li>
         <li>Fix for double counting of agricultural burning emissions (Nick Balasus, Harvard University)</li>
         <li>Update rice emissions to GRPI (Zichong Chen, Harvard University)</li>
         <li>Update to GFEI v3 (Tia Scarpelli, CarbonMapper)
        <li>Option to use TCR-2 OH fields (Kazu Miyazaki, NASA JPL)</li>
       </ul>
    </li>
    <li>Enable inversions at 12km resolution (Xiaolin Wang and Melissa Sulprizio, Harvard University)</li>
</ul>

<h3>Looking Forward<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/arrow-trend-up.svg" style = "height: 25px; width: 25px; margin-bottom: 5px; margin-left: 10px;"></span></h3>
<ul style = "font-size: 0.9em">
    <li>Near-real-time / low-latency capability (Lucas Estrada, Harvard University)</li>
    <li>Automated benchmarking of IMI (Melissa Sulprizio, Harvard University)</li>
    <li>Use GEOS-Chem carbon simulation instead of CH4 (Melissa Sulprizio, Harvard University)
      <ul>
        <li>Single species or joint carbon (CO2, CO, CH4, OCS) simulations</li>
        <li>Step toward expanding the IMI into the Integrated Carbon Inversion (ICI)</li>
      </ul>
    </li>
    <li>Incorporation of point sources (James East, Harvard University)</li>
    <li>Regional BC error diagnostic (Hannah Nesser, NASA JPL)</li>
    <li>ObsPack observation operator</li>
    <li>Integration of MethaneSAT data into the IMI
      <ul>
        <li>Option to use MethaneAIR and MethaneSAT data to quantify emissions with the IMI (led by Jack Bruno)</li>
      </ul>
    </li>
    <li>Extend the IMI to CO<sub>2</sub> (Hannah Nesser, NASA JPL)
      <ul>
        <li>Options for OCO-2/3, GOSAT-GW, CO2M</li>
        <li>Rename the IMI to Integrated Carbon Inversion (ICI)</li>
        </ul>
    </li>
    <li>Enable GEOS-Chem High Performance (GCHP) in the IMI (Dandan Zhang, Harvard University)</li>
</ul>
