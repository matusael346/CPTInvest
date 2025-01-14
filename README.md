<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPTInvest - Seu portal de investimento em criptomoedas</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #ff7e5f, #feb47b);
            color: #fff;
            padding: 20px 0;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 10%;
        }

        header h1 {
            margin: 0;
        }

        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        header nav ul li {
            margin-left: 20px;
        }

        header nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: color 0.3s;
        }

        header nav ul li a:hover {
            color: #333;
        }

        .hero {
            background: linear-gradient(90deg, #00c6ff, #0072ff);
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        .hero .btn {
            background: #ff7e5f;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 25px;
            transition: background 0.3s;
        }

        .hero .btn:hover {
            background: #feb47b;
        }

        section {
            padding: 60px 10%;
        }

        .about, .services, .contact {
            background: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .services .service-list {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            flex-wrap: wrap;
        }

        .services .service-item {
            flex: 1;
            min-width: 250px;
            background: #fff;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .services .service-item:hover {
            transform: translateY(-10px);
        }

        .contact form label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
        }

        .contact form input, .contact form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .contact form button {
            background: #00c6ff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            margin-top: 20px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .contact form button:hover {
            background: #0072ff;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>CPTInvest</h1>
            <nav>
                <ul>
                    <li><a href="#home">Início</a></li>
                    <li><a href="#about">Sobre</a></li>
                    <li><a href="#services">Serviços</a></li>
                    <li><a href="#contact">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Invista no futuro com CPTInvest</h2>
            <p>Descubra oportunidades em criptomoedas com segurança e facilidade.</p>
            <a href="#services" class="btn">Saiba Mais</a>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>Sobre Nós</h2>
            <p>A CPTInvest é dedicada a ajudar você a alcançar seus objetivos financeiros através de investimentos inteligentes em criptomoedas. Nossa equipe especializada oferece orientação personalizada e ferramentas avançadas para maximizar seus ganhos.</p>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Serviços</h2>
            <div class="service-list">
                <div class="service-item">
                    <h3>Consultoria Personalizada</h3>
                    <p>Receba orientação especializada para alinhar seus investimentos às suas metas.</p>
                </div>
                <div class="service-item">
                    <h3>Plataforma de Negociação</h3>
                    <p>Negocie com facilidade utilizando nossa interface intuitiva e segura.</p>
                </div>
                <div class="service-item">
                    <h3>Relatórios e Análises</h3>
                    <p>Fique informado com análises detalhadas e relatórios de mercado.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Entre em Contato</h2>
            <form action="#" method="post">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 CPTInvest. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
