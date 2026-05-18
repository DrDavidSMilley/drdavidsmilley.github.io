---
layout: archive
title: "Curriculum Vitae"
permalink: /cv-json/
author_profile: true
---
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css">
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet">

<style>
  /* Global Layout matching the Professional Resume */
  .cv-wrapper { line-height: 1.4; font-size: 0.95rem; color: var(--text-color, inherit); max-width: 800px; }
  .cv-section-title { display: flex; align-items: center; margin: 2rem 0 0.5rem; padding-bottom: 4px; border-bottom: 2px solid var(--primary-color, rgba(128,128,128,0.5)); text-transform: uppercase; font-size: 1.05rem; font-weight: 800; letter-spacing: 1px; color: var(--heading-color, inherit); }
  .cv-section-title i { margin-right: 8px; font-size: 0.95rem; opacity: 0.8; color: var(--primary-color, inherit); }
  
  /* Shared Entry Layouts */
  .cv-entry { display: flex; justify-content: space-between; margin-bottom: 0.8rem; }
  .cv-main { flex: 1; padding-right: 15px; }
  .cv-title { font-weight: 800; font-size: 1rem; margin: 0; color: var(--heading-color, inherit); }
  .cv-sub { font-style: italic; opacity: 0.9; font-size: 0.9rem; margin-top: 1px; color: var(--primary-color, inherit); }
  .cv-date { font-weight: 700; min-width: 110px; text-align: right; opacity: 0.7; font-size: 0.85rem; font-feature-settings: "tnum"; }
  
  /* Details & Nested Summaries */
  .cv-details { margin-top: 2px; }
  .cv-details-toggle { font-size: 0.75rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.5px; color: var(--primary-color, #494e52); cursor: pointer; list-style: none; display: inline-flex; align-items: center; padding: 2px 6px; background: rgba(128,128,128,0.08); border-radius: 3px; transition: background 0.2s ease; }
  .cv-details-toggle::-webkit-details-marker { display: none; }
  .cv-details-toggle:hover { background: rgba(128,128,128,0.15); }
  .cv-details-toggle::before { content: '\25B6'; font-size: 0.55rem; margin-right: 5px; transition: transform 0.2s; }
  .cv-details[open] .cv-details-toggle::before { transform: rotate(90deg); }
  .cv-details[open] .cv-details-toggle { margin-bottom: 4px; }
  
  /* Dissertation & Thesis Quote Box Style */
  .cv-summary { font-size: 0.85rem; margin: 4px 0 0 0; padding: 4px 10px; background: rgba(128,128,128,0.05); border-left: 3px solid var(--primary-color, rgba(128,128,128,0.3)); font-style: italic; }
  
  /* Content Bullet Lists */
  .cv-list { margin: 4px 0 0 1rem; padding: 0; list-style: none; font-size: 0.85rem; }
  .cv-list li { margin-bottom: 4px; text-align: justify; position: relative; }
  .cv-list li::before { content: "•"; color: var(--primary-color, inherit); position: absolute; left: -1rem; font-weight: bold; }

  /* Structured Minimalist Skills Layout */
  .skills-container { margin-top: 1rem; }
  .skill-group-row { display: flex; margin-bottom: 1rem; padding-bottom: 0.8rem; border-bottom: 1px solid rgba(128,128,128,0.1); }
  .skill-group-row:last-child { border-bottom: none; }
  .skill-row-label { flex: 0 0 180px; margin-right: 20px; font-weight: 800; font-size: 1rem; color: var(--heading-color, inherit); padding-top: 4px; }
  .skill-row-grid { flex: 1; display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; }
  .compact-tag { display: flex; align-items: center; justify-content: left; background: transparent; border-left: 2px solid var(--primary-color, rgba(128,128,128,0.3)); padding: 4px 0 4px 8px; font-size: 0.85rem; font-weight: normal; min-height: 36px; box-sizing: border-box; }
  .compact-tag i { color: var(--primary-color, inherit); opacity: 0.7; margin-right: 8px; font-size: 0.8rem; flex-shrink: 0; }
  
  /* Centered Download Links Footer Block */
  .cv-download-links { text-align: center; width: 100%; margin-bottom: 1.5rem; display: block; }
  .cv-download-links .btn { display: inline-block !important; float: none !important; }

  /* Responsive Grid Adaptations */
  @media (max-width: 850px) {
    .skill-row-grid { grid-template-columns: repeat(2, 1fr); } 
  }
  @media (max-width: 650px) {
    .cv-entry { flex-direction: column-reverse; } 
    .cv-date { text-align: left; margin-bottom: 2px; font-size: 0.8rem; }
    .skill-group-row { flex-direction: column; gap: 6px; margin-bottom: 1.2rem; }
    .skill-row-label { flex: none; margin-right: 0; padding-bottom: 2px; border-bottom: 1px solid rgba(128,128,128,0.1); }
    .skill-row-grid { grid-template-columns: repeat(2, 1fr); margin-top: 4px; }
  }
  @media (max-width: 450px) {
    .skill-row-grid { grid-template-columns: 1fr; }             
  }

  /* Theme Engine Integration Styles */
  html[data-theme="dark"] .cv-details-toggle { background: #262321; color: #c98a5d; border-color: #3d3935; }
  html[data-theme="dark"] .cv-details-toggle:hover { background: #3d3935; color: #dcd3c1; border-color: #c98a5d; }
  html[data-theme="dark"] .cv-summary { background: #262321; border-left-color: #c98a5d; }
</style>

<div class="cv-wrapper">

  <h2 class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">The Graduate Center, CUNY</div>
      <div class="cv-sub">PhD in Anthropological Archaeology</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">Dissertation</summary>
        <p class="cv-summary">Dissertation: Sensing Prehistory: A Framework Reconciling Scientific Modeling and Human Experience through Affordance Theory.</p>
      </details>
    </div>
    <div class="cv-date">2025</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">The Graduate Center, CUNY</div>
      <div class="cv-sub">MPhil in Anthropological Archaeology</div>
    </div>
    <div class="cv-date">2024</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">The Graduate Center, CUNY</div>
      <div class="cv-sub">MA in Anthropological Archaeology</div>
    </div>
    <div class="cv-date">2022</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Hunter College, CUNY</div>
      <div class="cv-sub">Advanced Certificate in Geographic Information Systems</div>
    </div>
    <div class="cv-date">2022</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">University of Calgary</div>
      <div class="cv-sub">MA in Archaeology</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">Thesis</summary>
        <p class="cv-summary">Thesis: Hydrological Landscape Analysis of a Sinuous Depression, Yaxnohcah, Mexico.</p>
      </details>
    </div>
    <div class="cv-date">2020</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">University of New Brunswick</div>
      <div class="cv-sub">BA (First Class Honours) in Archaeology and Philosophy</div>
    </div>
    <div class="cv-date">2017</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-briefcase"></i> Work Experience</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">GIS Analyst</div>
      <div class="cv-sub">Canada Post Corporation</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Managing spatial data and delivery implementation scenarios within the Ottawa region.</li>
          <li>Providing technical GIS support for strategic route planning and logistics.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2025 – Present</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Field Technician</div>
      <div class="cv-sub">True North Archaeological Services</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Conducted archaeological field surveys and technical assessments.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2024 – 2024</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Research Assistant</div>
      <div class="cv-sub">University of Calgary</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Curated an extensive EndNote database and assembled references under tight deadlines for journal publications.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2018 – 2019</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Lab Assistant</div>
      <div class="cv-sub">University of New Brunswick Anthropology Lab</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Coordinated and digitized decades-old records and field reports and cross-referenced these reports with artifact collections.</li>
          <li>Created site reconstruction using CorelDRAW, modelling indigenous dwellings, artifact distributions, and temporal change.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2016 – 2016</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Research Assistant</div>
      <div class="cv-sub">Atlantic Salmon Museum</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Photographed and catalogued artifact collections. Prepared museum display.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2015 – 2015</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Lab Assistant</div>
      <div class="cv-sub">University of New Brunswick Anthropology Lab</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Curated archaeological collection, updating incomplete catalogue entries. Digitally restored and enhanced artifact and excavation photos using Adobe Photoshop.</li>
          <li>Digitally rephotographed numerous artifacts and digitized paper archival records.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2014 – 2015</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Archival Imaging Assistant</div>
      <div class="cv-sub">UNB Electronic Text Centre</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Digitized archival documents, performed quality control, and managed image database.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2014 – 2014</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Volunteer Lab Assistant</div>
      <div class="cv-sub">University of New Brunswick Anthropology Lab</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Curated archaeological collection, extensively reorganizing precontact and historic artifact collections. Relocated artifacts to new storage containers.</li>
          <li>Verified all artifacts were catalogued and identified incomplete entries.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2013 – 2014</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-chalkboard-teacher"></i> Teaching</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Digging the Past (ANTH1400/CLAS3210)</div>
      <div class="cv-sub">Adjunct Professor, Brooklyn College (BC), CUNY</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Created an open and accepting course space that accommodated a variety of learning styles: Provided space for self-expression through directed introduction activities, space for blog-style biographies, and created space for all students to share and express ideas.</li>
          <li>Held one-on-one meetings with every student to develop a connection and understand their individual needs in terms of feeling safe and learning.</li>
          <li>Encouraged peer-based learning by dedicating time every session for group discussions and problem solving, assigning peer-reviewed projects, and creating online discussion boards to provide an additional venue for the exchange of ideas and collaborations.</li>
          <li>Designed assignments and examinations that provided flexibility for students to articulate their ideas.</li>
          <li>Favoured written answers over multiple choice as students are better able to communicate their understanding using this medium.</li>
          <li>Assigned an ‘unessay’ rather than a traditional essay. This assignment allowed students to research a traditional essay topic but placed no restrictions on the medium and methods they used to communicate their research findings.</li>
          <li>Provided extensive feedback on graded work and allowed students the option of oral rather than written examinations.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2021 – 2023</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Urban Archaeology (ANTH3420)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, Brooklyn College (BC), CUNY</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Administered lectures, graded course material, assisted in organizing sessions, held office hours and mentored students.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2021/2 – 2021/12</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Digging the Past (ANTH1400/CLAS3210)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, Brooklyn College (BC), CUNY</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Helped adapt course material to Zoom-based learning following the onset of the COVID-19 pandemic.</li>
          <li>Administered lectures, ran and oversaw all online non-lecture components of the course material, assisted in organizing classes, held office hours, and mentored students.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2020 – 2021</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Introduction to Archaeology (ANTH103)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, Queen’s College, CUNY</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Administered lectures, graded course material, and assisted in organizing sessions.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2019 – 2020</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">History of Anthropology (ANTH361)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, University of Calgary (UC)</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Assisted in organizing sessions, creating, administering, and grading assignments and examinations, held office hours and mentored students.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2019</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">The Incas and Their Successors (ARKY357)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, University of Calgary (UC)</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Assisted in organizing sessions, creating, administering, and grading assignments and examinations, held office hours and mentored students.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2018</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Ancient Civilizations (ARKY325)</div>
      <div class="cv-sub">Graduate Teaching Assistantship, University of Calgary (UC)</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Assisted in organizing sessions, creating, administering, and grading assignments and examinations, held office hours and mentored students.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2017</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-flask"></i> Research Projects</h2>
  
  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Poverty Point Research Project (Louisiana, USA)</div>
      <div class="cv-sub">Project Lead</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Directed a small team of researchers. Integrated GIS and phenomenology to examine prehistoric landscape use by complex hunter-gatherers, with an emphasis on hydrological modelling and spatial analysis.</li>
          <li>Established connections with local authorities and the community. Conducted drone and ground survey of the site and created a photogrammetry model using the imagery.</li>
          <li>Developed, planned, and performed a project combining experience-based learning with extensive GIS analysis.</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2023 – 2024</div>
  </div>

  <div class="cv-entry">
    <div class="cv-main">
      <div class="cv-title">Proyecto Arqueológico Yaxnohcah (Yaxnohcah, Mexico)</div>
      <div class="cv-sub">Graduate Researcher and Project Lead</div>
      <details class="cv-details">
        <summary class="cv-details-toggle">View Details</summary>
        <ul class="cv-list">
          <li>Developed a GIS and archaeological research project to explore the agricultural canal and directed a small team, working closely with the local and Indigenous community.</li>
          <li>Conducted extensive GIS-based hydrological analyses and field excavations. Applied for and received funding for the project.</li>
          <li>Created high-quality maps, visualizations, and reports, and communicated findings at conferences and publications (thesis and reports).</li>
        </ul>
      </details>
    </div>
    <div class="cv-date">2018 – 2018</div>
  </div>

  <h2 class="cv-section-title"><i class="fas fa-tools"></i> Technical Expertise</h2>

  <div class="skills-container">
    <div class="skill-group-row">
      <div class="skill-row-label">GIS & Remote Sensing</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fas fa-map-marked-alt"></i>ArcGIS Pro</span>
        <span class="compact-tag"><i class="fa-solid fa-map"></i>ArcGIS Desktop</span>
        <span class="compact-tag"><i class="fa-solid fa-globe"></i>ArcGIS Online</span>
        <span class="compact-tag"><i class="fas fa-globe-americas"></i>QGIS</span>
        <span class="compact-tag"><i class="fa-solid fa-layer-group"></i>ENVI</span>
        <span class="compact-tag"><i class="ri-barcode-line"></i>Lidar Analysis</span>
        <span class="compact-tag"><i class="fas fa-cubes"></i>Drone Photogrammetry (Agisoft Metashape)</span>
      </div>
    </div>
    
    <div class="skill-group-row">
      <div class="skill-row-label">Software & Analysis</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fa-solid fa-chart-simple"></i>R</span>
        <span class="compact-tag"><i class="fab fa-python"></i>Python</span>
        <span class="compact-tag"><i class="fas fa-square-root-alt"></i>LaTeX</span>
        <span class="compact-tag"><i class="fas fa-network-wired"></i>Spatial Analysis (Network, Hydrological)</span>
        <span class="compact-tag"><i class="fa-solid fa-database"></i>Database Management (EndNote, FileMaker Pro)</span>
        <span class="compact-tag"><i class="fa-solid fa-image"></i>Adobe Photoshop</span>
        <span class="compact-tag"><i class="fa-solid fa-bezier-curve"></i>CorelDRAW</span>
      </div>
    </div>

    <div class="skill-group-row">
      <div class="skill-row-label">Hardware & Systems</div>
      <div class="skill-row-grid">
        <span class="compact-tag"><i class="fas fa-helicopter"></i>DJI Mini 3 Pro</span>
        <span class="compact-tag"><i class="fas fa-helicopter"></i>DJI Mini SE</span>
        <span class="compact-tag"><i class="fab fa-linux"></i>Ubuntu Linux</span>
        <span class="compact-tag"><i class="fa-brands fa-windows"></i>Windows</span>
        <span class="compact-tag"><i class="fa-brands fa-apple"></i>MacOS</span>
      </div>
    </div>
  </div>
  
  <br>
  <div class="cv-download-links">
    <a href="/files/MilleyCV.pdf" class="btn btn--primary">Download CV as PDF</a>
  </div>
</div>