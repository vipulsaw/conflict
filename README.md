## Architecture Diagram

<svg width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <!-- Architecture components -->
  <rect x="50" y="150" width="120" height="60" rx="5" fill="#61dafb" stroke="#333" />
  <text x="110" y="180" text-anchor="middle" fill="#000">React Frontend</text>
  
  <rect x="350" y="150" width="120" height="60" rx="5" fill="#3c873a" stroke="#333" />
  <text x="410" y="180" text-anchor="middle" fill="#fff">Node.js Backend</text>
  
  <rect x="650" y="150" width="120" height="60" rx="5" fill="#13aa52" stroke="#333" />
  <text x="710" y="180" text-anchor="middle" fill="#fff">MongoDB Atlas</text>
  
  <!-- Animated arrows -->
  <path id="path1" d="M170 180 L350 180" stroke="#666" stroke-width="2" fill="none">
    <animate attributeName="stroke-dashoffset" from="100" to="0" dur="2s" repeatCount="indefinite" />
  </path>
  <path id="path2" d="M470 180 L650 180" stroke="#666" stroke-width="2" fill="none">
    <animate attributeName="stroke-dashoffset" from="100" to="0" dur="2s" repeatCount="indefinite" />
  </path>
  
  <!-- Animated dots representing data flow -->
  <circle r="5" fill="red">
    <animateMotion path="M170 180 L350 180" dur="2s" repeatCount="indefinite" />
  </circle>
  <circle r="5" fill="green">
    <animateMotion path="M470 180 L650 180" dur="2s" repeatCount="indefinite" />
  </circle>
</svg>
