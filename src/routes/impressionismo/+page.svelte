<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
    <style>
       body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to bottom, #680a1d, #680a1d); 
            color: #f8f9fa;
        }
        header {
            background-color: #003f69; 
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
    <title>Impressionismo</title>
</head>
<body>
    <header>
        <h1>Impressionismo</h1><br> 
        <p>O impressionismo foi um movimento artístico que surgiu na França, na segunda metade do século XIX, desafiando as convenções da arte acadêmica da época. Os impressionistas buscavam representar a luz e a cor de maneira mais fiel à percepção humana, ao invés de seguir os detalhes e a precisão das obras clássicas. Os artistas impressionistas usavam pinceladas soltas e rápidas, cores vibrantes e contrastantes, e muitas vezes pintavam ao ar livre (en plein air) para capturar a mudança constante da luz natural. Eles estavam mais interessados em capturar o momento efêmero e a sensação do que em representar a realidade de forma rígida.</p>
    </header>

    <br><center><h1>Outras obras</h1></center> 

    <div class="container my-5">
        <div class="row">
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="anjao.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title"> Solina </h5>
                        <p class="card-text"> Esta pintura representa a deusa do sol, "Solina, divindade de uma religião nórdica do extremo oeste."</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="mulheres.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">Chá da tarde</h5>
                        <p class="card-text">Observe que, nesta pintura, a sombra está a favor do sol. Curioso, não? Será descuido do pintor ou alguma mensagem subliminar?  </p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="ponte.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">Jardins de Monet</h5>
                        <p class="card-text">É como diz o ditado: Monet antes de pintar teve que plantar e esperar que seus jardins crescessem.</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="angel.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">Os arcanjos</h5>
                        <p class="card-text">Essa pintura representa os maiores arcanjos da Biblía cristã.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
