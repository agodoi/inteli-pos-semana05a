# Introdução às Redes de Computadores

## Tipos de Topologias de Rede

E a maneira como os elementos de uma rede estão organizados e interligados. Ela pode ser classificada em duas categorias: **topologia física** e **topologia lógica**. 

### Física

A **topologia física** se refere à disposição real e física dos cabos, dispositivos e outros componentes da rede. É a maneira como os cabos e equipamentos, como switches e roteadores, estão fisicamente conectados uns aos outros. Os hosts podem ser organizados em algum tipo de topologia a seguir:

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

A topologia lógica descreve como os dados se movem dentro da rede, ou seja, o caminho que as informações seguem independentemente da disposição física dos cabos e dispositivos. É sobre o fluxo de dados entre os dispositivos, que nem sempre segue a topologia física. Por exemplo, em uma rede fisicamente em estrela, os dados podem se comportar como se estivessem em uma topologia em barramento, dependendo de como os pacotes de dados são transmitidos entre os dispositivos.

**COLOCAR UMA FIGURA DA TOPOLOGIA LÓGICA**

## Tipos de Meios de Transmissão

Os meios de transmissão são os canais pelos quais os dados se movem de um dispositivo para outro em uma rede. Eles podem ser classificados em três grandes categorias: par metálico, óptico e eletromagnético. Cada um desses meios tem características próprias que influenciam sua velocidade, capacidade, e alcance.

### Par metálico

   O par metálico é um dos meios mais comuns e tradicionais usados para transmissão de dados, especialmente em redes locais e de telefonia. Ele utiliza cabos de cobre ou outro material metálico condutor para transmitir sinais elétricos. Existem dois tipos principais:

* Cabo coaxial: um condutor central de cobre cercado por uma malha metálica, usado principalmente em TV a cabo e redes antigas.
* Cabo de par trançado (UTP/STP): dois fios de cobre trançados entre si, que ajudam a reduzir interferências eletromagnéticas. Esse é o tipo mais comum em redes de computadores, especialmente em conexões Ethernet.
* Vantagens: baixo custo, facilidade de instalação e flexibilidade.
* Desvantagens: menor alcance e susceptibilidade a interferências em comparação com outros meios.


COLOCAR FOTOS DOS TIPOS DE CABOS

### Óptico

   O meio óptico utiliza fibras ópticas feitas de vidro ou plástico para transmitir dados por meio de pulsos de luz, em vez de sinais elétricos. A fibra óptica é capaz de transportar grandes quantidades de dados a altas velocidades por longas distâncias com mínima perda de sinal.

* Fibra monomodo: Ideal para transmissões de longa distância, geralmente em WANs, devido à baixa atenuação e alta capacidade.
* Fibra multimodo: Usada em curtas distâncias, como dentro de prédios ou campus, oferecendo também alta capacidade, mas com mais perda de sinal.
* Vantagens: Alta velocidade, grande capacidade de dados e imunidade a interferências eletromagnéticas.
* Desvantagens: custo mais alto e maior complexidade de instalação e manutenção.

### Eletromagnético

   O meio eletromagnético envolve a transmissão de dados por ondas de rádio, micro-ondas, ou infravermelho através do ar, sem a necessidade de cabos físicos. Esse tipo de transmissão é amplamente utilizado em redes sem fio (wireless).

* Ondas de rádio: usadas em redes Wi-Fi, comunicações de satélite e redes de longa distância (LTE/5G).
* Micro-ondas: usadas para transmissões de longa distância em linhas de visão direta, como em comunicações entre torres de transmissão.
* Infravermelho: Utilizado em comunicações de curta distância, como controles remotos ou em alguns dispositivos IoT.
* Vantagens: flexibilidade e mobilidade, já que não depende de cabos.
* Desvantagens: susceptibilidade a interferências, obstáculos físicos e limitações de alcance e largura de banda.



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



