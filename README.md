# Siteconcept
site
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Concept Car 2000</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Concept Car 2000</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Concept Car 2000</h1>
        <p>Paixão por carros de luxo e serviços de alta qualidade.</p>
        <a href="#servicos" class="cta-button">Nossos Serviços</a>
    </section>

    <section id="sobre" class="container">
        <h2>Sobre Nós</h2>
        <p>A Concept Car 2000 é especializada na reparação e manutenção de carros de luxo desde 2019. Nossa equipe possui vasta experiência e paixão por automóveis, garantindo um serviço impecável.</p>
    </section>

    <section id="servicos" class="container">
        <h2>Serviços</h2>
        <div class="servicos-grid">
            <div class="servico">
                <img src="https://images.unsplash.com/photo-1621928543303-f44632c1717f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Polissage, Lustrage, Cire">
                <h3>Polissage, Lustrage, Cire</h3>
                <p>Restauramos a beleza original do seu carro com nossos serviços de polimento e enceramento.</p>
            </div>
            <div class="servico">
                <img src="https://images.unsplash.com/photo-1549317022-a013989300c1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="PPF">
                <h3>PPF</h3>
                <p>Proteção de pintura com filme transparente, garantindo a integridade da superfície.</p>
            </div>
            <div class="servico">
                <img src="https://images.unsplash.com/photo-1551721434-849ddb592646?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" alt="Fabrication de pièces en carbone">
                <h3>Fabrication de peças em carbono</h3>
                <p>Produzimos peças em fibra de carbono sob medida para o seu veículo.</p>
            </div>
            <div class="servico">
                <img src="https://images.unsplash.com/photo-1631953628781-c039f54b46b4?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" alt="Restauration cuir">
                <h3>Restauration cuir</h3>
                <p>Serviços de restauração para interiores em couro, mantendo seu carro sempre novo.</p>
            </div>
            <div class="servico">
                <img src="https://images.unsplash.com/photo-1581382575275-53ad418569ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" alt="Conciergerie">
                <h3>Conciergerie</h3>
                <p>Serviços personalizados para a sua conveniência e conforto.</p>
            </div>
        </div>
    </section>

    <section id="contato" class="container">
        <h2>Contato</h2>
        <form>
            <input type="text" placeholder="Nome" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <section id="blog" class="container">
        <h2>Blog</h2>
        <div class="blog-grid">
            <div class="post">
                <img src="https://images.unsplash.com/photo-1489824904134-891ab643d84e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2074&q=80" alt="Dicas de Manutenção">
                <h3>Dicas de Manutenção</h3>
                <p>Descubra como manter seu carro em perfeito estado com nossas dicas.</p>
            </div>
            <div class="post">
                <img src="https://images.unsplash.com/photo-1492144534655-6f22a2f307e0?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80" alt="Novidades do Mundo Automotivo">
                <h3>Novidades do Mundo Automotivo</h3>
                <p>Fique por dentro das últimas notícias e lançamentos do setor automobilístico.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Concept Car 2000 | Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* style.css */

body {
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    background-color: #111;
    color: #fff;
}

header {
    background-color: #222;
    padding: 1rem 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 2rem;
}

nav a {
    text-decoration: none;
    color: #fff;
    transition: color 0.3s;
}

nav a:hover {
    color: #f00;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.hero {
    background-image: url('https://images.unsplash.com/photo-1494905998304-203d10b3c8f4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1770&q=80');
    background-size: cover;
    background-position: center;
    height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.5rem;
}

.cta-button {
    background-color: #f00;
    color: #fff;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.cta-button:hover {
    background-color: #d00;
}

.container {
    padding: 2rem;
}

h2 {
    border-bottom: 2px solid #f00;
    padding-bottom: 0.5rem;
}

.servicos-grid, .blog-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.servico, .post {
    background-color: #222;
    padding: 1.5rem;
    border-radius: 8px;
    transition: transform 0.3s;
}

.servico img, .post img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 1rem;
}

.servico:hover, .post:hover {
    transform: scale(1.05);
}

form {
    display: flex;
    flex-direction: column;
}

form input, form textarea {
    margin-bottom: 1rem;
    padding: 0.75rem;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
}

form button {
    padding: 0.75rem;
    background-color: #f00;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

form button:hover {
    background-color: #d00;
}

footer {
    background-color: #222;
    text-align: center;
    padding: 1rem 0;
}
