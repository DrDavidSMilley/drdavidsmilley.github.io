---
layout: single
title: "Professional Resume"
permalink: /cv-professional/
author_profile: true
---
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css">
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet">

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

  /* Structured Minimalist Skills Layout */
  .skills-container {
    margin-top: 1rem;
  }
  .skill-group-row {
    display: flex;
    margin-bottom: 1rem;
    padding-bottom: 0.8rem;
    border-bottom: 1px solid rgba(128,128,128,0.1);
  }
  .skill-group-row:last-child {
    border-bottom: none;
  }
  .skill-row-label {
    flex: 0 0 180px;
    margin-right: 20px;       /* Adds breathing room before the grid items */
    font-weight: 800;
    font-size: 1rem;
    color: var(--heading-color, inherit);
    padding-top: 4px;
  }
  .skill-row-grid {
    flex: 1;
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 8px;
  }
  .compact-tag {
    display: flex;
    align-items: center;     
    justify-content: left;  
    background: transparent;
    border-left: 2px solid var(--primary-color, rgba(128,128,128,0.3));
    padding: 4px 0 4px 8px;
    font-size: 0.85rem;
    font-weight: normal;
    min-height: 36px;         
    box-sizing: border-box;
  }
  .compact-tag i {
    color: var(--primary-color, inherit);
    opacity: 0.7;
    margin-right: 8px;
    font-size: 0.8rem;
    flex-shrink: 0;           
  }
  
  /* Responsive grid scaling */
  @media (max-width: 850px) {
    .skill-row-grid { grid-template-columns: repeat(2, 1fr); } 
  }
  @media (max-width: 650px) {
    .skill-group-row { flex-direction: column; gap: 6px; margin-bottom: 1.2rem; }
    .skill-row-label { flex: none; margin-right: 0; padding-bottom: 2px; border-bottom: 1px solid rgba(128,128,128,0.1); }
    .skill-row-grid { grid-template-columns: repeat(2, 1fr); margin-top: 4px; }
  }
  @media (max-width: 450px) {
    .skill-row-grid { grid-template-columns: 1fr; }             
  }
</style>

<div class="cv-wrapper">
  <h2 class="cv-section-title"><i class="fas fa-briefcase"></i> Work Experience</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Geographic Information Systems Analyst</div>
      <div class="cv-sub">Canada Post Corporation</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Maintained data integrity across federal enterprise datasets valued more than $500M, operating within a Crown corporation’s regulated IT environment.</li>
          <li>Collaborated with a 10-person cross-functional team to validate and deploy new tools through a staged production rollout, managing risk and stakeholder sign-off at each phase gate.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">Dec 2025 – Present</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Project Manager – Poverty Point Initiative</div>
      <div class="cv-sub">The City University of New York, Graduate Center</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Initiated a three-year project, supported by a 250,000USD funding package, at a UNESCO World Heritage Site, defining deliverables, milestones, and resource requirements.</li>
          <li>Developed and maintained project timelines and budget, ensuring on-time and on-budget delivery.</li>
          <li>Authored and successfully secured competitive funding proposals to finance all project phases.</li>
          <li>Procured all necessary permits and regulatory authorisations from state and local government bodies prior to project commencement.</li>
          <li>Established an environmental baseline through review of existing site reports and data, informing project scope and risk assessment.</li>
          <li>Ensured full regulatory compliance throughout project execution, adhering to all site-specific legal and environmental requirements.</li>
          <li>Led a cross-functional field team through three field phases, directing work allocation and ensuring execution.</li>
          <li>Managed operational logistics including travel, accommodation, and equipment procurement for remote-site deployments.</li>
          <li>Monitored and reassessed project risks in a dynamic field environment, adjusting schedule, scope, and objectives in response to emerging conditions.</li>
          <li>Conducted a drone survey of Poverty Point using DJI drone to create a 3D-photogrammetry model of site landscape and structure.</li>
          <li>Performed extensive landscape modeling in ArcGIS Pro and QGIS using lidar satellite imagery to reconstruct prehistoric hydrology, movement, and visibility.</li>
          <li>Authored project reports for institutional stakeholders, translating and communicating technical findings.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2022 – 2025</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Adjunct Professor</div>
      <div class="cv-sub">The City University of New York, Brooklyn College</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Delivered technical presentations to audiences of 30+, adapting communication style to varied levels of technical literacy.</li>
          <li>Managed team dynamics, resolved interpersonal conflict, and facilitated structured collaboration across diverse groups.</li>
          <li>Designed performance evaluation frameworks and delivered structured, goal-oriented feedback.</li>
          <li>Provided individualized coaching and mentorship in regular one-on-one sessions.</li>
          <li>Led rapid process redesign under operational constraints, migrating all workflows to remote delivery within a compressed timeline.</li>
          <li>Designed and maintained a collaborative online platform to centralize communications, resources, and stakeholder engagement.</li>
          <li>Fostered an inclusive team environment to maximise participation, engagement, and collaboration.</li>
          <li>Structured regular group problem-solving sessions and peer-review workflows to build team capacity and collaborative practice.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2021 – 2023</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Genealogical Analyst – The Van Cortlandt Park Project</div>
      <div class="cv-sub">The City University of New York, Brooklyn College</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Collaborated with experts and stakeholders throughout New York City, and performed archival and genealogical research, to uncover the lives of the residents of the historic plantation within New York City.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2021</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Project Manager – Yaxnohcah Archaeological Project</div>
      <div class="cv-sub">The University of Calgary</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Managed a remote field project in Campeche, Mexico, coordinating operations in a logistically complex environment with no on-site institutional support.</li>
          <li>Directed a diverse cross-functional team including Indigenous community members, managing cross-cultural communication and on-site task delivery.</li>
          <li>Developed complex 3D models using ArcMap and ArcGIS Pro to investigate the environmental impact of Maya canals on the local hydrology.</li>
          <li>Independently secured external project funding through competitive grant applications.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2018 – 2019</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Graduate Teaching Assistant</div>
      <div class="cv-sub">The University of Calgary / The City University of New York</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Administered lectures, graded course material, organized weekly meetings, and held office hours to assist or mentor students across multiple academic terms.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2017 – 2021</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Software Developer and Research Analyst – STRATUM</div>
      <div class="cv-sub">The University of New Brunswick</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Transcribed and analyzed oral interviews to determine user needs for the mobile application.</li>
          <li>Consulted with Indigenous stakeholders to assess concerns and desired app features.</li>
          <li>Performed User Acceptance Testing (UAT) to evaluate app’s performance in real-world scenarios.</li>
          <li>Prepared grant proposal and conference presentation to market product and secure funding.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2021</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Laboratory & Archival Imaging Assistant</div>
      <div class="cv-sub">The University of New Brunswick</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Digitized thousands of archival records, field reports, and historic documents, performed quality control, and managed image databases to modernise preservation workflows.</li>
          <li>Digitally reconstructed an archaeological site using CorelDRAW to model and analyze indigenous dwellings, artifact distributions, and temporal change.</li>
          <li>Digitally restored and enhanced artifact and excavation photos using Adobe Photoshop.</li>
          <li>Organized, documented, and curated precontact and historic artifact collections to facilitate relocation of collection.</li>
          <li>Prepared museum exhibit for public display at Greenspoint Lighthouse.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2013 – 2016</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</h2>
  
  <div class="cv-title" style="margin-top: 1rem; border-bottom: 1px solid rgba(128,128,128,0.1); padding-bottom: 2px; margin-bottom: 0.5rem;">
    The Graduate Center, CUNY
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        PhD in Anthropology (Archaeology)
      </div>
    </div>
    <div class="cv-date">2026</div>
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        MPhil in Anthropology
      </div>
    </div>
    <div class="cv-date">2024</div>
  </div>
  <div class="cv-entry" style="margin-bottom: 0.5rem;">
    <div class="cv-main" style="padding-left: 15px;">
      <div class="cv-sub" style="font-style: italic; font-weight: normal; font-size: 0.95rem;">
        MA in Anthropology
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
        BA (First-Class Joint-Honours) in Archaeology and Philosophy (4.0 GPA)
      </div>
    </div>
    <div class="cv-date">2017</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-tools"></i> Skills & Expertise</h2>

  <div class="skills-container">
    <div class="skill-group-row">
      <div class="skill-row-label">Project Management</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fas fa-file-invoice"></i>Stakeholder Reporting</span>
        <span class="compact-tag"><i class="fas fa-project-diagram"></i>Budget & Schedule</span>
        <span class="compact-tag"><i class="fas fa-balance-scale"></i>Regulatory Compliance</span>
        <span class="compact-tag"><i class="fas fa-file-signature"></i>Permit Procurement</span>
        <span class="compact-tag"><i class="fas fa-shield-alt"></i>Risk Assessment</span>
      </div>
    </div>
    <div class="skill-group-row">
      <div class="skill-row-label">Geospatial Software and Data</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fa-solid fa-map"></i>ArcMap</span>
        <span class="compact-tag"><i class="fas fa-map-marked-alt"></i>ArcGIS Pro</span>
        <span class="compact-tag"><i class="fas fa-globe-americas"></i>QGIS</span>
        <span class="compact-tag"><i class="fas fa-terminal"></i>ArcPy Scripting</span>
        <span class="compact-tag"><i class="fas fa-cubes"></i>Agisoft Metashape</span>
        <span class="compact-tag"><i class="fa-solid fa-layer-group"></i>ENVI</span>
        <span class="compact-tag"><i class="fa-solid fa-database"></i>ESRI Geodatabases</span>
        <span class="compact-tag"><i class="fa-solid fa-table-cells-large"></i>Raster Processing</span>
        <span class="compact-tag"><i class="ri-barcode-line"></i>LiDAR</span>
        <span class="compact-tag"><i class="fa-solid fa-satellite"></i>Landsat</span>
      </div>
    </div>
    <div class="skill-group-row">
      <div class="skill-row-label">Systems & Infrastructure</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fa-solid fa-server"></i>Ubuntu & Windows Server</span>
        <span class="compact-tag"><i class="fas fa-network-wired"></i>SSH / RDP Protocols</span>
        <span class="compact-tag"><i class="fab fa-git-alt"></i>Git & GitHub</span>
        <span class="compact-tag"><i class="fas fa-code"></i>Jekyll & Liquid</span>
        <span class="compact-tag"><i class="fa-solid fa-database"></i>FileMaker Pro</span>
        <span class="compact-tag"><i class="fas fa-tools"></i>Hardware assembly</span>
        <span class="compact-tag"><i class="fa-solid fa-bug"></i>Diagnosis and Repair</span>        
        <span class="compact-tag"><i class="fab fa-linux"></i>Linux</span>
        <span class="compact-tag"><i class="fa-brands fa-windows"></i>Windows</span>
        <span class="compact-tag"><i class="fa-brands fa-apple"></i>MacOS</span>
      </div>
    </div>
    <div class="skill-group-row">
      <div class="skill-row-label">Field Operations</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fas fa-helicopter"></i>UAV / Drone Survey</span>
        <span class="compact-tag"><i class="fas fa-route"></i>Remote Site Logistics</span>
        <span class="compact-tag"><i class="fas fa-leaf"></i>Environmental Baseline</span>
      </div>
    </div>
    <div class="skill-group-row">
      <div class="skill-row-label">Office & Productivity</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="far fa-file-word"></i>MS Office Suite</span>
        <span class="compact-tag"><i class="fab fa-google"></i>Google Workspace</span>
        <span class="compact-tag"><i class="fas fa-square-root-alt"></i>LaTeX Formatting</span>
        <span class="compact-tag"><i class="fa-solid fa-bezier-curve"></i>CorelDraw</span>
        <span class="compact-tag"><i class="fa-solid fa-image"></i>Adobe Photoshop</span>
      </div>
    </div>
    <div class="skill-group-row">
      <div class="skill-row-label">Languages</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fas fa-comment"></i>English (Native)</span>
        <span class="compact-tag"><i class="fas fa-comments"></i>French (Bilingual)</span>
      </div>
    </div>
  </div>
</div>

<div class="cv-download-links">
  <a href="{{ base_path }}/files/MilleyCV_Professional.pdf" class="btn btn--primary">Download Professional CV (PDF)</a>
</div>

<div style="margin-top: 3rem; padding: 1.5rem; background: rgba(128,128,128,0.05); border-radius: 8px; text-align: center; border: 1px solid rgba(128,128,128,0.1);">
  Looking for my academic qualifications? <a href="/cv-json" style="font-weight: 600; text-decoration: underline;">Visit my Academic CV</a>.
</div>