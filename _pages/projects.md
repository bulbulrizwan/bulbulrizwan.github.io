---
layout: page
permalink: /projects/
title: Projects
description:  I am part of following research projects. The highlighted projects are the ones where I have been involved in the core team for writing the proposal.
nav: true
nav_order: 3
---
{% assign publications = site.scholar.bibliography %}

{% assign project_publicatios = {
  "dts": ["WELSCHER2023103414", "Chishtie2023"],
  "geocrow": ["key3", "key4"],
  "ignite": ["key5", "key6"],
  "abm4et": ["key7", "key8"],
  "cagis": ["key9", "key10"]
} %}
<!-- 
{% assign project_publications = {
  "dts": ["WELSCHER2023103414", "Chishtie2023"],
  "geocrow": ["key3", "key4"],
  "ignite": ["key5", "key6"],
  "abm4et": ["key7", "key8"],
  "cagis": ["key9", "key10"]
} %} -->

## Ongoing Projects

<div class="container">
  <!-- Project dts -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://project-dts.eu/">
              <img src="../assets/img/projects/dts_logo.png" class="card-img" alt="Ignite Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">dTS - Data Driven Tourism for sustainibility</h5>
              <p class="card-text">
                <strong>Funded by:</strong> Austrian Research Promotion Agency (FFG), Federal Ministry of Climate Action, Env, Energy, Mobility, Innovation and Tech. <br>
                <strong>Project No:</strong> FO999887513 <br>
                <strong>Duration:</strong> 2021-2024 <br>
                <strong>Budget:</strong> 728k EUR (overall), 173k EUR (TU Graz)<br>
                <strong>Role:</strong> Project writeup, Project key scientist<br> 
                <strong>Skills:</strong>
                <div class="row">
                  <div class="col">
                    <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Mobility analysis</div>
                    <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Tourist flow simulation modeling</div>
                    <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Prediction of next PoI</div>
                    <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Combining ABM and AI</div>
                  </div>
                </div>
            </div>
              </p>
              <!-- Debugging output -->
              <!-- <p>Publications: {{ publications | jsonify }}</p>
              <p>Project : {{ project_publications| jsonify }}</p> -->
              <!-- Related Publications -->
              <!-- <p><strong>Related Publications:</strong></p>
              <ul>
                {% for publication_key in project_publications.dts %}
                  {% assign publication = publications | where: "key", publication_key | first %}
                  <li><a href="{{ publication.url }}">{{ publication.title }}</a></li>
                {% endfor %}
              </ul> -->
          </div>
        </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Project Geocrow -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://www.geocrow-project.info/">
              <img src="../assets/img/projects/geocrow_logo.png" class="card-img" alt="Project 1 Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">GeoCrow - GeoSemantic and Crowdsourced enhanced Virtual Reality for Situational Awareness“</h5>
              <p class="card-text">
                <strong>Funded by:</strong> Austrian Research Promotion Agency (FFG) <br>
                <strong>Project No:</strong> FO999895161 <br>
                <strong>Duration:</strong> 2023-2025 <br>
                <strong>Budget:</strong> 610k EUR <br>
                <strong>Role:</strong> Project writeup, Project key scientist 
              </p>
              <p><strong>Skills:</strong></p>
              <div class="row">
                <div class="col">
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">NLP</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Geoparsing</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Mordecai</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Geoparsepy</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Knowldge graphs</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Semantic enrichment</div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Project ignite -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://geoinfo-tugraz.github.io/projects/IGNITE/">
              <img src="../assets/img/projects/ignite_logo.png" class="card-img" alt="Ignite Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">IGNITE - Improved Assessment of Forest Fire Susceptibility</h5>
              <p class="card-text">
                <strong>Funded by:</strong> Waldfonds Austria (Federal Ministry for Agriculture, Regions and Tourism) <br>
                <strong>Duration:</strong> 2022-2025 <br>
                <strong>Budget:</strong> 379k EUR (overall), 63k EUR (TU Graz) <br>
                <strong>Role:</strong> Project writeup, Project key scientist 
              </p>
              <p><strong>Skills:</strong></p>
              <div class="row">
                <div class="col">
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Causal machine learning</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Uncertainity modeling</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Explainaiable AI</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Baysian ML</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">PyMC3</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Causal Inference</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Project abm4ET -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://geoinfo-tugraz.github.io/projects/ABM4EnergyTransition/">
              <img src="../assets/img/projects/abm4et_logo_small.png" class="card-img" alt="abm4et Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">ABM4EnergyTransition - Agent-based Simulation of Transition Scenarios for regional Heating and Energy Transformation</h5>
              <p class="card-text">
                <strong>Funded by:</strong> Austrian Research Promotion Agency (FFG),AI for Green 2021 <br>
                <strong>Project No:</strong> FO999892237 <br>
                <strong>Duration:</strong> 2022-2024 <br>
                <strong>Budget:</strong> 489k EUR <br>
                <strong>Role:</strong> Project writeup, Project key scientist 
              </p>
              <p><strong>Skills:</strong></p>
              <div class="row">
                <div class="col">
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">ABM</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Energy transition</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Spatial analysis</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Decision support</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Public policy</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Energy systems</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Project cagis -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://geoinfo-tugraz.github.io/projects/historical_regions/">
              <img src="../assets/img/projects/cagis_logo.png" class="card-img" alt="Project 2 Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">Modeling and Visualizing the Extents of Historical Regions</h5>
               <p class="card-text">
                <strong>Funded by:</strong> Cartography and Geographic Information Society (CaGIS), CaGIS Rising Grant Program 2021 <br>
                <strong>Duration:</strong> 2022-2024 <br>
                <strong>Partners:</strong> Karl Grossner ((University of Pittsburgh) and Eric Delmelle (University of North Carolina at Charlotte) <br>
                <strong>Budget:</strong> $9,848 <br>
                <strong>Role:</strong> Project writeup, Project Co-PI
              </p>
              <p><strong>Skills:</strong></p>
              <div class="row">
                <div class="col">
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Uncertain locations</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Boundaries of imprecise regions </div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Historical gazetteer</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Kernel Density Estimation (KDE)</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Quantification and visualization of uncertainity</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>  
</div>
</div>

## Completed Projects

<div class="container">
  <!-- Project pv4eag -->
  <div class="row">
    <div class="col-md-12">
      <div class="card border-primary mb-3">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <a href="https://www.fh-joanneum.at/projekt/pv4eag/">
              <img src="../assets/img/projects/pv4eag_logo.png" class="card-img" alt="Project 1 Image">
            </a>
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">Analysis Of Area And Energy Potential Using AI For Alternative PV Systems as aContribution To The EAG“</h5>
              <p class="card-text">
                <strong>Funded by:</strong> Austrian Research Promotion Agency (FFG) <br>
                <strong>Duration:</strong> 2022-2023 <br>
                <strong>Role:</strong> Project writeup, Project Partner 
              </p>
              <p><strong>Skills:</strong></p>
              <div class="row">
                <div class="col">
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Vertical PV</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">Extracting building facades </div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">MCDA</div>
                  <div class="rounded-pill bg-primary text-white d-inline-block p-2 mb-2">GeoAI for PV potential estimation</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>