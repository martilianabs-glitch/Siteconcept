<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Concept Car 2000 - Home</title>
    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <!-- Google Fonts -->
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Header e Navbar -->
    <header>
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
          <a class="navbar-brand" href="#">Concept Car 2000</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div id="navbarNav" class="collapse navbar-collapse">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
              <li class="nav-item"><a class="nav-link" href="#sobre">Sobre Nós</a></li>
              <li class="nav-item"><a class="nav-link" href="#servicos">Serviços</a></li>
              <li class="nav-item"><a class="nav-link" href="#blog">Blog</a></li>
              <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </header>

    <!-- Seção Hero -->
    <section id="home" class="hero-section">
      <div class="container text-center text-white">
        <div class="row align-items-center" style="min-height: 100vh;">
          <div class="col">
            <h1 class="display-3">Concept Car 2000</h1>
            <p class="lead">
              Paixão por carros de luxo e serviços de alta qualidade.
            </p>
            <a class="btn btn-danger btn-lg" href="#servicos"
              >Confira nossos serviços</a
            >
          </div>
        </div>
      </div>
    </section>

    <!-- Seção Sobre Nós -->
    <section id="sobre" class="py-5 bg-light">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-6">
            <img
              src="https://images.unsplash.com/photo-1534030347302-2594f0a417e3?auto=format&fit=crop&w=800&q=80"
              alt="Sobre nós"
              class="img-fluid rounded shadow"
            />
          </div>
          <div class="col-md-6">
            <h2 class="mb-3">Sobre Nós</h2>
            <p>
              A Concept Car 2000 é especializada na reparação e manutenção de
              carros de luxo desde 2019. Nossa equipe possui vasta experiência e
              paixão por automóveis, garantindo um serviço impecável e cheio de
              sofisticação.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Seção Serviços -->
    <section id="servicos" class="py-5">
      <div class="container">
        <h2 class="text-center mb-5">Serviços</h2>
        <div class="row g-4">
          <div class="col-md-4">
            <div class="card h-100 border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1621928543303-f44632c1717f?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Polissage, Lustrage, Cire"
              />
              <div class="card-body">
                <h5 class="card-title">Polissage, Lustrage, Cire</h5>
                <p class="card-text">
                  Restauramos a beleza original do seu carro com nossos
                  serviços de polimento e enceramento.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card h-100 border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1549317022-a013989300c1?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="PPF"
              />
              <div class="card-body">
                <h5 class="card-title">PPF</h5>
                <p class="card-text">
                  Proteção de pintura com filme transparente, garantindo a
                  integridade da superfície.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card h-100 border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1551721434-849ddb592646?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Peças em Carbono"
              />
              <div class="card-body">
                <h5 class="card-title">
                  Fabrication de peças em carbono
                </h5>
                <p class="card-text">
                  Produzimos peças em fibra de carbono sob medida para o seu
                  veículo.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card h-100 border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1631953628781-c039f54b46b4?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Restauração de Couro"
              />
              <div class="card-body">
                <h5 class="card-title">Restauração de Couro</h5>
                <p class="card-text">
                  Serviços de restauração para interiores em couro, mantendo seu
                  carro sempre novo e elegante.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card h-100 border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1581382575275-53ad418569ef?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Conciergerie"
              />
              <div class="card-body">
                <h5 class="card-title">Conciergerie</h5>
                <p class="card-text">
                  Serviços personalizados para a sua conveniência e conforto.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Seção Blog -->
    <section id="blog" class="py-5 bg-light">
      <div class="container">
        <h2 class="text-center mb-5">Blog</h2>
        <div class="row g-4">
          <div class="col-md-6">
            <div class="card border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1489824904134-891ab643d84e?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Dicas de Manutenção"
              />
              <div class="card-body">
                <h5 class="card-title">Dicas de Manutenção</h5>
                <p class="card-text">
                  Descubra como manter seu carro em perfeito estado com nossas
                  dicas exclusivas.
                </p>
                <a href="#" class="btn btn-danger">Leia mais</a>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card border-0 shadow">
              <img
                src="https://images.unsplash.com/photo-1492144534655-6f22a2f307e0?auto=format&fit=crop&w=800&q=80"
                class="card-img-top"
                alt="Novidades Automotivas"
              />
              <div class="card-body">
                <h5 class="card-title">
                  Novidades do Mundo Automotivo
                </h5>
                <p class="card-text">
                  Fique por dentro das últimas notícias e inovações do setor
                  automobilístico.
                </p>
                <a href="#" class="btn btn-danger">Leia mais</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Seção de Contato -->
    <section id="contato" class="py-5">
      <div class="container">
        <h2 class="text-center mb-5">Contato</h2>
        <div class="row justify-content-center">
          <div class="col-md-8">
            <form>
              <div class="mb-3">
                <label for="nome" class="form-label">Nome</label>
                <input
                  type="text"
                  class="form-control"
                  id="nome"
                  placeholder="Seu nome"
                  required
                />
              </div>
              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input
                  type="email"
                  class="form-control"
                  id="email"
                  placeholder="Seu email"
                  required
                />
              </div>
              <div class="mb-3">
                <label for="mensagem" class="form-label">Mensagem</label>
                <textarea
                  class="form-control"
                  id="mensagem"
                  rows="5"
                  placeholder="Sua mensagem"
                  required
                ></textarea>
              </div>
              <button type="submit" class="btn btn-danger btn-lg">
                Enviar Mensagem
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-center text-white py-3">
      <div class="container">
        <p class="mb-0">
          © 2025 Concept Car 2000 | Todos os direitos reservados.
        </p>
      </div>
    </footer>

    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
/* style.css */

/* Tipografia e base */
body {
  font-family: 'Montserrat', sans-serif;
}

/* Hero Section */
.hero-section {
  background: url('https://images.unsplash.com/photo-1494905998304-203d10b3c8f4?auto=format&fit=crop&w=1770&q=80')
    no-repeat center center;
  background-size: cover;
  position: relative;
  color: #fff;
}

.hero-section::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.5);
}

.hero-section .container {
  position: relative;
  z-index: 2;
}

/* Efeitos de transição para os cards */
.card:hover {
  transform: scale(1.02);
  transition: transform 0.3s;
}

/* Espaçamentos customizados */
section {
  /* Ajuste os espaçamentos entre seções, se necessário */
}
