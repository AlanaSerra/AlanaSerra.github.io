<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <style>
       
        header {
            background: linear-gradient(to right, #940602, #b60c04);
            color: #fff;
            padding: 30px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5rem;
            font-weight: bold;
        }
        header p {
            font-size: 1rem;
        }
        .card {
            border: none;
            border-radius: 15px;
            background-color: #f8f9fa;
            color: #3f1719;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }
        .card-title {
            font-size: 1.2rem;
            color: #680a1d;
            font-weight: bold;
        }
        .btn-primary {
            background-color: #d91306;
            border: none;
            border-radius: 20px;
            color: #fff;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn-primary:hover {
            background-color: #710000;
        }
        .btn-link {
            color: #157a8c;
            text-decoration: none;
            font-weight: bold;
        }
        .btn-link:hover {
            text-decoration: underline;
        }
        footer {
            background: linear-gradient(to right, #3f1719, #680a1d);
            color: #fff;
            padding: 15px 0;
            text-align: center;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }
        /* Estilos para as caixas de texto */
        .textarea-container {
            background-color: #f8f9fa;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 15px;
        }
        .textarea-container textarea {
            width: 100%;
            border-radius: 10px;
            border: 1px solid #ccc;
            padding: 10px;
            font-size: 1rem;
            color: #3f1719;
            transition: border 0.3s;
        }
        .textarea-container textarea:focus {
            border-color: #157a8c;
            outline: none;
        }
    </style>
    <title>Referencias</title>
</head>
<body>
    <header>
        <h1>Referenciando o mundo geek na arte</h1><br> 
        <p>Nesta página você encontrará recomendações de livros, músicas, filmes e seriados que se relacionam com os movimentos artisticos desta galeria. Espero que goste! s2 </p>
    </header>

    <!-- Cards -->
    <div class="container my-5">
        <div class="row">
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="gt.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title"> É assim que se perde a guerra do tempo </h5>
                        <p class="card-text">Esse livro é incrível e seus personagens não têm gênero ou nome, o que parece demais com as pinceladas do impressionismo! É um romance em uma guerra do tempo perfeito, simbolico e profundo. Parabéns às autoras! </p>
                        <a href="https://www.amazon.com.br/assim-que-perde-guerra-tempo/dp/8556511082" class="btn btn-primary">Leia aqui </a>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="mn.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">Milton Nascimento</h5>
                        <p class="card-text">Um cantor extremamente profundo que tem letras lindas que se encaixariam em todos os movimentos artisticos, mas darei enfâse especial no Renascimento! </p>
                          <p> <i> Vou me encontrar, longe do meu lugar. Eu, caçador de mim</i> </p>
                        <a href="https://www.youtube.com/watch?v=5Nq8RQLbWY0" class="btn btn-primary">Ouça aqui</a>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="dark.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">Dark</h5>
                        <p class="card-text">A série Dark aborda o realismo ao mostrar as complexas relações familiares e as consequências inevitáveis das escolhas humanas. Ela retrata um universo onde o sofrimento e o destino são inescapáveis, refletindo a crueza da realidade.</p>
                        <a href="https://www.netflix.com/browse" class="btn btn-primary"> Assista aqui </a>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="bp.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">Blue Period</h5>
                        <p class="card-text">Blue Period é um anime e mangá que fala justamente sobre um artista em descobrimento! Ele tenta ao máximo se encaixar na Arte Clássica, mas acaba percebendo que seu estilo era muito mais solto do que o requisitado para essa escola.</p>
                        <a href="https://www.netflix.com/browse" class="btn btn-primary">Assita aqui</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Caixas de texto -->
     <center>
    <div class="container my-5">
        <div class="row">
            <div class="col-sm-6 mb-4">
                <div class="textarea-container">
                    <h5>Caixa de Texto 1</h5>
                    <textarea rows="4" placeholder="Qual foi sua obra preferida entre essas da Galeria?"></textarea>
                </div>
            </div>
        </center> 

</body>
</html>
