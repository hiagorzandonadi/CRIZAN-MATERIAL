# CRIZAN-MATERIAL
SITE CRIZAN MATERIAL 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Materiais de Construção</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background-color: #ff0000;
            color: #fff;
            padding: 50px 20px;
            text-align: center;
        }
        .section {
            margin: 40px 0;
        }
        .section h2 {
            color: #333;
            text-align: center;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact-form button:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Loja de Materiais de Construção</h1>
    </header>
    <nav>
        <a href="#home">Início</a>
        <a href="#about">Sobre</a>
        <a href="#products">Produtos</a>
        <a href="#contact">Contato</a>
    </nav>
    <div id="home" class="hero">
        <h2>Bem-vindo à nossa Loja!</h2>
        <p>Os melhores materiais para sua construção</p>
    </div>
    <div id="about" class="container section">
        <h2>Sobre Nós</h2>
        <p>Somos uma empresa especializada em fornecer materiais de construção de alta qualidade. Com anos de experiência no mercado, garantimos os melhores produtos e atendimento personalizado para ajudar você a realizar seu projeto dos sonhos.</p>
    </div>
    <div id="products" class="container section">
        <h2>Produtos</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300x200" alt="Produto 1">
            <img src="https://via.placeholder.com/300x200" alt="Produto 2">
            <img src="https://via.placeholder.com/300x200" alt="Produto 3">
            <img src="https://via.placeholder.com/300x200" alt="Produto 4">
        </div>
    </div>
    <div id="contact" class="container section">
        <h2>Contato</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="message" placeholder="Sua Mensagem" rows="5" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Loja de Materiais de Construção. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
