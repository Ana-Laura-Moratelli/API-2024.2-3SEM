<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 04</h1>

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
            <td>Como administrador, eu quero salvar um rascunho no cadastro de projetos para que eu possa continuar o preenchimento posteriormente antes de publicar o projeto.</td>
            <td>O administrador deve ter a opção de salvar o formulário de projeto como rascunho. O rascunho deve permitir salvar os dados parcialmente preenchidos e não aparecerá na listagem de projetos ativos.</td>
            <td>Adicionar botão "Salvar como Rascunho" no formulário de cadastro de projetos.</td>
            <td>Implementar endpoint para salvar e atualizar rascunhos de projetos. Garantir que os rascunhos não sejam incluídos na listagem de projetos ativos.</td>
            <td>Adicionar campo de status ao modelo de projetos (“Rascunho” e “Publicado”).</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero salvar um rascunho ao editar um projeto existente para que eu possa revisar as mudanças antes de publicá-las.</td>
            <td>O administrador deve ter a opção de salvar as alterações como rascunho, sem substituir o projeto ativo. As informações do rascunho não devem afetar o projeto publicado até que seja confirmado.</td>
            <td>Adicionar botão "Salvar Rascunho" na página de edição de projetos. Adicionar seção para gerenciar e publicar rascunhos.</td>
            <td>Criar endpoint para salvar rascunhos de edições de projetos. Implementar lógica para distinguir entre rascunhos de edição e projetos publicados.</td>
            <td>Modificar estrutura de dados para suportar versões de rascunho associadas a um projeto existente. Armazenar status de rascunho temporário.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero ver uma lista de todos os rascunhos de projetos, para que eu possa identificar quais projetos estão com dados pendentes ao cadastrar e editar.</td>
            <td>A lista deve exibir todos os rascunhos de projetos, mostrando informações principais, como nome do projeto, data de criação do rascunho e status de conclusão. Os rascunhos não devem aparecer na lista de projetos ativos.</td>
            <td>Criar uma página para listagem de rascunhos de projetos.</td>
            <td>Implementar endpoint para retornar todos os rascunhos de projetos.</td>
            <td>Garantir que os rascunhos sejam armazenados com o campo status “Rascunho”.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero poder editar um rascunho de projeto para atualizar ou concluir as informações antes de publicá-lo.</td>
            <td>O administrador deve poder abrir um rascunho e editar qualquer campo do formulário. Após a edição, o administrador deve ter a opção de salvar as mudanças como rascunho novamente ou publicar o projeto.</td>
            <td>Criar interface para edição de rascunhos, semelhante à interface de criação de projetos. Adicionar opções de "Salvar como Rascunho" e "Publicar" na interface de edição.</td>
            <td>Implementar endpoint para atualização dos dados do rascunho. Configurar lógica para atualizar o status do rascunho caso ele seja publicado.</td>
            <td>Garantir que as atualizações feitas nos rascunhos sejam salvas sem afetar projetos publicados.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero excluir um rascunho de projeto para remover rascunhos desnecessários ou incorretos do sistema.</td>
            <td>O administrador deve ter a opção de excluir um rascunho da lista. Antes de excluir, uma mensagem de confirmação deve ser exibida para evitar exclusões acidentais.</td>
            <td>Adicionar botão de exclusão na interface de listagem e edição de rascunhos. Implementar diálogo de confirmação antes da exclusão.</td>
            <td>Implementar endpoint para exclusão de rascunhos de projetos.</td>
            <td>Configurar lógica de exclusão definitiva para rascunhos.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero receber uma notificação por e-mail no dia que o projeto estiver de expirar para que eu possa tomar ações preventivas.</td>
            <td>Uma notificação por e-mail deve ser enviada no dia da data de expiração de um projeto. O e-mail deve conter informações do projeto, incluindo referência do projeto e descrição.</td>
            <td>Criar notificações visuais que será enviada ao e-mail.</td>
            <td>Implementar rotina de verificação diária para identificar projetos a expirar no dia. Configurar envio de e-mail com informações do projeto.</td>
            <td>Registrar o status de notificação enviada para evitar duplicação de e-mails.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero registrar informações de bolsistas, incluindo dados pessoais, tipo de bolsa, duração e área de atuação, e vinculá-los a um projeto.</td>
            <td>O formulário de registro de bolsistas deve incluir campos para dados pessoais, tipo de bolsa, duração, área de atuação e vínculo ao projeto. O administrador deve poder escolher um projeto ao qual o bolsista será vinculado.</td>
            <td>Criar formulário para entrada de dados dos bolsistas. Adicionar funcionalidade para selecionar o projeto ao qual o bolsista será vinculado.</td>
            <td>Criar endpoint para registro de informações dos bolsistas. Implementar vínculo entre bolsista e projeto.</td>
            <td>Criar tabela para armazenar informações dos bolsistas. Configurar relação entre a tabela de bolsistas e a tabela de projetos.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero ver uma lista de todos os bolsistas registrados, para visualizar rapidamente as informações de cada um.</td>
            <td>A listagem deve exibir os dados principais de cada bolsista, como nome, tipo de bolsa e projeto associado. Deve haver um sistema de filtragem e busca para facilitar a navegação.</td>
            <td>Criar página de listagem de bolsistas com filtros e busca.</td>
            <td>Implementar endpoint para listagem de bolsistas.</td>
            <td>Otimizar consultas para listagem de bolsistas.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero poder editar as informações de um bolsista para manter os dados atualizados.</td>
            <td>O administrador deve poder acessar o perfil do bolsista e modificar os dados existentes.</td>
            <td>Criar interface de edição para o perfil do bolsista.</td>
            <td>Implementar endpoint para atualização dos dados do bolsista.</td>
            <td>Garantir que as atualizações sejam realizadas na tabela de bolsistas sem conflitos.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero poder excluir bolsistas do sistema para remover registros desatualizados ou incorretos.</td>
            <td>O administrador deve ter a opção de excluir um bolsista. Uma mensagem de confirmação deve ser exibida antes da exclusão.</td>
            <td>Adicionar botão de exclusão com confirmação na listagem e perfil do bolsista.</td>
            <td>Implementar endpoint para exclusão de registros de bolsistas.</td>
            <td>Remover o bolsista selecionado do banco de dados.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero ter a opção de gerar um plano de trabalho ao cadastrar um projeto para anexá-lo ao acordo de parceria para pesquisa e desenvolvimento entre a empresa e a fundação.</td>
            <td>O administrador deve ter a opção de gerar um plano de trabalho como parte do cadastro do projeto. O formulário de cadastro deve incluir campos para informações do coordenador do projeto, empresa contratante, descrição do projeto, resultados esperados, fases e entregas, cronograma, equipe executora, plano de aplicação e cronograma financeiro. Após o preenchimento dos campos, o plano de trabalho deve ser gerado em PDF e anexado ao projeto.</td>
            <td>Adicionar campos no formulário de cadastro para coleta das informações necessárias para o plano de trabalho. Incluir uma opção (checkbox ou botão) para indicar se o plano de trabalho deve ser gerado.</td>
            <td>Implementar endpoint para processar os dados do formulário.</td>
            <td>Armazenar as informações do plano de trabalho vinculadas ao projeto cadastrado em PDF.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero que o plano de trabalho preencha automaticamente campos específicos de um modelo Word, para facilitar a criação do documento.</td>
            <td>O documento Word deve ser preenchido automaticamente com os dados do formulário, usando um modelo predefinido. Campos como [CONTRATANTE], [COORDENADOR], e outros dados específicos devem ser substituídos pelos valores informados no cadastro do projeto. O sistema deve gerar um documento final em PDF com todos os campos preenchidos e permitir o download ou armazenamento como anexo ao projeto.</td>
            <td>Adicionar botão para download do documento gerado.</td>
            <td>Implementar lógica para preencher automaticamente os campos no modelo PDF com as informações do contrato. Gerar o documento final em PDF e disponibilizá-lo para download ou anexação ao projeto.</td>
            <td>Armazenar uma referência ao documento PDF gerado.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero que o plano de trabalho gerado seja salvo e acessível no sistema para futuras consultas.</td>
            <td>O plano de trabalho gerado deve ser armazenado e vinculado ao projeto correspondente. O administrador deve poder acessar e baixar o plano de trabalho gerado diretamente a partir da página de detalhes do projeto. O sistema deve manter uma lista de planos de trabalho gerados.</td>
            <td>Criar uma botão para baixar o plano de trabalho.</td>
            <td>Implementar endpoint para download do plano de trabalho associado a cada projeto.</td>
            <td>Adicionar estrutura para vincular o plano de trabalho ao projeto.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero poder criar um contrato com as informações do contratante, pesquisador, prazos e valores, para formalizar o acordo de parceria entre a empresa e a fundação.</td>
            <td>O administrador deve ter um formulário dedicado para entrada das informações necessárias ao contrato, incluindo detalhes do contratante, pesquisador, prazos e valores. Todas as informações obrigatórias devem ser validadas antes de permitir o progresso para a geração do contrato. O administrador deve ser notificado se houver algum campo obrigatório em falta.</td>
            <td>Criar formulário para entrada dos dados do contrato, com campos para informações do contratante, pesquisador, prazos e valores.</td>
            <td>Implementar endpoint para salvar temporariamente os dados do contrato.</td>
            <td>Criar estrutura para armazenar informações preliminares do contrato associadas ao projeto.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero que o contrato preencha automaticamente campos específicos de um modelo Word, para facilitar a criação do documento.</td>
            <td>O documento Word deve ser gerado automaticamente preenchendo campos como [CONTRATANTE], [PESQUISADOR], [PRAZO] e [VALOR] com os dados fornecidos no formulário. O sistema deve gerar um documento final em PDF com todos os campos preenchidos e permitir o download ou armazenamento como anexo ao projeto.</td>
            <td>Adicionar botão para baixar o contrato em PDF após o preenchimento do formulário.</td>
            <td>Implementar lógica para preencher automaticamente os campos no modelo Word com as informações do contrato. Gerar o documento final em PDF e disponibilizá-lo para download ou anexação ao projeto.</td>
            <td>Armazenar uma referência ao documento PDF gerado, permitindo o download posterior.</td>
        </tr>
        <tr>
            <td>Como administrador, eu quero que o contrato gerado seja salvo e acessível no sistema para futuras consultas.</td>
            <td>O contrato gerado deve ser armazenado e vinculado ao projeto correspondente. O administrador deve poder acessar e baixar o contrato gerado diretamente a partir da página de detalhes do projeto. O sistema deve manter uma lista de contratos gerados.</td>
            <td>Criar uma botão para baixar o contrato.</td>
            <td>Implementar endpoint para download do contrato associado a cada projeto.</td>
            <td>Adicionar estrutura para vincular o contrato ao projeto.</td>
        </tr>
    </tbody>
</table>


<h2>Modelo de Dados</h2>
<img src="https://github.com/Sync-FATEC/API-2024.2-3SEM/blob/main/sprints/sprint04/banco-de-dados.jpg">
