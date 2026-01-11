---
layout: page
title: Optimization Thesis
permalink: /projects/opti_thesis/
---

<div style="font-family:'Merriweather', Georgia, serif; color:#333333;">

  <!-- Title with gradient -->
  <div style="
    background: linear-gradient(90deg, #155799, #159957);
    padding:30px;
    border-left:5px solid #155799;
    margin-bottom:40px;
    text-align:center;
    border-radius:8px;
  ">
      <h1 style="color:#ffffff; margin:0;">Forest Management and NDVI Recovery</h1>
      <h2 style="color:#e0f7f1; margin:10px 0 0 0; font-weight:400; font-size:1.5rem;">
        Statistics Masters Thesis
      </h2>
  </div>

  <!-- Flex container: text + sidebar images -->
  <div style="display:flex; gap:30px; flex-wrap:wrap; justify-content:center;">

    <!-- Left: thin text column -->
    <div style="flex:1 1 0; max-width:450px;">

      <!-- Overview -->
      <h2 style="color:#159957; margin-top:30px; margin-bottom:15px;">Overview</h2>
      <p>
        This project analyzes how expanding an agricultural conservation program (CRP) to include lumber could reduce per-acre government costs while extending environmental benefits.
      </p>
      <hr style="border:0; border-top:2px solid #d3d3d3; margin:30px 0;" />

      <!-- Data -->
      <h2 style="color:#159957; margin-top:30px; margin-bottom:15px;">Data</h2>
      <ul>
        <li>FIA forest inventory data</li>
        <li>NOAA NDVI</li>
        <li>County-year panel data (controls and stumpage)</li>
      </ul>
      <hr style="border:0; border-top:2px solid #d3d3d3; margin:30px 0;" />

      <!-- Approach -->
      <h2 style="color:#159957; margin-top:30px; margin-bottom:15px;">Approach</h2>
      <ul>
        <li>Panel regression with county and year fixed effects</li>
        <li>Treatment timing and years-since-cut variables</li>
        <li>Optimization based on complex decision variables and parameter interactions</li>
      </ul>
      <hr style="border:0; border-top:2px solid #d3d3d3; margin:30px 0;" />

      <!-- Key Findings -->
      <div style="
        background-color:#d4f0e0;
        padding:20px;
        border-left:5px solid #00b894;
        border-radius:6px;
        margin-bottom:30px;
      ">
        <h2 style="color:#159957; margin-top:0;">Key Findings</h2>
        <ul>
          <li>Additional plots from New England could be added with little change in overall program costs</li>
          <li>NDVI recovery has the possibility of being large and statistically significant, especially when applied to other areas of the country</li>
        </ul>
      </div>

      <!-- Tools -->
      <div style="
        background-color:#d4f0e0;
        padding:20px;
        border-left:5px solid #00b894;
        border-radius:6px;
        margin-bottom:30px;
      ">
        <h2 style="color:#159957; margin-top:0;">Tools</h2>
        <p>R, Python, Gurobi</p>
      </div>

    </div> <!-- end text column -->

    <!-- Right: Sidebar images -->
    <div style="flex:0 0 200px; display:flex; flex-direction:column; gap:20px;">
      <img src="/assets/images/opti/results.png" alt="Main Results" style="width:100%; height:auto; border-radius:6px;">
      <img src="/assets/images/opti/plotsizes.png" alt="Randomized Plot Sizes" style="width:100%; height:auto; border-radius:6px;">
    </div>

  </div> <!-- end flex container -->

</div>
