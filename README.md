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
