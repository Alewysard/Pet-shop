<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetShop Informativo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #008000;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #f2f2f2;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #008000;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        h1, h2 {
            color: #008000;
        }
        .info-section {
            margin-bottom: 20px;
        }
        .contact {
            background-color: #e6f5e6;
            padding: 15px;
            border: 1px solid #c3e6c3;
            border-radius: 5px;
        }
        .products, .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .card {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            width: calc(33.333% - 20px);
            background-color: white;
            text-align: center;
        }
        .card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .card h3 {
            margin: 10px 0;
            color: #008000;
        }
        footer {
            background-color: #008000;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao PetShop Informativo</h1>
    </header>

    <nav>
        <a href="#sobre">Sobre Nós</a>
        <a href="#servicos">Serviços</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <div id="sobre" class="info-section">
            <h2>Sobre Nós</h2>
            <p>Somos um petshop dedicado a cuidar do seu melhor amigo! Oferecemos serviços de qualidade para todas as raças e portes.</p>
        </div>

        <div id="servicos" class="info-section">
            <h2>Nossos Serviços</h2>
            <div class="services">
                <div class="card">
                    <h3>Tosa de Pequeno Porte</h3>
                    <p>R$ 20,00</p>
                </div>
                <div class="card">
                    <h3>Tosa de Médio Porte</h3>
                    <p>R$ 50,00</p>
                </div>
                <div class="card">
                    <h3>Tosa de Grande Porte</h3>
                    <p>R$ 100,00</p>
                </div>
            </div>
        </div>

        <div id="produtos" class="info-section">
            <h2>Nossos Produtos</h2>
            <div class="products">
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Ração Premium">
                    <h3>Ração Premium</h3>
                    <p>R$ 150,00</p>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Brinquedo para Pet">
                    <h3>Brinquedo para Pet</h3>
                    <p>R$ 30,00</p>
                </div>
                <div class="card">
                    <img src="https://via.placeholder.com/300" alt="Cama Confortável">
                    <h3>Cama Confortável</h3>
                    <p>R$ 120,00</p>
                </div>
            </div>
        </div>

        <div id="contato" class="info-section contact">
            <h2>Contato</h2>
            <p>Telefone: <strong>(21) 99909-876</strong></p>
            <p>Venha nos visitar e cuidar do seu pet com carinho!</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 PetShop Informativo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
