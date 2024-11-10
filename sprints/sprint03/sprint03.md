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
        <tr>
            <td>Como administrador, eu quero visualizar um histórico de alterações de cada projeto, para rastrear todas as edições realizadas e garantir a integridade dos dados.</td>
            <td>O administrador deve ter a opção de visualizar os dados que foram alterados, a data da alteração e o conteúdo que foi alterado aparecendo o valor antigo e o novo.</td>
            <td>Adicionar um filtro de data para que o administrador possa selecionar e visualizar as alterações feitas e como o conteúdo estava anteriormente.</td>
            <td>Implementar lógica para armazenar o histórico das aterações dos projetos.</td>
            <td>Criar tabela para armazenar as informações dos projetos alteradas.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero exportar os dados do dashboards dos projetos, para obter uma visão geral e rápida do estado dos projetos.</td>
            <td>O administrador deve ter a opção de exportar os dados exibidos nos dashboards dos projetos em formatos, como PDF e Excel.</td>
            <td>Adicionar botão de exportação nos dashboards com opções para formatos PDF e Excel.</td>
            <td>Implementar a lógica de exportação dos dados do dashboard, gerando arquivos PDF e Excel com as informações apresentadas.</td>
            <td>Configurar a extração e formatação dos dados necessários para exportação, garantindo compatibilidade com os formatos de arquivo PDFe Excel.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero exportar dados de um projeto selecionado, para obter uma visão geral e rápida do estado do projeto.</td>
            <td>O administrador deve ter a opção de exportar os dados exibidos nos detalhes de um projeto específico em PDF.</td>
            <td>Adicionar botão de exportação na página de detalhes do projeto, permitindo a exportação para PDF.</td>
            <td>Implementar a lógica de exportação dos dados específicos de um projeto, gerando arquivo PDF com todas as informações do projeto.</td>
            <td>Configurar a extração e formatação dos dados necessários para exportação, garantindo compatibilidade com o formatos de arquivo PDF.</td>
        </tr>
    </tbody>
</table>

<h2>Modelo de Dados</h2>
<img src="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/sprints/sprint03/banco-de-dados.jpg">
