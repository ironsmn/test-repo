# Objetivo 
Criar um site para a STRYKERS, organização que joga o jogo Star Citizen.

## Sobre a STRYKERS
A STRYKERS é uma força paramilitar que atua dentro do mundo estabelecido no jogo Star Citizen.
A STRYKERS é uma força paramilitar brasileira organizada, que atua com hierarquia, estratégia e cooperação em todos os setores do universo do jogo Star Citizen. Seja em solo ou no espaço, operamos com profissionalismo e foco tático, oferecendo aos membros uma experiência imersiva baseada em operações reais, treinamentos, campanhas militares e um senso forte de unidade.
Aqui, você não apenas joga — você se alista, treina, cresce e se torna parte de uma tropa onde cada membro tem valor e função.
Do Recruta ao Marechal, todos têm um papel vital na engrenagem da corporação.
Se você busca organização, camaradagem, disciplina e oportunidades reais de evolução, aliste-se.
A STRYKERS está em marcha — com ou sem você.

Nossa missão é criar uma estrutura militar funcional, divertida e acolhedora. Cada membro é valorizado e guiado por uma hierarquia clara, com foco em treinamentos, missões, campanhas e evolução pessoal.

Por que existimos: Queremos mais do que jogar - buscamos imersão, identidade e propósito dentro do universo. Seja como recruta, instrutor ou comandante de uma nave capital, na STRYKERS você sempre terá um caminho para crescer.

Moto: Disciplina. Ordem. Supremacia.

# 1) Arquitetura do Site
## 1.1 Atores
### 1.1.1 Administradores
Usuários com permissões de acesso elevado no site.

### 1.1.2 Usuário Cadastrado
Usuário cadastrado no site.
Possui permissão para:
- Navegar e visualizar todas as páginas do site.
- Editar os campos do seu perfil: usuário, apelido, e-mail e foto de perfil.
- De acordo com o seu nível de patente.

### 1.1.3 Visitante
Pessoas que estão visitando o site sem estarem autenticadas, tendo acesso apenas à Página Inicial.

## 1.2 Página Inicial
A Página Inicial é a porta de entrada para o site da STRYKERS. 
É a página inicial pela qual todos deverão passar para acessar o site da STRYKERS, sejam Usuários Cadastrados ou Visitantes.
Na Página Inicial deverá haver os campos:
- Usuário: campo utilizado para o Usuário Cadastrado digitar o seu nome de usuário.
- Senha: campo utilizado para o Usuário Cadastrado digitar a sua senha.
- Esqueci a senha: campo utilizado para o Usuário Cadastrado trocar de senha.
- Cadastrar: campo utilizado para o Visitante realizar o Cadastro de Usuário.

## 1.3 Cadastro de Usuário
Qualquer pessoa pode realizar o cadastro.
Porém, a ativação da conta cadastrada deve ser confirmada por um grupo de administradores do site que podem ser desde desenvolvedores até oficiais superiores.
Campos para cadastro são: 
- Usuário: qualquer nome de usuário para realizar login no sistema.
- Senha: senha definida pelo usuário para realizar login no sistema.
- Apelido: deverá ser preenchido com o Star Citizen "Handle" utilizado pelo usuário dentro do jogo.  
- E-mail: e-mail a ser utilizado pelo usuário para realizar login no site.
- Foto de perfil: realizar upload de uma imagem para a foto de perfil.

As senhas deverão ser protegidas por hash, para que ninguém, mesmo que com acesso ao banco de dados, tenha acesso às mesmas.

Possível mecanismo para otimização e segurança da conta do usuário:
- O Visitante ao realizar Cadastro de Usuário não irá cadastrar uma Senha, ao invés disso, irá receber em seu e-mail um link para ativar a conta.
- Para realizar o login no site, o Usuário Cadastrado ao digitar o e-mail o usuário receberá um código em seu e-mail, e utilizará este código para então realizar login no site.

## 1.4 Perfil de Usuario
No perfil do usuário, possuirá:
- "Apelido": "Handle" do usuário dentro do jogo Star Citizen.
- "Patente": apresentando alguma das patentes listadas em patentes.md
- "Força": Força Aérea, Marinha ou Exército.
- "Forças Especiais", caso pertença a alguma.
- "Histórico Militar", contendo todo o histórico de participação do usuário, como:
- "Contribuições", caso possua algum trabalho "Voluntário" concluído ou alguma contribuição agregada aos "Objetivos".
- "Condecorações", caso possua alguma.
- "Página Star Citizen", URL completo do perfil do usuário no site do Star Citizen, https://robertsspaceindustries.com/citizens/Apelido, onde "Apelido" é substituído pelo Star Citizen "handle" cadastrado pelo usuário.

O perfil do usuário é de acesso público dentro do site entre os Usuários Cadastrados.

## 1.5 Forças Armadas
As Forças Armadas são: Marinha, Exército e Força Aérea.

## 1.6 Forças Especiais
As Forças Especiais são:
- GHOST, subordinados à Marinha.
- STORM, subordinados ao Exército.
- SPEAR, subordinados à Força Aérea.

## 1.7 Patentes
As Patentes estão listadas no arquivo patentes.md.

# 2) Páginas do Site

## 2.1 Perfil de Usuario
No perfil do usuário, possuirá:
- "Apelido": "Handle" dentro do Star Citizen.
- "Patente": apresentando alguma das patentes listadas em patentes.md
- "Força": Força Aérea, Marinha ou Exército.
- "Forças Especiais", caso pertença a alguma.
- "Histórico Militar", contendo todo o histórico de participação do usuário, como:
- "Contribuições", caso possua algum trabalho "Voluntário" concluído ou alguma contribuição agregada aos "Objetivos".
- "Condecorações", caso possua alguma.
O perfil do usuário é de acesso público dentro do site.

## 2.2 Quadro Militar
### 2.2.1 Forças Armadas
As Forças Armadas são: Marinha, Exército e Força Aérea.
O Usuário Cadastrado poderá aplicar para se alistar em uma destas três Forças.
E o Usuário Cadastrado que possuir a patente mínima de Oficial General daquela Força poderá aprovar ou não esta aplicação.

#### 2.2.1.1 Marinha
##### 2.2.1.1.1 Descrição sobre a Marinha: 
- Para os estrategistas do espaço! Se curte naves capitais, funções de tripulação e combates de grande escala, a Marinha é o seu lugar.
- Podem conter naves capitais e subcapitais sob o comando de um Almirante.
- Comande sua própria tripulação em grandes operações.
- Treinamento específico em coordenação e liderança.
- Faça parte de tripulações como FUZILEIRO ESPACIAL, com funções e objetivos variados.

#### 2.2.1.2 Exército
##### 2.2.1.2.1 Descrição sobre a Exército: 
- Para os que preferem o combate em solo, usando táticas FPS, ocupando posições, limpando estruturas e dominando terreno.
- Treinamentos intensivos de combate em solo.
- Operações estratégicas e táticas FPS.
- Oportunidade de liderar esquadrões de elite.

Dentro do Exército, contamos com as _Forças Auxiliares_:

- Engenharia:
Responsável pela logística da equipe, coleta de loot, suporte técnico e mobilização de veículos pesados.
Transporte de veículos de combate, tropas e equipamentos
Suporte operacional e reabastecimento em zonas de combate
Função essencial para o sucesso das missões
Reparo e manutenção essenciais no interior de naves

- Socorristas:
Especialistas em suporte médico, evacuação e primeiros socorros durante o combate.
Atue como Médico de Combate e Socorrista
Realize evacuações médicas em zonas de conflito
Especialize-se em suporte vital e primeiros socorros durante operações

#### 2.2.1.3 Força Aérea
##### 2.2.1.3.1 Descrição sobre a Força Aérea: 
- Para os caçadores do céu! Se você domina dogfights e quer ser um ás dos caças, essa é sua linha.
- Pilote caças leves e pesados
- Domine os céus em dogfights emocionantes
- Ofereça suporte aéreo para as naves capitais

### 2.2.2 Forças Especiais
GHOST operar com os melhores nas Forças Especiais ( 💀 GHOSTS)
STORM é a Força Especial operada pelos 
SPEAR é a Força Especial operada pelos pilotos de elite da Força Aérea que 

## 2.3 Inventario 
Quero criar um Inventário da organização. 
Nesta página de Inventário, as pessoas vão compartilhar o que elas têm disponível para doar para qualquer membro da organização.
Por exemplo, eu tenho um monte de componentes sobrando, eu quero que eles fiquem disponíveis no sistema pra que quem quiser eu possa dar

## 2.4 Sala de Guerra
No site poderão ser criadas Missões, Operações e Campanhas:
- _Missões_ podem ser criadas minimamente por Praças. Aprovação mínima de Oficiais para a confirmação da Missão. 
- _Operações_ podem ser criadas minimamente por Oficiais. Aprovação mínima de Oficiais Generais para a confirmação da Operação. 
- _Campanhas_ podem ser criadas minimamente por Oficiais Generais. Aprovação mínima do Marechal para a confirmação da Campanha.

Quando uma Missão/Operação/Campanha for criada, um card do evento será criado na página de Sala de Guerra. 
Missões, Operações e Campanhas são abertas para a participação de todos.
Recrutas não podem criar nada, mas podem participar de tudo.

## 2.5 Objetivos
Quero também criar "Objetivos"  da organização. Por exemplo, coletar materiais pra fazer uma Idris do Wikelo. Aí no sistema vai ter o que é preciso de item e o que cada um tem disponível pra contribuir até conseguirmos etc. Por exemplo, o Marechal cria no site um objetivo de conseguirmos a Idris do Wikelo. Aí então vai haver uma lista de itens necessários e aí as pessoas da organização vão postando neste objetivo específico da Idris quais e quantos componentes desta lista essas pessoas têm. E, consequentemente, conforme as pessoas da organização vão postando os itens com que irão colaborar, a tabela geral vai sendo atualizada mostrando quantos itens de cada componente faltam.

## 2.6 Treinamentos
Nesta página, apresentaremos os Treinamentos existentes. Os treinamentos são sempre abertos a todos, porém, alguns treinamentos mais avançados que forem mais específicos para uma função (por exemplo, pilotos oficiais da Força Aérea) poderão ter como pré-requisito a conclusão prévia de outro(s) treinamento(s).

## 2.7 Voluntários
Nesta pagina, de "Voluntários", serve para aqueles que estejam dispostos a ajudar os novatos ou em qualquer assunto especifico, da mesma forma que funciona o sistema da RSI onde as pessoas voluntárias se fazem dispostas a ensinarem novatos em qq assunto q seja.. por exemplo, uma pessoa é boa em Minerar e ele é voluntario, entao ele vai la e poe que ensina a quem quiser sobre minerar e ai vai mostrar os dias e horas da semana q ele vai estar disponível, e ai então as pessoas se inscrevem para aprender. O requisito mínimo para se tornar um voluntário no sistema é ter a patente de Sargento (seguir a hierarquia de patentes em patentes.md).

## 2.8 Centro de Comunicação
Central de comunicação onde mensagens/informativos serão compartilhados dentro dos canais de comunicação selecionados conforme estão listados abaixo:
- Geral (a todos)
- Oficiais Generais/Superiores
- Forças (Aérea, Marinha e Exército)
- Forças Especiais (SPEAR, GHOST, STORM).

## 2.9 Quadro de Condecorações e Promoções
Nesta página, apresentaremos o histórico (log) das condecorações e das promoções. 

### 2.9.1 Insígnias de Condecoração
🎖️ Medalha de Mérito Operacional: Concedida a membros que demonstraram excelência em incursões táticas e operações hostis com sucesso.
🛡️ Medalha de Defesa Avançada: Reconhecimento por atuações destacadas na proteção de VIPs, comboios e zonas estratégicas sob ameaça.
🥇 Medalha de Elite Aérea: Premiação para pilotos que demonstraram superioridade aérea, manobras avançadas e domínio total em combate espacial.
🥈 Medalha de Infantaria Pesada: Concedida a soldados de chão que atuaram com coragem, disciplina e precisão em combates terrestres e manobras com veículos.
🦅 Insígnia da Águia Dourada: Honraria rara, concedida apenas aos que lideraram operações completas com sucesso total, mostrando comando, estratégia e disciplina.
🪙 Distintivo de Honra Logística: Entregue a operadores de logística e transporte que garantiram o sucesso de missões com eficiência e organização impecável.

## 2.10 Uniformes
Nesta página, apresentaremos os Uniformes do padrão STRYKER no Star Citizen utilizados pelas três forças: Marinha, Exército e Força Aérea.

## 2.11 Sites Úteis
Lista de sites úteis com uma breve descrição deles e para o que eles servem ou para o que são úteis.
- https://starcitizen.tools/
- https://www.spviewer.eu/
- https://www.erkul.games/calculator
- https://finder.cstone.space/
- https://sc-trade.tools/home
- https://uexcorp.space/
- https://scmdb.net/
- https://robertsspaceindustries.com/galactapedia
- https://scblueprints.app/
- https://sccrafter.com/
- https://sc-market.space/
- https://verseguide.com/
- https://wikelotrades.com/
- https://battlestations.osiris-devworks.com/
- https://maps.adi.sc/
- https://wikelotrades.com/
- https://ccugame.app/
- https://fleetyards.net/
- https://docs.google.com/spreadsheets/d/1hPtkQZPNzyahafSuZlPWVj-SMnWxAw-Y5LgSIj62fq4/edit?pli=1&gid=0#gid=0

## 2.12 Ferramentas Úteis
Lista de ferramentas úteis para serem usadas dentro do Star Citizen, com uma breve descrição delas e para o que elas servem ou para o que são úteis.
- https://github.com/Osiris-DevWorks/smart-citizen
- https://github.com/MrKraken/StarStrings

## 2.13 Lojas Online
Lista de sites de lojas online relacionados ao Star Citizen, com uma breve descrição deles e para o que eles servem ou para o que são úteis.
- https://theimpound.com/
- https://star-hangar.com/
- https://www.pigeonspaceport.com/
- https://winctrl.com/view/
- https://virpil-controls.us.com/
- https://mozaracing.com/
https://vkbcontrollers.com/
https://www.logitech.com/en-us/shop/c/simulation
