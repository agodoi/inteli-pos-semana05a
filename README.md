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


### (3.1) BOAS PRÁTICAS [15min] Exercícios teóricos


### (3.2) BOAS PRÁTICAS [10min] Medição do dBm


### (3.3) BOAS PRÁTICAS [30min] Mapa de Calor WiFi

testar diferenças entre posições de antenas, gaiola de faraday, uso de metais próximos 

### (3.3) BOAS PRÁTICAS [30min] Alinhamento de antena de satélites


