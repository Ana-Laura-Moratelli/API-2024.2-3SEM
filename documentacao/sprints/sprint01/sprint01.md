<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 01</h1>

<table>
        <thead>
            <tr>
                <th>User Story</th>
                <th>Critério de Aceitação</th>
                <th>Tarefa Front</th>
                <th>Tarefa Back</th>
                <th>Tarefa BD</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Como administrador, eu quero acessar um portal exclusivo da área do administrador, para gerenciar projetos e visualizar relatórios detalhados.</td>
                <td>Para acessar o portal da área do administrador, o administrador deve ser autenticado com sucesso e, após o login, visualizará uma interface de gerenciamento de usuários, projetos e relatórios.</td>
                <td>Desenvolver interface de login para administradores com validação de credenciais.</td>
                <td>Implementar a lógica de autenticação e autorização de administrador, garantindo o acesso adequado às funcionalidades de gerenciamento.</td>
                <td>Criar tabelas para armazenar as informações dos usuários</td>
            </tr>
            <tr>
                <td>Como administrador, eu quero cadastrar projetos, para que eles estejam disponíveis no Portal de Transparência.</td>
                <td>O administrador deve ter acesso a um formulário de cadastro de projetos, no qual será necessário inserir informações como referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, classificação, status do projeto, data de início e término, e anexar arquivos como propostas e relatórios técnicos.</td>
                <td>Desenvolver interface de cadastro de projetos contendo os campos: referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, etc.</td>
                <td>Desenvolver a lógica de validação e processamento do formulário de projetos, incluindo o gerenciamento de uploads de arquivos.</td>
                <td>Criar tabelas para armazenar as informações dos projetos e anexos associados, com relação entre tabelas de projetos e arquivos.</td>
            </tr>
            <tr>
                <td>Como administrador, eu quero importar dados da aplicação legada, para garantir que os projetos antigos estejam acessíveis no novo portal.</td>
                <td>Para importar dados da aplicação legada, o administrador deve selecionar um arquivo de dados em formato .json. O sistema deve validar tanto o formato quanto a consistência dos dados antes de iniciar o processo de importação.</td>
                <td>Desenvolver botão para o administrador selecionar e carregar arquivos .json para importação de dados.</td>
                <td>Implementar a funcionalidade de validação do formato e consistência dos dados, além de processar a importação para o sistema.</td>
                <td>Atualizar as tabelas com os dados importados da aplicação legada, garantindo a consistência dos registros.</td>
            </tr>
            <tr>
                <td>Como usuário, eu quero visualizar os projetos no Portal de Transparência.</td>
                <td>O usuário deve ter acesso a uma lista de projetos no Portal de Transparência, onde cada projeto deve exibir informações básicas como referência do projeto, empresa, objeto, descrição, coordenador, valor do projeto, data de início e término. Ao clicar em um projeto, o sistema deve redirecionar o usuário para a página de detalhes do projeto.</td>
                <td>Desenvolver a página de listagem de projetos com exibição das informações básicas (referência, empresa, objeto, descrição, etc.).</td>
                <td>Implementar a API para buscar os projetos e retornar as informações essenciais para a interface.</td>
                <td>Realizar consultas eficientes para recuperar os dados dos projetos e apresentar na lista de forma otimizada.</td>
            </tr>
            <tr>
                <td>Como usuário, eu quero visualizar os detalhes completos de um projeto ao selecioná-lo na pesquisa, para entender todos os aspectos do projeto.</td>
                <td>O usuário deve poder selecionar um projeto da lista para visualizar seus detalhes completos com os dados e anexos relacionados àquele projeto.</td>
                <td>Criar a interface da página de detalhes do projeto com exibição dos dados completos e anexos.</td>
                <td>Implementar a lógica para carregar os detalhes do projeto selecionado, incluindo os anexos relacionados.</td>
                <td>Configurar as consultas para recuperar os detalhes completos do projeto e os arquivos anexados para exibição.</td>
            </tr>
        </tbody>
    </table>

<h2>Modelo de Dados</h2>
<img src="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/documentacao/sprints/sprint01/banco-de-dados.jpg">
