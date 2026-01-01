<h1 align="center">Mohamed Ashraf</h1>

<h2 align="center">
  <span id="typing"></span>
</h2>

<script>
  const titles = ["Front-End Developer"];
  let currentTitle = 0;
  let currentIndex = 0;
  let isDeleting = false;

  const typingElement = document.getElementById("typing");

  function typeEffect() {
    const text = titles[currentTitle];
    let displayedText = text.substring(0, currentIndex);
    typingElement.textContent = displayedText;

    if (!isDeleting && currentIndex < text.length) {
      currentIndex++;
    } else if (isDeleting && currentIndex > 0) {
      currentIndex--;
    }

    if (currentIndex === text.length) {
      setTimeout(() => isDeleting = true, 1000);
    } else if (currentIndex === 0 && isDeleting) {
      isDeleting = false;
    }

    setTimeout(typeEffect, 120);
  }

  typeEffect();
</script>

<style>
  #typing {
    font-weight: bold;
    font-size: 28px;
    color: #FF5733;
    font-family: 'Courier New', monospace;
    border-right: 2px solid #FF5733;
    padding-right: 5px;
    text-align: center;
    display: inline-block;
    animation: blink 0.7s infinite;
  }

  @keyframes blink {
    50% { border-color: transparent; }
  }
</style>

---

<h4 align="center">
My name is Mohamed, and I am a Front-End Developer from Egypt. I specialize in building modern, responsive, and user-focused websites using **HTML, CSS, Bootstrap, Tailwind CSS, SCSS, JavaScript, TypeScript, React, and Next.js**. I’m passionate about creating interfaces that are both visually appealing and highly functional, with a strong focus on performance, accessibility, and user experience.<br><br>
I enjoy solving challenges, improving UI interactions, and making websites more engaging through clean and maintainable code. I am always learning new technologies and techniques to stay updated and continue growing professionally in the field of web development.
</h4>

---

<h2 align="center">I code with</h2>

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="42" />
  <img width="14"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="42" />
</div>

---

<h2 align="center">Social Media</h2>

<div align="center">
  <a href="https://www.linkedin.com/in/your-linkedin/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="56" height="43" />
  </a>
  <a href="https://wa.me/your-number" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/whatsapp/default.svg" width="56" height="43" />
  </a>
  <a href="https://www.facebook.com/your-facebook/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg" width="56" height="43" />
  </a>
  <a href="https://www.instagram.com/your-instagram/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="56" height="43" />
  </a>
  <a href="https://t.me/your-telegram" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/telegram/default.svg" width="56" height="43" />
  </a>
</div>
