<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reparação de Carros de Luxo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <!-- Adicione o logotipo da empresa aqui -->
            <img src="logo.png" alt="Logotipo da Empresa">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#galeria">Galeria</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Reparo e Manutenção de Carros de Luxo</h1>
            <p>Especialistas em cuidar do seu veículo com excelência.</p>
            <a href="#servicos" class="btn">Saiba Mais</a>
        </div>
        <div class="hero-image">
            <img src="imagem1.jpg" alt="Carro de Luxo">
        </div>
    </section>

    <section id="servicos" class="servicos">
        <h2>Nossos Serviços</h2>
        <div class="servicos-grid">
            <div class="servico-item">
                <h3>Mecânica</h3>
                <p>Manutenção preventiva e corretiva, diagnóstico avançado.</p>
            </div>
            <div class="servico-item">
                <h3>Funilaria e Pintura</h3>
                <p>Reparo de amassados, pintura automotiva com alta qualidade.</p>
            </div>
            <div class="servico-item">
                <h3>Elétrica</h3>
                <p>Reparos e diagnósticos elétricos, instalação de acessórios.</p>
            </div>
            <!-- Adicione mais serviços aqui -->
        </div>
    </section>

    <section id="galeria" class="galeria">
        <h2>Galeria de Fotos</h2>
        <div class="galeria-grid">
            <img src="imagem2.jpg" alt="Carro Reparado">
            <img src="imagem3.jpg" alt="Carro Reparado">
            <!-- Adicione mais imagens aqui -->
        </div>
    </section>

    <section id="contato" class="contato">
        <h2>Contato</h2>
        <form>
            <input type="text" placeholder="Nome">
            <input type="email" placeholder="Email">
            <textarea placeholder="Mensagem"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Reparação de Carros de Luxo. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
.hero {
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 5em 2em;
    background-color: #eee;
}

.hero-text {
    max-width: 500px;
}

.hero-image img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

.btn {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

/* Serviços Section */
.servicos {
    padding: 2em;
    text-align: center;
}

.servicos-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px;
}

.servico-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* Galeria Section */
.galeria {
    padding: 2em;
    text-align: center;
}

.galeria-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.galeria-grid img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

/* Contato Section */
.contato {
    padding: 2em;
    text-align: center;
}

.contato input,
.contato textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contato button {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

