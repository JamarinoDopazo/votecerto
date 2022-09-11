# Especificações do Projeto
### Personas

| `Persona` | `Idade` | `Descrição` | `Fontes de informação utilizados` | `Motivações` | `Frustrações`  |  `Hobbies` |
|:-----------:|:---------:|:-------------:|:---------------------------------:|:--------------:|:----------------:|:------------:|
|Raimundo Mota|18|Estudante do ensino médio. Acabou de tirar o título de eleitor.|Instagram, Facebook, Twitter, Youtube|Verificcar como cada candidato se posiciona em relação às políticas de quotas raciais para ingresso na universidade.| Dificuldade de realmente conhecer os candidatos em ano eleitoral, já que tanto candidatos se maqueiam, quanto oposição dissemina fake news.|Filmes e séries, academia|
|Daniela Ferreira|34| Professora da rede pública estadual de Minas Gerais|Instagram, Portal de notícias, TV|Saber como os candidatos que ela pretende votar, se posicionam em relação ao piso salarial|Excesso de desinformação e notícias falsas, brigas em grupos de família.|Ler e mexer na Internet|
|Benício Almada |61|Policial Civil aposentado, se auto-intitulo como cidadão conservador de direita.|WhatsApp, rádio, TV, facebook e portais de notícias|Encontrar candidatos do legislativo que compartilhem da mesma pauta política e apoiem seus candidatos do executivo.|	Acredita que muitos (deputados e senadores) eleitos na última eleição por supostamente apoiarem o presidente da república, mudaram de posicionamento após estarem no poder.|Pescar, sair pra comer|
|Jaqueline de Jesus|27|Desempregada. Perdeu o emprego durante a pandemia e agora precisa de auxílio do governo para manter a família.|TV e WhatsApp| Ter acesso a informação confiável sobre os candidatos, e como eles pretendem reduzir a taxa de desemprego.|Recebe muita notícia no Whatsapp mas não sabe o que é verdade ou mentira|Assistir TV e passear com os filhos|

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>



## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

A seguir, os indicadores de desempenho que serão monitorados para controle e melhoria do sistema.

![indicadores de desempenho](img/02-indicadorDesempenho.png)

Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir a criação de contas, dentro do site e do App. | ALTA | 
|RF-002| Ter uma página para a listagem dos candidatos.   | ALTA |
|RF-003| Ter uma página para a listagem dos eleitos e membros ativos dos 3 poderes .  | ALTA |
|RF-004| Ter um link para o plano de governo de cada candidatos a partir do seu regisstro.   | ALTA |
|RF-005| Informar se o candidato já ocupou algum cargo no governo.   | ALTA |
|RF-006| Listar, dentro de cada candidato e membro ativo do governo, projetos de lei propostos por eles, caso eles já tenham proposto algum. | ALTA |
|RF-007| Ter uma página com todas as leis, decretos, resoluções ... já aprovadas (Resumo e link para o arquivo oficial no portal oficial do governo). | ALTA|
|RF-008| Na página de legislações. listar todos que votaram a favor e contra   | MEDIA |
|RF-009| Na página principal, permitir que o usuário pesquise dinamicamente, termos que deseja buscar |MEDIA|
|RF-010| Permitir que o usuário crie alertas por localidade, candidatos ou membros ativos, assunto que deseja receber notificação | BAIXA |
|RF-011| Cada candidato ou membro ativo do governo, precisa ter sua própria página, com informações do mesmo.   | ALTA |
|RF-012| Ter uma página de fake check. com notícias atuais.   | MÉDIA |
|RF-013| Na página de fake check, rotular as notícias como Verdade ou Mentira | MEDIA |
|RF-014| Justificar, na pagina de fake check, porque a informação foi rotulada como verdade ou mentira  | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Deve existir uma padronização na navegação tanto no Mobile quando no Web. | ALTA | 
|RNF-002| O Site deve atender aos requisitos de SEO, aplicados pelo Google. |  MÉDIA |
|RNF-003| O App e a aplicação Web, devem compartilhar as mesmas informações de login e cadastro de usuários. |  ALTA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
       |


## Diagrama de Casos de Uso

A seguir, apresentam-se os casos de uso que contemplam a aplicação á ser desenvolvida. O diagrama dá uma visão geral do comportamento do sistema pela parte de usuário e a interna do sistema.

![Diagrama de caso de uso Vote Certo](img/02-DiagramaCasoUso.png)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio.

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

O gerenciamento de tempo da equipe foi dividido em cinco etapas que contêm diversas subtarefas que deverão ser concluídas dentro do tempo estipulado. A seguir, pode-se observar o PDF gráfico da organização de cronograma que a equipe deverá seguir.

[Vote Certo cronograma.pdf](img/02-Cronogrma.png

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-timeline.png)

## Gestão de Orçamento

A seguir, apresenta-se a planilha de orçamento previsto para implementação efetiva do projeto. 

![Planilha de custos](img/02-PlanilhaDeCustos.png)
