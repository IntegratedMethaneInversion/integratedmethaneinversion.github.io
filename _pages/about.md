---
layout: default
title: About
permalink: /about/
---

<style>
  .pageWrapper {
    padding: 3% 12%;
  }

  #access-btn {
    background-color: #98c89a;
    color: white;
    border: none;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 5px;
    transition: all 300ms ease-in-out;
  }

  #access-btn:hover {
    background-color: #719873;
  }

  @media (max-width: 768px) {
    .pageWrapper {
      padding: 5% 5%;
      width: 100% !important;
    }

    #plot {
      scale: 0.7 !important;
    }

  }
</style>


<div class="pageWrapper">

<p>
The Integrated Methane Inversion (IMI) is a user-friendly research-grade cloud-computing tool for <strong>estimating total methane emissions for any domain and period of interest</strong> by analytical inversion of satellite observations from the TROPOspheric Monitoring Instrument (TROPOMI). It enables researchers and stakeholders to <strong>infer methane emissions at up to 0.125° × 0.15625° (≈ 12 × 12 km²) spatial resolution</strong> and up to weekly temporal resolution from <a href="https://registry.opendata.aws/sentinel5p/">TROPOMI satellite data resident on the Amazon Web Services (AWS) cloud</a>, without requiring
expert knowledge of inverse methods or cumbersome data download. 
<br>
<br>
The IMI uses the <a href="https://geos-chem.org">GEOS-Chem 3-D chemical transport model</a> driven by NASA Goddard Earth Observing System (GEOS) meteorological data as a forward model for the inversion. It uses <strong>cutting-edge algorithms developed by the <a href="https://carboninversion.com/people/">IMI team</a></strong> and is documented extensively in peer-reviewed research literature. The IMI is <strong>strongly documented and fully open-source to ensure transparency, reproducibility, and integrity of the results.</strong>
<br>
<br>
An IMI preview feature allows the users to display the satellite observations for their domain and period of interest along with prior emission inventories, point source data, and expected information to be achieved from the inversion.
</p>

<div style="display: flex; justify-content: center; align-items: center">
	<a href="{{ site.baseurl }}#topTwoColumn">
		<button id="access-btn">Learn How to Access</button>
    </a>
</div>

<hr />
<p>
<a href="https://integralearth.github.io">Integral Earth</a>, a simple web interface, allows non-experts to access the IMI with no learning curve. Users can request inversions with review by the IMI team and view inversion results through interactive visualizations.
</p>

<p align="center">
		<img src="../assets/plots/model.png" alt="Image depicting inversion workflow">
</p>

<p align="center">
		<img src="../assets/plots/optimized_emissions.png" alt="Map of optimized methane emissions"/> &nbsp;&nbsp;&nbsp;
		<img src="../assets/plots/emissions_timeline.png" alt="Methane emission timeseries"/>
</p>

</div>