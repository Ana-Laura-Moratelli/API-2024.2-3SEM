<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 03</h1>

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
            <td>Como administrador, eu quero garantir que conteúdo sensível de projetos não seja exibido para usuários comuns,
para proteger informações confidenciais e garantir que apenas usuários autorizados tenham acesso.</td>
            <td>Se o projeto contiver dados classificados como sensíveis, eles devem ser ocultados automaticamente dos usuários comuns. O administrador deve ter a capacidade de marcar ou desmarcar o conteúdo como sensível durante o cadastro ou edição do projeto.</td>
            <td>Criar botão para o administrador marcar ou desmarcar dados sensíveis no cadastro ou edição de projetos.</td>
            <td>Criar campo de classificação de sensibilidade nas tabelas dos projetos.</td>
            <td>Otimizar consulta para buscar projetos baseados no coordenador.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero visualizar dashboards dos projetos, para obter uma visão geral e rápida do estado dos projetos.</td>
            <td>O administrador deve ter acesso a dashboards que exibam uma visão geral do estado de todos os projetos. Esses dashboards devem incluir informações visuais, como progresso, status atual (em andamento, concluído, não iniciado), prazos e coordenadores e empresas associados.</td>
            <td>Desenvolver uma interface de dashboard com gráficos e indicadores de status dos projetos (progresso, prazo, coordenadores).</td>
            <td>Implementar endpoints para fornecer os dados necessários para o dashboard, incluindo agregações e filtros por status, coordenadores e empresas.</td>
            <td>Criar consultas que consolidem os dados dos projetos e retornem os resultados em formato otimizado para visualização no dashboard.</td>
        </tr>
    </tbody>
</table>

<h2>Modelo de Dados</h2>
<img src="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/sprints/sprint03/banco-de-dados.jpg">
