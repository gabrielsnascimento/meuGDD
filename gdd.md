<img src="../meuGDD/assets/logointeli.png">


# GDD - Game Design Document - Módulo 1 - Inteli

**_Os trechos em itálico servem apenas como guia para o preenchimento da seção. Por esse motivo, não devem fazer parte da documentação final_**

## Green Tech

#### *Nomes dos Integrantes:*
#### Andre Dleizer
#### André Lobo
#### Gabriel Nascimento
#### Laura Rodrigues
#### Milena Castro
#### Ryan Gartlan
      



## Sumário

[1. Introdução](#c1)

[2. Visão Geral do Jogo](#c2)

[3. Game Design](#c3)

[4. Desenvolvimento do jogo](#c4)

[5. Casos de Teste](#c5)

[6. Conclusões e trabalhos futuros](#c6)

[7. Referências](#c7)

[Anexos](#c8)

<br>


# <a name="c1"></a>1. Introdução (sprints 1 e 4)

## 1.1. Escopo do Projeto

### 1.1.1. Contexto da indústria (sprints 1 e 4)

A Unilever é uma das maiores empresas de bens de consumo do mundo, com presença em mais de 190 países. Fundada em 1929, ela é conhecida por uma vasta gama de marcas populares em diversas categorias, como alimentos, cuidados pessoais e limpeza doméstica. A empresa opera com uma estratégia de sustentabilidade e responsabilidade social, buscando reduzir seu impacto ambiental e melhorar as condições de vida em comunidades onde atua. Seu modelo de negócios inclui marcas globais, regionais e locais, permitindo uma abordagem adaptada às necessidades específicas de cada mercado (Unilever Brasil).


### 1.1.2. Análise SWOT (sprints 1 e 4)

A Análise SWOT de planejamento estratégico concede uma visão holística dos ambientes internos e externos da empresa. Ela é feita a partir de uma matriz 2x2 que engloba forças (strenghts), fraquezas (weakness), oportunidades (opportunities) e ameaças (threats). Desse modo, abaixo está a análise SWOT da empresa Unilever.
<div align="center">
Figura 1 - Análise SWOT

 
<img src="../meuGDD/assets/SWOT.png" width="768" height="432">

<sub>Fonte: autoria própria (2024)</sub>
</div>

### 1.1.3. Descrição da Solução Desenvolvida (sprints 1 e 4)

O problema central do parceiro Unilever é a necessidade de aumentar o engajamento e absorção do conteúdo sobre a empresa durante o processo de Onboarding dos funcionários de TI da empresa. O desafio é tornar a experiência mais atrativa, eficiente e alinhada à cultura híbrida de trabalho da Unilever.
De acordo com a transparência de dados em seu relatório anual de informações, a Unilever está presente em 190 países e tem 400 marcas presentes no mundo inteiro, dividido em 5 grandes segmentos: beleza e bem estar; cuidado pessoal; cuidados domiciliares; nutrição e sorvete. Além disso, 3,4 bilhões de pessoas usam produtos da Unilever todos os dias.


A solução proposta é um jogo para combater a falta de engajamento no Onboarding, apresentando informações da empresa e direcionando os jogadores para trilhas específicas na intranet. O jogo aborda suporte, equipe e estrutura organizacional entre outros conteúdos da trilha de maneira interativa, com puzzles, mini games e diálogos com NPCs para obter conquistas. 


O jogo será incorporado como uma etapa essencial no processo de integração de novos funcionários de TI na Unilever a partir de materiais mais lúdicos e interativos. Para garantir que tenham completado com sucesso o programa de integração, será necessário que joguem online e atendam aos requisitos estabelecidos. 


A solução do jogo para o problema do parceiro agrega alguns benefícios para a empresa, pois terá maior índice de funcionários que concluíram o Onboarding, aumentando o engajamento e a absorção do conteúdo. Assim, a empresa integra melhor seus funcionários na cultura da empresa e tem oportunidade de se identificar com os valores e propósitos da Unilever.


Para saber o sucesso da proposta será medido a melhoria do engajamento e absorção do conteúdo do Onboarding. Isso através de testes em forma de puzzles, mini games entre outros, que ajudam na fixação do conteúdo e feedbacks dos jogadores para coletar informações sobre dificuldade, aprendizado, satisfação e etc.


### 1.1.4. Proposta de Valor (sprints 1 e 4)

A Proposta de Valor identifica as necessidades do cliente, aponta os benefícios do produto e destaca de forma clara e objetiva como aquele produto satisfaz a necessidade do cliente e seu valor diante dos benefícios em relação aos concorrentes.
<div align="center">
Figura 2 - Value proposition Canva


<img src="../meuGDD/assets/valuePropositionCanva.png" width="768" height="432">

<sub>Fonte: Autoria própria(2024)</sub>
</div>

### 1.1.5. Matriz de Riscos (sprints 1 e 4)

A Matriz de Riscos expõe todos os riscos e impactos reais ou potenciais no desenvolvimento de um projeto, assim possibilitando o gerenciamento das incertezas existentes no processo de evolução do produto. A criação de uma matriz é feita por meio de uma tabela que relaciona a probabilidade e o impacto da ocorrência do risco analisado, classificando-o como baixo (cor verde), médio (cor amarela) ou alto (cor vermelha). Dessa forma, ao fazer uso da Matriz de Riscos, torna-se possível realizar a avaliação dos prováveis danos, facilitando assim a priorização na realização de tarefas.
<div align="center">
Figura 3 - Matriz de Riscos











<img src="../meuGDD/assets/matrizDeRiscos.png" width="768" height="432">

<sub>Fonte: Autoria própria(2024)</sub>
</div>
Diante do exposto, para realizar o desenvolvimento do jogo proposto pela empresa Unilever, tornou-se necessário identificar e pontuar os possíveis riscos apresentados na tabela exposta acima. Além disso, é importante estabelecer o planejamento e as respostas para cada desses riscos. Logo foi elaborado um plano de ação para cada um deles:

* Atrasos no desenvolvimento: Utilizar uma metodologia ágil para ter mais controle das datas de entrega e tarefas, além de redistribuir tarefas quando necessário.

* Problemas técnicos: Revisar o código regularmente para mantê-lo o mais polido possível e aderir às boas práticas de desenvolvimento.

* Falta de engajamento dos funcionários: Incorporar atividades interativas e relevantes para os funcionários, além de recompensas no jogo para incentivar o engajamento.

* Dificuldades de aprendizado: Diminuir a dificuldade do jogo e permitir que o jogador avance sem necessariamente ter vencido a fase anterior.

* Problemas de compatibilidade: Desenvolver o jogo para que seja compatível com as principais plataformas e, se possível, com as demais.

* Problemas na equipe de projeto: Informar o grupo com antecedência sobre qualquer acontecimento que possa afetar a equipe e redistribuir tarefas quando necessário.

* Risco de não atender às expectativas dos usuários: Definir a persona dos jogadores e desenvolver o game com elementos que motivem a essa persona.

* Risco de obsolescência tecnológica: Utilizar as tecnologias mais populares do mercado e aderir às boas práticas de desenvolvimento.

* Mudanças na estratégia de negócios: Manter diálogo com a empresa, avaliar suas demandas e, se possível, aplicar mudanças no desenvolvimento do jogo.


## 1.2. Requisitos do Projeto (sprints 1 e 2)

*ATUALIZE ESTA SEÇÃO SEMPRE QUE ALGUM REQUISITO MUDAR EM SEU PROJETO*

\# | Requisitos  
--- | ---
1 | O controle do personagem é realizado usando as teclas direcionais para navegar pelo mundo
2 | O personagem se movimenta em um mundo semi-aberto para todas as direções
3 | O personagem é personalizável para atender a diversidade de pessoas
4 | O jogo funciona com foco na web
5 | O jogo disponibiliza links para o hub do parceiro
6 | O jogo fornece puzzles e quizes para interagir com o player 
7 | Testa o conhecimento do player sobre a trilha de Onboarding

## 1.3. Público-alvo do Projeto (sprint 2)

*Posicione aqui uma descrição justificada do público-alvo do jogo, em termos demográficos e de preferências/gostos pessoais.*

# <a name="c2"></a>2. Visão Geral do Jogo (sprint 2)

## 2.1. Objetivos do Jogo (sprint 2)

O objetivo principal do jogo é recuperar as 3 partes do U roubado. Para isso, é preciso completar minigames inspirados na Uniops da Unilever contendo informações do processo de entrada como estrutura organizacional,  e principais marcas da companhia, além de recuperar as partes do U roubado. Após concluídas, uma última fase seria liberada, onde um npc iria parabenizar pelos obstáculos completados e trazer informações finais sobre o onboarding.

## 2.2. Características do Jogo (sprint 2)

### 2.2.1. Gênero do Jogo (sprint 2)

Um jogo de aventura é um gênero que se caracteriza principalmente por um enredo que gira em torno da exploração de um mundo virtual. O jogador assume o papel de protagonista e se depara com diversos quebra-cabeças e desafios ao mesmo tempo em que interage com NPCs, tudo isso com o objetivo de completar sua missão.
Dessa forma, através de links e mini games, o gênero que melhor descreve nosso jogo é a aventura. No início, o player tem a opção de escolher entre dois personagens. Em seguida, ele vai explorar os diferentes ambientes de trabalho da Unilever. Nesses espaços, o personagem vai interagir com NPCs além de ser redirecionado por links para aprender conteúdo sobre a empresa, posteriormente sendo testado por meio de minigames, recebendo uma recompensa caso complete adequadamente o desafio. 

### 2.2.2. Plataforma do Jogo (sprint 2)

A plataforma é desktop, utilizando a plataforma web como solicitado pelo parceiro, sem necessidade de instalação, para facilitar o acesso, possíveis atualizações, coleta de dados e monitoramento, sem dependências de outras plataformas. A ideia seria o usuário assim que ingressar na empresa, receber um notebook de trabalho e a primeira coisa que ele abriria no computador seria o site do jogo para o início do processo do onboarding.

### 2.2.3. Número de jogadores (sprint 2)

O jogo é de 1 player, pois é projetado oferecer uma experiência individual focada na jornada de desafios com foco no aprendizado da trilha de Onboarding do parceiro.  

### 2.2.4. Títulos semelhantes e inspirações (sprint 2)

Para a concepção do jogo foi fundamental conhecer e pesquisar sobre outros jogos que possuem mecânicas, objetivos, minigames, ou design similares para servirem de inspiração. 
Como inspirações tem-se os jogos “Stardew Valley” desenvolvido por Eric "ConcernedApe" Barone, onde os jogadores cuidam de uma fazenda em um jogo de RPG; “The Legend of Zelda” desenvolvido por Shigeru Miyamoto e Takashi Tezuka, um jogo de ação-aventura com elementos do RPG; e Pokémon versões de Gameboy, onde o jogador viaja pelo mundo capturando os monstrinhos, feito pela desenvolvedora de jogos Game Freak. 
Todos possuem dinâmicas de movimentação e mapas similares de exploração, que será utilizado para o usuário percorrer e conhecer os ambientes de trabalho da Unilever, conhecendo mais sobre a empresa, a área da Uniops e informações gerais, sendo desafiado por mini-games ao decorrer do jogo que os recompensaram com um pedaço do grande U roubado do prédio Unilever.


### 2.2.5. Tempo estimado de jogo (sprint 5)

*Ex. O jogo pode ser concluído em 3 horas passando por todas as fases.*

*Ex. cada partida dura até 15 minutos*

# <a name="c3"></a>3. Game Design (sprints 2 e 3)

## 3.1. Enredo do Jogo (sprints 2 e 3)

*Descreva o enredo/história do jogo, criando contexto para os personagens (seção 3.2) e o mundo do jogo (seção 3.3). Uma boa história costuma ter um arco narrativo de contexto, conflito e resolução. Utilize etapas sequenciais para descrever esta história.* 

*Caso seu jogo não possua enredo/história (ex. jogo Tetris), mencione os motivos de não existir e como o jogador pode se contextualizar com o ambiente do jogo.*

O novo funcionario da unilver, ao passar pelo onboarding deve conseguir absorver a maior quantidade de conteudo e entender a cultura da empresa da melhor forma possivel. Para isso, a gamificacao desse processo vira a ser muito interessante, e para fazer isso o grupo desenvolveu o jogo Cidade Unilever. Durante o desenvolvimento do jogo, muitas ideias e propostas foram feitas, depois de afunilar as ideias, um primeiro prototipo foi formado.

O jogo criado acompanha a jornada do personagem principal récem contratado na área de TI da empresa Unilever. Sendo assim, o jogador atráves de seu personagem controlável explora o mundo da "Cidade Unilever" para compreender as principais marcas produzidas pela empresa, sua importância para o mercado global e passar por um treinamento para ser introduzido no seu novo trabalho na área de UniOps. 



## 3.2. Personagens (sprints 2 e 3)

### 3.2.1. Controláveis

Para realizar o desenvolvimento do personagem controlável, foram considerados os seguintes requisitos:
* Personagens que fujam de representações estereotipadas;
* Promoção da identificação do jogador com o avatar controlável;
* Movimentação isométrica e com poucos controles 
* Fácil jogabilidade.

Sendo assim, com base nos requisitos listados, idealizou-se quatro opções de personagens controláveis, sendo que o jogador pode escolher uma de sua preferência logo após a tela de início do jogo e nomeá-la com seu próprio nome. 

Para a realização do desenvolvimento das ideias propostas, fez-se uso do software de desenvolvimento de personagens “Character Generator 2.0”, plataforma que possibilita a geração de sprites personalizadas de personagens de forma intuitiva e interativa. Dessa maneira, de acordo com os recursos disponíveis no software foram geradas as sprites das quatro possibilidades de personagens controláveis.   

Para isso,  idealizou-se uma aparência para o personagem principal baseada em um humanoide com tom de pele que trouxesse identificação com a paleta de cores apresentada pela empresa e fugisse da falta de representação de algum tom de pele real, portanto foram escolhidas as cores azul e rosa para serem as cores principais dos avatares retratados ao longo do game.
	
O personagem escolhido pelo jogador é o protagonista da jornada desenvolvida ao longo do game e caracteriza-se por ser um humanóide de pele azul ou rosa e aparência jovem, representando um recém contratado da empresa e que tem como objetivo provar sua capacidade através dos testes de treinamento (minigames) para se tornar um colaborador apto a trabalhar na empresa.

<div align="center">
Figura 4 - Personagens


<img src="../meuGDD/assets/personagem_4.png"><img src="../assets/personagem_2.png"><img src="../assets/personagem_1.png"><img src="../assets/personagem_3.png">

<sub>Fonte: Opengameart.org</sub>
</div>

### 3.2.2. Non-Playable Characters (NPC)

A Unilever é uma empresa onde o contato entre os funcionarios é essencial, independente do cargo é comum que a maioria das pessoas da mesma area se conecte e se conheca, sabendo disso, o jogo contara com a presenca de diversos NPCs, esses que serao a reecriacao de funcionarios, parceiros, produtos, etc. A funcao desses NPCs no jogo sera de extrema importancia, ao redor de todo o mapa eles estarao presentes para dar intrucoes, ordens, missoes, dicas e itens, auxiliando o entendimento e desenrolar do jogo para o jogador.

No primeiro contato do colaborador com o jogo, ele sera introduzido para um NPC, esse que o guiara para sua primeira fase, apos isso, antes de comecar a missao, outro npc tera essa funcao, e assim por diante, ate que o jogador termine o processo de onboarding.

### 3.2.3. Diversidade e Representatividade dos Personagens

Considerando as personagens do game, analise se estas estão alinhadas ao público-alvo do jogo (seção 1.3), e compare-as dentro da realidade da sociedade brasileira. Por fim, discorra sobre qual é o impacto esperado da escolha dessas personagens.

## 3.3. Mundo do jogo (sprints 2 e 3)

### 3.3.1. Locações Principais e/ou Mapas (sprints 2 e 3)

*Descreva o ambiente do jogo, em que locais ele ocorre. Ilustre com imagens. Se houverem mapas, posicione-os aqui, descrevendo as áreas em acordo com o enredo. Se houverem fases, descreva-as também em acordo com o enredo (pode ser um jogo de uma fase só). Utilize listas ou tabelas para organizar esta seção. Caso utilize material de terceiros em licença Creative Commons, não deixe de citar os autores/fontes.*

### 3.3.2. Navegação pelo mundo (sprints 2 e 3)

*Descreva como os personagens se movem no mundo criado e as relações entre as locações – como as áreas/fases são acessadas ou desbloqueadas, o que é necessário para serem acessadas etc. Utilize listas ou tabelas para organizar esta seção.*

### 3.3.3. Condições climáticas e temporais (sprints 2 e 3)

*\<opcional\> Descreva diferentes condições de clima que podem afetar o mundo e as fases, se aplicável*

*Caso seja relevante, descreva como o tempo passa, se ele é um fator limitante ao jogo (ex. contagem de tempo para terminar uma fase)*

### 3.3.4. Concept Art (sprint 2)

*Inclua imagens de Concept Art do jogo que ainda não foram demonstradas em outras seções deste documento. Para cada imagem, coloque legendas, como no exemplo abaixo.*

<img src="../meuGDD/assets/concept1.jpg">

Figura 1: detalhe da cena da partida do herói para a missão, usando sua nave

### 3.3.5. Trilha sonora (sprint 3)

*Descreva a trilha sonora do jogo, indicando quais músicas serão utilizadas no mundo e nas fases. Utilize listas ou tabelas para organizar esta seção. Caso utilize material de terceiros em licença Creative Commons, não deixe de citar os autores/fontes.*

*Exemplo de tabela*
\# | titulo | ocorrência | autoria
--- | --- | --- | ---
1 | tema de abertura | tela de início | própria
2 | tema de combate | cena de combate com inimigos comuns | Hans Zimmer
3 | ... 

## 3.4. Inventário e Bestiário (sprint 3)

### 3.4.1. Inventário

*\<opcional\> Caso seu jogo utilize itens ou poderes para os personagens obterem, descreva-os aqui, indicando títulos, imagens, meios de obtenção e funções no jogo. Utilize listas ou tabelas para organizar esta seção. Caso utilize material de terceiros em licença Creative Commons, não deixe de citar os autores/fontes.* 

*Exemplo de tabela*
\# | item |  | como obter | função | efeito sonoro
--- | --- | --- | --- | --- | ---
1 | moeda | <img src="../assets/coin.png"> | há muitas espalhadas em todas as fases | acumula dinheiro para comprar outros itens | som de moeda
2 | madeira | <img src="../assets/wood.png"> | há muitas espalhadas em todas as fases | acumula madeira para construir casas | som de madeiras
3 | ... 

### 3.4.2. Bestiário

*\<opcional\> Caso seu jogo tenha inimigos, descreva-os aqui, indicando nomes, imagens, momentos de aparição, funções e impactos no jogo. Utilize listas ou tabelas para organizar esta seção. Caso utilize material de terceiros em licença Creative Commons, não deixe de citar os autores/fontes.* 

*Exemplo de tabela*
\# | inimigo |  | ocorrências | função | impacto | efeito sonoro
--- | --- | --- | --- | --- | --- | ---
1 | robô terrestre | <img src="../assets/inimigo2.PNG"> |  a partir da fase 1 | ataca o personagem vindo pelo chão em sua direção, com velocidade constante, atirando parafusos | se encostar no inimigo ou no parafuso arremessado, o personagem perde 1 ponto de vida | sons de tiros e engrenagens girando
2 | robô voador | <img src="../assets/inimigo1.PNG"> | a partir da fase 2 | ataca o personagem vindo pelo ar, fazendo movimento em 'V' quando se aproxima | se encostar, o personagem perde 3 pontos de vida | som de hélice
3 | ... 

## 3.5. Gameflow (Diagrama de cenas) (sprint 2)

*Posicione aqui seu "storyboard de programação" - o diagrama de cenas do jogo. Indique, por exemplo, como o jogo começa, quais opções o jogador tem, como ele avança nas fases, quais as condições de 'game over', como o jogo reinicia. Seu diagrama deve representar as classes, atributos e métodos usados no jogo.*

## 3.6. Regras do jogo (sprint 3)

*Descreva aqui as regras do seu jogo: objetivos/desafios, meios para se conseguir alcançar*

*Ex. O jogador deve pilotar o carro e conseguir terminar a corrida dentro de um minuto sem bater em nenhum obstáculo.*

*Ex. O jogador deve concluir a fase dentro do tempo, para obter uma estrela. Se além disso ele coletar todas as moedas, ganha mais uma estrela. E se além disso ele coletar os três medalhões espalhados, ganha mais uma estrela, totalizando três. Ao final do jogo, obtendo três estrelas em todas as fases, desbloqueia o mundo secreto.*  

## 3.7. Mecânicas do jogo (sprint 3)

*Descreva aqui as formas de controle e interação que o jogador tem sobre o jogo: quais os comandos disponíveis, quais combinações de comandos, e quais as ações consequentes desses comandos. Utilize listas ou tabelas para organizar esta seção.*

*Ex. Em um jogo de plataforma 2D para desktop, o jogador pode usar as teclas WASD para mecânicas de andar, mirar para cima, agachar, e as teclas JKL para atacar, correr, arremesar etc.*

*Ex. Em um jogo de puzzle para celular, o jogador pode tocar e arrastar sobre uma peça para movê-la sobre o tabuleiro, ou fazer um toque simples para rotacioná-la*

# <a name="c4"></a>4. Desenvolvimento do Jogo

## 4.1. Desenvolvimento preliminar do jogo (sprint 1)

*Descreva e ilustre aqui o desenvolvimento da sua primeira versão do jogo, explicando brevemente o que foi entregue em termos de código e jogo. Utilize prints de tela para ilustrar. Indique as eventuais dificuldades e próximos passos.*

  O protótipo é composto por um mapa ortogonal e uma sprite de um personagem para que fosse possível a animação do mesmo. O mapa do protótipo é ambientado em uma ilha no meio do mar, onde posteriormente será substituído por um escritório, para que a ambientação seja de acordo com a proposta de UniOps. 




<div align="center">
Figura 5 - Protótipo 1
 
<img src="../meuGDD/assets/4.1/prot_1.png" width="400" height="300">

<sub>Fonte:Autoria própria(2024)</sub>
</div>
<div align="center">


Figura 6 - Mapa escritório


<img src="../meuGDD/assets/4.1/prot_2.jpg" width="400" height="300">


<sub>Fonte: Autoria própria(2024)</sub>
</div>
As animações dos personagens foram feitas a partir de Sprites, onde foi possível inserir dentro do código a partir de poucas linhas. Além de alinhar a colisão do personagem com os objetos e bordas da ilha. 




<div align="center">
Figura 7 - Sprite Personagem


<img src="../meuGDD/assets/4.1/sprite1.jpeg" width="400" height="300"> 


<sub>Fonte: LimeZu</sub>
</div>
Temos como principal meta a inserção de um npc dentro do mapa para que posteriormente, um diálogo seja atribuído a esse personagem. Dessa forma, as informações mais importantes sobre os conceitos do parceiro de projeto (Unilever) serão passadas de forma simples.
  
## 4.2. Desenvolvimento básico do jogo (sprint 2)

Durante a segunda sprint de desenvolvimento, a equipe concentrou-se em expandir os recursos básicos do jogo e consolidar sua estrutura fundamental. Em vista disso, abaixo está o progresso alcançado no que tange o desenvolvimento, dificuldades encontradas e os passos futuros. 
Descrição do desenvolvimento: 1. Cena Inicial: Implementamos uma cena inicial que apresenta o título do jogo, o cenário principal e um botão "play". O botão "play" foi refinado com efeitos visuais ativados quando o jogador passa o mouse sobre ele.
<div align ="center">
Figuras 8 e 9 - Tela inicial


<img src="../meuGDD/assets/telaInicial.jpg" width="400" height="300">
<img src="../meuGDD/assets/telaInicial2.jpg" width="400" height="300">

<sub>Fonte:Autoria própria(2024)</sub>  
</div>
2. Implementação da Seleção de Personagem: Desenvolvemos uma cena de seleção de personagem com quatro opções. Cada opção possui efeitos visuais distintos ao passar o mouse sobre elas, proporcionando uma experiência interativa ao jogador. 
<div align="center">
Figuras 10 e 11

<img src="../meuGDD/assets/selecaoDePersonagem.jpg" width="400" height="300">
<img src="../meuGDD/assets/selecaoDePersonagem2.jpg" width="400" height="300">

<sub>Fonte:Autoria própria (2024)</sub>
</div>
3. Integração das Cenas: - Realizamos a integração entre todas as cenas do jogo, garantindo uma transição suave entre elas. Ao pressionar o botão "play", o jogador é redirecionado para a seleção de personagem e, posteriormente, para a cena principal do jogo.
**imagem**

4 - Adição de Interatividade: - Introduzimos o botão 'E' como principal meio de interação do jogador. Esse botão permite interações com NPCs e acesso a diferentes áreas do jogo.
<div align="center">
Figura 12 - Interação com NPC

<img src="../meuGDD/assets/InteracaoNPC.jpg" width="400" height="300">

<sub> Fonte: Autoria própria(2024)</sub>
</div>
5 - Melhorias no Código: - Adicionamos comentários ao código para facilitar a compreensão e manutenção futura. - Modularizamos o código, promovendo uma estrutura mais organizada e expansível.
<div align="center">
Figura 13

<img src="../meuGDD/assets/modulacaoCodigo.jpg">

<sub>Fonte: Autoria própria(2024)</sub>
</div>

Durante esta sprint, enfrentamos desafios significativos, sendo assim algumas das dificuldades encontradas estão: 

1 - Integração das Cenas: Encontramos dificuldades ao conectar a cena de seleção de personagem à cena principal do jogo, exigindo uma análise mais aprofundada da lógica de transição entre as cenas. 

2 - Implementação dos Balões de Fala: Encontramos obstáculos na implementação dos balões de fala para garantir uma interação eficaz entre NPCs e jogadores, exigindo iterações adicionais para alcançar a funcionalidade desejada. 

Para superar esses obstáculos, realizamos uma distribuição de tarefas entre os membros da equipe, permitindo diferentes perspectivas e abordagens para solucionar os problemas encontrados. Além disso, buscamos orientação de colegas que enfrentaram desafios semelhantes. 

Entre os próximos passos no projeto, incluem-se:

1 - Desenvolvimento de Novas Cenas (Fases): Expandir o jogo com a criação de novos níveis contendo desafios únicos e mecânicas de jogo aprimoradas. 

2 - Polimento Gráfico e Sonoro: Continuar aprimorando os aspectos visuais e sonoros do jogo para proporcionar uma experiência imersiva e envolvente aos jogadores.

3 - Testes de Jogabilidade: Realizar testes rigorosos para garantir uma experiência de jogo satisfatória e livre de problemas.

Esta sprint foi fundamental para estabelecer uma base sólida para o jogo e nos preparar para implementações mais avançadas nas próximas iterações. Embora tenhamos enfrentado algumas dificuldades, avançamos consideravelmente no desenvolvimento do jogo.




## 4.3. Desenvolvimento intermediário do jogo (sprint 3)

*Descreva e ilustre aqui o desenvolvimento da versão intermediária do jogo, explicando brevemente o que foi entregue em termos de código e jogo. Utilize prints de tela para ilustrar. Indique as eventuais dificuldades e próximos passos.*

## 4.4. Desenvolvimento final do MVP (sprint 4)

*Descreva e ilustre aqui o desenvolvimento da versão final do jogo, explicando brevemente o que foi entregue em termos de MVP. Utilize prints de tela para ilustrar. Indique as eventuais dificuldades e planos futuros.*

## 4.5. Revisão do MVP (sprint 5)

*Descreva e ilustre aqui o desenvolvimento dos refinamentos e revisões da versão final do jogo, explicando brevemente o que foi entregue em termos de MVP. Utilize prints de tela para ilustrar.*

# <a name="c5"></a>5. Testes (sprint 4)

## 5.1. Casos de Teste

*Descreva nesta seção os casos de teste comuns que podem ser executados a qualquer momento para testar o funcionamento e integração das partes do jogo. Utilize tabelas para facilitar a organização.*

*Exemplo de tabela*
\# | pré-condição | descrição do teste | pós-condição 
--- | --- | --- | --- 
1 | posicionar o jogo na tela de abertura | iniciar o jogo desde seu início | o jogo deve iniciar da fase 1
2 | posicionar o personagem em local seguro de inimigos | aguardar o tempo passar até o final da contagem | o personagem deve perder uma vida e reiniciar a fase
3 | ...

## 5.2. Testes de jogabilidade (playtests) (sprint 4)

### 5.2.1 Registros de testes

*Descreva nesta seção as sessões de teste/entrevista com diferentes jogadores. Registre cada teste conforme o template a seguir.*

Nome | João Jonas (use nomes fictícios)
--- | ---
Já possuía experiência prévia com games? | sim, é um jogador casual
Conseguiu iniciar o jogo? | sim
Entendeu as regras e mecânicas do jogo? | entendeu as regras, mas sobre as mecânicas, apenas as essenciais, não explorou os comandos complexos
Conseguiu progredir no jogo? | sim, sem dificuldades  
Apresentou dificuldades? | Não, conseguiu jogar com facilidade e afirmou ser fácil
Que nota deu ao jogo? | 9.0
O que gostou no jogo? | Gostou  de como o jogo vai ficando mais difícil ao longo do tempo sem deixar de ser divertido
O que poderia melhorar no jogo? | A responsividade do personagem aos controles, disse que havia um pouco de atraso desde o momento do comando até a resposta do personagem

### 5.2.2 Melhorias

*Descreva nesta seção um plano de melhorias sobre o jogo, com base nos resultados dos testes de jogabilidade*

# <a name="c6"></a>6. Conclusões e trabalhos futuros (sprint 5)

*Escreva de que formas a solução do jogo atingiu os objetivos descritos na seção 1 deste documento. Indique pontos fortes e pontos a melhorar de maneira geral.*

*Relacione os pontos de melhorias evidenciados nos testes com plano de ações para serem implementadas no jogo. O grupo não precisa implementá-las, pode deixar registrado aqui o plano para futuros desenvolvimentos.*

*Relacione também quaisquer ideias que o grupo tenha para melhorias futuras*

# <a name="c7"></a>7. Referências (sprint 5)

_Incluir as principais referências de seu projeto, para que seu parceiro possa consultar caso ele se interessar em aprofundar. Um exemplo de referência de livro e de site:_<br>

ROCK CONTENT. Como fazer uma análise SWOT. Disponível em: <https://rockcontent.com/br/blog/como-fazer-uma-analise-swot/>. Acesso em: < 28 fev. 2024>

FERRAMENTAS DA QUALIDADE. Matriz de Riscos: Matriz de Probabilidade e Impacto. Disponível em: <https://ferramentasdaqualidade.org/matriz-de-riscos-matriz-de-probabilidade-e-impacto/>. Acesso em: <08 fev. 2024>

OPENGAMEART. 2D RPG character walk spritesheet. Disponível em: <https://opengameart.org/content/2d-rpg-character-walk-spritesheet>. Acesso em: 09 de fevereiro de 2024>.

LIMEZU. Disponível em: <https://limezu.itch.io/>. Acesso em: 08 fev. 2024>

UNILEVER. Objetivos, valores e princípios. Disponível em: <https://www.unilever.com.br/our-company/objetivos-valores-e-principios/>. Acesso em: < 08 fev. 2024>

# <a name="c8"></a>Anexos

*Inclua aqui quaisquer complementos para seu projeto, como diagramas, imagens, tabelas etc. Organize em sub-tópicos utilizando headings menores (use ## ou ### para isso)*