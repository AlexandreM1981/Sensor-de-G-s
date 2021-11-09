# Sensor-de-G-s

Projeto: PCB do circuito de sensor de gás;
Autores: Alexandre de Magalhães e Marco Antonio;
Universidade: Universidade Federal de Ouro Preto.

DESCRIÇÃO

1)Os componentes ultilizados para criar a PCB foram: dois resistores de 250 onhs, um led verde, um led vermelho, TBlock-I2, TBlock-I3, TBlock-M3,TBlockM2, um arduino nano, quatro pontos GROUND e um ponto POWER;
2)O led verde foi ligado em serie com um resistor que foi ligado na porta D3 do arduino, já o led vermelho foi ligado ao outro resistor que estava na porta D6. As outras pontas dos led's foram ligadas cada uma em um ponto GROUND;
3)O TBlock-M2 teve uma ponta ligada na porta D10 e outra em um ponto GROUND, esse conenctor foi utilizado para ser substituido pela imagem 3D de um buzzer;
4)O TBlock-I2 foi ultilizado para alimentação, então um ponta foi ligada no Vin e outra em um ponto GROUND;
5)O TBlock-M3 foi ultilizado para representar os conectores onde o sensor de gás deve ser ligado. A sua ligação foi feita da maneira que o sensor deveria ser ligado sendo assim a ponta  1 foi ligada em um POWER, a ponta 2 foi ligada em um GROUND e a ponta 3 foi ligada na porta analogica A1;
6)Para o TBlock-I3 não foi feito nenhuma ligação, ele foi apenas usado para posteriormete ser substituido por um imagem 3D do Sensor de Gás(MQ2) que deveria ser usado no projeto.

PRINCIPAIS DIFICULDADES:

1)A nescessidade de baixar as imagens 3D dos conectores TBlock-I2 e TBlock-M3 para que fossem melhores representados na PCB;
2)Baixar a imagem 3D do buzzer que substituiu o TBlock-M2;
3)Outra grande dificuldade é que não foi possivel conectar o sensor de gás direto na PCB pois o espaçamento dos furos na PCB sempre eram maiores que os pinos do sensor. Portanto foi colocado o TBlock-M3 para representar onde o sensor deveria ser ligado na PCB e o TBlock-I3 que não foi ligado a nada e apenas usado para mostrar na representação 3D a forma e o tipo de sensor de gas que deveria ser ultilizado.


ARQUIVO DA PCB E DO CÓDIGO DO ARDUINO:
[Sensor de Gás.zip](https://github.com/AlexandreM1981/Sensor-de-G-s/files/7501249/Sensor.de.Gas.zip)
