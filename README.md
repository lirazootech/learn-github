# 📚 Módulo 3: Recursos de Colaboração

| ![GitHub4Women](https://github.com/lirazootech/learn-github/blob/35028e51e92637c9a121679992b6f029fe87556f/GitHub4Women_Domain3.png) |
|:--:|
| Este repositório foi criado para praticar e aplicar os conhecimentos adquiridos durante o curso GitHub4Women sobre “Collaboration Features” que significa “Recursos de Colaboração”. Esses recursos são ferramentas digitais que ajudam equipes remotas a se conectarem e trabalharem juntas. Nesse momento o foco principal é a ferramenta de gerenciamento de projetos GitHub.
O GitHub permite comunicação assíncrona para membros da equipe em diferentes fusos horários, acesso a documentação e bases de conhecimento a qualquer hora. Essas ferramentas melhoram a eficiência da equipe, reduzem a complexidade das tarefas e permitem que todos colaborem de forma eficaz. |

## 🎯 Conceito e abordagem:

A atividade visa consolidar o conhecimento apresentado em sala de aula, abordando os seguintes tópicos:

- Issues
- Pull requests
- Discussions
- Notifications
- Wikis

## 🤖 Tecnologias Utilizadas:

Para realização dessa atividade, eu utilizei a seguinte tecnologia:

- **GitHub:** Plataforma de hospedagem de código-fonte e colaboração de desenvolvimento de software essencial para desenvolvedores colaborarem, compartilharem código e automatizarem seus fluxos de trabalho.

Aqui estão algumas de suas principais funcionalidades:

#### **Colaboração:**

- ***Contribuição rápida:*** Nos possibilita configurar automaticamente ambientes de desenvolvimento para contribuir com projetos.

- ***Pull requests:*** Permite que colaboradores notifiquem sobre alterações em um repositório e facilmente mesclam as mudanças aceitas.

- ***Discussões:*** Espaço dedicado para a comunidade fazer perguntas e ter conversas abertas.

- ***Pesquisa e visualização de código:*** Nos permite buscar, navegar e compreender rapidamente o código diretamente no <a href="https://github.com/" target="_blank">GitHub.com</a>. 

- ***Notificações:*** Nos permite receber atualizações sobre atividades que seguimos.

#### **Automação e CI/CD:**

- ***GitHub Copilot:*** Sugestões de linhas ou funções inteiras diretamente no editor.

- ***Automação:*** Nos permite automatizar processos como CI/CD, testes, gerenciamento de projetos e mais.

- ***Integrações:*** Nos permite personalizar nosso fluxo de trabalho com integrações para revisão de código, gerenciamento de projetos e muito mais.

## 🧐 Processo de Criação

### Através da plataforma do GitHub:

  Inicialmente criei um novo repositório, e como já visto não devemos fazer alterações direto na “main”, por tanto criei uma nova branch clicando na opção New branch (lado direito superior).

  Na nova branch criada adicionei um novo 'arquivo.md' clicando em 
'Add file' e escrevi uma passagem do livro de Machado de Assis "Memórias Póstumas de Brás Cubas" e realizei o commit. Confira: <a href="https://github.com/lirazootech/learn-github/blob/35028e51e92637c9a121679992b6f029fe87556f/arquivo.md" target="_blank">arquivo.md</a>.

### Criando e gerenciando uma Issue:

  Ao criar o repositório não havia adicionado um arquivo 'README' contendo a descrição informativa, então quando foi solicitado a criação de uma Issue, pensei por bem criar uma nova Issue solicitando não só a criação de um arquivo README, mas também uma descrição detalhada sobre o repositório e ao que se propõe. Como mostra a imagem abaixo:

| ![Issue](https://github.com/lirazootech/learn-github/blob/7989983b45bee39a61f5c422311333084fa6de18/Captura%204.PNG) |
|:--:|
***A Issue foi fechada após a solicitação ser atendida!***

### Criando Discussions

  Na aba "Discussions" e depois em "New discussion" criei uma nova discussão e selecionei a categoria ideia, pois gostaria de simular uma discussão em que um colaborador lança mão de algumas ideias para melhorar o projeto.

| ![Discussion](https://github.com/lirazootech/learn-github/blob/9fd6eff78ec047dbb978078a3ed17f1ce72cbded/Captura%207.PNG) |
|:--:|

As ideias foram enviadas e em seguida eu respondi. Marquei minha resposta como a oficial usando "Mark as answer".

| ![Discussion](https://github.com/lirazootech/learn-github/blob/9fd6eff78ec047dbb978078a3ed17f1ce72cbded/Captura%208.PNG) |
|:--:|
**Ao criar uma nova Discussão é possível compreender como elas se diferenciam das issues.**

**Issues (Problemas): Detalhes específicos, como bugs e melhorias.**

- São úteis para rastrear detalhes específicos de um projeto, como relatórios de bugs, melhorias planejadas e feedback.
- São específicos de um repositório e geralmente têm um proprietário claro.
- Funcionam como um sistema de rastreamento de bugs do GitHub.
- Permitem discussões específicas e ações concretas.
- Podem ser fechados quando o problema é resolvido.

**Discussões (GitHub Discussions): Ideias abertas e colaboração comunitária.**

- São fóruns de comunidade integrados diretamente aos repositórios no GitHub.
- São ideais para conversas abertas, compartilhamento de ideias e conexões com a comunidade.
- Não têm rótulos como os Issues.
- Não podem ser convertidas em Issues, mas um Issue pode ser criado referenciando uma Discussão.
- Podem abranger vários repositórios.
- Criam uma experiência colaborativa fora do código-fonte, permitindo a criação de uma base de conhecimento da comunidade.
- São mais abertas e flexíveis, permitindo conversas sem limitações específicas
- Não podem ser fechadas, mas podem ser resolvidas ou bloqueadas.

Em resumo:

| ![OctaCat](https://github.com/lirazootech/learn-github/blob/13f7473c547782275246e2b00c7f11f785a6285c/Octacat.PNG) |
|:--:|
| Issues são específicos e acionáveis, enquanto Discussões são mais abertas e colaborativas. |

### Trabalhando com Pull Requests

  Na aba "Pull requests" cliquei em "New pull request" para criar uma nova solicitação Pull, selecione a branch base (onde as mudanças foram integradas) e o branch compare (de onde as mudanças vêm). Então usei a branch criada anteriormente, no inicio do exercicio e cliquei em "Create pull request".

  Adicionei "Closes #1" na descrição para linkar a issue correspondente e em seguida conclui o Pull Request clicando em “ merge pull request “.

| ![Discussion](https://github.com/lirazootech/learn-github/blob/eabac5479b7b0127d2407bf5d548e20bb1372526/Captura%206.PNG) |
|:--:|
Com a utilização de um Pull request para o fechamento de uma Issue criada anteriormente, é possivel identificar a diferença entre Issue e Pull Request.

**Issues (Problemas): Detalhes específicos, como bugs e melhorias.**

- Os Issues são usados para rastrear ideias, bugs, tarefas e outras informações importantes em um projeto.
- Qualquer pessoa pode criar um Issue em um repositório público que tenha os Issues habilitados.
- Eles são específicos de um repositório e podem ser usados para discussões abertas.

| ![OctaCat](https://github.com/lirazootech/learn-github/blob/13f7473c547782275246e2b00c7f11f785a6285c/Octacat.PNG) |
|:--:|
| Por exemplo, se você encontrar um bug ou tiver uma ideia, crie um Issue para compartilhar com a comunidade. | 

**Pull Requests (Solicitações de Pull): Propor alterações específicas**

- Os Pull Requests permitem propor alterações específicas em um repositório.
- Você cria um Pull Request após fazer alterações em um branch e desejar mesclá-las ao projeto.
- Com um Pull Request, você pode discutir e iterar sobre as mudanças antes de mesclá-las.
- Eles não precisam estar vinculados a um Issue, mas é importante verificar as diretrizes do projeto.

| ![OctaCat](https://github.com/lirazootech/learn-github/blob/13f7473c547782275246e2b00c7f11f785a6285c/Octacat.PNG) |
|:--:|
| Por exemplo, se você corrigiu um bug, faça um Pull Request para que a comunidade revise e aprove a alteração. | 

#### **Em resumo:**

| ![OctaCat](https://github.com/lirazootech/learn-github/blob/13f7473c547782275246e2b00c7f11f785a6285c/Octacat.PNG) |
|:--:|
| Issues são para rastrear informações e discussões, enquanto Pull Requests são para propor e revisar alterações no código. |

### Criando e Gerenciando Wikis

  A Wiki no GitHub é uma seção onde podemos hospedar documentação para o seu repositório. Ela permite que outras pessoas usem e contribuam com o projeto. Podemos usar a Wiki para compartilhar conteúdo detalhado sobre o nosso projeto, como instruções de uso, design ou princípios fundamentais. É uma maneira de fornecer informações mais extensas além do arquivo README.

  Na aba "Wiki" no repositório cliquei em "Create the first page" e editei a página de Wiki usando Markdown. A visibilidade das Wikis segue a configuração de privacidade do repositório.

| ![Wiki](https://github.com/lirazootech/learn-github/blob/c181d275746981b7aab96e49331d9d313127d489/Captura%209.PNG) |
|:--:|
| A priori adicionei uma informação sucinta apenas para demonstração. |

## 🚀 Resultados

  A utilização da interface do GitHub acelera o processo de criação e desenvolvimento, com uma interface amigável possibilita uma organização visual pouco poluída, além de deixar disponível informações importantes do processo de desenvolvimento para um melhor controle de versão.

| [![Microsoft](https://github.com/lirazootech/GitHub4Women-Modulo2/blob/069ae05de973dca5391bc9b6efc8389c71abc934/Microsoft.png)]() |
|:--:|
| [![maismulheres.tech](https://github.com/lirazootech/GitHub4Women-Modulo2/blob/069ae05de973dca5391bc9b6efc8389c71abc934/maismulheres.tech.png)](https://www.maismulheres.tech/) |
| Este curso é oferecido pela Microsoft em parceria com a WoMakersCODE através da plataforma maismulheres.tech com o objetivo de capacitar e inserir mais mulheres na tecnologia. Ao final do curso, após avaliação as participantes concorrem à premiação do voucher para a certificação GitHub Foundations. |

Copyright © 2024. Feito com 🧡 por <a href="https://github.com/lirazootech/" target="_blank">lirazootech</a>.
