# KICAD

## SUMÁRIO
- [I. CARACTERISTICAS DO SOFTWARE](#I.-CARACTERISTICAS-DO-SOFTWARE)
- [II. DOWNLOAD DO SOFTWARE](#II.-DOWNLOAD-DO-SOFTWARE)
- [III. CRIANDO UM NOVO PROJETO](#III.-CRIANDO-UM-NOVO-PROJETO)
    - [III.I. Adicionar Componente ](#III.I.-Adicionar-Componente)
    - [III.II. Rotacionar componente](#III.II.-Rotacionar-componente)
    - [III.III. Duplicar Componente](#III.III.-Duplicar-Componente)
    - [III.IV. Mover Componentes ](#III.IV.-Mover-Componentes)
- [IV. DIAGRAMAS ESQUEMÁTICOS](#IV.-DIAGRAMAS-ESQUEMÁTICOS)
    - [IV.I. Projeto Astável 555](#IV.I.-Projeto-Astável-555)
    - [IV.II. Inserir Alimentação ao circuito e o GND](#IV.II.-Inserir-Alimentação-ao-circuito-e-o-GND)
    - [IV.III. Inserir linha (wire)](#IV.III.-Inserir-linha-(wire))
    - [IV.IV. Mover Componente sem perder a linha](#IV.IV.-Mover-Componente-sem-perder-a-linha)
    - [IV.V. Rotações do compotente sobre eixos X e Y](#IV.V.-Rotações-do-compotente-sobre-eixos-X-e-Y)
    - [IV.VI. Alterar o Nome e valores dos componentes](#IV.VI.-Alterar-o-Nome-e-valores-dos-componentes)
    - [IV.VII. Anotate do Diagrama Esquemático](#IV.VII.-Anotate-do-Diagrama-Esquemático)

- [OBSERVAÇÕES](#OBSERVAÇÕES)

## I. CARACTERISTICAS DO SOFTWARE
- Multiplataforma 
    - Windows 
    - Linux
    - Mac
    - ...
- Gratuito e Ilimitado
- Extensão dos arquivos esquemáticos são ".sch"
- Extensão do layout ".kicad_pcb"
- Possui simulador (não tão eficiente)
<br>[⬆︎](#SUMÁRIO)

## II. DOWNLOAD DO SOFTWARE
- Site:
    - https://www.kicad.org/
    - Link recomendado: CERN
<br>[⬆︎](#SUMÁRIO)

## III. CRIANDO UM NOVO PROJETO
- Caminho 
    - File > New > Project ou File > New Project
    - Em arquivos do projeto é gerado uma arvore de arquivos com os formatos kicad_sch e kocad_pcb
- Edição e configuração do arquivo de esquema eletrico 
    - Duplo clique sobre o arquivo com extensão kicad_sch
- Configurações da Página 
    - Arquivos > Configurações da Página ...
    - Será aberto uma janela para inclusão de dados que irão na legenda no canto inferior da página 
<br>[⬆︎](#SUMÁRIO)

### III.I. Adicionar Componente 
- Na tela de elaboração da pcb clicar em "A"(add)
    - Será aberto uma nova janela, onde é possivel selecionar o componente
<><br>[⬆︎](#SUMÁRIO)

### III.II. Rotacionar componente
- Com o Componente selecionado clicar em "R"(rotate)
<br>[⬆︎](#SUMÁRIO)

### III.III. Duplicar Componente 
- Com o cursor sobre o componente clicar "CTRL"+"C" e depois "CTRL"+"V" e posicionar o componete
<br>[⬆︎](#SUMÁRIO)

### III.IV. Mover Componentes  
- É possivel mover o componente com os direcionais do teclado, (inclusive o cursor);
- Com o cursor sobre o componente, clicar em "M"(move), o componente estará selecionado, a partir disso, alocar o componente na região desejada, ao chegar no local clicar em "ENTER" 
<br>[⬆︎](#SUMÁRIO)

## IV. DIAGRAMAS ESQUEMÁTICOS

### IV.I. Projeto Astável 555
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
<br>[⬆︎](#SUMÁRIO)

### IV.II. Inserir Alimentação ao circuito e o GND
- A inserão é feita com a tecla "P" do teclado, seguind a isso verificando a tensão desejada 
<br>[⬆︎](#SUMÁRIO)

### IV.III. Inserir linha (wire)
- Pode ser efetuado com a tecla "W"
- Para fazer as quebras em 90° utilizar a tecla "Enter"
<br>[⬆︎](#SUMÁRIO)

### IV.IV. Mover Componente sem perder a linha 
- Utilizar a tecla "G"
<br>[⬆︎](#SUMÁRIO)

### IV.V. Rotações do compotente sobre eixos X e Y
- Utilizar tecla "X" para o eixo X e a tecla "Y" para o eixo Y com o cursor sobre o componente
<br>[⬆︎](#SUMÁRIO)

### IV.VI. Alterar o Nome e valores dos componentes 
- EM um componente existem dois textos, o texto acima refere-se ao nome e o texto subsequente refere-se ao valor
- Clicando sobre cada um deles com um duplo clique é possivel alterar o nome e o valor 
- A segunda opção para alterar o valor de um componente é com o cursor sobre ele e clicar em "V" 
<br>[⬆︎](#SUMÁRIO)

### IV.VII. Anotate do Diagrama Esquemático
- Dar número aos componentes 
- Geralmente utiliza-se a configuração padrão do proprio KiCad onde a numeração é feita de cima para baixo e da esquerda para a direita 
- O processo é feito no botão abaixo <br> 
![Anotate](/img/001.png)
- Cada inserção de um componente feito após um anotate é necessário um novo anotate
<br>[⬆︎](#SUMÁRIO)





## OBSERVAÇÕES
- Sempre trabalhar com o grid habilitado 
- Optar por trabalhar com medidas em polegadas 
- Help > List HotKeys contem a lista completa de atalhos do KiCad
- É possivel mover o nome do componente assim como é feito com o componente em sí, bastando para isso colocar o cursor sobre o nome e apertar m, efetuando o mesmo processo que é feito com o componente como um todo 
<br>[⬆︎](#SUMÁRIO)