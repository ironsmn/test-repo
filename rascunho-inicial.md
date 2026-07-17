Voce é expert em sistemas .

Estou tentando levantar os requisitos, os

Analise as minhas anotações abaixo e :

No sistema eu quero ter além de tudo isso que já conversamos sobre histórico, patentes e etc, 

# 1) Estrutura do site

## Atores
### Administradores
### Usuário Cadastrado
Usuário cadastrado poderá editar os campos do seu perfil.
### Visitante

## Página Inicial
A Página Inicial é a porta de entrada para o site da STRYKERS. 
É a página inicial pela qual todos deverão passar para acessar o site da STRYKERS, sejam Usuários Cadastrados ou Visitantes.
Na Página Inicial deverá haver os campos:
- Usuário: campo utilizado para o Usuário Cadastrado digitar o seu nome de usuário.
- Senha: campo utilizado para o Usuário Cadastrado digitar a sua senha.
- Esqueci a senha: campo utilizado para o Usuário Cadastrado trocar de senha.
- Cadastrar: campo utilizado para o Visitante realizar o Cadastro de Usuário.

## Cadastro de Usuário
Qualquer pessoa pode realizar o cadastro.
Porém, a ativação da conta cadastrada deve ser confirmada por um grupo de administradores do site que podem ser desde desenvolvedores até oficiais superiores.
Campos para cadastro são: 
- Usuário: qualquer nome de usuário para realizar login no sistema.
- Senha: senha definida pelo usuário para realizar login no sistema.
- Apelido: deverá ser preenchido com o Star Citizen "Handle" utilizado pelo usuário dentro do jogo.  
- E-mail: e-mail a ser utilizado pelo usuário para realizar login no site.

As senhas deverão ser protegidas por hash, para que ninguém, mesmo que com acesso ao banco de dados, tenha acesso às mesmas.

## Perfil de Usuario
No perfil do usuário, possuirá:
- "Apelido": handle id dentro do Star Citizen.
- "Patente": apresentando alguma das patentes listadas em patentes.md
- "Força": Força Aérea, Marinha ou Exército.
- "Forças Especiais", caso pertença a alguma.
- "Histórico Militar", contendo todo o histórico de participação do usuário, como:
- "Contribuições", caso possua algum trabalho "Voluntário" concluído ou alguma contribuição agregada aos "Objetivos".
- "Condecorações", caso possua alguma.
O perfil do usuário é de acesso público dentro do site.

## Forças Armadas
As Forças Armadas são: Marinha, Exército e Força Aérea.

### Marinha
Para os estrategistas do espaço! Se curte naves capitais, funções de tripulação e combates de grande escala, a Marinha é o seu lugar.
- Frotas: Podendo conter naves Capitais e Subcapitais sob o comando de um Almirante.
- Esquadras: Caças subordinados aos líderes de naves capitais, com o objetivo de dar suporte e defesa.

### Exército
Para os que preferem o combate em solo, usando táticas FPS, ocupando posições, limpando estruturas e dominando terreno.
Dentro do Exército, contamos com:
- Engenharia: Responsável pela logística da equipe, coleta de loot, suporte técnico e mobilização de veículos pesados.
- Socorristas: Especialistas em suporte médico, evacuação e primeiros socorros durante o combate.
- Forças Especiais: Unidades com treinamento avançado para missões específicas, infiltrações e tarefas táticas de alta complexidade.

### Força Aérea
Para os caçadores do céu! Se você domina dogfights e quer ser um ás dos caças, essa é sua linha.

## Forças Especiais


# 2) Páginas do Site

## Perfil de Usuario
No perfil do usuário, possuirá:
- "Apelido": handle id dentro do Star Citizen.
- "Patente": apresentando alguma das patentes listadas em patentes.md
- "Força": Força Aérea, Marinha ou Exército.
- "Forças Especiais", caso pertença a alguma.
- "Histórico Militar", contendo todo o histórico de participação do usuário, como:
- "Contribuições", caso possua algum trabalho "Voluntário" concluído ou alguma contribuição agregada aos "Objetivos".
- "Condecorações", caso possua alguma.
O perfil do usuário é de acesso público dentro do site.

## Inventario 
Quero criar um Inventário da organização. Onde as pessoas vão compartilhar o que elas têm de disponível para doar para qualquer membro da organização.
Por exemplo, eu tenho um monte de componentes sobrando, eu quero que eles fiquem disponíveis no sistema pra que quem quiser eu possa dar

## Sala de Guerra
No site as pessoas poderão criar missões, operações e campanhas. 
- __Missões__ podem ser criadas minimamente por Praças, porém, aprovadas pelos Oficiais. 
- __Operações__ podem ser criadas minimamente por Oficiais, porém, aprovadas pelos Oficiais Generais ou pelo Marechal. 
- __Campanhas__ criadas minimamente pelos Oficiais Generais, e aprovadas pelo Marechal.
Quando for criado a Missão ou Operação, haverá um card na página de 
Recrutas não podem criar nada, mas podem participar de tudo.

## Objetivos
Quero também criar "Objetivos"  da organização. Por exemplo, coletar materiais pra fazer uma Idris do Wikelo. Aí no sistema vai ter o que é preciso de item e o que cada um tem disponível pra contribuir até conseguirmos etc. Por exemplo, o Marechal cria no site um objetivo de conseguirmos a Idris do Wikelo. Aí então vai haver uma lista de itens necessários e aí as pessoas da organização vão postando neste objetivo específico da Idris quais e quantos componentes desta lista essas pessoas têm. E, consequentemente, conforme as pessoas da organização vão postando os itens com que irão colaborar, a tabela geral vai sendo atualizada mostrando quantos itens de cada componente faltam.

## Treinamentos
Nesta página, apresentaremos os Treinamentos existentes. Os treinamentos são sempre abertos a todos, porém, alguns treinamentos mais avançados que forem mais específicos para uma função (por exemplo, pilotos oficiais da Força Aérea) poderão ter como pré-requisito a conclusão prévia de outro(s) treinamento(s).

## Voluntários
Nesta pagina, de "Voluntários", serve para aqueles que estejam dispostos a ajudar os novatos ou em qualquer assunto especifico, da mesma forma que funciona o sistema da RSI onde as pessoas voluntárias se fazem dispostas a ensinarem novatos em qq assunto q seja.. por exemplo, uma pessoa é boa em Minerar e ele é voluntario, entao ele vai la e poe que ensina a quem quiser sobre minerar e ai vai mostrar os dias e horas da semana q ele vai estar disponível, e ai então as pessoas se inscrevem para aprender. O requisito mínimo para se tornar um voluntário no sistema é ter a patente de Sargento (seguir a hierarquia de patentes em patentes.md).

## Centro de Comunicação
Geral, para Oficiais Generais/Superiores, Forças e .

## Quadro de Condecorações e Promoções
Nesta página, apresentaremos o histórico (log) das condecorações e das promoções. 

### Insígnias de Condecoração
🎖️ Medalha de Mérito Operacional: Concedida a membros que demonstraram excelência em incursões táticas e operações hostis com sucesso.
🛡️ Medalha de Defesa Avançada: Reconhecimento por atuações destacadas na proteção de VIPs, comboios e zonas estratégicas sob ameaça.
🥇 Medalha de Elite Aérea: Premiação para pilotos que demonstraram superioridade aérea, manobras avançadas e domínio total em combate espacial.
🥈 Medalha de Infantaria Pesada: Concedida a soldados de chão que atuaram com coragem, disciplina e precisão em combates terrestres e manobras com veículos.
🦅 Insígnia da Águia Dourada: Honraria rara, concedida apenas aos que lideraram operações completas com sucesso total, mostrando comando, estratégia e disciplina.
🪙 Distintivo de Honra Logística: Entregue a operadores de logística e transporte que garantiram o sucesso de missões com eficiência e organização impecável.

## Uniformes
Nesta página, apresentaremos os Uniformes do padrão STRYKER no Star Citizen utilizados pelas três forças: Marinha, Exército e Força Aérea.

## Sites Úteis
Lista de sites úteis com uma breve descrição deles e para o que eles servem ou para o que são úteis.
https://starcitizen.tools/
https://www.spviewer.eu/
https://www.erkul.games/calculator
https://finder.cstone.space/
https://sc-trade.tools/home
https://uexcorp.space/
https://scmdb.net/
https://robertsspaceindustries.com/galactapedia
https://scblueprints.app/
https://sccrafter.com/
https://sc-market.space/
https://verseguide.com/
https://wikelotrades.com/
https://battlestations.osiris-devworks.com/
https://maps.adi.sc/
https://wikelotrades.com/

## Ferramentas Úteis
Lista de ferramentas úteis para serem usadas dentro do Star Citizen, com uma breve descrição delas e para o que elas servem ou para o que são úteis.

## Lojas Online
Lista de sites de lojas online relacionados ao Star Citizen, com uma breve descrição deles e para o que eles servem ou para o que são úteis.
