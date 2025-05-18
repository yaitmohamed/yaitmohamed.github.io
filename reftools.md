<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reference Tools - Yassine Ait Mohamed</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #555;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      font-weight: 300;
      background-color: #f5f5f5;
    }
    
    .left-column {
      width: 30%;
      padding-right: 40px;
    }
    
    .right-column {
      width: 65%;
    }
    
    h1 {
      font-size: 28px;
      margin-bottom: 5px;
      color: #2c3e50;
      font-weight: 600;
    }
    
    h2 {
      font-size: 24px;
      margin-top: 30px;
      margin-bottom: 15px;
      font-weight: 500;
      color: #2c3e50;
    }
    
    h4 {
      font-size: 22px;
      margin-top: 30px;
      margin-bottom: 15px;
      font-weight: 500;
      color: #2c3e50;
      padding-bottom: 8px;
      border-bottom: 1px solid #ddd;
    }
    
    p {
      margin-bottom: 15px;
      font-size: 16px;
      color: #444;
      line-height: 1.7;
    }
    
    a {
      color: #3498db;
      text-decoration: none;
    }
    
    a:hover {
      color: #e74c3c;
      text-decoration: underline;
    }
    
    .nav-link {
      display: block;
      margin-bottom: 15px;
      font-size: 17px;
      font-weight: 500;
      color: #2c3e50;
    }
    
    .reference-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    
    .reference-card {
      background-color: white;
      border-radius: 4px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
      padding: 20px;
      transition: all 0.2s ease;
      display: flex;
      flex-direction: column;
      border-left: 3px solid #3498db;
    }
    
    .reference-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      border-left-color: #e74c3c;
    }
    
    .reference-card h3 {
      font-size: 18px;
      margin-top: 0;
      margin-bottom: 10px;
      color: #2c3e50;
      font-weight: 500;
    }
    
    .reference-card p {
      font-size: 14px;
      color: #7f8c8d;
      margin-bottom: 15px;
      flex-grow: 1;
    }
    
    .reference-card .tag {
      display: inline-block;
      background-color: #f0f0f0;
      color: #7f8c8d;
      padding: 3px 8px;
      border-radius: 3px;
      font-size: 12px;
      margin-right: 5px;
      margin-bottom: 5px;
    }
    
    .reference-link {
      display: block;
      text-align: center;
      background-color: #3498db;
      color: white;
      padding: 8px 12px;
      border-radius: 4px;
      margin-top: 15px;
      font-weight: 500;
      transition: background-color 0.2s ease;
    }
    
    .reference-link:hover {
      background-color: #2980b9;
      text-decoration: none;
      color: white;
    }
    
    .entry {
      position: relative;
      margin-bottom: 25px;
      padding-left: 20px;
      border-left: 3px solid #3498db;
      padding-bottom: 5px;
    }
    
    .entry:hover {
      background-color: #f1f1f1;
      border-left-color: #e74c3c;
    }
    
    .entry h3 {
      font-size: 18px;
      margin-top: 0;
      margin-bottom: 5px;
      color: #2c3e50;
    }
    
    .entry p {
      margin-bottom: 5px;
    }
    
    .entry .description {
      font-style: italic;
      color: #7f8c8d;
      font-size: 14px;
    }
    
    @media (max-width: 768px) {
      .left-column, .right-column {
        width: 100%;
        padding-right: 0;
      }
      
      .reference-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <div class="left-column">
    <h1>Yassine Ait Mohamed</h1>
    <p>
      PhD Student<br>
      Department of Mathematics<br>
      University of Sherbrooke
    </p>
    
    <div class="navigation">
      <a href="index.html" class="nav-link">Home</a>
      <a href="research.html" class="nav-link">Research</a>
      <a href="talks.html" class="nav-link">Talks</a>
      <a href="cv.html" class="nav-link">CV</a>
      <a href="teaching.html" class="nav-link">Teaching</a>
      <a href="reftools.html" class="nav-link" style="color: #e74c3c;">Reference Tools</a>
    </div>
    
    <div style="margin-top: 30px;">
      <a href="https://www.usherbrooke.ca/" target="_blank">University of Sherbrooke</a><br>
      <a href="https://www.usmba.ac.ma/" target="_blank">Sidi Mohamed Ben Abdellah University</a>
    </div>
  </div>
  
  <div class="right-column">
    <h4>Reference Collection Tools</h4>
    
    <p>This page provides links to various reference collection and management tools that I have developed or found useful for my research. These resources focus primarily on tracking publications in symplectic geometry and related fields.</p>
    
    <h4>ArXiv Reference Trackers</h4>
    
    <div class="reference-grid">
      <div class="reference-card">
        <h3>Coisotropic Manifold Papers</h3>
        <p>A comprehensive database of research articles on coisotropic manifolds from 1975 to present, automatically updated weekly from arXiv.</p>
        <div>
          <span class="tag">Symplectic</span>
          <span class="tag">Coisotropic</span>
          <span class="tag">ArXiv</span>
        </div>
        <a href="coisotropic-database/index.html" class="reference-link">Access Database</a>
      </div>
      
      <div class="reference-card">
        <h3>Poisson Geometry Tracker</h3>
        <p>Collection of papers on Poisson geometry and related topics from ArXiv, updated monthly with visualization tools.</p>
        <div>
          <span class="tag">Poisson</span>
          <span class="tag">Geometry</span>
          <span class="tag">ArXiv</span>
        </div>
        <a href="poisson-tracker/index.html" class="reference-link">Access Database</a>
      </div>
      
      <div class="reference-card">
        <h3>Symplectic Dynamics</h3>
        <p>Papers on symplectic dynamics, Hamiltonian systems, and integrable systems from ArXiv, with categorization by subtopic.</p>
        <div>
          <span class="tag">Symplectic</span>
          <span class="tag">Dynamics</span>
          <span class="tag">Hamiltonian</span>
        </div>
        <a href="symplectic-dynamics/index.html" class="reference-link">Access Database</a>
      </div>
      
      <div class="reference-card">
        <h3>Quantum Geometry</h3>
        <p>Articles on quantization, quantum geometry, and quantum groups with connections to symplectic geometry.</p>
        <div>
          <span class="tag">Quantum</span>
          <span class="tag">Quantization</span>
          <span class="tag">Mathematical Physics</span>
        </div>
        <a href="quantum-geometry/index.html" class="reference-link">Access Database</a>
      </div>
    </div>
    
    <h4>Data Collection Tools</h4>
    
    <div class="entry">
      <h3>ArXiv Reference Collector</h3>
      <p>A Python tool for collecting, filtering, and organizing research papers from ArXiv based on customizable search criteria.</p>
      <p class="description">This tool allows automated weekly updates of specialized research databases.</p>
      <a href="https://github.com/your-username/arxiv-collector" target="_blank">GitHub Repository</a>
    </div>
    
    <div class="entry">
      <h3>Reference Database Generator</h3>
      <p>Scripts for generating searchable online interfaces for reference collections with interactive visualizations.</p>
      <p class="description">Create your own ArXiv reference tracker with these templates.</p>
      <a href="https://github.com/your-username/reference-database-generator" target="_blank">GitHub Repository</a>
    </div>
    
    <h4>External Resources</h4>
    
    <div class="entry">
      <h3>MathSciNet</h3>
      <p>Comprehensive database of mathematical literature provided by the American Mathematical Society.</p>
      <p class="description">Requires institutional subscription.</p>
      <a href="https://mathscinet.ams.org/" target="_blank">Visit MathSciNet</a>
    </div>
    
    <div class="entry">
      <h3>Zentralblatt MATH</h3>
      <p>Comprehensive database of mathematical literature collected by the European Mathematical Society.</p>
      <p class="description">Some free access available.</p>
      <a href="https://zbmath.org/" target="_blank">Visit Zentralblatt</a>
    </div>
    
    <div class="entry">
      <h3>arXiv.org</h3>
      <p>Open-access archive for scholarly articles in mathematics, physics, and related disciplines.</p>
      <p class="description">Primary source for my reference trackers.</p>
      <a href="https://arxiv.org/" target="_blank">Visit arXiv</a>
    </div>
  </div>
</body>
</html>
