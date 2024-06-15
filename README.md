<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinicius Miranda - Portfólio Profissional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #004d40;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #004d40;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .bio, .contact {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .bio h2, .contact h2 {
            color: #004d40;
        }
        .social-icons {
            text-align: center;
            margin: 20px 0;
        }
        .social-icons a {
            color: #004d40;
            text-decoration: none;
            margin: 0 10px;
            font-size: 24px;
        }
        footer {
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px;
            background-color: #004d40;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #00332e;
        }
    </style>
</head>
<body>
    <header>
        <h1>Vinicius Miranda</h1>
        <p>Marketing e Influência</p>
    </header>
    <nav>
        <a href="#bio">Sobre Mim</a>
        <a href="#contact">Contato</a>
    </nav>
    <div class="container">
        <section id="bio" class="bio">
            <h2>Sobre Mim</h2>
            <p>Olá, meu nome é Vinicius Miranda. Sou especialista em marketing e influência, com vasta experiência em criar estratégias eficazes para aumentar a presença online de marcas e indivíduos. Minha paixão por marketing começou cedo, e desde então, tenho trabalhado com diversas empresas para ajudá-las a alcançar seus objetivos.</p>
            <p>Com uma abordagem centrada no cliente, sempre busco entender as necessidades específicas de cada projeto para oferecer soluções personalizadas e eficientes. Estou comprometido em manter-me atualizado com as últimas tendências e tecnologias do setor para garantir que meus clientes sempre estejam à frente.</p>
        </section>
        <section id="contact" class="contact">
            <h2>Contato</h2>
            <form>
                <input type="text" name="name" placeholder="Seu Nome" required>
                <input type="email" name="email" placeholder="Seu Email" required>
                <textarea name="message" placeholder="Sua Mensagem" rows="5" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <div class="social-icons">
            <a href="https://www.facebook.com" target="_blank">Facebook</a>
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://www.twitter.com" target="_blank">Twitter</a>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Vinicius Miranda. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
