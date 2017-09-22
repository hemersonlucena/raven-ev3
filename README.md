# Raven EV3

Software de transmissão mecânica de dados entre controladores LEGO EV3 desenvolvido na plataforma [EV3Basic](https://sites.google.com/site/ev3basic/).

## Instalação

- Usando o EV3Explorer contido na instalação do [EV3Basic](https://sites.google.com/site/ev3basic/), instale o arquivo `raven-sender.sb ` no `controlador A` (conectado ao motor) e o arquivo `raven-receiver.sb` no `controlador B` (conectado ao sensor de toque);

- Posicione os robôs de forma que o atuador do `controlador A` alcance o sensor de toque do `controlador B`;

- Inicie o `controlador A`;

- Inicie o `controlador B` no momento em que o controlador A soltar o botão do sensor de toque;

- Utilize o `controlador A` para escrever mensagens e veja o resultado no `controlador B`.