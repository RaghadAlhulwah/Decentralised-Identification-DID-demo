<h1>DID & VC Trust Flow – Interactive Web Demo</h1>

<h3>Overview</h3>
<p>This project is an interactive web-based demonstration designed to explain the trust flow of <strong>Decentralized Identifiers (DIDs)</strong> and <strong>Verifiable Credentials (VCs)</strong>.<br>
It walks the viewer step-by-step through the process of:</p>
<ul>
  <li>Generating DIDs.</li>
  <li>Publishing DID Documents.</li>
  <li>Issuing and signing Verifiable Credentials.</li>
  <li>Resolving DIDs.</li>
  <li>Verifying credential signatures.</li>
</ul>
<p>This work is created as part of the Topic Presentation requirements for the Advanced web technologies course providing a simple interactive interface to visually demonstrate the fundamentals of decentralized identity.</p>
<hr>
<h3>Project Goal</h3>
<p>The demo simplifies decentralized identity concepts by visually showing how DIDs and VCs work together without relying on a central authority.<br>
It demonstrates:
<ul>
  <li>How DIDs are created and linked to public keys</li>
  <li>How VCs (e.g., digital diplomas) are signed</li>
  <li>How verifiers check authenticity using DID Documents</li>
  <li>How trust is built without centralized authorities</li>
</ul>

This helps students understand how decentralized identity systems operate in real-world scenarios.</p>
<hr>
<h3>Tech Stack</h3>
<ul>
  <li>HTML</li>
  <li>CSS & TailwindCSS</li>
  <li>JavaScript</li>
  <li>Font Awesome</li>
  <li>Lightweight cryptography simulation </li>
</ul>
<hr>
<h3>Key Features</h3>
<ol>
  <li><strong>Generate & Publish DID</strong></li>
  <p>Simulates DID creation, key generation, and publishing DID Documents.</p>
  <li><strong>Issue & Sign a Verifiable Credential</strong></li>
  <p>Produces a VC in JWT-like format and signs it using a private key.</p>
  <li><strong>Resolve DID & Present Credential</strong></li>
  <p>The verifier retrieves the corresponding public key from the DID Document.</p>
  <li><strong>Verify Credential Signature</strong></li>
  <p>Displays verification results and makes each step visible for learning.</p>
</ol>
  <hr>
  <h3>UI Highlights</h3>
  <ul>
    <li>Clean, modern layout using TailwindCSS.</li>
    <li>Tabs for Registry / Wallet / Verification.</li>
    <li>Highlighted credential structure.</li>
    <li>Console-style logs to guide users through each step.</li>
  </ul>
<hr>
<h3>How to Run the Demo</h3>
<p>Since the code is self-contained within a single HTML file, you have two easy ways to run it :<br>
  <ol>
    <li><strong>Live via GitHub Pages (Recommended):</strong></li>
    <p>You can view the interactive demo instantly via the GitHub Pages link:<br> <strong><a href="https://raghadalhulwah.github.io/Decentralised-Identification-DID-demo/">DID & VC Trust Flow Demo</strong></p>
    <li><strong>Local Setup:</strong></li>
      <ol>
        <li>Download or clone the project.</li> 
        <li>Open index.html in any browser.</li> 
        <li>No backend or server setup required.</li></p>
      </ol>
  </ol>
</p>
<hr>
<h3>Usage Flow</h3>
<ol>
  <li>Click <strong>Generate & Publish DID</strong></li>
  <li>View DID Document under the <strong>Registry tab</strong></li>
  <li>Click <strong>Issue & Sign VC</strong></li>
  <li>Click <strong>Resolve DID & Present VC</strong></li>
  <li>Click <strong>Verify Signature</strong></li>
</ol>
<p><em>This flow demonstrates the full lifecycle of decentralized identity creation, credential issuance, presentation, and signature verification.</em></p>
