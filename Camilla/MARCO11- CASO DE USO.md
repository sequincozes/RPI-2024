Caso de Uso: Manter informações dos usuários (Alterar, Incluir e Excluir)
Ator Principal: Secretaria.
Ator Secundário: Aluno/Servidor (usuário do sistema)
Pré-condições:
A Secretaria deve estar autenticada no sistema.
O sistema deve ter um registro existente de usuários ou a capacidade de criar novos registros.
Pós-condições:
As informações dos usuários são atualizadas, adicionadas ou excluídas conforme solicitado pela Secretaria.
O sistema reflete as alterações feitas, mantendo a integridade dos dados.
Fluxo Principal:
A Secretaria acessa a seção de gerenciamento de usuários no sistema.
A Secretaria seleciona um usuário para alterar, incluir um novo usuário, ou excluir um usuário existente.
Para Alteração:
A Secretaria modifica as informações necessárias do usuário selecionado (como nome, CPF, foto, etc.).
A Secretaria revisa as alterações para precisão.
A Secretaria confirma a atualização das informações do usuário.
O sistema valida as informações inseridas e atualiza o banco de dados.
O sistema exibe uma confirmação de que as informações do usuário foram atualizadas com sucesso.
Para Inclusão:
A Secretaria insere as informações necessárias para criar um novo perfil de usuário.
A Secretaria revisa as informações inseridas para precisão.
A Secretaria confirma a adição das informações do usuário.
O sistema valida as informações inseridas e adiciona o novo usuário ao banco de dados.
O sistema exibe uma confirmação de que o novo usuário foi adicionado com sucesso.
Para Exclusão:
A Secretaria seleciona a opção de excluir o usuário.
O sistema pede uma confirmação para a exclusão.
A Secretaria confirma a exclusão.
O sistema exclui o usuário do banco de dados.
O sistema exibe uma mensagem confirmando a exclusão bem-sucedida do usuário.
Fluxos Alternativos:
Erro na Atualização/Inserção de Dados:
Se as informações inseridas pela Secretaria são inválidas ou incompletas, o sistema exibe uma mensagem de erro.
A Secretaria corrige os erros nas informações e tenta novamente.
Cancelamento pelo Usuário:
A qualquer momento, a Secretaria pode optar por cancelar a operação.
Se o cancelamento ocorrer, nenhuma alteração é feita no perfil do usuário e o sistema retorna à tela anterior.


Caso de uso: Visualizar com destaque as alterações no cardápio
Ator Principal: Aluno/Servidor.
Ator Secundário:Cozinha e Administração.
Pré-condições:
O ator principal deve ter acesso ao sistema de agendamento de refeições.
Pós-condições:
O aluno/servidor está informado sobre as alterações no cardápio.
O aluno/servidor toma uma decisão sobre fazer, manter ou cancelar o agendamento da refeição com base nas alterações.
Fluxo Principal:
O Aluno/Servidor acessa o sistema de agendamento de refeições.
O sistema exibe o cardápio atual, incluindo as refeições agendadas pelo usuário.
Se houver alterações no cardápio desde o último acesso, estas alterações são destacadas visualmente (por exemplo, através de um ícone de "novo" ou texto em negrito).
O Aluno/Servidor revisa as alterações no cardápio.
Com base nas alterações, o Aluno/Servidor decide fazer, manter ou cancelar seu agendamento de refeição.
Se o Aluno/Servidor decidir cancelar, ele seleciona a opção de cancelamento e o sistema processa o pedido.
O sistema confirma a ação tomada pelo usuário (fazer, manter ou cancelar a refeição).
Fluxos Alternativos:
Nenhuma Alteração no Cardápio:
Se não houver alterações no cardápio desde o último acesso do usuário, o sistema mostra o cardápio como está.
O Aluno/Servidor revisa o cardápio e continua com seu agendamento atual.
Falha na Visualização das Alterações:
Se o sistema falhar ao destacar as alterações no cardápio, o Aluno/Servidor pode não perceber as mudanças.
O Aluno/Servidor pode entrar em contato com a administração da escola para esclarecimentos ou aguardar a atualização do sistema.
Caso de Uso: Controlar e Analisar a Frequência de Alunos no Refeitório
Ator Principal: Administração da Escola.
Ator Secundário: -
Pré-condições:
A administração deve ter acesso ao sistema de gerenciamento do refeitório.
O sistema deve ser capaz de rastrear e registrar a frequência dos alunos no refeitório.
Pós-condições:
A administração obtém informações sobre a média de frequência de alunos no refeitório.
A administração consegue identificar os dias de maior demanda no refeitório.
Fluxo Principal:
A Administração da Escola acessa o sistema de gerenciamento do refeitório.
A Administração seleciona a opção para visualizar relatórios de frequência dos alunos.
O sistema apresenta opções para especificar o período de tempo para o relatório (por exemplo, semanal, mensal).
A Administração seleciona o período desejado e solicita o relatório.
O sistema processa os dados de frequência dos alunos no período especificado.
O sistema gera e exibe um relatório mostrando a média diária de alunos no refeitório e identifica os dias de maior demanda.
A Administração analisa os dados do relatório para planejar recursos e estratégias para os dias de maior demanda.
Fluxos Alternativos:
Dados Insuficientes:
Se o sistema não tem dados suficientes para o período selecionado, ele notifica a Administração sobre a falta de dados.
A Administração pode escolher um período diferente ou tomar medidas para melhorar a coleta de dados.
Falha na Geração do Relatório:
Se o sistema não conseguir gerar o relatório, ele exibe uma mensagem de erro.
A Administração pode tentar novamente ou contatar o suporte técnico.
Caso de Uso: Imprimir Relatório de Agendamento versus Refeição
Ator Principal: Administração da Escola.
Ator Secundário: Não aplicável.
Pré-condições:
A administração deve estar autenticada no sistema de gerenciamento do refeitório.
O sistema deve ter dados de agendamento de refeições disponíveis para relatório.
Pós-condições:
Um relatório de agendamento/refeição é impresso para uso da administração.
A administração tem dados concretos sobre o agendamento de refeições para análise e planejamento.
Fluxo Principal:
A Administração da Escola acessa o sistema de gerenciamento do refeitório.
A Administração navega até a seção de relatórios do sistema.
A Administração seleciona a opção para gerar um relatório de agendamento/refeição.
O sistema apresenta opções para especificar o período de tempo e outras configurações para o relatório.
A Administração define os critérios desejados e solicita a geração do relatório.
O sistema processa a solicitação e gera um relatório baseado nos critérios fornecidos.
A Administração visualiza uma prévia do relatório na tela.
A Administração seleciona a opção para imprimir o relatório.
O sistema envia o relatório para a impressora configurada.
A Administração coleta o relatório impresso para análise e uso subsequente.
Fluxos Alternativos:
Falha na Impressão do Relatório:
Se ocorrer um erro na impressão (por exemplo, impressora offline ou sem papel), o sistema notifica a Administração sobre o problema.
A Administração soluciona o problema com a impressora e tenta imprimir novamente.
Alteração dos Critérios do Relatório:
Antes de imprimir, a Administração pode optar por alterar os critérios do relatório.
O sistema permite a modificação dos critérios e a geração de um novo relatório para visualização e impressão.
Caso de Uso: Acesso à Lista de Usuários Agendados
Ator Principal: Porteiro(a).
Ator Secundário: Não aplicável.
Pré-condições:
O porteiro(a) deve estar autenticado no sistema de controle de acesso.
O sistema deve ter dados de agendamento de refeições disponíveis.
Pós-condições:
O porteiro(a) obtém acesso à lista de usuários agendados para refeições.
O porteiro(a) pode verificar o nome dos usuários agendados conforme necessário.
Fluxo Principal:
O Porteiro(a) acessa o sistema de controle de acesso.
O Porteiro(a) navega até a seção de "Lista de Usuários Agendados" ou uma funcionalidade semelhante.
O sistema exibe a lista de usuários agendados para refeições, incluindo seus nomes e informações.
O Porteiro(a) verifica a lista para identificar os nomes dos usuários agendados que estejam na fila ou necessitem de verificação.
O Porteiro(a) toma as medidas apropriadas com base nas verificações realizadas, como permitir ou negar o acesso dos usuários à refeição agendada.
Fluxos Alternativos:
Usuário Não Encontrado na Lista:
Se um usuário na fila não estiver na lista de usuários agendados, o Porteiro(a) pode tomar medidas apropriadas, como pedir que o usuário saia da fila ou aguarde a verificação da disponibilidade da cozinha.
Falha no Acesso ao Sistema:
Se houver uma falha no acesso ao sistema, o Porteiro(a) pode contatar o suporte técnico ou tentar novamente após resolver o problema.