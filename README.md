# Vestivel
Acoplamentos Sensíveis é o título de uma série de <b>objetos artísticos vestíveis que exploram conexões entre o homem e a
natureza mediadas pela tecnologia.</b> A performance se desenvolve na forma de uma intervenção poética que busca nos aproximar
da natureza e das coisas através do jogo da arte. Sonoplanta é uma peça composta de uma planta e um sistema eletrônico que,
acoplada ao corpo, produz variações sonoras e luminosas. Essas variações resultam da relação entre a planta, a(o) performer
e o público e podem ser percebidas como metáforas de uma possível consciência vegetal.

<hr>
##Código
Disponibilizamos o material pesquisado e desenvolvido no <a href="http://nano.eba.ufrj.br">Núcleo de Artes e Novos Organismos (NANO)</a>
, na Universidade Federal do Rio de Janeiro.

<b>acoplamentos_yun_osc</b><br>
A pasta e o arquivo de mesmo nome são utilizados no Arduino. O código obtém informações da interação com a planta e dados dos 
sensores do ambiente e os transmite para um servidor OSC (Open Sound Control) através de uma rede wifi. O arduino utilizando pode ser 
o Arduino Yun ou o Dragino Yun Shield, ambos funcionam da mesmoa forma e requerem os arquivos da pasta YunOSC.

<b>YunOSC</b><br>
Está pasta contem os arquivos que devem ser utilizados para possibilitar o envio dos dados dos sensores para o servidor OSC.
As instruções detalhadas de como proceder estão dentro da mesma.
