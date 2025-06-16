`portifolio-psiquiatra.html`
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portfólio Psiquiatra - Dra. Laura Laport Venâncio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: #fff;
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    a {
      color: #ffd166;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #f4a261;
    }
    header {
      background: rgba(0,0,0,0.25);
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    header h1 {
      font-weight: 700;
      font-size: 2.8rem;
      margin-bottom: 0.3rem;
      letter-spacing: 1px;
      user-select: none;
    }
    header p {
      font-weight: 300;
      font-size: 1.2rem;
      font-style: italic;
      margin-top: 0;
      user-select: none;
    }
    main {
      flex-grow: 1;
      max-width: 900px;
      margin: 3rem auto 4rem auto;
      background: rgba(255 255 255 / 0.1);
      border-radius: 10px;
      padding: 2rem 3rem;
      box-shadow: 0 8px 18px rgba(0,0,0,0.3);
      backdrop-filter: blur(8px);
    }
    section {
      margin-bottom: 3rem;
    }
    section h2 {
      font-weight: 700;
      font-size: 2rem;
      border-bottom: 3px solid #ffd166;
      padding-bottom: 0.3rem;
      margin-bottom: 1.2rem;
      user-select: none;
    }
    .about p, .services ul, .credentials ul, .testimonials blockquote {
      font-weight: 300;
      font-size: 1.1rem;
      line-height: 1.7;
    }
    .services ul, .credentials ul {
      list-style-type: disc;
      margin-left: 1.5rem;
    }
    .testimonials blockquote {
      background: rgba(255 255 255 / 0.15);
      border-left: 5px solid #ffd166;
      padding: 1rem 1.5rem;
      margin: 1rem 0;
      font-style: italic;
      color: #fffbf0;
      position: relative;
    }
    .testimonials blockquote:before {
      content: "“";
      font-size: 3rem;
      position: absolute;
      top: -10px;
      left: 10px;
      color: #ffd166;
      font-weight: 700;
    }
    .testimonial-author {
      text-align: right;
      margin-top: 0.5rem;
      font-weight: 500;
      font-style: normal;
      color: #ffd166;
      user-select: none;
    }
    form {
      max-width: 400px;
      margin-top: 1rem;
      display: flex;
      flex-direction: column;
    }
    form label {
      font-weight: 500;
      margin-bottom: 0.3rem;
      user-select: none;
    }
    form input, form textarea, form button {
      padding: 0.8rem;
      margin-bottom: 1rem;
      font-size: 1rem;
      border-radius: 5px;
      border: none;
      outline: none;
      font-family: 'Poppins', sans-serif;
      resize: none;
      transition: background-color 0.3s ease;
    }
    form input, form textarea {
      background: rgba(255 255 255 / 0.9);
      color: #333;
    }
    form textarea {
      min-height: 100px;
    }
    form input:focus, form textarea:focus {
      background: #ffd166;
      color: #222;
    }
    form button {
      background: #ffd166;
      color: #222;
      font-weight: 700;
      cursor: pointer;
      transition: background-color 0.25s ease;
      border-radius: 30px;
      border: 2px solid transparent;
    }
    form button:hover {
      background: transparent;
      border-color: #ffd166;
      color: #ffd166;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-weight: 300;
      font-size: 0.9rem;
      color: #ddd;
      background: rgba(0,0,0,0.15);
      user-select: none;
    }
    @media (max-width: 600px) {
      main {
        padding: 1.5rem 1.5rem;
        margin: 2rem 1rem 3rem 1rem;
      }
      header h1 {
        font-size: 2rem;
      }
      section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Dr. Laura Laport Venâncio</h1>
    <p>Psiquiatra | Saúde Mental e Bem-estar</p>
  </header>
  <main>
    <section class="about" id="about">
      <h2>Sobre Mim</h2>
      <p>
        Sou Dra. Laura, psiquiatra, formada pela USP, dedicada ao cuidado integral da saúde mental. Acredito que cada indivíduo é único e merece um tratamento humanizado, baseado em evidências científicas e empatia. Minha missão é ajudar meus pacientes a encontrarem equilíbrio emocional e qualidade de vida.
      </p>
    </section>

    <section class="services" id="services">
      <h2>Serviços</h2>
      <ul>
        <li>Consultas psiquiátricas individuais</li>
        <li>Avaliação e tratamento de transtornos mentais</li>
        <li>Acompanhamento de pacientes com ansiedade e depressão</li>
        <li>Psicoterapia combinada com medicação quando necessário</li>
        <li>Orientação e suporte para familiares</li>
      </ul>
    </section>

    <section class="credentials" id="credentials">
      <h2>Formação e Credenciais</h2>
      <ul>
        <li>Graduado em Medicina pela Universidade Federal de São Paulo (UNIFESP)</li>
        <li>Residência em Psiquiatria no Hospital das Clínicas</li>
        <li>Especialização em Psicofarmacologia</li>
        <li>Membro da Associação Brasileira de Psiquiatria</li>
      </ul>
    </section>

    <section class="testimonials" id="testimonials">
      <h2>Depoimentos</h2>
      <blockquote>
        A atenção e sensibilidade do Dr. João fizeram toda a diferença na minha recuperação. Recomendo com confiança!
        <div class="testimonial-author">- Maria Fernandes</div>
      </blockquote>
      <blockquote>
        Profissional dedicado e atualizado. Sempre me senti acolhido e seguro durante todo o tratamento.
        <div class="testimonial-author">- Carlos Eduardo</div>
      </blockquote>
    </section>

    <section class="contact" id="contact">
      <h2>Contato</h2>
      <p>Entre em contato para agendar uma consulta ou tirar dúvidas.</p>
      <form>
        <label for="name">Nome</label>
        <input type="text" id="name" name="name" placeholder="Seu nome" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="seu@email.com" required />

        <label for="message">Mensagem</label>
        <textarea id="message" name="message" placeholder="Escreva sua mensagem aqui..." required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <footer>
    &copy; 2024 Dr. Laura Laport - Todos os direitos reservados
  </footer>
</body>
</html>

```
