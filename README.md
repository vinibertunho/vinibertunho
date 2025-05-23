```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Olá Interativo</title>
  <style>
    body {
      background: #18181b;
      color: #fafafa;
      font-family: 'Segoe UI', sans-serif;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    button {
      background: linear-gradient(90deg, #38bdf8 0%, #6366f1 100%);
      color: #fff;
      border: none;
      border-radius: 8px;
      padding: 12px 32px;
      font-size: 1.25rem;
      cursor: pointer;
      transition: background 0.3s;
      margin-top: 32px;
    }
    button:hover {
      background: linear-gradient(90deg, #6366f1 0%, #38bdf8 100%);
    }
    .ola {
      opacity: 0;
      font-size: 2.5rem;
      margin-top: 32px;
      transition: opacity 1s;
      animation: bounce 1s 1;
      color: #38bdf8;
      font-weight: bold;
    }
    .ola.show {
      opacity: 1;
    }
    @keyframes bounce {
      0% { transform: translateY(-50px);}
      60% { transform: translateY(10px);}
      80% { transform: translateY(-5px);}
      100% { transform: translateY(0);}
    }
  </style>
</head>
<body>
  <button id="btn-ola">Clique para dizer Olá 👋</button>
  <div id="ola" class="ola">Olá, seja bem-vindo!</div>

  <script>
    const btn = document.getElementById('btn-ola');
    const ola = document.getElementById('ola');
    ola.classList.remove('show');
    btn.addEventListener('click', () => {
      ola.classList.add('show');
      ola.style.animation = "bounce 1s";
      setTimeout(() => {
        ola.style.animation = "";
      }, 1000);
    });
  </script>
</body>
</html>
```
---

<h3 align="center">Sobre mim</h3>

<p align="center">
  👨‍💻 Foco total em <b>HTML5, CSS3 e JavaScript</b> — interfaces modernas e responsivas.<br>
  ☁️ Técnico em <b>Computação em Nuvem</b> (Azure e Google Cloud).<br>
  📚 Sempre aprendendo, sempre compartilhando.<br>
  🤝 Aberto para colaboração e trocas de conhecimento!
</p>

---

<h3 align="center">Estatísticas & Tecnologias</h3>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vinibertunho&layout=compact&langs_count=8&theme=dracula" alt="Linguagens mais usadas"/>
</p>

---

<h3 align="center">Contato</h3>

<p align="center">
  <a href="mailto:vbertunho@gamil.com">vbertunho@gmail.com</a> • 
  <a href="www.linkedin.com/in/vinicius-marcos-bertunho-da-silva-85172134a">LinkedIn</a>
</p>
