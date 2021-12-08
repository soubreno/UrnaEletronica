<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urna Eletrônica</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="urna">
        <div class="tela">
            <div class="d-1">
                <div class="d-1-left">
                    <div class="d-1-1">
                        <span>SEU VOTO PARA</span>
                    </div>
                    <div class="d-1-2">
                        <span>VEREADOR</span>
                    </div>
                    <div class="d-1-3">
                       <div class="numero pisca"></div>
                       <div class="numero"></div>
                    </div>
                    <div class="d-1-4">
                        Nome: FULANO <br/>
                        Partido: DEV<br/>
                        Vice-Prefeito: BELTRANO
                    </div>
                </div>
                <div class="d-1-right">
                    <div class="d-1-image">
                        <img src="../urna eletronica/images/84.jpg" alt="" >
                        Prefeito
                    </div>
                    <div class="d-1-image small">
                        <img src="../urna eletronica/images/84_2.jpg" alt="" >
                        Vice-Prefeito
                    </div>
                </div>
            </div>
            <div class="d-2">
                Aperte a tela:<br/>
                CONFIRMA para CONFIRMAR este voto <br/>
                CORRIGE para REINICIAR este voto.
            </div>
        </div>
        <div class="teclado">
            <div class="teclado--linha">
                <div class="teclado--botao" onclick="clicou('1')">1</div>
                <div class="teclado--botao" onclick="clicou('2')">2</div>
                <div class="teclado--botao" onclick="clicou('3')">3</div>
            </div>
            <div class="teclado--linha">
                <div class="teclado--botao" onclick="clicou('4')">4</div>
                <div class="teclado--botao" onclick="clicou('5')">5</div>
                <div class="teclado--botao" onclick="clicou('6')">6</div>
            </div>
            <div class="teclado--linha">
                <div class="teclado--botao" onclick="clicou('7')">7</div>
                <div class="teclado--botao" onclick="clicou('8')">8</div>
                <div class="teclado--botao" onclick="clicou('9')">9</div>
            </div>
            <div class="teclado--linha">
                <div class="teclado--botao" onclick="clicou('0')">0</div>
            </div>
            <div class="teclado--linha">
                <div class="teclado--botao botao--branco" onclick="branco()">BRANCO</div>
                <div class="teclado--botao botao--corrige" onclick="corrige()">CORRIGE</div>
                <div class="teclado--botao botao--confirma" onclick="confirma()">CONFIRMA</div>
            </div>
        </div>
    </div>

    <script src="etapas.js"></script>
    <script src="script.js"></script>
</body>
</html>
