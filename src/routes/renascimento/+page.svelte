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
    <title>Renascimento</title>
</head>
<body>
    <header>
        <h1> Renascimento </h1><br> 
        <p>O Renascimento foi um movimento cultural e artístico que teve início no final da Idade Média, no século XIV, e se estendeu até o século XVII. Surgiu na Itália, mas se espalhou rapidamente pela Europa, marcando uma mudança radical na forma de pensar e de se expressar artisticamente. O Renascimento é caracterizado pela valorização do ser humano, da razão e da natureza, em contraste com os dogmas da Igreja e a visão medieval do mundo. No campo artístico, o Renascimento representou uma redescoberta da arte e dos valores da Antiguidade Clássica, como a Grécia e Roma antigas, buscando reviver seus princípios estéticos, técnicos e filosóficos.</p>
    </header>

    <br><center><h1>Outras obras</h1></center> 

    <div class="container my-5">
        <div class="row">
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="navio.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title">O navio de Egdar</h5>
                        <p class="card-text">Tomara que os tripulantes tenham se salvo!</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="corasao.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">Amor</h5>
                        <p class="card-text">Quem nunca, né? Essa pintura hiper-realista não foi bem aceita em sua época (1976), mas hoje é aplaudida.</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="choro.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">A carta de despedida</h5>
                        <p class="card-text">Essa pintura representa uma jovem em sofrimento, e cabe a você especular o que estava escrito na carta.</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="gc.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">Primos</h5>
                        <p class="card-text">Esses são os senhores Ballwack, uma familia muito importante da Escócia por volta de 1900-1920, que financiou vários artistas. </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
