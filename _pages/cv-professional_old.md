---
#layout: single
#title: "Professional Resume"
#permalink: /cv-professional/
# author_profile: true
---
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css">

<style>
  .cv-wrapper { line-height: 1.4; font-size: 0.95rem; color: var(--text-color, inherit); max-width: 800px; }
  .cv-section-title { display: flex; align-items: center; margin: 1.5rem 0 0.5rem; padding-bottom: 4px; border-bottom: 2px solid var(--primary-color, rgba(128,128,128,0.5)); text-transform: uppercase; font-size: 1.05rem; font-weight: 800; letter-spacing: 1px; color: var(--heading-color, inherit); }
  .cv-section-title i { margin-right: 8px; font-size: 0.95rem; opacity: 0.8; color: var(--primary-color, inherit); }
  .cv-entry { display: flex; justify-content: space-between; margin-bottom: 0.8rem; }
  .cv-main { flex: 1; padding-right: 15px; }
  .cv-title { font-weight: 800; font-size: 1rem; margin: 0; color: var(--heading-color, inherit); }
  .cv-sub { font-style: italic; opacity: 0.9; font-size: 0.9rem; margin-top: 1px; color: var(--primary-color, inherit); }
  .cv-date { font-weight: 700; min-width: 110px; text-align: right; opacity: 0.7; font-size: 0.85rem; font-feature-settings: "tnum"; }
  .cv-details { margin-top: 2px; }
  .cv-details-toggle { font-size: 0.75rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; color: var(--primary-color, #494e52); cursor: pointer; list-style: none; display: inline-flex; align-items: center; padding: 2px 6px; background: rgba(128,128,128,0.08); border-radius: 3px; transition: background 0.2s ease; }
  .cv-details-toggle::-webkit-details-marker { display: none; }
  .cv-details-toggle:hover { background: rgba(128,128,128,0.15); }
  .cv-details-toggle::before { content: '\25B6'; font-size: 0.55rem; margin-right: 5px; transition: transform 0.2s; }
  .cv-details[open] .cv-details-toggle::before { transform: rotate(90deg); }
  .cv-details[open] .cv-details-toggle { margin-bottom: 4px; }
  .cv-list { margin: 4px 0 0 1rem; padding: 0; list-style: none; font-size: 0.85rem; }
  .cv-list li { margin-bottom: 4px; text-align: justify; position: relative; }
  .cv-list li::before { content: "•"; color: var(--primary-color, inherit); position: absolute; left: -1rem; font-weight: bold; }

  .skill-group { margin-bottom: 0.8rem; } 
  .skill-label { font-weight: 800; text-transform: uppercase; font-size: 0.75rem; letter-spacing: 1px; opacity: 0.6; display: block; margin-bottom: 4px; }

  .skill-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1.1rem;
    margin-top: 1.5rem;
  }

  .skill-badge {
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
  .skill-badge:hover {
    background: #fff;
    border-color: #9d3a26;
    transform: translateY(-2px);
  }
  .skill-badge i { color: #9d3a26; margin-right: 12px; }


</style>
 <h2 class="cv-section-title"><i class="fas fa-briefcase"></i> Work Experience</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">GIS Technician</div>
      <div class="cv-sub">Canada Post Corporation</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Managing spatial data and delivery implementation scenarios within the Ottawa region.</li>
          <li>Providing technical GIS support for strategic route planning and logistics coordination.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2025 – Present</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Project Lead & Spatial Analyst</div>
      <div class="cv-sub">International Operations (USA / Mexico / Canada)</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Directed multi-disciplinary teams in high-stakes environments, managing logistics, safety protocols, and operational timelines.</li>
          <li>Led large-scale GIS and LiDAR data integration projects to support environmental and spatial modeling.</li>
          <li>Coordinated stakeholder relations and regulatory compliance across diverse jurisdictional frameworks.</li>
          <li>Synthesized technical geospatial findings into actionable reports for non-technical leadership.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2018 – 2024</div>
  </div>

<div class="cv-wrapper">  
  <h2 class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</h2>
  
  <div class="cv-title" style="margin-top: 1rem; border-bottom: 1px solid rgba(128,128,128,0.1); padding-bottom: 2px; margin-bottom: 0.5rem;">
    The Graduate Center, CUNY
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        PhD in Anthropological Archaeology
      </div>
    </div>
    <div class="cv-date">2025</div>
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        MPhil in Anthropological Archaeology
      </div>
    </div>
    <div class="cv-date">2024</div>
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        MA in Anthropological Archaeology
      </div>
    </div>
    <div class="cv-date">2022</div>
  </div>

  <div class="cv-title" style="margin-top: 1rem; border-bottom: 1px solid rgba(128,128,128,0.1); padding-bottom: 2px; margin-bottom: 0.5rem;">
    Hunter College, CUNY
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        Advanced Certificate in Geographic Information Systems
      </div>
    </div>
    <div class="cv-date">2022</div>
  </div>

  <div class="cv-title" style="margin-top: 1rem; border-bottom: 1px solid rgba(128,128,128,0.1); padding-bottom: 2px; margin-bottom: 0.5rem;">
    University of Calgary
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        MA in Archaeology
      </div>
    </div>
    <div class="cv-date">2020</div>
  </div>

  <div class="cv-title" style="margin-top: 1rem; border-bottom: 1px solid rgba(128,128,128,0.1); padding-bottom: 2px; margin-bottom: 0.5rem;">
    University of New Brunswick
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        BA (First Class Honours) in Archaeology and Philosophy
      </div>
    </div>
    <div class="cv-date">2017</div>
  </div>
  <h2 class="cv-section-title"><i class="fas fa-tools"></i>Skills</h2>

  <div class="skill-group">
    <span class="skill-label">Geospatial Intelligence</span>
    <div class="skill-grid">
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">ArcGIS Pro</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">QGIS</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Lidar Processing</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Spatial Statistics</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Hydrological Modeling</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Drone Photogrammetry</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Asisoft Metashape</span>
      </a>
    </div>
    <br>
    <span class="skill-label"> Project & Management</span>
     <div class="skill-grid">
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Agile (Scrum) </span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Operational Logistics</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Stakeholder Engagement</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Risk Mitigation</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Technical Writing</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Database Administration</span>
      </a>
    </div>
    <br>
    <span class="skill-label">Programming & Systems </span>
     <div class="skill-grid">
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Python</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">R</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Git</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Markdown</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Jekyll</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">VS Code</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">Remote Data Collection</span>
      </a>
    </div>
       <br>
    <span class="skill-label">Languages</span>
     <div class="skill-grid">
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">English</span>
      </a>
      <a class="skill-badge">
        <i class="fas fa-certificate"></i>
        <span class="badge-text">French</span>
      </a>
    </div>
  </div>
</div>

<div class="cv-download-links">
  <a href="{{ base_path }}/files/MilleyCV_Professional.pdf" class="btn btn--primary">Download Professional CV (PDF)</a>
</div>

<div style="margin-top: 3rem; padding: 1.5rem; background: rgba(128,128,128,0.05); border-radius: 8px; text-align: center; border: 1px solid rgba(128,128,128,0.1);">
  Looking my for my academic qualificaitons? <a href="/cv-json" style="font-weight: 600; text-decoration: underline;"> Visit my Academic CV</a>.
</div>
