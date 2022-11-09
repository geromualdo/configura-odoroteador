# configuração do roteador
Configuração do Roteador através do Cisco

Ao fazer as conexões de rede. É necessario clicar em "Router"
Em seguida entrar na opção CLI. Vai aparecer a mensagem "Continue with configuration dialog? yes/no
Que significa se você deseja um configuração com dialogo. Ai basta digitar "No" e apertar Enter.

<b>OBS: É necessario prestar bastante atenção na escrita, pois é muito importante, caso digite uma palavra errada dará erro e irá travar por alguns segundos ai caso aconteça de enter e volte na opção Return e digite corretamente a palavra.</b>

<b>PRIMEIRA PARTA - PASSO a PASSO (Esta fase é simples basta se atentar a escrita)</b>

<b>Lembrando que basta digitar nessa ordem ao lado das palavras "Router>" e "Router#". Conforme vai aparecendo as mensagem basta digitar ao lado os seguindes comando:</b>

1º Digite "Enable" - Tecla Enter

2º #Configure Terminal - Tecla Enter

3º #hostaname <b>(DIGITAR O NOME DA REDE QUE DESEJA)</b> - Tecla Enter

<b><i>A partir deste momento, a palavra "Router" sera substituida pelo nome da rede que você escolheu.</b></i>

4º #Line console 0 - Tecla Enter

5º #Password (Senha) - Tecla Enter

6º #login - Tecla Enter

7º #exec-timeout 5 0 <b>(o tempo que deseja para a sessão ser encerrada por inatividade,  no caso irei colocar 5 0 que corresponde a segundos)</b> - Tecla Enter

8º #exit Tecla Enter

<b>SEGUNDA PARTE PARA CONFIGURAR A INTARFACE DA REDE COM ENDEREÇO IP E GATEWAY E SALVAR</b>

Para configurar basta digitar Enter, em seguida, #interface  (nome que estã conectado o roteador ao switch).

1 - #ip addres. Seguido da numeração e do gateway

2 - #description(nome que quiser colocar)

3 - #no shutdow para finalizar, e  teclar enter.

<b> Para sair das configurações basta terclar enter e digitar #exit e repetir outra vez enter e #exit.</b>

Para salvar tudo o que foi feito basta digitar: #copy  running-config  startup-config e teclar 2 vezes enter.

Segue o exemplo atraves das imagens.


![Config1](https://user-images.githubusercontent.com/102399570/200941330-b0bd76c8-7dea-4199-b3a0-87480b16785d.png)
![Configu2](https://user-images.githubusercontent.com/102399570/200941739-07a9908f-27d2-4dd7-b7a3-20416e830632.png)
![Confi3](https://user-images.githubusercontent.com/102399570/200941852-a677b9b1-df67-4a60-924b-e6398e9ed618.png)



