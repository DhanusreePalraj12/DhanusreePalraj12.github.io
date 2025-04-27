<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dhanusree Palraj - AI Engineer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #000;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }
    .container, .about, .certificates {
      display: none;
      padding: 3rem;
    }
    .container.active, .about.active, .certificates.active {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    .content {
      max-width: 800px;
      padding: 1rem;
    }
    .content h1, .content h2 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    .content h3 {
      font-size: 1.75rem;
      margin-bottom: 1rem;
    }
    .content p, .about p {
      font-size: 1.1rem;
      line-height: 1.6;
    }
    .content button {
      margin-top: 1.5rem;
      padding: 0.8rem 1.5rem;
      font-size: 1rem;
      background-color: #1c6e9e;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .about, .certificates {
      flex-direction: column;
    }
    .socials {
      width: 100%;
      text-align: center;
      margin-top: 2rem;
    }
    .socials a {
      margin: 0 15px;
      display: inline-block;
    }
    .socials img {
      width: 40px;
      height: 40px;
      vertical-align: middle;
    }
    .certificate-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 1.5rem;
      width: 100%;
      justify-content: center;
    }
    .certificate-grid div {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .certificate-grid img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .certificate-grid p {
      text-align: center;
      margin-top: 0.5rem;
      font-size: 1rem;
      line-height: 1.4;
    }
  </style>
</head>
<body>

<header>
  <div><strong>Dhanusree Palraj</strong></div>
  <nav>
    <a onclick="showSection('home')">Home</a>
    <a onclick="showSection('about')">About</a>
    <a onclick="showSection('certificates')">Certificates</a>
    <a onclick="showSection('projects')">Projects</a>
  </nav>
</header>

<!-- Home Section -->
<div class="container active" id="home">
  <div class="content">
    <h2>Hi, I am Dhanusree</h2>
    <h3>AI Engineer</h3>
    <p>
      A skilled Artificial Intelligence professional with a strong base learning in AI development and advanced security solutions. I practiced to train and fine-tune models on real-world datasets.
      I specialize in developing innovative tools to address real-world security challenges and have led impactful ideas for execution. Passionate about mentoring, I guide aspiring AI developers while driving innovation in Artificial Intelligence.
    </p>
    <a href="files/Dhanusree Palraj.RESUME.pdf"><button>Resume</button></a>
  </div>

  <!-- Social Links -->
  <div class="socials">
    <a href="mailto:dhanusree975@gmail.com" target="_blank" title="Email">
      <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email">
    </a>
    <a href="https://wa.me/919597076279" target="_blank" title="WhatsApp">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </a>
    <a href="https://github.com/DhanusreePalraj12?tab=stars" target="_blank" title="GitHub">
      <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
    </a>
    <a href="https://www.linkedin.com/in/dhanusree-palraj-493097298" target="_blank" title="LinkedIn">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
    </a>
    <a href="https://leetcode.com/u/DhanusreePalraj/" target="_blank" title="LeetCode">
      <img src="https://cdn.iconscout.com/icon/free/png-256/leetcode-3521542-2944960.png" alt="LeetCode">
    </a>
  </div>
</div>

<!-- About Section -->
<div class="about" id="about">
  <h2>About Me</h2>
  <p>
    I'm Dhanusree, I am an aspiring AI Engineer with a strong passion for building intelligent systems 
    that solve real-world problems. My academic and personal projects have centered around  AI enhancement ,machine learning, data analytics, and automation, 
    where I’ve explored model training, neural networks, and predictive analysis. I enjoy working at the intersection of data and innovation, constantly learning new technologies to stay ahead in the evolving field of artificial intelligence. With a commitment to continuous growth and a curiosity-driven mindset, I aim to contribute to cutting-edge AI solutions that drive meaningful change.
  </p>
</div>

<!-- Certificates Section -->
<div class="certificates" id="certificates">
  <h2>Certificates</h2>
  <p>Here are some of my course completion and workshop certificates:</p>
  <div class="certificate-grid">
    <div>
      <img src="https://github.com/DhanusreePalraj12/DhanusreePalraj12.github.io/issues/2" alt="workshop 1" />
      
      <p>This certificate is awarded by IIT Madras Shaastra Events 2025 for my participation in the Blockchain development workshop, held in 2024.</p>
    </div>
    <div>
      <img src="images/Screenshot 2024-12-20 204241.png" alt="Workshop 2" />
      <p>Certificate for completion of an Ignite learning challenge on AI solutions by MICROSOFT AZURE, held in 2024</p>
    </div>
    <div>
      <img src="images/Screenshot 2025-04-24 184049.png" alt="Certificate 3" />
      <p>Certificate for the completion of Networking and Web Technology using the online learning platform INFOSYS</p>
    </div>
    <div>
      <img src="images/Screenshot 2025-04-24 205819.png" alt="Certificate 4" />
      <p>Certificate for the completion of a course AWS Certified Developer</p>
    </div>
    <div>
      <img src="images/Screenshot 2025-04-25 121529.png" alt="Certificate 5" />
      <p>Certificate for completing Engineering modeling fundamentals CAD 2D/3D</p>
    </div>
    <div>
      <img src="images/Screenshot 2025-04-25 121841.png" alt="Certificate 6" />
      <p>Certificate of challenge completion on Microsoft Copilot for Security by MICROSOFT AZURE</p>
    </div>
    <div>
      <img src="images/Screenshot 2025-04-25 121704.png" alt="Certificate 7" />
      <p>Certificate for completing mining fundamentals using AI tools by Clonis learning platform</p>
    </div>
  </div>
</div>

<script>
  function showSection(sectionId) {
    document.getElementById('home').classList.remove('active');
    document.getElementById('about').classList.remove('active');
    document.getElementById('certificates').classList.remove('active');
    document.getElementById(sectionId).classList.add('active');
  }
</script>

</body>
</html>
