---
permalink: /
title: "Professional Profile"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css">

<style>
  /* Professional Pitch Box */
  .pitch-box { 
    font-size: 1.15rem; 
    color: #4a2c20; 
    background: linear-gradient(135deg, rgba(201, 138, 93, 0.15) 0%, rgba(201, 138, 93, 0.05) 100%);
    border-left: 6px solid #9d3a26; 
    padding: 2rem; 
    margin: 2rem 0; 
    font-weight: 500;
    line-height: 1.6;
    border-radius: 0 8px 8px 0;
  }
  
  html[data-theme="dark"] .pitch-box { 
    color: #dcd3c1; 
    background: #262321;
    border-left-color: #c98a5d;
  }

  /* Competency & Project Grid */
  .competency-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1.2rem;
    margin-top: 1.5rem;
  }
  
  .competency-item {
    flex: 1 1 calc(50% - 1.2rem);
    min-width: 280px;
    background: rgba(128,128,128,0.05);
    padding: 1.5rem;
    border-radius: 8px;
    border: 1px solid rgba(128,128,128,0.1);
    transition: all 0.2s ease;
  }

  .competency-item h3 { 
    font-size: 1.1rem; 
    margin: 0 0 0.8rem 0; 
    color: #9d3a26; 
    display: flex;
    align-items: center;
  }

  .competency-item h3 i { margin-right: 12px; width: 20px; text-align: center; }
  .competency-item ul { list-style: none !important; padding: 0 !important; margin: 0 !important; font-size: 0.9rem; }
  .competency-item li { margin-bottom: 0.5rem; border: none; }
  
  /* Learning Badges */
  .learning-badge {
    display: flex;
    align-items: center;
    padding: 12px 18px;
    background: rgba(128, 128, 128, 0.04);
    border: 1px solid rgba(128, 128, 128, 0.1);
    border-radius: 8px;
    text-decoration: none !important;
    color: inherit !important;
    transition: all 0.2s ease;
    flex: 1 1 calc(50% - 1.2rem);
  }
  .learning-badge:hover {
    background: #fff;
    border-color: #9d3a26;
    transform: translateY(-2px);
  }
  .learning-badge i { color: #9d3a26; margin-right: 12px; }

  /* Project Details Styling */
  summary { cursor: pointer; color: #9d3a26; font-weight: 600; font-size: 0.85rem; margin-top: 10px; outline: none; }
  summary:hover { text-decoration: underline; }
  .details-content { padding: 10px; font-size: 0.85rem; border-top: 1px solid rgba(128,128,128,0.2); margin-top: 10px; font-style: italic; }

  .hero-frame { margin-bottom: 2rem; border-radius: 8px; overflow: hidden; border: 1px solid rgba(128,128,128,0.2); }
  .hero-frame img { width: 100%; height: 350px; object-fit: cover; display: block; }
  
  @media (max-width: 600px) { 
    .competency-item, .learning-badge { flex: 1 1 100%; } 
  }
</style>

<div class="pitch-box">
  <strong>Bilingual (English/French) Project Professional</strong> specialized in GIS-based analytical systems and operational coordination. PhD-trained in leading complex initiatives—integrating technical workflows, environmental considerations, and stakeholder engagement to deliver actionable results.
  <br><br>
  <a href="{{ base_path }}/cv-professional/" class="btn btn--primary">View Professional CV</a>
</div>

## Professional Profile

I coordinate technical and field-based initiatives within complex regulatory environments. With over a decade of experience, I manage large-scale data workflows and **remote operational logistics**, applying systems thinking to bridge the gap between technical research and strategic decision-support.

My background includes navigating **Indigenous heritage concerns** and **environmental impact considerations**, focusing on proactive risk mitigation. I utilize **Agile (Scrum) principles** to maintain transparency and iterative progress across cross-functional workflows, driving projects from planning to final reporting.

## Project Case Studies

<div class="competency-grid">
  <div class="competency-item">
    <h3><i class="fas fa-map-pin"></i> Remote Logistics & Coordination</h3>
    <p>Managed multi-disciplinary field logistics and team in the Maya Lowlands. Oversaw resource allocation and operational timelines, and project execution for remote four-person team.</p>
    <details>
      <summary>View Technical Details</summary>
      <div class="details-content">
        Integrated traditional archaeological excavations and data with GIS hydrological modeling at Yaxnohcah, Campeche. Navigated tropical rainforest logistics while maintaining data integrity across disparate software systems.
      </div>
    </details>
  </div>

  <div class="competency-item">
    <h3><i class="fas fa-chart-line"></i> Analytical Systems Design</h3>
    <p>Led the integration of large-scale Lidar and legacy spatial data to support landscape-scale modeling. Focused on converting complex environmental variables into actionable insights.</p>
    <details>
      <summary>View Technical Details</summary>
      <div class="details-content">
        Developed 3D visibility and hydrological models for the Poverty Point monumental landscape. Utilized ArcGIS Pro for quantitative affordance modeling.
      </div>
    </details>
  </div>
</div>

## Core Competencies

<div class="competency-grid">
  <div class="competency-item">
    <h3><i class="fas fa-project-diagram"></i> Project Coordination</h3>
    <ul>
      <li>Strategic planning & Lifecycle management</li>
      <li>Independent project execution</li>
      <li>Stakeholder communication & reporting</li>
    </ul>
  </div>
  <div class="competency-item">
    <h3><i class="fas fa-map-marked-alt"></i> GIS & Geospatial</h3>
    <ul>
      <li>Spatial modeling & Data visualization</li>
      <li>Analytical decision-support systems</li>
      <li>Advanced ArcGIS Pro & QGIS</li>
    </ul>
  </div>
  <div class="competency-item">
    <h3><i class="fas fa-sync-alt"></i> Data & Agile Systems</h3>
    <ul>
      <li>Agile (Scrum) workflow management</li>
      <li>Information synthesis & Documentation</li>
      <li>Quantitative analysis (R/Python)</li>
    </ul>
  </div>
  <div class="competency-item">
    <h3><i class="fas fa-users"></i> Operations & Relations</h3>
    <ul>
      <li>Remote logistics & Field coordination</li>
      <li>Indigenous & Stakeholder engagement</li>
      <li>Operational risk mitigation</li>
    </ul>
  </div>
</div>

## Professional Development & Credits

<div class="competency-grid">
  <a href="/cv-json/" class="learning-badge">
    <i class="fas fa-certificate"></i>
    <span class="badge-text">Advanced GIS Certificate (CUNY)</span>
  </a>
  <a href="/academic/" class="learning-badge">
    <i class="fas fa-language"></i>
    <span class="badge-text">Bilingual Proficiency (English/French)</span>
  </a>
  <a href="/cv-json/" class="learning-badge">
    <i class="fas fa-sync-alt"></i>
    <span class="badge-text">Agile & Scrum Methodologies</span>
  </a>
  <a href="/cv-json/" class="learning-badge">
    <i class="fas fa-tools"></i>
    <span class="badge-text">Technical Literacy (Git & Markdown)</span>
  </a>
</div>

<div style="margin-top: 3rem; padding: 1.5rem; background: rgba(128,128,128,0.05); border-radius: 8px; text-align: center; border: 1px solid rgba(128,128,128,0.1);">
  Looking for my research and publications? <a href="/academic" style="font-weight: 600; text-decoration: underline;">Visit the Academic Portfolio</a>.
</div>