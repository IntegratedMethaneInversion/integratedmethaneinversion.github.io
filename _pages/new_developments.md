---
layout: single
title: New Developments
permalink: /new_developments/
---

 <h2 id = "new_developments">IMI 2.0 and Beyond<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/rocket.svg" style = "height: 25px; width: 25px; margin-left: 10px;"></span></h2>

IMI 2.0 is slated to be released soon and will offer significant improvements over 1.x.

<ul style = "font-size: 0.9em">
            <li><strong>Blended Dataset Compatibility</strong>: IMI 2.0 is now compatible with a blended TROPOMI+GOSAT dataset, which helps to mitigate data artifacts and improve the accuracy of methane observations.</li>
            <li><strong>Incorporation of Point Source Observations</strong>: IMI 2.0 integrates high-resolution point source observations, allowing for more precise identification and quantification of methane emissions from large point sources.</li>
            <li><strong>Improved Computational Efficiency</strong>: The construction of the Jacobian matrix, a key computational step, has been sped up by an order of magnitude, making the inversion process significantly faster.</li>
            <li><strong>Enhanced Error Characterization</strong>: The use of super-observations improves error characterization by averaging multiple individual observations, thus reducing noise and enhancing the reliability of the inversion results.</li>
            <li><strong>Adaptive Spatial Resolution and Global Capability</strong>: IMI 2.0 features adaptive spatial resolution based on the information content of observations, and it now supports global inversions, including the capability to optimize emissions and atmospheric concentrations on a global scale.</li>
        </ul>

<hr>

<h3>Looking Forward: Goals for IMI 3.0<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/arrow-trend-up.svg" style = "height: 25px; width: 25px; margin-bottom: 5px; margin-left: 10px;"></span></h3>
<ul style = "font-size: 0.9em">
    <li><strong>12-km inversion capability</strong>
        <ul>
            <li>Enable inversions at 12-km resolution in the IMI (led by Melissa Sulprizio and Xiaolin Wang)
            </li>
        </ul>
    </li>
    <li><strong>Integration of MethaneSAT data into the IMI</strong>
        <ul>
            <li>Option to use MethaneAIR and MethaneSAT data to quantify emissions with the IMI (led by Jack Bruno)
            </li>

        </ul>
    </li>
    <li><strong>Incorporation of point sources</strong></li>
        <ul>
            <li>
            E.g., by incorporating point source observations into IMI prior emission estimates (led by James East)

            </li>
        </ul>
    <li><strong>Extend the IMI to CO<sub>2</sub> (IMI + CO<sub>2</sub> = ICI)</strong>
        <ul>
            <li>Develop CO2 inversion capabilities (led by Hannah Nesser)
            </li>
            <li>Options for OCO-2/3, GOSAT-GW, CO2M
            </li>
        </ul>
    </li>

</ul>
