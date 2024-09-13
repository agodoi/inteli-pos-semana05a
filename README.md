# Introdução às Redes de Computadores

## (1) Topologias de Rede

Topologia de Rede é a maneira como os elementos de uma rede estão organizados e interligados. Ela pode ser classificada em duas categorias: **topologia física** e **topologia lógica**. 

### (1.1) Topologia Física

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

### (1.2) Topologia Lógica

A topologia lógica descreve como os dados se movem dentro da rede, ou seja, o caminho que as informações seguem independentemente da disposição física dos cabos e dispositivos. É sobre o fluxo de dados entre os dispositivos, que nem sempre segue a topologia física. Por exemplo, em uma rede fisicamente em estrela, os dados podem se comportar como se estivessem em uma topologia em barramento, dependendo de como os pacotes de dados são transmitidos entre os dispositivos.

**COLOCAR UMA FIGURA DA TOPOLOGIA LÓGICA**

---

## (2) Tipos de Meios de Transmissão

   Os meios de transmissão são os canais pelos quais os dados se movem de um dispositivo para outro em uma rede. Eles podem ser classificados em três grandes categorias: par metálico, óptico e eletromagnético. Cada um desses meios tem características próprias que influenciam sua velocidade, capacidade, e alcance.

### (2.1) Par metálico

   O par metálico é um dos meios mais comuns e tradicionais usados para transmissão de dados, especialmente em redes locais e de telefonia. Ele utiliza cabos de cobre ou outro material metálico condutor para transmitir sinais elétricos. Existem dois tipos principais:

* Cabo coaxial: um condutor central de cobre cercado por uma malha metálica, usado principalmente em TV a cabo e redes antigas.
* Cabo de par trançado (UTP/STP): dois fios de cobre trançados entre si, que ajudam a reduzir interferências eletromagnéticas. Esse é o tipo mais comum em redes de computadores, especialmente em conexões Ethernet.
* Vantagens: baixo custo, facilidade de instalação e flexibilidade.
* Desvantagens: menor alcance e susceptibilidade a interferências em comparação com outros meios.


#### (2.1.1) BOAS PRÁTICAS [30min] Crimpagem de cabo UTP e Teste

Crimpar um cabo UTP (Unshielded Twisted Pair) Cat 5 exige atenção a alguns detalhes para garantir uma conexão eficiente e estável. Aqui estão as boas práticas para esse processo:

### Boas Práticas para Crimpar um Cabo UTP Cat 5

Sua missão é crimpar um cabo UTP CAT 5 com um conector RJ45 em cada ponta e passar no teste de condutividade. Usar o padrão 568A nas duas pontas. Você também pode optar pelo 568B nas duas pontas.

1. **Escolha do Cabo e Conectores Corretos**
   - Verifique se o cabo é compatível com o padrão Cat 5.
   - Utilize conectores RJ-45 adequados para cabos Cat 5 (ou Cat 5e).
   
2. **Corte Limpo do Cabo**
   - Utilize uma ferramenta de corte para garantir que o cabo seja cortado de forma reta e precisa, evitando fios desalinhados que podem dificultar a conexão.

3. **Desencape o Cabo Com Cuidado**
   - Ao remover a capa externa do cabo, deixe expostos cerca de 2,5 cm (1 polegada) dos pares trançados internos.
   - Não corte ou danifique os fios internos ao desencapar a parte externa.

4. **Desenrolar e Organizar os Fios**
   - Separe os pares de fios e os alinhe de acordo com o padrão escolhido (T568A ou T568B).
   - Certifique-se de que os fios estão alinhados e retos antes de inserir no conector.
   - Não desenrole demais os fios; mantenha a torção o mais próximo possível do conector, pois isso ajuda a minimizar interferências.

5. **Escolha do Padrão Correto**
   - Decida entre o padrão **T568A** ou **T568B** e certifique-se de seguir o mesmo padrão em ambas as extremidades do cabo, especialmente se estiver fazendo um cabo patch.
   - As combinações de cores para o padrão T568A são:
     - Verde/Branco
     - Verde
     - Laranja/Branco
     - Azul
     - Azul/Branco
     - Laranja
     - Marrom/Branco
     - Marrom
   - Para o padrão T568B (mais usado em redes residenciais):
     - Laranja/Branco
     - Laranja
     - Verde/Branco
     - Azul
     - Azul/Branco
     - Verde
     - Marrom/Branco
     - Marrom

6. **Inserção Correta dos Fios no Conector**
   - Certifique-se de que os fios estão perfeitamente alinhados e nivelados antes de inserir no conector RJ-45.
   - Pressione firmemente os fios dentro do conector até que cada um toque seu respectivo pino de metal.
   - O cabo externo (capa) deve estar preso dentro do conector para maior resistência e durabilidade.

7. **Uso da Ferramenta de Crimpagem**
   - Posicione o conector no alicate de crimpagem e aperte firmemente para fixar os contatos metálicos nos fios.
   - Certifique-se de que o conector está totalmente inserido no alicate antes de crimpar para evitar crimpar mal e danificar o conector.

8. **Teste o Cabo**
   - Após crimpar, utilize um **testador de cabos** para garantir que todos os fios estão corretamente conectados e o cabo está funcionando corretamente.
   - Verifique se todos os pares estão funcionando e se não há fios cruzados ou mal conectados.

---

#### (2.1.2) BOAS PRÁTICA [20min] Emendas de Cabos de Dados

COLOCAR IMAGEM DE UMA EMENDA DE CABO FLEXÍVEL

Fazer emendas de cabos coaxiais exige cuidado para garantir que o sinal seja transmitido corretamente, sem perda de qualidade ou interferência. Aqui estão algumas boas práticas ao realizar esse tipo de emenda:

### Boas Práticas para Emendas de Cabos Coaxiais

1. **Utilize Conectores e Ferramentas de Qualidade**
   - Use conectores coaxiais de boa qualidade, compatíveis com o tipo de cabo (RG6, RG59, etc.).
   - Ferramentas adequadas, como alicates decapadores e crimpatrizes, são essenciais para garantir uma emenda firme e sem danos ao cabo.

2. **Corte Limpo e Reto do Cabo**
   - Ao cortar o cabo coaxial, utilize uma ferramenta apropriada para garantir que o corte seja reto e uniforme. Alicates cegos deixam rebarbas que podem fechar curto.
   - Um corte torto pode causar problemas de conexão ou dificuldade ao fixar os conectores.

3. **Desencape o Cabo com Cuidado**
   - Utilize uma ferramenta decapadora para remover a camada externa do cabo coaxial. É importante remover a quantidade correta da capa + malha sem danificar o condutor central.
   - Deixe expostos o condutor central (fio de cobre ou alumínio).
   - Certifique-se que a malha metálica não está encostando no fio central.
   - Alguns conectores de coaxial exigem que a malha seja preservada dobrando-a cuidadosamente para trás para evitar que entre em contato com o condutor central.

4. **Não Deixe Exposta a Blindagem**
   - A malha de proteção e o condutor central nunca devem se tocar, pois isso pode causar curtos-circuitos e perda de sinal.
   - Após desencapar, certifique-se de que a malha está dobrada e organizada, e o condutor central está isolado.

5. **Use Conectores F (ou outros conectores apropriados)**
   - Utilize conectores F, BNC ou outros apropriados para o tipo de cabo coaxial que está sendo utilizado. Os conectores devem ser crimpos ou rosqueados corretamente para garantir boa conexão.
   - Conectores F exigem que o condutor central passe pelo orifício no centro do conector, e a malha fique em contato com o corpo metálico do conector para fazer a blindagem adequada.

COLOCAR FOTOS

6. **Uso de Adaptadores de Emenda**
   - Para emendas diretas entre dois cabos coaxiais, utilize adaptadores de emenda específicos (barril de emenda coaxial). Eles garantem uma emenda estável e minimizam a perda de sinal.
   - Evite emendas improvisadas (como fitas isolantes), que podem prejudicar a qualidade do sinal e a durabilidade da conexão.

COLOCA FOTOS

7. **Verificação da Impedância**
   - Verifique se os conectores e cabos utilizados são compatíveis em termos de impedância. Cabos coaxiais são normalmente de 50 ou 75 ohms, e é importante manter a mesma impedância ao longo de toda a conexão para evitar perda de sinal ou reflexões.

8. **Dobras e passagens**
   - Jamais faça dobras de 90º no cabo coaxial, pois isso danifica internamente a estrutura do material dielétrico que separa o condutor central da malha metálica, causando reflexões do sinal e perdas do dBm.

9. **Isolamento Adequado**
   - Certifique-se de que o condutor central e a malha estão bem isolados para evitar interferências e curto-circuitos.
   - Para isso, use um multímetro na escala ôhmica e um terminal de 75 ohms conectado na outra ponta do cabo coaxial.
   - Após conectar o cabo coaxial em um conector, isole a emenda adequadamente com **fita isolante de autofusão** fazendo uma camada de ida e outra camada de volta partindo do lado do cabo e cobrindo até o conector metálico em um comprimento equivalente a um conector sobre a capa e a emenda. Sobreposição de 50%.
   - Após fazer a camada de ida e volta com a fita de autofusão, faça outra 2 camadas de ida e volta usando fita isolante. Sobreposição de 50%.
   - Finalize a emenda com uma fita tipo Hellerman travando as pontas da fita isolante para não se soltar no calor.
   
10. **Teste Final da Conexão**
    - Após a emenda, teste a qualidade do sinal usando um multimetro e o terminal de carga de 75 ohms. O valor marcado no multímetro deve o mais próximo de 75 ohms.
    - Verifique a integridade da conexão e, se necessário, refaça a crimpagem ou substitua os conectores.

---

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

---

#### (2.3.1) Antenas

Aqui está um levantamento dos principais tipos de antenas, suas aplicações, vantagens e desvantagens:

### 1. **Antena Dipolo**
   
#### Descrição:
A antena dipolo é uma das antenas mais simples e comuns, composta por dois condutores retos alinhados de maneira colinear. Geralmente é utilizada para transmissões em VHF e UHF.

#### Aplicações:
- Radiodifusão (rádio AM/FM)
- Comunicações de rádio e TV
- Redes de comunicação sem fio em curta distância (Wi-Fi)

#### Vantagens:
- Fácil de construir e implementar
- Funciona bem em ambientes de linha de visão
- Custo baixo

#### Desvantagens:
- Ganho relativamente baixo
- Sensível a interferências e ruídos em áreas urbanas

---

### 2. **Antena Yagi-Uda**

#### Descrição:
A antena Yagi consiste em um dipolo ativo e uma série de elementos direcionais que melhoram o ganho em uma direção específica. É uma antena direcional bastante utilizada para sinais de TV e rádio.

#### Aplicações:
- Recepção de TV
- Comunicações ponto-a-ponto de rádio
- Sistemas de transmissão e recepção de sinais em VHF e UHF

#### Vantagens:
- Alto ganho direcional
- Boa para distâncias médias e longas em ambientes de linha de visão
- Menor interferência por ser direcional

#### Desvantagens:
- Direcional, requer alinhamento preciso
- Eficiência reduzida fora da linha de visão

---

### 3. **Antena Parabólica**

#### Descrição:
A antena parabólica utiliza uma superfície em formato de prato parabólico para refletir as ondas de rádio em direção a um ponto focal, onde o receptor ou transmissor está localizado.

#### Aplicações:
- Telecomunicações via satélite
- Antenas de televisão por satélite
- Comunicações ponto-a-ponto de longa distância

#### Vantagens:
- Muito alto ganho
- Ótima para comunicações de longa distância
- Direcionalidade precisa, reduzindo interferências

#### Desvantagens:
- Exige alinhamento muito preciso
- Grande tamanho e estrutura complexa
- Funciona melhor apenas em linha de visão

---

### 4. **Antena Log-Periódica**

#### Descrição:
Uma antena log-periódica é composta por vários elementos de tamanhos variáveis dispostos de maneira sequencial. Ela é projetada para operar em uma ampla faixa de frequências.

#### Aplicações:
- Antenas de TV multibanda
- Sistemas de comunicação que exigem múltiplas frequências
- Monitoramento de espectro de rádio

#### Vantagens:
- Larga faixa de frequências
- Direcionalidade moderada
- Boa para situações que exigem flexibilidade de banda

#### Desvantagens:
- Ganho moderado comparado a outras antenas direcionais
- Mais complexa de construir

---

### 5. **Antena Omnidirecional**

#### Descrição:
As antenas omnidirecionais transmitem e recebem sinais em todas as direções no plano horizontal, sendo ideais para cobrir grandes áreas ao redor do ponto de emissão.

#### Aplicações:
- Redes Wi-Fi (roteadores)
- Comunicações móveis (torres de celular)
- Redes de comunicação de curto alcance

#### Vantagens:
- Cobertura ampla em todas as direções
- Ideal para áreas onde os receptores estão distribuídos ao redor da antena
- Fácil instalação e uso

#### Desvantagens:
- Ganho mais baixo comparado às antenas direcionais
- Menos eficiente para comunicações de longa distância

---

### 6. **Antena de Patch (Microstrip)**

#### Descrição:
Antenas de patch, ou microstrip, são compostas por uma pequena superfície metálica plana que emite ou recebe sinais. Elas são comumente integradas a superfícies e são compactas.

#### Aplicações:
- Comunicações via satélite
- Redes móveis e Wi-Fi
- Dispositivos portáteis (antenas embutidas em celulares)

#### Vantagens:
- Muito compacta e leve
- Fácil de integrar em superfícies planas
- Boa para aplicações móveis e portáteis

#### Desvantagens:
- Ganho relativamente baixo
- Faixa de frequência limitada

---

### 7. **Antena de Loop**

#### Descrição:
Antenas de loop consistem em um fio condutor em formato de círculo ou elipse. Elas podem ser pequenas (loop magnético) ou grandes, dependendo da aplicação.

#### Aplicações:
- Radiodifusão AM
- Comunicações militares e submarinas (loop magnético)
- Monitoramento de espectro de rádio

#### Vantagens:
- Pequeno tamanho para frequências baixas
- Boa resistência à interferência eletromagnética
- Utilizável em ambientes com espaço restrito

#### Desvantagens:
- Ganho menor em comparação com outras antenas
- Direcionalidade limitada

---

### 8. **Antena Slot**

#### Descrição:
A antena slot é uma abertura feita em uma superfície condutora, como uma folha de metal, que irradia sinais de rádio. Ela pode ser usada em várias formas e é aplicada principalmente em micro-ondas.

#### Aplicações:
- Antenas de radar
- Comunicações de micro-ondas
- Sistemas de navegação aérea

#### Vantagens:
- Compacta e discreta
- Boa para frequências de micro-ondas
- Direcionalidade moderada

#### Desvantagens:
- Ganho moderado
- Pode ser complexa de construir para aplicações de alta potência

---

### 9. **Antena Helicoidal**

#### Descrição:
Uma antena helicoidal é formada por um fio enrolado em forma de hélice e é utilizada para frequências que vão desde VHF até micro-ondas.

#### Aplicações:
- Comunicações via satélite
- Antenas para receptores GPS
- Sistemas de transmissão em frequências elevadas

#### Vantagens:
- Boa para frequências elevadas
- Compacta para sua faixa de operação
- Capacidade de operar em polarização circular

#### Desvantagens:
- Ganho relativamente baixo para comunicações de longa distância
- Direcionalidade limitada


### 10. **Antena de Chifre (Horn Antenna)**

#### Descrição:
As antenas de chifre utilizam uma abertura em forma de cone para direcionar as ondas de rádio em frequências de micro-ondas. São geralmente usadas em conjunto com guias de onda.

#### Aplicações:
- Radar e radiotelescópios
- Comunicações de micro-ondas
- Medições de campo de antenas

#### Vantagens:
- Alto ganho em frequências de micro-ondas
- Direcionalidade precisa
- Baixa distorção de sinal

#### Desvantagens:
- Grande tamanho físico para operações de alta potência
- Difícil de fabricar e ajustar para frequências mais baixas



#### (2.3.2) Comunicação via Satélite


A comunicação via satélite desempenha um papel essencial nas redes de computadores, especialmente quando se trata de conectar áreas geograficamente dispersas e fornecer cobertura global. Aqui estão os principais conceitos que podem ser explorados para um curso de alto nível sobre Redes de Computadores:

### 1. **Princípio de Funcionamento da Comunicação via Satélite**
A comunicação via satélite envolve a transmissão de sinais de rádio entre estações terrestres e satélites que orbitam a Terra. Esses satélites recebem, amplificam e retransmitem os sinais de volta para a Terra, permitindo a comunicação entre locais distantes.

#### Componentes principais:
- **Estação transmissora (uplink)**: Envia o sinal da Terra para o satélite.
- **Satélite**: Recebe o sinal, o amplifica e retransmite para outra região da Terra.
- **Estação receptora (downlink)**: Recebe o sinal do satélite e o direciona ao destino final.

### 2. **Órbitas de Satélites**
Satélites podem operar em diferentes órbitas, cada uma com suas características, dependendo da aplicação da rede de comunicação.

- **Órbita Geoestacionária (GEO)**: Satélites estão a aproximadamente 35.786 km acima do equador, mantendo uma posição fixa em relação à Terra. Usada principalmente para comunicações de longa distância e televisão por satélite.
  - *Vantagem*: Cobertura contínua de grandes áreas, incluindo a cobertura de continentes inteiros.
  - *Desvantagem*: Latência elevada (cerca de 250 ms), o que pode afetar a qualidade em aplicações de tempo real, como videoconferências.

- **Órbita Baixa da Terra (LEO)**: Satélites a altitudes entre 500 e 2.000 km, movendo-se rapidamente em torno da Terra.
  - *Vantagem*: Baixa latência (20-40 ms), ideal para serviços de internet de alta velocidade, como as constelações de satélites Starlink.
  - *Desvantagem*: Cobertura limitada, o que requer uma constelação de satélites para garantir cobertura contínua.

- **Órbita Média da Terra (MEO)**: Satélites entre 2.000 e 35.786 km, usados para comunicações de alcance intermediário.
  - *Vantagem*: Latência moderada (60-80 ms) com cobertura maior que os satélites LEO.
  - *Desvantagem*: Menor cobertura e maior latência que os satélites GEO.

### 3. **Frequências de Operação**
A comunicação via satélite utiliza várias bandas de frequência para transmissão, dependendo da aplicação e da distância.

- **Banda C (4-8 GHz)**: Usada principalmente para transmissões de televisão e algumas comunicações de voz.
  - *Vantagem*: Alta resistência a interferências atmosféricas.
  - *Desvantagem*: Necessita de antenas maiores.

- **Banda Ku (12-18 GHz)**: Muito usada para televisão por satélite e internet via satélite.
  - *Vantagem*: Antenas menores e mais acessíveis.
  - *Desvantagem*: Vulnerável a interferências climáticas (chuvas intensas).

- **Banda Ka (26-40 GHz)**: Usada para internet de alta velocidade e novos serviços de satélites.
  - *Vantagem*: Oferece alta largura de banda.
  - *Desvantagem*: Muito sensível à interferência atmosférica, como chuva.

### 4. **Latência e Considerações de Desempenho**
A latência é uma questão importante na comunicação via satélite, especialmente em satélites geoestacionários (GEO). Isso se deve à grande distância que os sinais precisam percorrer. Para mitigar esse efeito, satélites de órbitas mais baixas (LEO) estão sendo utilizados para aplicações que exigem baixa latência, como jogos online e videoconferências.

### 5. **Aplicações da Comunicação via Satélite**
- **Internet via satélite**: Usada em áreas rurais e remotas onde a infraestrutura terrestre de internet é limitada ou inexistente. Exemplos incluem Starlink, HughesNet, e Viasat.
- **Comunicações de emergência**: Em desastres naturais ou situações em que a infraestrutura terrestre é destruída, a comunicação via satélite pode fornecer conectividade rápida e eficaz.
- **Transmissões de TV**: A televisão via satélite, como a DirecTV ou a Sky, usa satélites para enviar conteúdo diretamente para os usuários finais.
- **Sistemas de navegação**: O GPS é um exemplo de comunicação via satélite para navegação, permitindo rastreamento e posicionamento em tempo real.

### 6. **Desafios da Comunicação via Satélite**
- **Interferência atmosférica**: Fenômenos meteorológicos, como chuvas fortes e tempestades, podem afetar a qualidade do sinal, especialmente nas bandas Ku e Ka.
- **Altos custos de lançamento**: Colocar satélites em órbita é caro, tanto em termos de lançamento quanto de manutenção.
- **Capacidade limitada**: Embora satélites modernos tenham aumentado a largura de banda disponível, a capacidade ainda é limitada em comparação com redes terrestres de fibra óptica.

### 7. **Tecnologias Emergentes**
- **Constelações de satélites de órbita baixa (LEO)**: Empresas como SpaceX (Starlink) e Amazon (Project Kuiper) estão desenvolvendo grandes constelações de satélites em órbita baixa para fornecer internet de alta velocidade e baixa latência em todo o mundo.
  
- **Satélites de órbita inclinada**: Satélites que cobrem regiões específicas, como áreas polares, onde satélites geoestacionários não têm cobertura direta.

### 8. **Comparação com Outras Tecnologias de Rede**
- **Vantagens**:
  - Cobertura global, incluindo áreas remotas.
  - Alta confiabilidade em zonas de desastre ou onde a infraestrutura terrestre é limitada.
- **Desvantagens**:
  - Maior latência em comparação com redes terrestres (especialmente fibra óptica).
  - Dependência de condições climáticas para qualidade de sinal.

### 9. **Segurança na Comunicação via Satélite**
A comunicação via satélite enfrenta desafios de segurança, incluindo criptografia de dados para evitar interceptações e técnicas de mitigação de interferências, como jamming ou spoofing. Métodos modernos de segurança incluem o uso de chaves criptográficas robustas e firewalls dedicados para proteger as estações terrestres e satélites.



### (3) Potência dBm

### Conceito de dBm

O **dBm** é uma unidade de medida que expressa a potência de um sinal em **decibéis** (dB) em relação a **1 milivatt (mW)**. É uma medida logarítmica utilizada para avaliar a força de um sinal de transmissão ou recepção, como o sinal de Wi-Fi em uma rede LAN.

- **dB** (decibéis) é uma medida relativa, usada para comparar níveis de potência.
- **dBm** é uma medida absoluta, referida a uma potência de 1 mW.

A fórmula para converter a potência em watts para dBm é:

\[
\text{dBm} = 10 \cdot \log_{10} \left( \frac{\text{P (em milivats)}}{1 mW} \right)
\]

Por exemplo:
- Se a potência do sinal é de 1 mW, o valor em dBm será 0 dBm.
- Se a potência é 10 mW, o valor será 10 dBm.

### Importância do dBm na Medição de Sinal Wi-Fi

No contexto de redes LAN, particularmente para redes Wi-Fi, o **dBm** é extremamente importante para avaliar a **qualidade e a força do sinal**. Ele indica o nível de potência que um dispositivo está recebendo do ponto de acesso (AP). Como o sinal de Wi-Fi tende a se atenuar à medida que se distancia do roteador ou encontra obstáculos (como paredes), o valor de dBm ajuda a determinar a qualidade da conexão.

### Interpretação dos Valores de dBm

Como o dBm é uma escala logarítmica, números mais negativos indicam sinais mais fracos. Aqui está uma escala de interpretação comum para redes Wi-Fi:

- **0 a -30 dBm**: Sinal excelente. O dispositivo está muito próximo ao roteador, e a conexão será muito rápida e estável.
- **-31 a -50 dBm**: Sinal muito bom. Ainda proporciona alta qualidade de conexão.
- **-51 a -60 dBm**: Sinal bom. A maioria das aplicações funcionará sem problemas.
- **-61 a -70 dBm**: Sinal aceitável. Pode haver alguma queda na velocidade ou na estabilidade da conexão, especialmente em ambientes congestionados.
- **-71 a -80 dBm**: Sinal fraco. A conexão pode ser instável, com quedas de velocidade ou interrupções.
- **-81 dBm ou mais fraco**: Sinal muito fraco ou inexistente. Provavelmente, o dispositivo não conseguirá se conectar.

### Por que Medir o dBm em Redes Wi-Fi?

- **Otimização de Cobertura**: Medir o dBm permite identificar pontos "cegos" ou áreas de sinal fraco dentro de um ambiente, como em um escritório ou residência. Isso ajuda a otimizar a localização de roteadores ou pontos de acesso.
  
- **Diagnóstico de Problemas de Conexão**: Se um dispositivo estiver experimentando problemas de conexão, medir o dBm pode ajudar a diagnosticar se o problema é causado por um sinal fraco.

- **Configuração de Redes Mesh**: Em redes Wi-Fi que utilizam tecnologia Mesh, a medição de dBm ajuda a posicionar os nós de forma eficiente para maximizar a cobertura e minimizar a interferência.

- **Análise de Interferência**: O dBm também pode ser utilizado para detectar interferências de outros dispositivos que operam na mesma frequência, como micro-ondas ou telefones sem fio, permitindo ajustes no canal de operação do Wi-Fi.

### Aplicação Prática no Curso de Redes

Em um curso de redes de computadores, a medição do dBm pode ser abordada através de atividades práticas, como:

1. **Utilização de Ferramentas de Medição**: Softwares e aplicativos como **Wi-Fi Analyzer** ou **inSSIDer** podem ser usados para medir o dBm em diferentes pontos de uma rede Wi-Fi.
   
2. **Mapeamento de Sinal Wi-Fi (Heatmaps)**: Ensinar os alunos a criar um mapa de sinal Wi-Fi, mostrando as áreas com diferentes níveis de dBm. Isso visualiza a cobertura da rede e permite ajustes para melhorar o desempenho.

3. **Configuração de Antenas e Amplificadores**: Compreender o dBm é essencial ao ajustar antenas, amplificadores ou repetidores de sinal para melhorar a cobertura de uma rede Wi-Fi.

4. **Simulações**: Emular cenários onde o sinal Wi-Fi tem uma forte atenuação (por exemplo, obstáculos como paredes) e como o valor do dBm muda conforme o ambiente.

### Conclusão

O **dBm** é um conceito fundamental para quem deseja medir e melhorar a qualidade de uma rede Wi-Fi, permitindo entender melhor a distribuição do sinal e identificar problemas de cobertura. Ensinar aos alunos a interpretação dos valores de dBm e como aplicar esse conhecimento em cenários práticos garante que eles possam planejar, otimizar e solucionar problemas em redes LAN, especialmente em ambientes de redes sem fio.


### (3.1) BOAS PRÁTICAS [15min] Exercícios teóricos


### (3.2) BOAS PRÁTICAS [10min] Medição do dBm


### (3.3) BOAS PRÁTICAS [30min] Mapa de Calor WiFi

testar diferenças entre posições de antenas, gaiola de faraday, uso de metais próximos 

### (3.3) BOAS PRÁTICAS [30min] Alinhamento de antena de satélites


