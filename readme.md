# KICAD

## SUMÁRIO
- [CARACTERISTICAS DO SOFTWARE](#CARACTERISTICAS-DO-SOFTWARE)
- [DOWNLOAD DO SOFTWARE](#DOWNLOAD-DO-SOFTWARE)
- [CRIANDO UM NOVO PROJETO](#CRIANDO-UM-NOVO-PROJETO)
    - [Adicionar Componente ](#Adicionar-Componente)
    - [Rotacionar componente](#Rotacionar-componente)
    - [Duplicar Componente](#Duplicar-Componente)
    - [Mover Componentes ](#Mover-Componentes)
- [DIAGRAMAS ESQUEMATICOS](#DIAGRAMAS-ESQUEMATICOS)
    - [Projeto Astável 555](#Projeto-Astável-555)
    - [Inserir Alimentação ao circuito e o GND](#Inserir-Alimentação-ao-circuito-e-o-GND)
    - [Inserir wire](#Inserir-wire)
    - [Mover Componente sem perder a linha](#Mover-Componente-sem-perder-a-linha)
    - [Rotações do compotente sobre eixos X e Y](#Rotações-do-compotente-sobre-eixos-X-e-Y)
    - [Alterar o Nome e valores dos componentes](#Alterar-o-Nome-e-valores-dos-componentes)
    - [Anotate do Diagrama Esquemático](#Anotate-do-Diagrama-Esquemático)
    - [Achar Componente mais rápido](#Achar-Componente-mais-rápido)
    - [Organização Profissional de esquemáticos](#organização-profissional-de-esquemáticos)
    - [Método para simular circuitos](#método-para-simular-circuitos)
    - [Criando novos componentes e bibliotecas](#criando-novos-componentes-e-bibliotecas)
    - [Exportando seus esquemáticos profissionais](#Exportando-seus-esquemáticos-profissionais)
- [PLACA DE CIRCUITO IMPRESSO](#PLACA-DE-CIRCUITO-IMPRESSO)
    - [Criando o primeiro lay-out de PCB em face simples](#Criando-o-primeiro-lay-out-de-PCB-em-face-simples)



- [OBSERVAÇÕES](#OBSERVAÇÕES)

## CARACTERISTICAS DO SOFTWARE
- Multiplataforma 
    - Windows 
    - Linux
    - Mac
    - ...
- Gratuito e Ilimitado
- Extensão dos arquivos esquemáticos são ".sch"
- Extensão do layout ".kicad_pcb"
- Possui simulador (não tão eficiente)
<br>[↑](#SUMÁRIO)

## DOWNLOAD DO SOFTWARE
- Site:
    - https://www.kicad.org/
    - Link recomendado: CERN
<br>[↑](#SUMÁRIO)

## CRIANDO UM NOVO PROJETO
- Caminho 
    - File > New > Project ou File > New Project
    - Em arquivos do projeto é gerado uma arvore de arquivos com os formatos kicad_sch e kocad_pcb
- Edição e configuração do arquivo de esquema eletrico 
    - Duplo clique sobre o arquivo com extensão kicad_sch
- Configurações da Página 
    - Arquivos > Configurações da Página ...
    - Será aberto uma janela para inclusão de dados que irão na legenda no canto inferior da página 
<br>[↑](#SUMÁRIO)

### Adicionar Componente 
- Na tela de elaboração da pcb clicar em "A"(add)
    - Será aberto uma nova janela, onde é possivel selecionar o componente
<br>[↑](#SUMÁRIO)

### Rotacionar componente
- Com o Componente selecionado clicar em "R"(rotate)
<br>[↑](#SUMÁRIO)

### Duplicar Componente 
- Com o cursor sobre o componente clicar "CTRL"+"C" e depois "CTRL"+"V" e posicionar o componete
<br>[↑](#SUMÁRIO)

### Mover Componentes  
- É possivel mover o componente com os direcionais do teclado, (inclusive o cursor);
- Com o cursor sobre o componente, clicar em "M"(move), o componente estará selecionado, a partir disso, alocar o componente na região desejada, ao chegar no local clicar em "ENTER" 
<br>[↑](#SUMÁRIO)

## DIAGRAMAS ESQUEMÁTICOS

### Projeto Astável 555
- Será descrito um passo a passo do desenvolvimento de um projeto simples de um circuito 555 astável;
- Criar novo Projeto 
- File(Arquivos) > Page Settings (Configurações de Página)
    - Configurar data do Projeto 
    - Configurar o tamanho do papel
        - Em geral projetos são feitos em A4
        - Orientação de página em formato paisagem 
    - Escrever o numero da revisão
    - Escrever o título (Nome do projeto)
    - Nome da empresa
    - Compentário1: nome do criador do projeto 
    - Finalização com "ENTER"
- Inserir o componente 555
- Inserir o Power do circuito
- Inserir o GND do circuito
- Conexões 
    - Pin4 em VCC
    - Pin6 em Pin2
- Inserão dos demais componentes para o funcionamento 
- Inserir os valores dos componentes bem como os nome
- Projeto finalizado <br>
![Esquema Finalizado](/img/002.png)
<br>[↑](#SUMÁRIO)

### Inserir Alimentação ao circuito e o GND
- A inserão é feita com a tecla "P" do teclado, seguind a isso verificando a tensão desejada 
<br>[↑](#SUMÁRIO)

### Inserir wire
- Pode ser efetuado com a tecla "W"
- Para fazer as quebras em 90° utilizar a tecla "Enter"
<br>[↑](#SUMÁRIO)

### Mover Componente sem perder a linha 
- Utilizar a tecla "G"
<br>[↑](#SUMÁRIO)

### Rotações do compotente sobre eixos X e Y
- Utilizar tecla "X" para o eixo X e a tecla "Y" para o eixo Y com o cursor sobre o componente
<br>[↑](#SUMÁRIO)

### Alterar o Nome e valores dos componentes 
- EM um componente existem dois textos, o texto acima refere-se ao nome e o texto subsequente refere-se ao valor
- Clicando sobre cada um deles com um duplo clique é possivel alterar o nome e o valor 
- A segunda opção para alterar o valor de um componente é com o cursor sobre ele e clicar em "V" 
<br>[↑](#SUMÁRIO)

### Anotate do Diagrama Esquemático
- Dar número aos componentes 
- Geralmente utiliza-se a configuração padrão do proprio KiCad onde a numeração é feita de cima para baixo e da esquerda para a direita 
- O processo é feito no botão abaixo <br> 
![Anotate](/img/001.png)
- Cada inserção de um componente feito após um anotate é necessário um novo anotate
<br>[↑](#SUMÁRIO)


### Achar Componente mais rápido
- Criar novo Projeto para a aula
    - Configurar o Descritivo do projeto 

- Com o KiCad aberto, ao clicar em "A", será aberto uma nova janela com todos os componentes disponiveis para o KiCad
![Biblioteca de Componentes](/img/003.png)
- No espaço filtro digitando apenas uma letra é possivel encontrar de forma rápida alguns compenetes 
    - "r" resistor
    - "c" capacitor
    - "l" indutor
    - "c_p" capacitor polarizado
    - "crys cristal
<br>[↑](#SUMÁRIO)


### Organização Profissional de esquemáticos
- Em eletronica analógica pura, existe uma metodologia um pouco diferente de ligação em relação a circuitos da eletronica digital ou circuitos microcontrolados ou microprocessados
- Exemplo Quarto_Organização_Analogico
    - Amplificador com duplo car diferencial (Circuito amplificador de audio)
    - Não é comum trabalhar com labels(nets com nomes que definem conexão de um ponto a outro do esquemático) em eletronica analógica  
    - É interessante posicionar os componentes mais proximos um do outro quanto possivel 
    - Labels de alimentação e GND são permitidas
    - Procure deixar nivelado as alimentações e os GND
    - Buscar sempre a simetria nos desenhos dos componentes  

- Exemplo Quinto_Organização_Microprocessado
    - Utilizar labels, para cria-las pressionar a tecla "L"
        - Por mais que fisicamente no desenho não exista a conexão o programa entende que existe sim aquela conexão fisica 
    - É interessante separar trechos do circuito com linhas tracejadas que são feitas com o a tecla "I" ou no botão descrito abaixo
![Botão de Linha tracejada](/img/004.png)
    - Observando o seguinte aspecto conforme exemplo abaixo:<br>
![Tracejado em trecho do circuito](/img/005.png)
    - As labels podem ser colocadas sobre as wires conforme acima 
<br>[↑](#SUMÁRIO)


### Método para simular circuitos 
- A simulação fornecida pelo KiCad é muito simples e bem superficial, não sendo a melhor forma de para análise;
- O teste do simulador será feito atraves do projeto  "Sexto_Simul_Test";
    - Circuito resistivo<br> 
    ![Circuito Resistivo](/img/006.png)
- A ferramenta de simulação fica em Tools > Simulator ou em Inspecione > Simulador
- O KiCad possui uma ferramenta de port do circuito criado para o LT Spice que é uma ferramenta de simulação apropriada. Para fazer a conversão ir em Arquivo > Exportar > Exporte a Netlist
    - Apagar a mensagem descrita no campo "Comando externo do simulador" e clicar em "Exporte a Netlist"
    - Será salvo um arquivo com extensão .cir
<br>[↑](#SUMÁRIO)

### Criando novos componentes e bibliotecas
- É possivel criar e editar componentes já existentes 
- Para iniciar a criação de um novo componente na janela principal do KiCad clicar em:
    - Editor de símbolos<br>
    ![Editor de Símbolo](/img/007.png)
    - Será aberto uma nova janela 
- É possivel ao criar um novo componente, salva-lo em uma biblioteca já existente ou criar uma nova biblioteca para armazenar o componente 

- Para criar uma nova biblioteca, clicar em Arquivo > Nova Biblioteca, em seguida será solicitado um nome para a bilbioteca 

- Para criar um novo símbolo clicar em "Criar Novo Símbolo" ou digitar a tecla "N"<br>
![Simbolo](/img/008.png)
    - Para criar um novo símbolo é necessário antes criar uma nova biblioteca, aparentemente não se pode criar simbolos em bibliotecas já existentes do kicad;
    - Deve-se selecionar a biblioteca a qual o componente será alocado e depois clicar em "Criar Novo Símbolo";<br>
    ![New Window](/img/009.png)
    - Em "Nome do símbolo" inserir o nome do componente;
    - Designador de referência padrão pode ser deixado como "U" bem como "A quantidade das unidades por pacote" como "1"
    - Feito isso clicar em "OK" e será apresentado o nome do componente na tela bem como sua letra de referencia (tudo junto);<br>
    ![Paso1](/img/010.png)
    - movido 
    ![Paso2](/img/011.png)
- Feito os passos acima é necessário adicionar os pinos (TODOS DE PREFERENCIA, UM POR UM, DEPOIS É POSSIVEL ORGANIZA-LOS)
    - A adição pode ser feita de duas formas, clicando no icone de adicionar pinos ou clicando em "P"<br>
    ![Paso3](/img/012.png)
    - Será aberto a seguinte janela para configuração do pino;<br>
    ![Paso4](/img/013.png)
    - É importante configurar os pinos na nova janela:
        - "Nome do pino"
        - "Numero do Pino"
        - "Tipo elétrico" colocar bidirecional, (APENAS NÃO COLOCA-LO COMO BIDIRECIONAL QUANDO SOUBER EXATAMENTE DO QUE SE TRATA O PINO)
- As bolinhas em cada pino representa a conexão externa do circuito integrado denvendo elas ficarem para foram 
- Criado todos os pinos se faz necessário a sua organização, recomenda-se conforme o descrito no datasheet do componente:
- Descritivo do componente<br>
![Descritivo do Componente](/img/014.png)
- Após a organização criar o retangulo para efetuar o contorno com a ferramenta "Adicionar retangulo<br>
![Botão Retangulo](/img/015.png)
- Apos isso clicar com o botão direito sobre a linha do retangulo, ir em propriedade e selecionar "Preencha com a cor de fundo do corpo"
- Ficando da seguinte forma:<br>
![Componente Desenhado](/img/016.png)
- Feito isso basta salvar e o componente ja estará pronto para uso 
<br>[↑](#SUMÁRIO)

### Exportando seus esquemáticos profissionais
- Gerar o pdf do esquemático
- Para gerar o pdf será utilizado o projeto no qual foi desenvolvido o amplificador 
- Para gerar o esquemático clicar em "Plot"<br>
![Botão Plot](/img/017.png)
- Na janela aberta é possivel escolher o diretorio em que será salvo, o formato de saida, o tamanho da folha e se colorido e preto e branco 
![Configuração de pdf](/img/018.png)
    - Em geral pdf de esquemáticos são colocados em preto e branco
- Observação: Caso deseje-se gerar mais de um arquivo (preto e branco e colorido) acarretará em um erro pois não é possivel configurar o nome do arquivo de saída. Para não ocorrer o arquivo gerado deve ser mudado de diretorio 
<br>[↑](#SUMÁRIO)

## PLACA DE CIRCUITO IMPRESSO
- Projetos em face simples;
- Dupla face;
- Com circuitos smd;
- Criação de footprint específicas para componentes, caso não exista na biblioteca padrão;
- Geração dos arquivos gerber;
<br>[↑](#SUMÁRIO)

### Criando o primeiro lay-out de PCB em face simples 
- Projeto de um regulador de 5V
    - Os capacitores de entrada são para filtragem do sinal de entrada em especial o eletrolítico
    - O Resistor na saída é limitante de corrente para o led indicador de funcionamento<br>
    ![Esquema Elétrico](/img/019.png)
    - Dar o anotate no circuito para numerar os componentes 
- Após o esquema elétrico montado deve-se verificar algum erro de conexão eletrica indo em Inspecione > Verificador das Regras elétricas
    - Será apresentado alguns erros nesse caso entretanto os erros não devem ser levados em consideração
- Após a analise em cima  efetuar a atribuição dos footprints em "Executa a ferramenta de atribuição de footprint"<br>
![Atribuição de footprint](/img/020.png)
- Será aberto uma nova janela para fazer associação de footprints a cada componente, nesse momento é necessário de ter o conhecimento de cada componente utilizado  
    - É necessário escolher a biblioteca de footprint a esquerda e as medições do footprints filtrados a direita, ao escolher dar um duplo clique 
    - Finalizando o processo a janela ficaria como abaixo;<br>
    ![Atribuição de footprint](/img/021.png)
    - Ao finalizar clicar em "Aplique, Salve o Esquema & Continue"
- Ao que parece a partir da versão 6 do KiCad a geração de netList não é necessária, após o passo anterior, clicar em "Abra a PCI no editor"<br>
![Editar PCI](/img/022.png)
- Na nova Janela aberta, clicar em "Update PCB with changes made to schematic"<br>
![Editar PCI 2](/img/023.png)
    - Todos os componentes serão colocados na folha, deve-se arrastalos para o meio e deve-se organiza-los
    - Os mesmos comandos de organização no editor de esquema também se aplicam aqui (movimento, rotação e etcm)<br>
    ![Organizado](/img/024.png)
- Desenhar as layers
    - Como se trata de uma placa de face simples selecionar na aba Aparence layers > B.Cu<br>
    ![Organizado layer](/img/025.png)
    - Seguido a isso clicar em "Route Track" e a partir disso desenhar as layers acompanhando os riscos brancos do desenho<br>
    ![Route Track](/img/026.png)<br>
    ![Route Track 2](/img/027.png)
- Desenhar o contorno da placa 
    - Selecionar "Edge.Cuts na mesma Guia Aparence layers
- Para verificar o tamanho da placa selecionar a unidade de medida a esquerda e em seguida utilizar o botão de medição a direita<br>
![Medição](/img/028.png)<br> 
![Medição](/img/029.png)<br> 
- É possivel visualizar através de uma animação 3d o resultado clocando em View > 3D Viewer<br>
![Visualizacao](/img/030.png)<br> 
<br>[↑](#SUMÁRIO)

### Criando o primeiro lay-out de PCB em dupla face
- Placas em dupla face de esquemas intermediários a avançados minimiza indutancias e capacitancias parasitas (trilhas longas ou paralelas);
- Para efeturar trilhas superiores ou seja na outra face, utilizar "F.Cu", sendo um tracejado vermelho
- Para adicionar os furos de passagem de trilha de uma face para outra, ao fazer a trilha basta pressionar a tecla "V"
- Fazer o contorno de corte da placa com Edge.Cuts
- Após efetuar todas as trilhas verificar se existe algum problema encontrado, clicando em Inspecione > Verificador das Regras do Desenho
- Para fazer escritas na placa escolha F.SilkScreen

- Para adicionar os furos de fixação clicar no icone "Adicionar um Footprint" ou clicar em A;
- Escolher o furo de prefernecia, ( no caso ado autor MountingHole 3.2,,_M3)

### Criando lay-out em SMD
- Para um circuito compacto, é necessário desenvolver a placa de circuito impreso com componentes SMD;
- Nono Projeto
- Para trabalhar em smd o primeiro passo é desenvolver o esquemático normalmente
- Após todo o desenvolvimento normalmente efetuado, basta clicar na ferramenta "Executar a ferramenta de atribuição de footprint (versão 6.0 kicad)" e escolher os componentes smd que serão utilizados
- Associar todos os footprints dos componentes que podem ser SMD
    ![Marcação de Footprint](/img/031.png)<br> 
    - O kicad não faz associação automática de footprints a componentes, para isso deve-se acessar o datasheet do componente e verificar as especificações de tamanho e tipo de soquete do componente e efetuar manualmente esse processo
- Após o processo acima, salvar as associações retornar para a folha de projeto e clicar em "Abra a PCI no editor da placa (versão Kicad 6.0)"
- Na nova janela clicar em "Update PCB whith changes made to schematic (F8)", os componentes irão para folha;
- Organizar os componentes
- Observação, o componente TL084 ja possui internamente os 4 circuitos necessários, logo no esquema elétrico para sua utilização é necessário nomea-lo como U1 em todos e clicando no componente será aberto uma nova janela onde é possivel escolher os canais para os demais circuitos internos do componente (A,B,C,D)
![Observação 1](/img/032.png)<br> 
![Observação 2](/img/033.png)<br> 
- Diferentes das placas pth se começa o desenho das trilhas pelo front cupper (F.Cu)
    - Atalho para esse desenho a tecla "X"

- Após o desenho de todas as trilhas clicar no botão "Mostrar a janela do verificador das regras do desenho"
![Verificação](/img/034.png)<br> 
    - É informado na janela erros e inclusive conexões faltantes 

- Para Economizar material corrosivo inclusive inserir fornecer uma proteção a placa do ponto de vista elétrico é possivel nos pontos que não há trilha serem inseridos uma conexão com o gnd.
- Para adicionar deve-se clicar no botão "Add a filled zone ou Ctrl + Shift + Z"
![botao](/img/035.png)<br> 
- Será aberto uma janela na qual deve-se selecionar F.Cu, B.Cu e GND. Será solicitado para que se 
selecione a area. Após isso deve-se clicar dentro da area com o botão direito, ir em "Zonas" e clicar em preencher todas as zonas

### Desenhando footprints personalizados
- Em alguns casos quando o componente não possui footprint é necessário cria-lo;
- O Kicad possui uma ferramenta simples e eficaz para desenhos de footprints;
- Criação exemplo de um componente pth e um smd 
    - Componente PTMM
        - O componente a ser utilizado será o AN7125 (pth)

    - Primeiro passo para a criação é abrir o editor de footprints localizado como um icone na pagina principal do kicad
    ![icone](/img/036.png)<br> 
    - Na janela aberta clicar no icone "Create a new, empty footprint (ctrl + N)
    ![icone](/img/037.png)<br>
    - Na nova janela aberta deve-se dar um nome para o componente e na versão do KiCad nova também é solicitado o tipo de componente
    - É possivel configurar a passada do kiCad para ser algo semelhante ou proximo da passada dos pads do componente facilitando assim o desenho do mesmo. Deve-se clicar com o botão direito ta tela do Kicad na area de desenhor e ir em "Grid" e em seguida efetuar a seleção do novo step
    ![icone](/img/038.png)<br>
    - Para adicionar os furos que o componente possui (PTH) que transpassam a placa, clicar no botão  "Add Pad"
    ![icone](/img/039.png)<br>
    - Para aumentar a espeçura do buraco (recomenda-se sempre que o buraco seja um pouco maior que o conector para que a solda possa entrar ), para configurar isso, clica-se duas vezes sobre o pad e se altera Pad Size X para determinar o tamanho da região de conexão com as trilhas e em Hole size x para alterar o tamanho do buraco 

    - O Buraco possui uma camada redonda, entretanto convenciona-se que o pino 1 do componente a sua regiao em torno do buraco não seja redonda mais sim quadrado 

    - É importante desenhar o contorno do componente com o tipo de linha "F.Silkscreen"

    - Convenciona-se no entorno do primeiro pino desenhar um quadrado, ficando ao final da seguinte forma
    ![icone](/img/040.png)<br>

    - No caso do componente desenhado AN7125 é possivel também desenhar uma região a qual o dissipador estaria posicionado. Ficando ao final conforme abaixo
    ![icone](/img/041.png)<br>

    - Para efetuar desenhos na parte de baixo da placa utiliza-se a layer "B.Silkscreen"

    - Caso o componente possuia uma area para seus pads e uma area maior para o componente em só é possivel defini-la com a layer "F.Courtyard"

    - Para salvar no kicad 6 não é possivel salvar nas bibliotecas ja existentes é necessário criar uma biblioteca nova, clicando em File > New Libraries, em seguida criar uma pasta na qual os footprints serão salvos. Feito isso clicar em SAve As e selecionar a biblioteca criada  

- O Kicad possui uma ferramenta que auxilia na criação de footprints de forma muito mais fácil
- Terá como exemplo a criação de um footprint para o microcontrolador ATMega328P com o encapsulamento TQFP
    - Após criar o projeto do footprint clicar em "Create a new footprint using the Footprint Wizard"
    - Será aberto uma nova janela solicitando como base alguns footprints base, para o exemplo será selecionado o tipo "QFP". Será aberto um footprint base de 100pinos e uma tabela ao lado para configurar o footprint 
    ![icone](/img/042.png)<br>

    - Configurando basta clicar em "Export footprint to editor"

### Gerando o arquivo Gerber para fabricação
- Arquivo necessário para envio para empresas que fabricam placas;
- Antes de gerar o arquivo é interessante verificar se existe algum erro na placa atraves da ferramenta presente no KiCad chamada "Show the design rules checker window"
![icone](/img/043.png)<br>
- Será aberto uma janela "DRC Control", devendo-se clicar em "Run DRC" para verificar possiveis erros antes de gerar o arquivo de produção
- Para se gerar o arquivo gerber deve-se clicar em plot 
![icone](/img/044.png)<br>
- Será aberto uma nova janela na qual é solicitado o caminho em que deverá ser salvo o arquivo. Escolhendo a pasta, deve-se apenas clicar em "Plot"
- Após o passo acima clicar em "Generate Drill Files...", será aberto uma nova janela e deve-se clicar em "Generate Drill File"
- Para verificar se os arquivos foram gerados corretamente, na tela principal do KiCad existe um visualizador de arquivos gerber que pode ser utilizado para visualizar o resultado 
![window](/img/045.png)<br>
    - Aberto A nova janela basta selecionar os arquivos e visualizar se esta tudo correto 


### Projeto Final: Placa controladora (PIC)





## OBSERVAÇÕES
- Sempre trabalhar com o grid habilitado 
- Optar por trabalhar com medidas em polegadas 
- Help > List HotKeys contem a lista completa de atalhos do KiCad
- É possivel mover o nome do componente assim como é feito com o componente em sí, bastando para isso colocar o cursor sobre o nome e apertar m, efetuando o mesmo processo que é feito com o componente como um todo 
- Segurando "CTRL" e apertando as fechas direita ou esquerda se tem o movimento horizontal no desenho
- Segurando "SHIFT" e apertando para baixo ou para cima se tem o movimento vertical da folha de desenho
- Não é recomendado usar processos de roteamento de trilhas automáticas, o KiCad não possui nativamente essa ferramenta, entretanto não é recomendado seu uso 
- A borda que define as margens da placa é a "Edge.Cuts"
- Alguns componentes possuem mais de um circuito integrado interno como é o caso do nono projeto, para a utilização de todos ele é necessário copia-lo e cola-lo a quantidade de itens a ser utilizado e em seu nome U?X a interrogação, manter o mesmo numero e só alterar o X correspondente a letra. Para alterar a letra basta dar dois cliques no componente e na nova janela ir em General Units e escolher (A, B, C, ...)
<br>[↑](#SUMÁRIO)




