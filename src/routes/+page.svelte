    <style>
        header {
            background: linear-gradient(to right, #680a1d, #3f1719);
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
            background-color: #157a8c;
            border: none;
            border-radius: 20px;
            color: #fff;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn-primary:hover {
            background-color: #003f69;
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

        body {
        background-color: #003f69; /* Cor do fundo do corpo */
        color: #fff; /* Para garantir que o texto seja legível */
    }

    </style>

    <title>Galeria de Arte</title>
    <header>
        <h1>Galeria de Arte</h1><br> 
        <p>O tempo é como um sopro suave que acaricia nossas memórias</p>
        <p><i>E, no final, nós todos viramos apenas histórias.</i></p>

    </header>

    <div class="container my-5">
        <div class="row">

            
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="monet.jpg" alt="Lílios d'água">
                    <div class="card-body text-center">
                        <h5 class="card-title">Lílios d'água</h5>
                        <p class="card-text">Um mergulho nas cores do impressionismo, uma das mais emblemáticas de Monet.</p>
                        <a href="impressionismo" class="btn btn-primary">Impressionismo</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>

           
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="anjo.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">O anjo caído</h5>
                        <p class="card-text">Beleza na tragédia. A minha favorita! É minha capinha de celular :) </p>
                        <a href="academica" class="btn btn-primary">Arte acadêmica</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>

            
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="venus.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">O despertar de Vênus</h5>
                        <p class="card-text">Vênus é muito amada por todos do Renascimento e essa pintura não deixa a desejar!</p>
                        <a href="renascimento" class="btn btn-primary">Renascimento</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>

           
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="pos.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">Amendoeira em flor</h5>
                        <p class="card-text">Uma ode à natureza no realismo, que é um dos aspectos mais marcantes desse movimento.</p>
                        <a href="realismo" class="btn btn-primary">Realismo</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container my-5">
        <div class="row">
          

            
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="carne.jpg" alt="O anjo caído">
                    <div class="card-body text-center">
                        <h5 class="card-title">Cabeça de cordeiro à mesa</h5>
                        <p class="card-text">Beleza e tragédia na arte acadêmica, que destaca elementos desconfotáveis que preferimos evitar.</p>
                        <a href="academica" class="btn btn-primary">Arte acadêmica</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>

          
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="deluge.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">Dilúvio</h5>
                        <p class="card-text">Essa obra representa algum condenado que não entrou na arca de Noé.</p>
                        <a href="renascimento" class="btn btn-primary">Renascimento</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="jarra.jpg" alt="O nascimento de Vênus">
                    <div class="card-body text-center">
                        <h5 class="card-title">Circe Invidiosa</h5>
                        <p class="card-text">Essa obra representa e dá vida a lenda de Circe Invidiosa, que foi traída e derramou o sangue de seu amante por terra, para que este descesse lentamente ao inferno.</p>
                        <a href="renascimento" class="btn btn-primary">Renascimento</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>

           
            <div class="col-sm-3 mb-4">
                <div class="card">
                    <img class="card-img-top" src="bjo.jpg" alt="Amendoeira em flor">
                    <div class="card-body text-center">
                        <h5 class="card-title">La Belle Dame</h5>
                        <p class="card-text">Essa obra simbolica feminista mostra um caveleiro recebendo seu posto de uma rainha.</p>
                        <a href="realismo" class="btn btn-primary">Realismo</a>
                        <a href="referencias" class="btn btn-link">Referências</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 - nenhum direito reservado (exceto a frase do começo!) à Alana Serra</p>
    </footer>