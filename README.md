# sm
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>SM Personalizados</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 2px;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 600;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .intro {
            text-align: center;
            margin-bottom: 40px;
        }
        .intro h2 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #4a90e2;
        }
        .intro p {
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .product-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }
        .product-card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 280px;
            padding: 20px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            max-width: 100%;
            border-radius: 6px;
            margin-bottom: 15px;
        }
        .product-card h3 {
            margin: 0 0 10px 0;
            color: #333;
        }
        .product-card p {
            font-size: 1rem;
            color: #666;
        }
        footer {
            background-color: #4a90e2;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 60px;
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            .product-section {
                flex-direction: column;
                align-items: center;
            }
            .product-card {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>SM Personalizados</h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#produtos">Produtos</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>
    <main>
        <section class="intro" id="sobre">
            <h2>Personalização de Canecas de Porcelana</h2>
            <p>Na SM Personalizados, transformamos suas ideias em canecas únicas e exclusivas. Trabalhamos com personalização de canecas de porcelana para presentear, divulgar sua marca ou simplesmente deixar seu dia a dia mais especial.</p>
        </section>
        <section class="product-section" id="produtos">
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1517686469429-8b0a4a7a1f3a?auto=format&fit=crop&w=400&q=80" alt="Caneca personalizada 1" />
                <h3>Caneca Clássica</h3>
                <p>Caneca de porcelana branca 300ml, personalizada com sua arte ou frase favorita.</p>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=400&q=80" alt="Caneca personalizada 2" />
                <h3>Caneca Colorida</h3>
                <p>Caneca com interior colorido e personalização externa para destacar sua criatividade.</p>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1528825871115-3581a5387919?auto=format&fit=crop&w=400&q=80" alt="Caneca personalizada 3" />
                <h3>Caneca Premium</h3>
                <p>Porcelana de alta qualidade com acabamento brilhante e personalização detalhada.</p>
            </div>
        </section>
        <section id="contato" style="margin-top: 60px; text-align: center;">
            <h2>Contato</h2>
            <p>Quer personalizar sua caneca? Entre em contato conosco!</p>
            <p>Email: contato@smpersonalizados.com.br</p>
            <p>Telefone: (11) 99999-9999</p>
        </section>
    </main>
    <footer>
        &copy; 2024 SM Personalizados - Todos os direitos reservados
    </footer>
</body>
</html>
