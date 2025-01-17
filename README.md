<h1>EV Web</h1>
<p>This guide explains how to create and run a React-based frontend for an Electric Vehicle (EV) Website, showcasing photos and videos of electric vehicles.</p>
<h2>Steps to Run the React App:</h2>
<ol>
  <li>
    <b>Install Node.js:</b>
    <p>Ensure you have Node.js installed on your system. Download it from <a href="https://nodejs.org" target="_blank">https://nodejs.org</a>.</p>
  </li>
  <li>
    <b>Navigate to the Project Directory:</b>
    <pre><code>cd electric-vehicle-website</code></pre>
  </li>
  <li>
    <b>Build the EV Website:</b>
    <p>Customize the app by editing files in the <code>src</code> folder. You can create components for:</p>
    <ul>
      <li>Homepage with a hero section featuring videos of EVs</li>
      <li>Photo Gallery showcasing different EV models</li>
      <li>About Us section describing the company</li>
      <li>Features and Benefits of EVs</li>
      <li>Contact Form for inquiries</li>
    </ul>
  </li>
  <li>
    <b>Integrate Photos and Videos:</b>
    <p>Use <code>img</code> tags or video components to embed media.</p>
    <pre><code>
      <img src="/path-to-image.jpg" alt="Electric Vehicle" />
      <video controls>
        <source src="/path-to-video.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </code></pre>
  </li>
  <li>
    <b>Connect to a Backend (Optional):</b>
    <p>If you need dynamic content (e.g., new models or media), integrate a backend API.</p>
    <pre><code>fetch('https://api.example.com/ev-models')
  .then(response => response.json())
  .then(data => console.log(data));</code></pre>
  </li>
  <li>
    <b>Build for Production:</b>
    <p>When your app is ready for deployment, run:</p>
    <pre><code>npm run build</code></pre>
    <p>This creates an optimized production build in the <code>build</code> folder.</p>
  </li>
</ol>

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
