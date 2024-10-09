<!-- README.md -->

<div class="about-me">
  <h1>About Me</h1>
  <p>Hi, I'm [Your Name], a 19th of May Computer Programming student with a passion for cyber security, online gaming, and coding.</p>
  <p>When I'm not busy coding away, you can find me exploring the latest security threats and vulnerabilities, dominating online gaming arenas, or reminiscing about my 8-year boxing career.</p>
</div>

<div class="interests">
  <h1>Interests</h1>
  <ul>
    <li>
      <i class="fas fa-lock"></i> Cyber Security
      <p>I'm fascinated by the cat-and-mouse game between hackers and security experts. I enjoy learning about the latest security threats and developing my skills to stay one step ahead.</p>
    </li>
    <li>
      <i class="fas fa-gamepad"></i> Online Gaming
      <p>Gaming is my go-to way to unwind. I'm a fan of strategy games and enjoy the thrill of competition with fellow gamers.</p>
    </li>
    <li>
      <i class="fas fa-code"></i> Coding
      <p>I'm passionate about writing clean, efficient code that solves real-world problems. I'm always looking to improve my skills and learn new programming languages.</p>
    </li>
    <li>
      <i class="fas fa-boxing-glove"></i> Boxing
      <p>With 8 years of boxing experience under my belt, I appreciate the discipline and focus required to succeed in the ring. I enjoy staying active and pushing myself to new limits.</p>
    </li>
    <li>
      <i class="fas fa-car"></i> Cars
      <p>I'm a car enthusiast and enjoy learning about the latest models, technologies, and innovations in the automotive industry.</p>
    </li>
  </ul>
</div>

<div class="skills">
  <h1>Skills</h1>
  <ul>
    <li>Programming languages: [list your programming languages, e.g., Python, Java, C++]</li>
    <li>Cyber security tools: [list any cyber security tools you're familiar with, e.g., Nmap, Burp Suite]</li>
    <li>Gaming platforms: [list your favorite gaming platforms, e.g., Steam, Xbox]</li>
  </ul>
</div>

<!-- Animasyon için CSS -->
<style>
  .about-me, .interests, .skills {
    margin-bottom: 20px;
  }

  .interests ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .interests li {
    margin-bottom: 10px;
  }

  .interests li i {
    margin-right: 10px;
  }

  .skills ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  /* Animasyon */
  .about-me, .interests, .skills {
    animation: fadeIn 2s;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>

<!-- Animasyon için JavaScript -->
<script>
  // Animasyon için bir fonksiyon oluşturun
  function animate() {
    // Animasyon için bir zamanlayıcı oluşturun
    setTimeout(function() {
      // Animasyon için bir efekt oluşturun
      document.querySelector('.about-me').style.transform = 'translateY(0)';
      document.querySelector('.interests').style.transform = 'translateY(0)';
      document.querySelector('.skills').style.transform = 'translateY(0)';
    }, 1000);
  }

  // Fonksiyonu çağırın
  animate();
</script>
