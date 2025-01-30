<svelte:head>
    <title>Arte Acadêmica</title>
</svelte:head>

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
    
    <header>
        <h1>Arte Acadêmica</h1><br> 
        <p>A arte acadêmica é um estilo artístico que se desenvolveu a partir dos ensinamentos das academias de arte, especialmente na Europa, a partir do século XVII. Ela é caracterizada pela adesão a normas rígidas de técnica e estilo, muitas vezes com um foco na perfeição técnica e na representação realista da figura humana e da natureza. As academias, como a Académie des Beaux-Arts em Paris, eram instituições educacionais que formavam artistas dentro de parâmetros considerados "adequados" para a arte, estabelecendo regras sobre composição, proporções e uso de cores.</p>
    </header>

    <br><center><h1>Outras obras</h1></center> 

    <div class="container my-5">
        <div class="row">
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="muie.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title">A mãe</h5>
                        <p class="card-text">Um retrato simbólico de uma mãe e sua filha recém noiva.</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="siren.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">Quatro sereias</h5>
                        <p class="card-text">Essa pintura retrata o que tanto fez os marinheiros temerem: as sereias. Mas essas parecem inofensivas, certo? É aí que mora o perigo</p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="sla.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">Trombetas</h5>
                        <p class="card-text">Essa pintura retrata Lúcifer, caído e belo. É muito discutido quem seriam esses anjos que lhe seguravam. </p>
                    </div>
                </div>
            </div>

            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="zoi.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">Os olhos da condessa</h5>
                        <p class="card-text">Essa obra não tem muita explicação. Que não venha uma tempestade da cor destes olhos castaaaaaaaaanhos!</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
