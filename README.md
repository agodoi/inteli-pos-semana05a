# Introdução às Redes de Computadores

## (1) Tipos de Topologias de Rede

E a maneira como os elementos de uma rede estão organizados e interligados. Ela pode ser classificada em duas categorias: **topologia física** e **topologia lógica**. 

### (1.1) Física

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

### (1.2) Lógica

A topologia lógica descreve como os dados se movem dentro da rede, ou seja, o caminho que as informações seguem independentemente da disposição física dos cabos e dispositivos. É sobre o fluxo de dados entre os dispositivos, que nem sempre segue a topologia física. Por exemplo, em uma rede fisicamente em estrela, os dados podem se comportar como se estivessem em uma topologia em barramento, dependendo de como os pacotes de dados são transmitidos entre os dispositivos.

**COLOCAR UMA FIGURA DA TOPOLOGIA LÓGICA**

## (2) Tipos de Meios de Transmissão

Os meios de transmissão são os canais pelos quais os dados se movem de um dispositivo para outro em uma rede. Eles podem ser classificados em três grandes categorias: par metálico, óptico e eletromagnético. Cada um desses meios tem características próprias que influenciam sua velocidade, capacidade, e alcance.

### (2.1) Par metálico

   O par metálico é um dos meios mais comuns e tradicionais usados para transmissão de dados, especialmente em redes locais e de telefonia. Ele utiliza cabos de cobre ou outro material metálico condutor para transmitir sinais elétricos. Existem dois tipos principais:

* Cabo coaxial: um condutor central de cobre cercado por uma malha metálica, usado principalmente em TV a cabo e redes antigas.
* Cabo de par trançado (UTP/STP): dois fios de cobre trançados entre si, que ajudam a reduzir interferências eletromagnéticas. Esse é o tipo mais comum em redes de computadores, especialmente em conexões Ethernet.
* Vantagens: baixo custo, facilidade de instalação e flexibilidade.
* Desvantagens: menor alcance e susceptibilidade a interferências em comparação com outros meios.


#### (2.1.1) Crimpagem de cabo UTP e Teste

Boas práticas

#### (2.1.2) Boas Práticas de Emendas de Cabos de Dados

Boas práticas com coaxial e cabos flexíveis


### (2.2) Óptico

   O meio óptico utiliza fibras ópticas feitas de vidro ou plástico para transmitir dados por meio de pulsos de luz, em vez de sinais elétricos. A fibra óptica é capaz de transportar grandes quantidades de dados a altas velocidades por longas distâncias com mínima perda de sinal.

* Fibra monomodo: Ideal para transmissões de longa distância, geralmente em WANs, devido à baixa atenuação e alta capacidade.
* Fibra multimodo: Usada em curtas distâncias, como dentro de prédios ou campus, oferecendo também alta capacidade, mas com mais perda de sinal.
* Vantagens: Alta velocidade, grande capacidade de dados e imunidade a interferências eletromagnéticas.
* Desvantagens: custo mais alto e maior complexidade de instalação e manutenção.

### (2.3) Eletromagnético

   O meio eletromagnético envolve a transmissão de dados por ondas de rádio, micro-ondas, ou infravermelho através do ar, sem a necessidade de cabos físicos. Esse tipo de transmissão é amplamente utilizado em redes sem fio (wireless).

* Ondas de rádio: usadas em redes Wi-Fi, comunicações de satélite e redes de longa distância (LTE/5G).
* Micro-ondas: usadas para transmissões de longa distância em linhas de visão direta, como em comunicações entre torres de transmissão.
* Infravermelho: Utilizado em comunicações de curta distância, como controles remotos ou em alguns dispositivos IoT.
* Vantagens: flexibilidade e mobilidade, já que não depende de cabos.
* Desvantagens: susceptibilidade a interferências, obstáculos físicos e limitações de alcance e largura de banda.

#### (2.3.1) Antenas

tipos e utilidades


#### (2.3.2) Comunicação via Satélite


### (3) Potência dBm


### (3.1) Exercícios teóricos


### (3.2) Exercícios práticos de medição do dBm usando celular

### (3.3) Mapa de Calor WiFi

### (3.3) Alinhamento de antena de satélites


