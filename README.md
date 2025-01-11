# https-seu-usuario.github.io-laboratorio-eduardo-santos-
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laboratório Eduardo Santos - Prótese Dentária</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #e0f7fa;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #2e7d32;
        }
        nav {
            text-align: center;
            background-color: #b2dfdb;
            padding: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #2e7d32;
            font-weight: bold;
        }
        .banner {
            background-image: url('imagem-banner.jpg');
            background-size: cover;
            height: 300px;
            text-align: center;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .banner h2 {
            font-size: 2.5em;
        }
        section {
            padding: 30px;
            text-align: center;
        }
        footer {
            background-color: #e0f7fa;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer p {
            margin: 0;
        }
        .cta-button {
            background-color: #2e7d32;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .cta-button:hover {
            background-color: #1b5e20;
        }
    </style>
</head>
<body>

    <header>
        <h1>Laboratório Eduardo Santos</h1>
        <p>Especialistas em Prótese Dentária</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#servicos">Serviços</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="banner">
        <h2>Transformando sorrisos com qualidade e confiança</h2>
    </div>

    <section id="home">
        <h2>Bem-vindo ao Laboratório Eduardo Santos!</h2>
        <p>Oferecemos soluções de prótese dentária personalizadas, com qualidade e precisão para garantir o seu melhor sorriso.</p>
        <a href="#servicos" class="cta-button">Saiba Mais</a>
    </section>

    <section id="servicos">
        <h2>Serviços</h2>
        <p>Oferecemos diversos tipos de próteses dentárias:</p>
        <ul>
            <li>Prótese Fixa</li>
            <li>Prótese Removível</li>
            <li>Implantes Dentários</li>
        </ul>
        <a href="#contato" class="cta-button">Solicite um Orçamento</a>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>O Laboratório Eduardo Santos é uma empresa especializada em próteses dentárias, com anos de experiência e compromisso com a excelência.</p>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <p>Preencha o formulário abaixo para solicitar mais informações ou agendar uma consulta.</p>
        <form>
            <input type="text" placeholder="Seu Nome" required><br><br>
            <input type="email" placeholder="Seu E-mail" required><br><br>
            <textarea placeholder="Sua Mensagem" required></textarea><br><br>
            <button type="submit" class="cta-button">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Laboratório Eduardo Santos - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
