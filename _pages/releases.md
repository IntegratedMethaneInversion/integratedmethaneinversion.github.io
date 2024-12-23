---
layout: single
title: Releases
permalink: /releases/
---

<hr>
<h2 id = "new_developments">IMI 2.0<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/flask.svg" style = "height: 25px; width: 25px; margin-bottom: 5px; margin-left: 10px;"></span></h2>

<div style = "display: flex; justify-content: left; gap: 1.5rem; align-items: center; margin-bottom: 1.5rem">

<button style = "background-color: #98C89A; outline: none; border: none; color: white; transform: scale(1.2); margin-left: 1.1rem">
IMI-2.0.0-beta.3
</button>
<a href = "https://github.com/geoschem/integrated_methane_inversion/releases" target = "#">

    <img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" title = "GitHub Repo" style = "height: 30px; width: 30px;">

</a>
</div>

<img src="{{ site.baseurl }}/assets/plots/IMI2.png" />

<p>
IMI 2.0 is now in beta testing with a host of new capabilities, including:

<ul>
<li>
<strong>Improved TROPOMI observations</strong>: Users have the option of accessing the most recent operational product from SRON or a blended TROPOMI+GOSAT product constructed using machine learning (Balasus et al., 2023).
</li>
<li>
<strong>Continuous emission monitoring</strong>: IMI 2.0 introduces a Kalman filter feature to regularly quantify emissions from a region of interest with low latency (e.g., weekly, monthly estimates).
</li>
<li>
<strong>Optimization of methane sinks</strong>: Users can optimize methane sinks from oxidation by the hydroxyl radical and uptake by soils.
</li>
<li>
<strong>Improved computational efficiency</strong>: The construction of the Jacobian matrix, a key computational step, has been sped up by an order of magnitude, making the inversion process much faster.
</li>

<li>
<strong>Improved error characterization</strong>: IMI 2.0 has improved characterization of observational errors, allows users to use log-normal errors on emissions, and returns detailed error diagnostics on the results.
</li>

<li>
<strong>Global inversions</strong>: IMI 2.0 supports global methane inversions in addition to regional.
</li>
<li>
<strong>Incorporation of point source observations</strong>: IMI 2.0 uses high-resolution point source observations to construct the state vector of emissions optimized in the inversion, improving the quantification of methane emissions where large point sources have been observed.
</li>
<li>
<strong>And much more</strong>: See the IMI 2.0 development paper by <a href = "https://acmg.seas.harvard.edu/sites/projects.iq.harvard.edu/files/acmg/files/estrada2024_imi.pdf" target = "#">Estrada et al. (2024)</a> for more information.

</li>

</ul>

</p>

<h2 id = "new_developments">Previous Releases<span><img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/house.svg" style = "height: 25px; width: 25px; margin-bottom: 5px; margin-left: 10px;"></span></h2>

<div style = "display: flex; justify-content: left; gap: 1.5rem; align-items: center; margin-bottom: 1.5rem">

    <button style = "background-color: #98C89A; outline: none; border: none; color: white; transform: scale(1.2); margin-left: 1.1rem">
    IMI 1.2.1
    </button>

<a href = "https://github.com/geoschem/integrated_methane_inversion/releases" target = "#">

    <img src = "https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" title = "GitHub Repo" style = "height: 30px; width: 30px;">

</a>

</div>

<div style = "font-size: 0.9em">
<strong>Bugfixes</strong>
<ul>
    <li>Removed TROPOMI albedo filters after consultation with SRON.</li>
    <li>Fixed various errors including those in TROPOMI variables, observation array size, and Harvard GEOS Chem environment files.</li>
</ul>

<strong>New Features</strong>

 <ul>
    <li>Introduced a new default boundary conditions version (v2023-06) with significant updates, including the removal of a misapplied stratospheric correction and albedo filters.</li>
    <li>Added support for specifying partitions for sbatch commands to enhance ease of use on local clusters.</li>
</ul>

<strong>General Improvements</strong>

<ul>
<li>Enabled nc4 compression, significantly reducing the file size of the output directory generated by the IMI.</li>
</ul>

 </div>
