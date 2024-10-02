<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 02</h1>

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
            <td>Como usuário, eu quero pesquisar projetos por coordenador, para encontrar informações específicas.</td>
            <td>O usuário deve ter a capacidade de buscar projetos filtrando pelo nome do coordenador. O sistema deve fornecer uma interface de busca ou filtros onde o usuário possa selecionar um coordenador específico.</td>
            <td>Implementar filtros para seleção de coordenador.</td>
            <td>Criar endpoint para busca de projetos filtrados por coordenador.</td>
            <td>Otimizar consulta para buscar projetos baseados no coordenador.</td>
        </tr>
        <tr>
            <td>Como usuário, eu quero pesquisar projetos por empresa, para encontrar informações específicas.</td>
            <td>O usuário deve ter a capacidade de buscar projetos filtrando pelo nome da empresa. O sistema deve fornecer uma interface de busca ou filtros onde o usuário possa selecionar uma empresa específica.</td>
            <td>Implementar filtros para seleção de empresa.</td>
            <td>Criar endpoint para busca de projetos filtrados por empresa.</td>
            <td>Otimizar consulta para buscar projetos baseados na empresa.</td>
        </tr>
        <tr>
            <td>Como usuário, eu quero pesquisar projetos por status (em andamento, encerrados e não iniciados), para acompanhar o progresso dos projetos.</td>
            <td>O usuário deve ter a opção de pesquisar projetos com base em seu status (em andamento, encerrados ou não iniciados).</td>
            <td>Adicionar filtros de status (dropdown).</td>
            <td>Implementar endpoint para consulta por status (em andamento, encerrado, não iniciado).</td>
            <td>Otimizar consulta para buscar projetos baseados no status dos projetos.</td>
        </tr>
        <tr>
            <td>Como usuário, eu quero pesquisar projetos por classificação, para acompanhar o progresso dos projetos.</td>
            <td>O usuário deve ser capaz de classificar os projetos de acordo com categorias estabelecidas, como AS, OF, PC, e/ou outros, contrato, convênio, patrocínio, termo de cooperação e termo de outorga.</td>
            <td>Adicionar filtros de classificação dos projetos (AS, OF, PC, contrato, convênio, patrocínio, etc).</td>
            <td>Implementar endpoint para pesquisa de projetos por classificação.</td>
            <td>Otimizar consulta para buscar projetos baseados pela classificação dos projetos.</td>
        </tr>
        <tr>
            <td>Como usuário, eu quero pesquisar projetos por data de início ou término, para encontrar informações específicas.</td>
            <td>O usuário deve ter a opção de buscar projetos por data de início ou término. O sistema deve disponibilizar um calendário ou campo para inserção de datas, permitindo que o usuário defina um intervalo específico para sua pesquisa.</td>
            <td>Criar campo de seleção de intervalo de datas (calendário).</td>
            <td>Desenvolver endpoint que filtre projetos com base na data de início ou término.</td>
            <td>Otimizar consulta para buscar projetos baseados pela data de início ou término dos projetos.</td>
        </tr>
        <tr>
            <td>Como usuário, eu quero utilizar uma barra de pesquisa para buscar conteúdos no site com base em palavras-chave, para encontrar informações de maneira rápida e eficiente.</td>
            <td>O sistema deve permitir que o usuário insira uma palavra-chave na barra de pesquisa e, ao clicar em buscar, o conteúdo relevante seja exibido. O sistema deve retornar todos os resultados que contenham a palavra-chave, seja no título, descrição ou corpo do conteúdo.</td>
            <td>Implementar o campo de input para inserção de palavras-chave e um botão de busca.</td>
            <td>Implementar a lógica de busca que verifica a presença da palavra-chave nos campos de título, descrição ou corpo do conteúdo.</td>
            <td>Desenvolver a consulta que faça a busca por palavra-chave em múltiplos campos (título, descrição e corpo).</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero editar projetos existentes, para manter as informações atualizadas.</td>
            <td>O administrador deve ter acesso a uma funcionalidade de edição para modificar detalhes de projetos já cadastrados.</td>
            <td>Criar interface de edição de projetos com campos para alteração de dados.</td>
            <td>Implementar a lógica para validar e salvar as edições feitas pelo administrador no banco de dados.</td>
            <td>Atualizar os registros existentes no banco de dados com as novas informações do projeto editado.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero excluir projetos obsoletos ou incorretos, para manter os dados atualizados.</td>
            <td>O administrador deve ser capaz de excluir projetos que estejam incorretos ou obsoletos. Antes da exclusão, o sistema deve exibir uma confirmação para evitar remoções acidentais.</td>
            <td>Criar botão de exclusão com modal de confirmação para o administrador confirmar a remoção.</td>
            <td>Implementar a lógica para exclusão de projetos, garantindo a validação da ação através da confirmação do administrador.</td>
            <td>Remover o projeto selecionado do banco de dados.</td>
        </tr>
    </tbody>
</table>

<h2>Modelo de Dados</h2>
<img src="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/documentacao/sprints/sprint02/banco-de-dados.jpg">
