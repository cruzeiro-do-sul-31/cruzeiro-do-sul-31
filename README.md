<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Fotos - Augusta, Respeitável, Fiel e Grande Benemérita Loja Maçônica Cruzeiro do Sul nº 31</title>
    <style>
        /* Estilos Gerais (Tema Maçônico Classic) */
        body {
            font-family: 'Times New Roman', Times, serif, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #0b1d3a; /* Azul Maçônico Escuro */
            color: #dfb76c; /* Detalhes em tom de Ouro */
            text-align: center;
            padding: 2rem 1rem;
            border-bottom: 4px solid #dfb76c;
        }

        header h1 {
            margin: 0;
            font-size: 2.2rem;
            letter-spacing: 2px;
        }

        header p {
            margin: 0.5rem 0 0 0;
            font-style: italic;
            color: #ffffff;
        }

        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* Container da Galeria */
        .galeria-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        /* Card de Cada Foto */
        .foto-card {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s ease;
            border: 1px solid #e0e0e0;
        }

        .foto-card:hover {
            transform: translateY(-5px);
            border-color: #dfb76c;
        }

        .foto-card img {
            width: 100%;
            height: 220px;
            object-fit: cover; /* Garante que as fotos fiquem alinhadas sem distorcer */
            display: block;
        }

        .foto-info {
            padding: 15px;
            text-align: center;
        }

        .foto-info h3 {
            margin: 0 0 8px 0;
            font-size: 1.2rem;
            color: #0b1d3a;
        }

        .foto-info p {
            margin: 0;
            font-size: 0.9rem;
            color: #666;
        }

        /* Rodapé */
        footer {
            background-color: #0b1d3a;
            color: #ffffff;
            text-align: center;
            padding: 1.5rem 1rem;
            margin-top: 4rem;
            border-top: 4px solid #dfb76c;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Augusta, Respeitável, Fiel e Grande Benemérita Loja Maçônica Cruzeiro do Sul nº 31</h1>
        <p>Galeria de Registros Históricos e Eventos</p>
    </header>

    <main>
        <section class="galeria-container">
            
            <!-- Foto 1 -->
            <div class="foto-card">
                <img src="veneravel1.jpg" alt="Veneravel1">
                <div class="foto-info">
                    <h3>Fachada do Templo</h3>
                    <p>Registro da nossa sede oficial.</p>
                </div>
            </div>

            <!-- Foto 2 -->
            <div class="foto-card">
                <img src="veneravel2.jpg" alt="veneravel">
                <div class="foto-info">
                    <h3>Sessão de Aniversário</h3>
                    <p>Celebração dos [X] anos de fundação.</p>
                </div>
            </div>

            <!-- Foto 3 -->
            <div class="foto-card">
                <img src="veneravel3.jpg" alt="veneravel">
                <div class="foto-info">
                    <h3>Ágape / Ação Social</h3>
                    <p>Entrega de doações para a comunidade local.</p>
                </div>
            </div>

            <!-- Foto 4 -->
            <div class="foto-card">
                <img src="veneravel4.jpg" alt="veneravel">
                <div class="foto-info">
                    <h3>Nosso Estandarte</h3>
                    <p>Detalhe do pavilhão da oficina.</p>
                </div>
            </div>

            <!-- Adicione mais blocos de "foto-card" se precisar de mais fotos -->

        </section>
    </main>

    <footer>
        <p>&copy; 2026 A.R.L.S. [Nome da Loja] - Todos os direitos reservados.</p>
        <p>T.·.F.·.A.·.</p>
    </footer>

</body>
</html>
