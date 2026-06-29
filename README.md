<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Fotos - A.R.L.S. [Nome da Loja]</title>
    <style>
        /* Estilos Gerais (Tema Maçônico Clássico) */
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
            object-fit: cover;
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
        <h1>A.R.L.S. [Nome da Loja]</h1>
        <p>Galeria de Registros Históricos e Eventos</p>
    </header>

    <main>
        <section class="galeria-container">
            
            <!-- Foto 1 -->
            <div class="foto-card">
                <!-- Caminho atualizado para veneravel1.jpg -->
                <img src="imagens/veneravel1.jpg" alt="Galeria de Veneráveis 1">
                <div class="foto-info">
                    <h3>Venerável Mestre [Nome]</h3>
                    <p>Gestão [Ano - Ano]</p>
                </div>
            </div>

            <!-- Foto 2 -->
            <div class="foto-card">
                <!-- Caminho atualizado para veneravel2.jpg -->
                <img src="imagens/veneravel2.jpg" alt="Galeria de Veneráveis 2">
                <div class="foto-info">
                    <h3>Venerável Mestre [Nome]</h3>
                    <p>Gestão [Ano - Ano]</p>
                </div>
            </div>

            <!-- Foto 3 -->
            <div class="foto-card">
                <!-- Caminho atualizado para veneravel3.jpg -->
                <img src="imagens/veneravel3.jpg" alt="Galeria de Veneráveis 3">
                <div class="foto-info">
                    <h3>Venerável Mestre [Nome]</h3>
                    <p>Gestão [Ano - Ano]</p>
                </div>
            </div>

            <!-- Foto 4 -->
            <div class="foto-card">
                <!-- Caminho atualizado para veneravel4.jpg -->
                <img src="imagens/veneravel4.jpg" alt="Galeria de Veneráveis 4">
                <div class="foto-info">
                    <h3>Venerável Mestre [Nome]</h3>
                    <p>Gestão [Ano - Ano]</p>
                </div>
            </div>

        </section>
    </main>

    <footer>
        <p>&copy; 2026 A.R.L.S. [Nome da Loja] - Todos os direitos reservados.</p>
        <p>T.·.F.·.A.·.</p>
    </footer>

</body>
</html>
