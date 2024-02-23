# Agendamento de Refeições Escolares
Este repositório contém todos os arquivos e documentações relacionados ao projeto "Agendamento de Refeições Escolares". O sistema foi desenvolvido para otimizar e gerenciar o processo de agendamento de refeições em um ambiente escolar. Ele oferece uma interface intuitiva para que alunos, servidores e equipe administrativa possam interagir de maneira eficaz com o sistema.

## HISTÓRIAS DE USUÁRIO

* [HU01] Como usuário do sistema, eu quero logar na minha conta usando meu login e senha para que eu possa realizar as tarefas que são de minha responsabilidade.

* [HU02] Como secretaria, eu quero cadastrar, atualizar e excluir informações dos usuários para organizar o processo de agendamentos de refeição.

* [HU03] Como secretaria, eu quero fazer a liberação do aluno/servidor, quando houver bloqueio parcial do usuário, devido a repetição tripla de não presença após agendamento, para que o aluno siga usando o sistema de agendamentos.

* [HU04] Como aluno/servidor, eu quero visualizar o cardápio para que eu possa decidir se eu irei realizar o agendamento ou não.

* [HU05] Como aluno/servidor, eu quero visualizar com destaque as mudanças no cardápio para que eu possa decidir se irei manter meu agendamento ou cancela-lo.

* [HU06] Como aluno/servidor, eu quero agendar minhas refeições, para poder jantar.

* [HU07] Como aluno/servidor, eu quero ser notificado quando não houver refeições no dia para eu não ir ao refeitório em vão.

* [HU08] Como aluno/servidor, eu quero que o programa tenha a possibilidade de desmarcar o agendamento para eu não ser punido por faltar.

* [HU09] Como administração da escola, eu quero ter controle de quantos alunos em média vão ao refeitório para que eu consiga visualizar os dias de maior demanda.

* [HU10] Como administração da escola, eu quero ter acesso a um relatório que cruze os dados de agendamento e refeições para eu assegurar que o agendamento está funcionando de maneira satisfatória.

* [HU11] Como administração da escola, eu quero poder modificar o cardápio quando necessário para quando os auxiliares de cozinha não conseguirem fazer a alteração, eu possa fazê-la.

* [HU12] Como equipe da cozinha, eu quero atualizar o cardápio caso não haja refeição no dia para que os usuários não terem a possibilidade de realizar agendamentos no dia.

* [HU13] Como equipe da cozinha, eu quero analisar a quantidade de pessoas que agendaram refeições no dia, para eu preparar somente a quantidade necessária de alimentos.

* [HU14] Como equipe da cozinha, eu quero modificar informações do cardápio, quando necessário, para que o sistema seja atualizado e assegurar a adesão.

* [HU15] Como porteiro(a), eu quero validar os QR Codes gerados após agendamento para eu poder confirmar ou não o agendamento do usuário.

* [HU16] Como porteiro(a), eu quero ter acesso ao numero de agendamentos feitos no dia para averiguar se há uma quantidade satisfatória de alimentos para uma possivel refeição sem agendamento.

* [HU17] Como porteiro(a), desejo acessar a lista de usuários agendados para eu poder confirmar a identidade daqueles na fila que não apresentarem comprovação de agendamento, verificando assim seus nomes.

## REQUISITOS NÃO-FUNCIONAIS
* [RNF01] Sistema poderá emitir um registro dos excessos/faltas de comida.

* [RNF02] O sistema deve ser restrito somente aos professores e servidores da escola.

* [RNF03] O sistema deverá atender a demanda de 350 a 400 usuários.

* [RNF04] O sistema deve implementar um mecanismo de backup automático para garantir a integridade e a recuperação de dados.

* [RNF05] O sistema deverá ser confiável, impedindo o vazamento de informações dos usuários.

* [RNF06] O sistema deve ser intuitivo e fácil de usar, pois será utilizado por diversos tipos de pessoas.

* [RNF07] O sistema poderá receber atualizações, se caso necessário.

* [RNF08] Para alterar a foto do sistema, o usuário precisará encaminhar-se à secretaria da escola. 

* [RNF09] O sistema deverá ter uma interface intuitiva e fácil de usar.

* [RNF10] O sistema deverá ser eficiente, garantindo respostas ágeis.

* [RNF11] O sistema deverá garantir alta disponibilidade e baixa taxa de erros.

* [RNF12] O sistema deverá ter uma integração eficaz com a base de dados já existente da escola para a automação eficiente do cadastro de usuários do sistema de agendamento.

* [RNF13] O sistema deverá ser compatível com diferentes sistemas operacionais, para assim permitir o acesso de diferentes dispositivos (computadores, tablets, smartphones).

* [RNF14] O sistema deverá ter a capacidade de gerar relatórios detalhados das listas de agendamento para a cozinha e gestão.

* [RNF15] O sistema deverá notificar caso não há refeições no dia.


## Regras de negócios
* [RN01] A distribuição das refeições será condicionada à validação do QRCode pelo sistema.

* [RN02] Caso o usuáriode agendamento não comparecido, será permitido um máximo de 3 faltas.

* [RN03] Se o aluno exceder o limite de 3 faltas, o agendamento ficará parcialmente bloqueado.

* [RN04] Os usuários têm a opção de cancelar seus pedidos, sendo necessário notificar a cozinha em caso de cancelamento.

* [RN05] As notificações sobre a falta de refeição devem ser enviadas para os usuários, através de uma notificação do sistema de agendamentos.

* [RN06] O cardápio, e suas possiveis alterações, precisa ser visível para todos os usuários.

* [RN07] O agendamento para o jantar do dia só é possível até às 19:30; após esse horário, somente será permitido agendar para o dia seguinte.

* [RN08] A cozinha receberá uma lista dos agendamentos diários, para o preparo das refeições.

* [RN09] O acesso ao serviço requer a apresentação e verificação do QRCode.

* [RN10] Para a validaçõa do cadastro, o sistema integrará-se aos dados existentes na secretaria.

* [RN11] Caso o usuário não tenha feito o agendamento, a cozinha deve levar em conta a disponibilidade de refeições,se o saldo for positivo, a cozinha pode optar por servir o usuário.

* [RN12] No banco de dados do sistema de agendamento devem estar informações do usuário, incluindo nome, CPF, status (aluno ou servidor), e opcionalmente uma foto, para fins de identificação e segurança.

* [RN13] O aluno poderá desmarcar seu agendamento, apenas antes das 19:30.
