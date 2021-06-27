<h1 align="center"> Chaveiro em Placa de Circuito Impresso </h1>

<h2 align="center"> Autor: Rafael Marcelo Walter </h2>

<h3 align="center"> Data: Junho de 2021 </h3>

Você já pensou em projetar placas de circuito impresso e fazer delas um objeto
decorativo? Pois bem, projetar placas de circuito impresso pode ir além de apenas
criar circuitos eletrônicos. Você pode usar sua imaginação e elaborar diversos tipos
de desenhos decorativos com elas.

Pensando nisso, quero apresentar um modelo de chaveiro que desenhei para
ser fabricado em placas de circuito impresso, não apenas como um item para
decoração, mas que seja de utilização em seu dia a dia.

Como tema deste projeto, busquei algo de grande importância no universo da
ciência, que combinasse eletrônica e engenharia. Foi então que optei pelas quatro
equações definidas pelo escocês James Clerk Maxwell.

Em 1861, Maxwell estabeleceu a relação entre o campo elétrico e o campo
magnético e desta forma consolidou a teoria eletromagnética em quatro equações
conforme visto na figura 1.

**Figura 1 - Equações de Maxwell na forma diferencial**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/5b45afcad0c7e0e6136c3f95e369ea3652f798f0/assets/Figura%201%20-%20Equa%C3%A7%C3%B5es%20de%20Maxwell%20na%20Forma%20Diferencial.png)

Como o foco deste artigo não são as equações em si, mas o desenvolvimento
dos chaveiros em circuito impresso, não me aprofundarei no tema, mas sim no
desenvolvimento da placa, pois isso possibilitará o conhecimento necessário para que
cada um crie a arte que desejar.

Então vamos começar a projetar o nosso chaveiro. O *software* que mais tenho
familiaridade para o desenvolvimento de *PCBs* é o *EasyEDA*, por isso ele foi o
escolhido para trabalharmos neste projeto. Conheci o software em uma vídeo aula no
canal *WR Kits* no *YouTube*. Gosto dele por ser fácil de utilizá-lo, também não há
necessidade de instalação em seu computador, pode-se utilizar apenas a plataforma
online para criar e armazenar seus projetos.

## Iniciando o projeto da *PCB* no *EasyEDA*

Nesta etapa vou explicar os principais passos para o desenvolvimento deste
projeto e também quero mostrar algumas dicas bem legais para você deixar o seu
projeto de *PCB* com um acabamento diferenciado.

### 1º Passo (Novo Projeto)

Inicie um novo projeto no software. Se você ainda não tem um perfil criado no
site, basta acessar o *link* <https://easyeda.com> e se cadastrar.
Como neste projeto não possuímos um diagrama esquemático, podemos partir
direto para a definição das linhas de borda da placa, que são chamadas de *Board
Outline*. Na figura 2 é possível verificar as dimensões definidas para esta placa.

**Figura 2 – Board Outline**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/70a554f7ab283c6486256716ab29f77f475dbe5a/assets/Figura%202%20-%20Board%20Outline.png)

Com base em outros chaveiros que já fabriquei, essas foram as dimensões que
mais me agradaram. Vale ressaltar uma dica bem legal: note que considerei um raio
de 1,4mm nas bordas da placa. Este detalhe é muito importante para o projeto, pois
caso não seja considerado, os cantos pontiagudos irão lhe causar um certo
desconforto quando estiver com o chaveiro no bolso de sua calça. Na figura 3 temos
as linhas de borda já definidas.

**Figura 3 – Board Outline Definida**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%203%20-%20Board%20Outline%20Definida.png)

Conforme visto na figura 3, observe os cantos arredondados da placa e note
também que mudei a configuração padrão do *software* para utilizar unidades de
medida em milímetros (mm). Para a espessura da placa, considere 1.6mm.

### 2º Passo (Adicionando Furos)

Adicione um furo na placa para prender a correntinha do seu chaveiro. Para
adicionar, você pode usar a tecla de atalho (p) ou clicar na ferramenta destacada em
vermelho na figura 4.

**Figura 4 – PCB Tools**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%204%20-%20PCB%20Tools.png)

Conforme indicado na figura 4, os furos também podem ser adicionados
clicando na ferramenta *Hole*, destacada em verde, porém, prefiro adicionar usando
pontos de conexões (destaque em vermelho), dessa forma a furação terá um
acabamento metalizado e caso queira, você pode definir o ponto de conexão como
sendo o *GND* (malha de aterramento) da placa.

Agora que você inseriu um furo na placa, precisamos definir algumas
propriedades para essa furação, bem como: diâmetro interno, diâmetro externo e as
coordenadas X e Y. Na figura 5 podem ser observadas as propriedades consideradas
para o furo da placa.

**Figura 5 – Pad Properties**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%205%20-%20Pad%20Properties.png)

Na figura 5, apresento as definições de minha preferência, mas caso você
queira mudar alguns parâmetros, apenas tome cuidado para não deixar o furo muito
próximo da borda da placa, isso evitará que a região do furo fique frágil.

Agora que já temos essas definições, vamos verificar na figura 6 como ficou o
resultado da placa com a furação adicionada.

**Figura 6 – Furo Adicionado À Placa**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%206%20-%20Furo%20Acionado%20%C3%80%20Placa.png)

Observe na figura 6 que para manter a rigidez da placa, há um espaçamento
seguro entre o furo e a linha de borda dela.

## 3º Passo (Inserindo Imagens, Textos e Trilhas)

Nesta etapa é hora de você elaborar a sua arte. Insira imagens, textos, trilhas
(circuitos eletrônicos) harmonizando com o seu desenho. Para ficar mais claro,
adiante irei apresentar algumas ideias para o tema que escolhi neste artigo.

- 3.1 – Inserindo Imagens

Você pode adicionar diversos formatos de imagem para o seu projeto, porém,
gosto de utilizar arquivos com o formato .PNG e de preferência que sejam de boa
resolução. Se você quiser adicionar outras imagens, carregadas com muitos detalhes,
possivelmente haverá a necessidade de edição destas. Quando necessário, gosto
muito de utilizar o *software Paint* para fazer alguns ajustes, pois me atende muito bem.

Vamos adicionar a primeira imagem à *PCB*. A figura 7 indica a primeira equação
de Maxwell a ser adicionada.

**Figura 7 – Lei de Gauss do Magnetismo**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%207%20-%20Lei%20de%20Gauss%20do%20Magnetismo.png)

Para inserir a equação da figura 7 na placa, clique sobre o ícone destacado na
figura 8.

**Figura 8 – Ferramenta de Imagem**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%208%20-%20Ferramento%20de%20Imagem.png)

Feito o passo da figura 8, a tela a seguir deverá ser exibida conforme visto na
figura 9.

**Figura 9 – Inserir Imagem**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%209%20-%20Inserir%20Imagem.png)

Destaquei na figura 9 os ajustes que serão necessários configurar para cada
imagem inserida. Note que em vermelho são as dimensões e em verde são os ajustes
de contorno e acabamento.

- 3.2 – Inserindo Textos

Textos podem ser facilmente inseridos pressionando a tecla de atalho (s) ou
clicando no destaque da figura 10.

**Figura 10 – Ferramenta de Texto**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2010%20-%20Ferramento%20de%20Texto.png)

Após fazer o passo da figura 10, será necessário ajustar as propriedades do
texto conforme figura 11.

**Figura 11 – Propriedades de Texto**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2011%20-%20Propriedades%20de%20Texto.png)

Na figura 11 destaquei as principais propriedades que necessitamos configurar.
No destaque em vermelho será definido em qual *layer* o texto será gravado, nesse
caso, *TopLayer* indica que a gravação será feita na face superior da placa e o material
será o cobre (mesmo formato de impressão das trilhas). Explicarei isso adiante. No
destaque em verde é feito o ajuste do tamanho e espessura da fonte. 

- 3.3 – Inserindo Trilhas (Traks)

Uma boa dica é fazer desenhos utilizando as trilhas. Imagine circuitos
eletrônicos ligando um ponto a outro, ou utilize-as para fazer contornos ao desenho.
Na figura 12 apresento duas ferramentas que você poderá utilizar.

**Figura 12 – Inserir Trilhas**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2012%20-%20Inserir%20Trilhas.png)

A ferramenta em destaque vermelho da figura 12 é utilizada para inserir as
trilhas. Também é possível inserir pressionando a tecla de atalho (w). Na mesma
figura, o destaque em verde será utilizado para criar pequenos arcos que farão o
contorno a placa. Na figura 13 podem ser observadas as trilhas (linhas vermelhas)
adicionadas ao desenho.

**Figura 13 – Linhas de Contorno**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2013%20-%20Linhas%20de%20Contorno.png)

Conforme visto na figura 13, as trilhas estão adicionadas na face superior da
placa (*TopLayer*). Lembre-se que é possível acessar as propriedades e fazer ajustes
importantes como: espessura, comprimento, definição do *layer*, etc.

Obs.: caso queira desenhar as trilhas na face inferior da placa, utilize
*BottomLayer*.

## 4º Passo (Definição dos Layers)

Saber escolher e definir os *layers* em seu projeto é muito importante. Nos meus
primeiros projetos de *PCBs*, com o conhecimento limitado, eu fazia pequenos detalhes
tentando utilizar *layers* diferentes, assim ao receber a placa era possível verificar na
prática o que cada *layer* resultava no projeto. Na figura 14 é possível visualizar os
*layers* para seleção.

**Figura 14 – Layers**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2014%20-%20Layers.png)


A seleção dos *layers* (camadas) é feita conforme apresentado na caixa de
seleção da figura 14. Para acessá-la selecione as propriedades de cada objeto
inserido.

Nos itens a seguir, irei descrever brevemente qual a função dos *layers*
utilizados no projeto desta placa.

- *TopLayer*: Utilizado para impressões sólidas (acabamento cobreado) na
face superior da placa. Exemplo: trilhas, logomarcas e malha de
aterramento.

- *BottomLayer*: Utilizado para impressões sólidas (acabamento cobreado) na
face inferior da placa. Exemplo: Idem *TopLayer*.

- *TopSilkLayer*: É a serigrafia ou pintura na face superior da placa. Exemplo:
Identificação dos componentes, textos e imagens em geral.

- *BottomSilkLayer*: É a serigrafia ou pintura na face inferior da placa.
Exemplo: Idem *TopSilkLayer*.

- *TopSolderMaskLayer*: Remove o acabamento em verniz, na face superior
da placa, deixando a placa “crua” à mostra. Observação: caso inserido
sobreposto ao *TopLayer*, como resultado, deixará o cobre estanhado
exposto. Exemplo: pontos de conexões para *slots*, área de cobre exposta
para permitir o contato com dissipadores de calor, acabamento da região
prateada.

- *BottomSolderMaskLayer*: Remove o acabamento em verniz, na face inferior
da placa, deixando a placa “crua” à mostra. Observação: caso inserido
sobreposto ao *BottomLayer*, como resultado, deixará o cobre estanhado
exposto. Exemplo: Idem *TopSolderMaskLayer*.

- *BoardOutLine*: Define a linha de corte da placa. Dica: Facilmente podem ser
criadas geometrias retangulares ou circulares para a linha de corte da placa.
Caso queira um formato diferente, opte em fazer o desenho da linha de corte
no *AutoCad* e salve o arquivo no formato .DXF, após, importe o arquivo no
*EasyEDA*.

## 5º Passo (Apresentação 2D)

Para chegar até aqui, descrevi os principais passos a serem seguidos, poderia
os detalhar ainda mais, mas não quero que este artigo se estenda muito tornando-o
uma leitura pesada.

A qualquer momento é possível gerar uma visualização 2D ou 3D de como seu
projeto está ficando, assim, você vai fazendo os ajustes necessários.

Neste momento, gostaria de apresentar o projeto do chaveiro finalizado
mostrando as duas faces da placa (*TopLayer* e *BottomLayer*). Na figura 15 e 16
apresento a face superior e inferior da placa respectivamente.

**Figura 15 – TopLayer**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2015%20-%20Top%20Layer.png)

**Figura 16 – BottomLayer**

![showcase](https://github.com/rkfael/PCB-Keychain/blob/main/assets/Figura%2016%20-%20Bottom%20Layer.png)

## Acesso ao Projeto

Disponibilizei o projeto para que você possa gerar os arquivos de fabricação,
esclarecer eventuais dúvidas e editá-los conforme sua preferência. Confira acessando
o *link* <https://easyeda.com/rkfael/maxwell_equations_keychain_artigo>

## Fabricação das Placas (*JLCPCB*)

A *JLCPCB* fornece um serviço de excelente qualidade e baixo custo para a
fabricação das placas. Confira acessando o *link* <https://jlcpcb.com/IRG>

## Meu Perfil nas Redes Sociais

Finalizando este artigo, gostaria de apresentar meu perfil no *Instagram*
(@notas_eletronicas). Aproveite para ver mais algumas das minhas ideias deste tipo
de arte feitas em placas de circuito impresso, e claro, não deixe de seguir meu perfil.





