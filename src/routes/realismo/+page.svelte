<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <style>
        
        header {
            background: linear-gradient(to right, #003f69, #1e0069); 
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
    </style>
    <title>Realismo</title>
</head>
<body>
    <header>
        <h1>Realismo</h1><br> 
        <p>O realismo foi um movimento artístico e literário que surgiu na França, no meio do século XIX, como uma reação ao romantismo e ao idealismo predominantes na arte da época. O realismo buscava representar a vida cotidiana de forma fiel e sem idealizações, retratando as pessoas, os ambientes e os eventos com um olhar mais objetivo, muitas vezes focando nas classes populares e nas dificuldades da vida real.Na pintura, os artistas realistas evitavam os temas mitológicos ou históricos, comuns em movimentos anteriores, e se concentravam em cenas da vida diária, como trabalhadores, camponeses, e cenas urbanas.</p>
    </header>

    <br><center><h1>Outras obras</h1></center> 

    <div class="container my-5">
        <div class="row">
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="kiss.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title">Na cama</h5>
                        <p class="card-text">Eu diria que essa é uma manhã preguiçosa de domingo.</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="pincel.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title"> O beijo fatal </h5>
                        <p class="card-text">Essa pintura desenha "Covardes", de William Shakspeare. </p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="veni.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">O nascimento de Vênus</h5>
                        <p class="card-text">Uma obra-prima do Renascimento, hoje conhecida em todo o mundo. </p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="beijao.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">O beijo </h5>
                        <p class="card-text">Essa é outra figura da arte, que todos já viram. Um ode aos beijoqueiros! </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
