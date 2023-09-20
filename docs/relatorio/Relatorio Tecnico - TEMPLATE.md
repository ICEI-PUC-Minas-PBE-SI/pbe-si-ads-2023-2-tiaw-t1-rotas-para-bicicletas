# Informações do Projeto
`TÍTULO DO PROJETO`  

......  Bike Route ......

`CURSO` 

......  Sistemas de Informação ......

## Participantes

...... Os membros do grupo são: <br>
Victor Lucas de Ângela Martins <br>
Bruno Gustavo Rezende <br>
Gustavo Mourão <br>
Higor Rodrigo Campolina Veneroso <br>
Jefferson Marlon Maciel Silva <br>
Raul Adelino Silva
 

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

...... O problema objetivado é o impasse dos ciclistas iniciantes e intermediários em relação a rotas para pedalar, é um problema que acomete principalmente ciclistas iniciantes, pois procuram uma rota mais fácil e menos movimentada para treinar o seu corpo e evoluir no esporte, e muita das vezes o ambiente da cidade grande pode ser um obstáculo para os ciclistas inexperiêntes, devido ao tráfego pesado e locais sem uma ciclovia. Isso faz com que ciclistas iniciantes e intermediários busquem de uma maneira fácil e rápida, uma maneira de conseguir novas rotas para praticar o esporte.
As vezes o abandono do esporte por parte dos ciclistas se dá principalmente devido a falta de locais para irem ou até a falta de um companheiro de pedal, inicialmente pedalar com um amigo ou com uma turma é mais vantajoso e incentivador para o iniciante, e a falta de um local para achar as rotas e companheiros acomete a vida de praticantes inexperientes.
......

## Objetivos

......  OBJETIVO GERAL

-Desenvolver um software web para procurar rotas de biclicleta.

OBJETIVO ESPECÍFICO
Nosso software tem como objetivo direcionar o usuário para a escolha de rotas para a prática do ciclismo. <br>
-Com base em suas preferências e capacidades, o software poderá auxiliar o usuário a escolher qual a melhor rota e quais condições daquela e outras rotas disponíveis; <br>
-Identificar e detalhar as rotas e quais suas condições; <br>
Os ciclista poderão utilizar o site para encontrar rotas para pedalar em sua região, interagir com a rota de outros ciclistas e também postar suas rotas para toda a comunidade ver <br>
-Fornecer uma ferramenta, que permita ao usuário, planejar, descobrir e experimentar rotas; <br>
-Incentivar a comunidade à prática do ciclismo a partir da fácil usabilidade do software. <br> ......

## Justificativa

...... São vários os fatores que justificam a criação de uma aplicação como a nossa, voltada para usuários praticantes (e possíveis aspirantes) ao ciclismo: 

-Sustentabilidade: Prática que incentiva sustentabilidade, uma vez que bicicletas são meios de transportes não poluentes; <br>
-Desafogo de trânsito: o uso de bicicletas é comprovadamente um meio de transporte rápido, prático e que desafoga o trânsito através da redução de espaço das vias; <br>
-Lazer: usado para ciclistas que querem se divertir; <br>
-Segurança e conforto: através das informações sobre rotas, o usuário tem a informação sobre o lugar que ele vai, a fim de se precaver de imprevistos viários, lugares perigosos, ou até mesmo problemas relacionados ao clima; <br>
-HYPE: o hype, agitação, gerado em cima de uma aplicação bem sucedida, acaba sendo difundida e consequente mais usada, o que potencializa todos os itens anteriores; <br> ......

## Público-Alvo

Público-alvo: Entusiastas de Ciclismo Urbano e Aventura

Descrição:
O público-alvo da Bike Route é composto por pessoas que são apaixonadas por ciclismo e estão interessadas em explorar rotas urbanas, trilhas de aventura em suas bicicletas e compartilhar com os demais entusiastas. São pessoas que valorizam a liberdade, a saúde e o contato com a natureza, ao mesmo tempo em que adotam um estilo de vida ativo e ecologicamente consciente. Esse público busca experiências únicas, desafiadoras e emocionantes, enquanto desfruta dos benefícios físicos e mentais que o ciclismo proporciona.

Características do Público-alvo:

Idade: Principalmente entre 15 e 55 anos, embora possa variar.

Estilo de Vida Ativo: Valorizam atividades ao ar livre e buscam maneiras de se manterem ativos e saudáveis.

Variedade de Níveis de Habilidade: Desde ciclistas iniciantes que estão explorando a prática até ciclistas experientes que buscam desafios mais intensos.

Aventura e Exploração: Procuram por novas rotas, trilhas e destinos para expandir seus horizontes e vivenciar aventuras.

Comunidade e Socialização: Participam de grupos de ciclistas, eventos e encontros para compartilhar experiências e conhecimentos.

Equipamento de Qualidade: Estão dispostos a investir em bicicletas de qualidade, acessórios e equipamentos que melhorem sua experiência de ciclismo.

Conectados Digitalmente: Usam aplicativos, redes sociais e plataformas online para planejar rotas, acompanhar o progresso e interagir com outros ciclistas.

Saúde Mental e Bem-estar: Reconhecem os benefícios do ciclismo para o alívio do estresse e a melhoria do estado de espírito.
 
# Especificações do Projeto

...... No documento serão abordadas as funções que nosso site irá realizar, como a aba comunidade, a área de mapas e etc.
Serão utilizadas algumas abas html para fazer uma parte de navegação, uma API de mapas do google pra poder visualizar e mexer nos mapas disponibilizados pelos usuários, e será usado um arquivo CSS para fazer a estilização do site, com uma paleta de cores, uma logo e com imagens durante o site. ......

## Personas e Mapas de Empatia

...... Persona - Victor Lucas <br>
![persona_Victor Lucas](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/8fccbfd5-0d35-4960-a0b2-6c5939b114b7) <br>
Mapa de Empatia - Victor Lucas <br>
![mapa de empatia_Victor Lucas](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/d4f46071-305d-4248-9c97-2c5955a74ac1) <br>

Persona - Bruno Gustavo <br>
![persona-bruno](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/blob/master/docs/relatorio/images/persona-bruno.jpg) <br>
Mapa de empatia - Bruno Gustavo <br>
![mapa de empatia bruno](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/blob/master/docs/relatorio/images/mapa%20de%20empatia%20-%20bruno.jpg) <br>

Persona - Jefferson Marlon <br>
![breno](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/1d630934-08e6-4d2f-ab13-1293c69174c0) <br>
Mapa de Empatia - Jefferson Marlon <br>
![mapa-empatia-jeff](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/714595d4-d90f-4db6-a3f2-4292e0a1e57b) <br>

Persona - Gustavo Mourão <br>
![Captura de tela 2023-09-13 110726](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/140968286/46b8bafd-31f1-46a3-b167-ee45038068e0) <br>
Mapa de Empatia - Gustavo Mourão <br>
![MAPA EMPATIA](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/140968286/a7d5eea9-7709-442e-9304-1f901cb3f5fd) <br>

Persona - Raul Adelino <br>
![Persona - José da Silva.jpg](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/blob/master/docs/relatorio/images/Persona%20-%20Jos%C3%A9%20da%20Silva.jpg) <br>
Mapa de Empatia - Raul Adelino <br>
![Mapa de Empatia - José da Silva.jpg](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/blob/master/docs/relatorio/images/Mapa%20de%20empatia%20-%20Jos%C3%A9%20da%20Silva.jpeg) <br>

Persona - Higor Campolina <br>
![1694778426702-9cda70c6-7d50-4932-ae06-6d14aa9b6c91_1](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/132582545/884817ed-5cfa-4213-878e-cb42029aecce) <br>

Mapa de Empatia - Higor Campolina <br>
![Template - Mapa de Empatia-1](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/132582545/3f0707ce-9db0-4eb4-949b-b8826129d67e) <br>

......

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Utilizar o site                    | Conseguir novas rotas              |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir ao usuário acesso ao gps com informações de ruas, bairros e cidades  | ALTA | 
|RF-002| O sistema deve perimitir ao usuário colocar mapas e rotas no site | ALTA | 
|RF-003| O usuário deve conseguir alterar o seu perfil dentro da aplicação | MÉDIA| 
|RF-004| O usuário deve informar a região onde ele mora |ALTA| 
|RF-005| Permitir que o usuário interaja com outros usuárioss | MÉDIA | 
|RF-006| Emitir a quantidade de rotas salvas pelo usuário  | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Segurança dos dados do usuário | ALTA |
|RNF-002| O sistema deve ser responsivo para todas as plataformas| ALTA | 
|RNF-003| Facilidade do acesso as rotas | ALTA | 
|RNF-004| O sistema deve ter acesso à localização do usuário |MÉDIA| 
|RNF-005| O sistema deve ser desenvolvido em JavaScript e HTML |MÈDIA| 
|RNF-006| O sistema deve emitir um relatório de acessos todo final de semana | BAIXO| 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O usuário não pode acessar o código fonte do site     |
|02| O usuário não pode alterar a aparência do site        |
|03| O usuário pode utilizar somente imagens dos mapas     |
|04| O sistema não pode ser utilizado em tela divida no    
mobile.                                                    |
|05| O usuário não pode excluir ou alterar os posts de     
outro usuário.                                             |
|06| O usuário poderá utilizar arquivos em formato         
.jpg ou .png                                               |

# Projeto de Interface

......  As interfaces principais serão: <br> A tela inicial (início) <br> A interface onde ficarão localizadas as rotas (rotas) <br> A interface da comunidade, onde os usuários poderão interagir entre si <br> A interface do perfil do usuário, onde ele poderá alterar seu perfil de acordo com o próprio gosto(perfil) <br> A parte de patrocínios, onde ele poderá ver os parceiros do nosso site (patrocínios) <br> A área de contatos, onde se encontrará os nossos meios de contato (contato) <br> E a parte onde poderão conhecer um pouco mais da nossa equipe e dos nossos objetivos (sobre nós). ......

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

...... O nosso wireframe foi feito ulilizando html e css e é somente a aparência básica do site, possíveis mudanças podem ser feitas
 ![Captura de tela 2023-09-19 104424](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/5c90111d-14ab-45be-91ed-3761502cdb62)
<br>
![Captura de tela 2023-09-20 080156](https://github.com/ICEI-PUC-Minas-PBE-SI/pbe-si-ads-2023-2-tiaw-t1-rotas-para-bicicletas/assets/142837785/54d8a23e-fccc-4fe9-9e8d-0ecdd2d08836)

......

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
