<h2 id='topo'><img src="documentacao/media/banner_apresentacao.png"></h2>

<div align="center">
<a href="#objetivo"> 🎯 Objetivo </a> |
<a href="#proposta"> 📧 Proposta de Solução </a> |
<a href="#requisitos"> 📚 Requisitos do Parceiro </a> |
<a href="#product-backlog"> 📖 Product Backlog </a> |
<a href="#dor"> DoR </a> |
<a href="#dod"> DoD </a> |
<a href="#mvp"> 📎 MVP </a> |
<a href="#sprints"> 📌 Sprints </a> |
<a href="#tecnologias"> 💻 Tecnologias </a> |
<a href="#manual-usuario"> 📃 Manual do Usuário </a> |
<a href="#padroes-de-commit"> 📨 Padrões de Commit </a> |
<a href="#membros"> 👥 Membros </a> 
</div>

<br>

<h2 id='objetivo'> 🎯 Objetivo </h2>
Este projeto tem como objetivo desenvolver um portal de transparência para a Fundação de Apoio à Pesquisa de Pós-Graduandos (FAPG). Nossa meta é entregar uma plataforma robusta e eficiente, com funcionalidades que permitam a inserção de projetos, a realização de buscas avançadas por meio de filtros e a geração de estatísticas apresentadas em gráficos interativos, promovendo um acesso transparente e facilitado às informações públicas.

<br>

<h2 id='proposta'> 📧 Proposta de Solução </h2>
Nossa proposta é desenvolver um sistema moderno e eficiente, utilizando novas tecnologias, permitindo a adição e o gerenciamento ágil de projetos.

Arquitetura de Microserviços: Garantiremos flexibilidade e escalabilidade com uma estrutura modular, facilitando a manutenção e a expansão futura do sistema.

Gestão Eficiente de Projetos: Usuários poderão adicionar, monitorar e gerenciar projetos de forma simples, com uma interface que permite a visualização detalhada dos projetos.

Painel Intuitivo: Desenvolveremos um painel de controle simples e intuitivo, com gráficos interativos que facilitam a compreensão rápida e clara das informações.

<br>

<h2 id='requisitos'> 📚 Requisitos do Parceiro </h2>

| Número | Requisito do Parceiro |
| ------ | --------------------- |
| 1 | Ferramenta de importação de dados da aplicação legada no novo banco de dados projetado |
| 2 | Interface para cadastro de novos projetos |
| 3 | Interface de pesquisa de projetos |
| 4 | Interface de cadastro de usuários |
| 5 | Relatórios/dashboards de projetos desenvolvidos, com diferentes tipos de filtros |

<br>

<h2 id='product-backlog'> 📖 Product Backlog </h2>

<table>
    <thead>
        <tr align="center">
            <th>Rank</th>
            <th>Prioridade</th>
            <th>User Story</th>
            <th>Estimativa</th>
            <th>Sprint</th>
            <th>Req. Parceiro</th>
        </tr>
    </thead>
    <tbody>
        <tr align="center">
            <td>1</td>
            <td>ALTA</td>
            <td>Como administrador, eu quero acessar um portal exclusivo da área do administrador, para gerenciar projetos e visualizar relatórios detalhados, garantindo a manutenção e a segurança dos dados do sistema.</td>
            <td>8</td>
            <td>1</td>
            <td>4</td>
        </tr>
        <tr align="center">
            <td>2</td>
            <td>ALTA</td>
            <td>Como administrador, eu quero cadastrar projetos, para que eles estejam disponíveis no Portal de Transparência.</td>
            <td>8</td>
            <td>1</td>
            <td>2</td>
        </tr>
        <tr align="center">
            <td>3</td>
            <td>ALTA</td>
            <td>Como administrador, eu quero importar dados da aplicação legada, para garantir que os projetos antigos estejam acessíveis no novo portal.</td>
            <td>13</td>
            <td>1</td>
            <td>4</td>
        </tr>
        <tr align="center">
            <td>4</td>
            <td>ALTA</td>
            <td>Como usuário, eu quero visualizar os projetos no Portal de Transparência.</td>
            <td>5</td>
            <td>1</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>5</td>
            <td>ALTA</td>
            <td>Como usuário, eu quero visualizar os detalhes completos de um projeto ao selecioná-lo na pesquisa, para entender todos os aspectos do projeto.</td>
            <td>5</td>
            <td>1</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>6</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero pesquisar projetos por coordenador, para encontrar informações específicas.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>7</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero pesquisar projetos por empresa, para encontrar informações específicas.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>8</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero pesquisar projetos por status (em andamento, encerrados e não iniciados), para acompanhar o progresso dos projetos.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>9</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero pesquisar projetos por classificação, para acompanhar o progresso dos projetos.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>10</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero pesquisar projetos por data de início ou término, para encontrar informações específicas.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>11</td>
            <td>MÉDIA</td>
            <td>Como usuário, eu quero utilizar uma barra de pesquisa para buscar conteúdos no site com base em palavras-chave, para encontrar informações de maneira rápida e eficiente.</td>
            <td>5</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr align="center">
            <td>12</td>
            <td>MÉDIA</td>
            <td>Como administrador, eu quero editar projetos existentes, para manter as informações atualizadas.</td>
            <td>3</td>
            <td>2</td>
            <td>2</td>
        </tr>
        <tr align="center">
            <td>13</td>
            <td>MÉDIA</td>
            <td>Como administrador, eu quero excluir projetos obsoletos ou incorretos, para manter os dados atualizados.</td>
            <td>3</td>
            <td>2</td>
            <td>2</td>
        </tr>
        <tr align="center">
            <td>14</td>
            <td>MÉDIA</td>
            <td>Como administrador, eu quero garantir que conteúdo sensível de projetos não seja exibido para usuários comuns, para proteger informações confidenciais e garantir que apenas usuários autorizados tenham acesso.</td>
            <td>5</td>
            <td>3</td>
            <td>2</td>
        </tr>
        <tr align="center">
            <td>15</td>
            <td>MÉDIA</td>
            <td>Como administrador, eu quero visualizar dashboards dos projetos, para obter uma visão geral e rápida do estado dos projetos.</td>
            <td>8</td>
            <td>3</td>
            <td>5</td>
        </tr>
        <tr align="center">
            <td>16</td>
            <td>BAIXA</td>
            <td>Como administrador, eu quero visualizar um histórico de alterações de cada projeto, para rastrear todas as edições realizadas e garantir a integridade dos dados.</td>
            <td>8</td>
            <td>4</td>
            <td>2</td>
        </tr>
        <tr align="center">
            <td>17</td>
            <td>BAIXA</td>
            <td>Como administrador, eu quero exportar os dados dos dashboards dos projetos, para obter uma visão geral e rápida do estado dos projetos.</td>
            <td>8</td>
            <td>4</td>
            <td>5</td>
        </tr>
        <tr align="center">
            <td>18</td>
            <td>BAIXA</td>
            <td>Como administrador, eu quero exportar dados de um projeto selecionado, para obter uma visão geral e rápida do estado do projeto.</td>
            <td>8</td>
            <td>4</td>
            <td>5</td>
        </tr>
    </tbody>
</table>

<br>

<h2 id='dor'> DoR (Definitions of Ready) </h2>

### User Stories
- Definidas e compreendidas por todos.
- Pequenas o suficiente para serem feitas em um sprint.

### Critério de Aceitação
- Mensurável e testável.
- Descreve claramente quando a funcionalidade está completa.

### Tarefas
- Tarefas identificadas e documentadas para cada história.
- Cada tarefa tem um responsável definido.

### Modelo de Dados
- Modelo de dados definido e documentado.
- Campos, tipos de dados e relações claramente especificados.

<br>

<h2 id='dod'> DoD (Definition of Done) </h2>

### Código
- Completo e implementa todos os critérios de aceitação.
- Todos os testes escritos e passando com sucesso.

### Commit
- Todos os commits estão devidamente documentados com mensagens claras e descritivas.
- Os commits seguem o padrão de nomenclatura acordado pela equipe (ex: "feat:", "fix:").

### Mockups
- Mockups na interface funcionam conforme esperado.
- Experiência do usuário corresponde aos critérios definidos.

### Manual do Usuário
- O manual do usuário está completo e disponível online.
- Inclui instruções passo a passo sobre como usar todas as funcionalidades do produto.

### Guia de Instalação
- O guia de instalação detalha todos os passos necessários para configurar e instalar o software em diferentes plataformas ou ambientes.
- Inclui requisitos de sistema, dependências e configurações de software/hardware.

<br>

<h2 id='mvp'>📎 MVP</h2>
<video src="https://github.com/user-attachments/assets/c7db084c-06f8-4b49-ba67-1303ac2c0e5e"></video>

<h2 id='sprints'> 📌 Sprints </h2>

<table>
  <thead>
    <tr align="center">
      <th>Sprints</th>
      <th>Data de Início</th>
      <th>Data de Término</th>
      <th>Documentos</th>
      <th>Status</th>
    </tr>
  </thead>
 <tbody>
  <tr align="center">
    <td>01</td>
    <td>09/09/2024</td>
    <td>29/09/2024</td>
    <td><a href="https://github.com/Sync-FATEC/API-2024.2-3SEM/tree/main/documentacao/sprints/sprint01/sprint01.md">Relatório</a></td> 
    <td>✅</td>
  </tr>
  <tr align="center">
    <td>02</td>
    <td>30/09/2024</td>
    <td>20/10/2024</td>
    <td><a href="https://github.com/Sync-FATEC/API-2024.2-3SEM/tree/main/documentacao/sprints/sprint02/sprint02.md">Relatório</a></td> 
    <td>🔁</td>
  </tr>
  <tr align="center">
    <td>03</td>
    <td>21/10/2024</td>
    <td>10/11/2024</td>
    <td>Em desenvolvimento!</td> 
    <td>❌</td>
  </tr>
  <tr align="center">
    <td>04</td>
    <td>11/11/2024</td>
    <td>01/12/2024</td>
    <td>Em desenvolvimento!</td> 
    <td>❌</td>
  </tr>
</tbody>
</table>


<br>

<h2 id='manual-usuario'> 📃 Manual do Usuário </h2>
<a href="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/documentacao/ManualdoUsuario.pdf">Clique Aqui</a>

<br>

<h2 id='tecnologias'> 💻 Tecnologias </h2>
<img src="documentacao/media/tecnologias.png">

<br>

<h2 id='padroes-de-commit'> 📨 Padrões de Commit </h2>
<img src="documentacao/media/padroes.png">

<br>

<h2 id='membros'> 👥 Membros </h2>

| Foto | Nome | Função | Github | Linkedin |
| :---------: | :---------: | :---------------------: | :-----------------: | :-------: |
| <img src="https://github.com/Kaue-Francisco.png?size=50" width=50px> | Kauê Francisco | Scrum Master | <a href="https://github.com/Kaue-Francisco"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/kau%C3%AA-francisco-3b13aa255/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/Ana-Laura-Moratelli.png?size=50" width=50px> | Ana Laura Moratelli | Product Owner | <a href="https://github.com/Ana-Laura-Moratelli"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/anamoratelli/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/yokotaerik.png?size=50" width=50px> | Erik Yokota | Desenvolvedor | <a href="https://github.com/yokotaerik"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/erik-camara-yokota-685439233/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/joaogabgr.png?size=50" width=50px> | João Gabriel Solis | Desenvolvedor | <a href="https://github.com/joaogabgr"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/joaoggbs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/joycesilvaaa.png?size=50" width=50px> | Joyce Silva | Desenvolvedora | <a href="https://github.com/joycesilvaaa"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/joyce-silva-79a4b9287/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| <img src="https://github.com/yuribragga.png?size=50" width=50px> | Yuri Braga | Desenvolvedor | <a href="https://github.com/yuribragga"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/yuri-braga/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |

<a href='#topo'> Voltar ao topo </a>
