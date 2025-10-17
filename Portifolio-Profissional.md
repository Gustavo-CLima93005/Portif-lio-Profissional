<!doctype html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="description" content="Portfólio de Gustavo Cardoso Lima" />
    <meta
      name="author"
      content="Gustavo Cardoso Lima, Desenvolvedor Full-Stack & Analista de Dados"
    />
    <title>Gustavo C. Lima | Desenvolvedor Full-Stack & Analista de Dados</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB"
      crossorigin="anonymous"
    />
    <meta name="theme-color" content="#FF4500" />
    <link
      href="https://fonts.googleapis.com/css?family=Playfair+Display:700,900&display=swap"
      rel="stylesheet"
    />

    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }
      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
      .b-example-divider {
        width: 100%;
        height: 3rem;
        background-color: #0000001a;
        border: solid rgba(0, 0, 0, 0.15);
        border-width: 1px 0;
        box-shadow:
          inset 0 0.5em 1.5em #0000001a,
          inset 0 0.125em 0.5em #00000026;
      }
      .b-example-vr {
        flex-shrink: 0;
        width: 1.5rem;
        height: 100vh;
      }
      .bi {
        vertical-align: -0.125em;
        fill: currentColor;
      }
      .btn-bd-primary {
        --bd-violet-bg: #ff4500;
        --bd-violet-rgb: 255, 69, 0;
        --bs-btn-font-weight: 600;
        --bs-btn-color: var(--bs-white);
        --bs-btn-bg: var(--bd-violet-bg);
        --bs-btn-border-color: var(--bd-violet-bg);
        --bs-btn-hover-color: var(--bs-white);
        --bs-btn-hover-bg: #ff8c00;
        --bs-btn-hover-border-color: #ff8c00;
        --bs-btn-focus-shadow-rgb: var(--bd-violet-rgb);
        --bs-btn-active-color: var(--bs-btn-hover-color);
        --bs-btn-active-bg: #ff8c00;
        --bs-btn-active-border-color: #ff8c00;
      }
      .bd-mode-toggle {
        z-index: 1500;
      }
      .bd-mode-toggle .bi {
        width: 1em;
        height: 1em;
      }
      .bd-mode-toggle .dropdown-menu .active .bi {
        display: block !important;
      }
      body {
        background-color: #f8f8ff;
      }
      a {
        color: #ff8c00;
        text-decoration: none;
      }
      a:hover {
        color: #ff4500;
        text-decoration: underline;
      }
      .border-bottom {
        border-bottom-color: #ffd700 !important;
      }
      hr {
        border-color: #ffd700;
        opacity: 0.5;
      }
      .blog-header-logo {
        font-family: 'Playfair Display', Georgia, 'Times New Roman', serif;
        font-size: 2.25rem;
        color: #ff4500;
      }
      .blog-header-logo:hover {
        color: #ff8c00;
        text-decoration: none;
      }
      h1,
      h2,
      h3 {
        color: #ff4500;
      }
      h4,
      h5,
      h6 {
        color: #ff8c00;
      }
      h1,
      h2,
      h3,
      h4,
      h5,
      h6 {
        font-family: 'Playfair Display', Georgia, 'Times New Roman', serif;
      }
      .flex-auto {
        flex: 0 0 auto;
      }
      .h-250 {
        height: 250px;
      }
      @media (min-width: 768px) {
        .h-md-250 {
          height: 250px;
        }
      }
      .blog-post {
        margin-bottom: 4rem;
      }
      .blog-post-meta {
        margin-bottom: 1.25rem;
        color: #ff8c00;
        font-style: italic;
      }
      .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
        background-color: #f8f8ff;
      }
      .nav-scroller .nav-link {
        color: #ff8c00;
      }
      .nav-scroller .nav-link:hover {
        color: #ff4500;
      }
      .nav-scroller .nav-link.active {
        color: #ff4500;
        font-weight: bold;
        border-bottom-color: #ff4500;
      }
      .bg-body-secondary {
        background-color: #f0e68c !important;
        border: 1px solid #ffd700;
      }
      .col-md-4 .bg-body-tertiary {
        background-color: #f8f8ff !important;
        border: 1px solid #ffd700;
        box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
      }
      footer.bg-body-tertiary {
        background-color: #f0e68c !important;
        border-top: 2px solid #ffd700;
        border-bottom: 0;
        border-left: 0;
        border-right: 0;
      }
      footer.bg-body-tertiary a {
        color: #ff4500;
        font-weight: bold;
      }
      footer.bg-body-tertiary a:hover {
        color: #ff8c00;
      }
    </style>
  </head>
  <body>
    <svg xmlns="http://www.w3.org/2000/svg" class="d-none">
      <symbol
        id="aperture"
        fill="none"
        stroke="currentColor"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        viewBox="0 0 24 24"
      >
        <circle cx="12" cy="12" r="10"></circle>
        <path
          d="M14.31 8l5.74 9.94M9.69 8h11.48M7.38 12l5.74-9.94M9.69 16L3.95 6.06M14.31 16H2.83m13.79-4l-5.74 9.94"
        ></path>
      </symbol>
      <symbol id="cart" viewBox="0 0 16 16">
        <path
          d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .49.598l-1 5a.5.5 0 0 1-.465.401l-9.397.472L4.415 11H13a.5.5 0 0 1 0 1H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5zM3.102 4l.84 4.479 9.144-.459L13.89 4H3.102zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2zm7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"
        ></path>
      </symbol>
      <symbol id="chevron-right" viewBox="0 0 16 16">
        <path
          fill-rule="evenodd"
          d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"
        ></path>
      </symbol>
    </svg>

    <div class="container">
      <header class="border-bottom lh-1 py-3">
        <div class="row flex-nowrap justify-content-between align-items-center">
          <div class="col-4 pt-1">
            <span class="link-secondary"
              >Desenvolvedor Full-Stack & Analista de Dados</span
            >
          </div>
          <div class="col-4 text-center">
            <a
              class="blog-header-logo text-body-emphasis text-decoration-none"
              href="#"
              >Gustavo Cardoso Lima</a
            >
          </div>
          <div class="col-4 d-flex justify-content-end align-items-center">
            <span class="text-body-secondary"
              >Vila Velha, ES, Brazil</span
            >
          </div>
        </div>
      </header>
      <div class="nav-scroller py-1 mb-3 border-bottom">
        <nav class="nav nav-underline justify-content-between">
          <a class="nav-item nav-link link-body-emphasis active" href="#inicio"
            >Início</a
          >
          <a class="nav-item nav-link link-body-emphasis" href="#experiencia"
            >Experiência Profissional</a
          >
          <a class="nav-item nav-link link-body-emphasis" href="#graduacoes"
            >Graduações</a
          >
          <a class="nav-item nav-link link-body-emphasis" href="#contatos"
            >Contatos</a
          >
        </nav>
      </div>
    </div>
    <main class="container">
      <div
        class="p-4 p-md-5 mb-4 rounded text-body-emphasis bg-body-secondary"
        id="inicio"
      >
        <div class="col-lg-12 px-0">
          <h1 class="display-4 fst-italic">Gustavo Cardoso Lima</h1>
          <p class="lead my-3">
            Desenvolvedor Full-Stack & Analista de Dados
          </p>
          <p class="lead mb-0">
            Profissional com 19 anos de experiência (fictícia) em desenvolvimento
            de software e análise de dados. Especialista em Python e JavaScript,
            com foco em soluções escaláveis para o setor financeiro. Buscando uma
            posição desafiadora para aplicar conhecimentos em Big Data e Machine
            Learning.
          </p>
        </div>
      </div>
      <div class="row g-5">
        <div class="col-md-8">
          <h3 class="pb-4 mb-4 fst-italic border-bottom" id="experiencia">
            Experiência Profissional
          </h3>
          <article class="blog-post">
            <h2 class="display-5 link-body-emphasis mb-1">
              Engenheiro de Dados Pleno na DataSec Solutions (Fictício)
            </h2>
            <p class="blog-post-meta">
              25/10/2015 – Presente
            </p>
            <p>
              Desenvolvimento e manutenção de pipelines ETL/ELT para ingestão de
              dados em tempo real. Otimização de consultas em bancos de dados
              NoSQL e suporte à equipe de Machine Learning.
            </p>
            <h4>Destaques:</h4>
            <ul>
              <li>
                Desenvolvi um pipeline de processamento de dados usando Apache
                Spark e Python, reduzindo o tempo de processamento de dados em
                50%.
              </li>
              <li>
                Implementei um sistema de monitoramento de qualidade de dados com
                Grafana e Prometheus.
              </li>
              <li>
                Colaborei na arquitetura de um Data Lake na AWS (S3, Redshift)
                para armazenamento eficiente de petabytes de dados.
              </li>
            </ul>
          </article>
          <hr />
          <article class="blog-post">
            <h2 class="display-5 link-body-emphasis mb-1">
              Desenvolvedor Front-end Júnior na Innovate Web Studio (Fictício)
            </h2>
            <p class="blog-post-meta">08/04/2004 – 20/11/2006</p>
            <p>
              Responsável por criar e manter interfaces de usuário para
              aplicações web com foco em acessibilidade e responsividade,
              utilizando React e JavaScript.
            </p>
            <h4>Destaques:</h4>
            <ul>
              <li>
                Reescrevi o código CSS utilizando styled-components, melhorando a
                modularidade e reuso do código.
              </li>
              <li>
                Participei da implementação de testes unitários com Jest,
                elevando a cobertura para 85%.
              </li>
              <li>
                Trabalhei em metodologias ágeis (Scrum), garantindo a entrega
                contínua de novas functionalities.
              </li>
            </ul>
          </article>

          <h3 class="pb-4 mb-4 fst-italic border-bottom" id="graduacoes">
            Graduações
          </h3>
          <article class="blog-post">
            <h2 class="display-5 link-body-emphasis mb-1">
              Bacharelado em Ciência da Computação
            </h2>
            <p class="blog-post-meta">
              Universidade Federal do Espírito Santo (UFES) (Fictício) -
              Conclusão: 01/08/2001
            </p>
            <p>Conclusão com Distinção Acadêmica (Magna Cum Laude).</p>
          </article>
          <hr />
          <article class="blog-post">
            <h2 class="display-5 link-body-emphasis mb-1">
              Pós-Graduação em Análise e Desenvolvimento de Sistemas
            </h2>
            <p class="blog-post-meta">
              FAESA Campus Vitória - Conclusão: Dez/1996
            </p>
            <p>Bolsista Nossa Bolsa.</p>
          </article>

          </div>
        <div class="col-md-4">
          <div class="position-sticky" style="top: 2rem">
            <div class="p-4 mb-3 bg-body-tertiary rounded">
              <h4 class="fst-italic">Sobre</h4>
              <p class="mb-0">
                Especialista em Python e JavaScript, com 19 anos de experiência
                (fictícia). Foco em soluções de Big Data, ETL/ELT e Machine
                Learning para o setor financeiro.
              </p>
              <hr />
              <p class="mb-0">
                <small class="text-body-secondary"
                  >Localização: Vila Velha, ES, Brazil</small
                >
              </p>
            </div>
            <div class="p-4" id="contatos">
              <h4 class="fst-italic">Contatos e Redes</h4>
              <ol class="list-unstyled">
                <li>
                  <strong>Email:</strong>
                  <a href="mailto:gtavo.jobs@gmail.com"
                    >gtavo.jobs@gmail.com</a
                  >
                </li>
                <li>
                  <strong>Telefone:</strong>
                  <a href="tel:+5527988975318">+55 (27) 98897-5318</a>
                </li>
                <li>
                  <a href="https://github.com/Gustavo-CLima93005"
                    >GitHub: Gustavo-CLima93005</a
                  >
                </li>
                <li>
                  <a href="https://linkedin.com/in/gustavo-cardoso-lima"
                    >LinkedIn: /in/gustavo-cardoso-lima</a
                  >
                </li>
                <li>
                  <a href="#">Instagram (Adicionado a Pedido)</a>
                </li>
              </ol>
            </div>
          </div>
        </div>
      </div>
    </main>
    <footer class="py-5 text-center text-body-secondary bg-body-tertiary">
      <p>
        Template modificado de
        <a href="https://getbootstrap.com/">Bootstrap</a>.
      </p>
      <p class="mb-0"><a href="#">Voltar ao topo</a></p>
    </footer>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-Y7Tf6C/hHqTq5j4O1+A3lXqY9aR/l+D/KzU5sQ8wS7hW5E/YtJc/IqJ/oE4F3uW4"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
