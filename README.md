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
    <a href="https://github.com/DhanusreePalraj12/DhanusreePalraj12.github.io/raw/main/Dhanusree%20Palraj.RESUME.pdf"><button>Resume</button></a>
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
      <img src="https://private-user-images.githubusercontent.com/192505596/437956123-33bb04d4-a075-4e24-9ea6-fd88fd096c63.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjEyNjQsIm5iZiI6MTc0NTc2MDk2NCwicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTU2MTIzLTMzYmIwNGQ0LWEwNzUtNGUyNC05ZWE2LWZkODhmZDA5NmM2My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxMzM2MDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ZTMxMjE3ZmUzYTliMTYyNjNlYzJiZTNiNmJkMTQzNDFhMTMxMDJlNjZiMWI5MGE0OWM1NjhlN2Y2ZmQwODRhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.HDCb8Y6AbTD2OtwxkueG_sjqpRLTxtXkIXCtxG2HRPk" alt="workshop 1" />
      
      <p>This certificate is awarded by IIT Madras Shaastra Events 2025 for my participation in the Blockchain development workshop, held in 2024.</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437968520-3b38af23-bde0-4d41-b39f-59a28b9cf34b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjgwMzYsIm5iZiI6MTc0NTc2NzczNiwicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTY4NTIwLTNiMzhhZjIzLWJkZTAtNGQ0MS1iMzlmLTU5YTI4YjljZjM0Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxNTI4NTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05YzVhNTNhY2YzMmRkNzM1MWEwMTI2N2NmZGY5NjIxZDY1OTQxYjg5MTg0OTZiYzI4MWEwZjAxOTI5OGFmMGE0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.99V_GCSEHYcgC2sLAvMaJi34pnTZp8syQ7af5zP4d20" alt="Workshop 2" />
      <p>Certificate for completion of an Ignite learning challenge on AI solutions by MICROSOFT AZURE, held in 2024</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437959828-18861436-70d1-4d99-a39c-9bca6b79d59f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjE4MTcsIm5iZiI6MTc0NTc2MTUxNywicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTU5ODI4LTE4ODYxNDM2LTcwZDEtNGQ5OS1hMzljLTliY2E2Yjc5ZDU5Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxMzQ1MTdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01YmE0ODVjZjRlZjdiNjUzZDMyZDFjMjVmMTIyZDBlMmRhY2RkZTgxN2VhMGExNTZlNTE1NzQxNDcwNzc2NDk4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.UM2yEA-cVXjwNlYkwWfkJC42A2W5MZnCbSvkux-YnA4" alt="Certificate 3" />
      <p>Certificate for the completion of Networking and Web Technology using the online learning platform INFOSYS</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437968944-737bbeb9-bf0e-430e-9af0-c8f27bc505e1.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjgzMTYsIm5iZiI6MTc0NTc2ODAxNiwicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTY4OTQ0LTczN2JiZWI5LWJmMGUtNDMwZS05YWYwLWM4ZjI3YmM1MDVlMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxNTMzMzZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xYjgyOTYyNzY0YzZmYmVjMWQzODM2ZDc1MTM1YjZlY2Y0ZmNkOGVhYmM3Njc5Y2NkNWFkOWYyNmFkMjliNjZkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.36arDu4lDbMd9G2ZeOvCpSpP0HH73zGIUcTDQaKWxn0" alt="Certificate 4" />
      <p>Certificate for the completion of a course AWS Certified Developer</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437963992-b376b622-97bf-40da-bb99-bdad1afa1376.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjQ4NjIsIm5iZiI6MTc0NTc2NDU2MiwicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTYzOTkyLWIzNzZiNjIyLTk3YmYtNDBkYS1iYjk5LWJkYWQxYWZhMTM3Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxNDM2MDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMjY3OWE0MWQ1ZTcxN2ZkNDk3MzVhNDFiOWFjMzUzYjNjNDRiMDVhMzJiOGIxYzU1NmM1MzMzMDM1M2E4ZTUzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.WJdRMhX5VfxEgYLrpLP7-6ottA6rvr8DwS_vAD6Y0kk" alt="Certificate 5" />
      <p>Certificate for completing Engineering modeling fundamentals CAD 2D/3D</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437960453-c8b274a0-bfee-461d-964a-58e9ed7982b0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjI2NjMsIm5iZiI6MTc0NTc2MjM2MywicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTYwNDUzLWM4YjI3NGEwLWJmZWUtNDYxZC05NjRhLTU4ZTllZDc5ODJiMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxMzU5MjNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01MTI3YzI1ZmNhYmI1YTIxZjcwOTU0Y2E1NDRhNGMzMTE1NjFlNzAwNzVkOTZhM2IwODA0ZTk1NTgzZTM4MmEwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.dO-TGvFnT0qaNgD0PTqfPugsEuZqnJdTfdB7gqOQrnA" alt="Certificate 6" />
      <p>Certificate of challenge completion on Microsoft Copilot for Security by MICROSOFT AZURE</p>
    </div>
    <div>
      <img src="https://private-user-images.githubusercontent.com/192505596/437964246-c9eac648-f070-43e9-9366-aff0333ecbfa.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU3NjUwNjEsIm5iZiI6MTc0NTc2NDc2MSwicGF0aCI6Ii8xOTI1MDU1OTYvNDM3OTY0MjQ2LWM5ZWFjNjQ4LWYwNzAtNDNlOS05MzY2LWFmZjAzMzNlY2JmYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNDI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDQyN1QxNDM5MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iZTViNTg2MDA0NzVmMmM0Y2ViZGU4YjdmYTQ5NjI2YmUzOTIyZjE5MzdkNjk0MWY4NDY2NjI1MjdiMDJkNjdhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.gY3Iv-bOdLkXVS-G8OGP3aoGlcf3jk6lRw9NimP3LOE" alt="Certificate 7" />
      <p>Certificate for completing mining fundamentals using AI tools by Celonis learning platform</p>
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
