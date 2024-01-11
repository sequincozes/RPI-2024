# Agendamento de Refeições Escolares
Este repositório contém todos os arquivos e documentações relacionados ao projeto "Agendamento de Refeições Escolares". O sistema foi desenvolvido para otimizar e gerenciar o processo de agendamento de refeições em um ambiente escolar. Ele oferece uma interface intuitiva para que alunos, servidores e equipe administrativa possam interagir de maneira eficaz com o sistema.

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
