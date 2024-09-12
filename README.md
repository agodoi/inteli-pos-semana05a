# Introdução às Redes de Computadores

## Tipos de Topologias de Rede



### Física

## Topologias de Redes

Os hosts podem ser organizados em algum tipo de topologia a seguir:

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/SubRedes/blob/main/imgs/network-topology.png">
   <img alt="Topologias de Redes" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/SubRedes/blob/main/imgs/network-topology.png)">
</picture>

O mais comum para o ambiente de computadores é o **Estrela** que também pode ser estendido para **Estrela Estendida** quando uma estrela dá origem para outra estrela.


<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/SubRedes/blob/main/imgs/estrela_extendida.png">
   <img alt="Estrela Estendida" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/SubRedes/blob/main/imgs/estrela_extendida.png)">
</picture>



### Lógica

## Tipos de Meios de Transmissão

### Par metálico

### Óptico

### Eletromagnético

#### Antenas

#### Comunicação via Satélite

### Potência dBm

exercícios teóricos
exercícios práticos de medição do dBm usando celular
alinhamento de antena de satélites


## Tipos de Rede

### PAN (Personal Area Network)

Basicamente feita de dispositivos de curto alcance, em especial, os sem fio, via bluetooth;

### LAN (Local Area Network)

Feita de cabos UTP ou STP, WiFi, conectando computadores, notebooks, TVs, projetores, Alexa, dispositivos IoT, impressores e servidores.
 
### MAN (Metropolitan Area Network)

Feita de fibra óptica e rádio tipo minilink conectando empresas, hospitais, faculdades de diferentes endereços dentro de uma região metropolitana. Uma empresa ISP (Internet Service Provider) que alcança usuários dentro de uma cidade ou região metropolitana possui topologia física e lógica MAN.

### WAN (Wide Area Network)

Feita de fibra óptica e satélite. A Internet se mistura com uma WAN.

## Vantagens de Desvantagens


## Importância do Modelo OSI em Redes

1) Organização dos protocolos em camadas (Modelo OSI);
2) Protocolo IPV6;
3) Topologias de redes;
4) TCP e UDP;

Ambas as redes servem para conectar os hosts (que são end-devices numa grande rede chamada Internet).

Os hosts se comunincam usando diversos protocolos que trabalham de **camada N para camada N**.


<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/SubRedes/blob/main/imgs/modelo_osi.png">
   <img alt="Modelo OSI" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/SubRedes/blob/main/imgs/modelo_osi.png)">
</picture>

Alguns detaques da figura:

* O Modelo OSI (Opened Standard Interconnection) possui 7 camadas. É uma pilha de camadas totalmente abstrata, isto é, não existe essas camadas na vida real e não correspondem à nenhuma placa específica do computador;

## Modelo OSI

* **Camada 07 - Aplicação :** cuida de tudo o que aparece na sua tela, é a aplicação;
* **Camada 06 - Apresentação :** é o tradutor com criptografia/descriptografia;
* **Camada 05 - Sessão :** é a camada de intercomunicação entre hosts. É como se fosse uma sessão de cinema que tem hora para começar e acabar, isto é, o serviço ficará disponível para você por X minutos ou horas;
* **Camada 04 - Transporte :** é a camada de transferência de dados fim a fim. É o frete de pacotes. É a cada do TCP e UDP. TCP garante a entrega, UDP transporta, mas não garante a entrega de pacotes;
* **Camada 03 - Redes :** determina o caminho e a lógica de roteamento de pacotes. É a cada do IPV4 e IPV6;
* **Camada 02 - Enlace :** é a camada que trata do endereço físico dos dispositivos de redes, isto é, o chassis da placa que trafega dados;
* **Camada 01 - Física :** é a camada dos padrões elétricos, eletrônicos e mecânicos.



