#Caso de Uso:  Verificar número de agendamentos
Descrição:  Esta é uma das principais funções do sistema. A cozinha receberá do sistema, diariamente, às 19:30h o número total de agendamentos, sempre que houver janta.
 
Ator Principal: Cozinha
Ator Secundário: Aluno/Servidor
 
Pré-condições: 
1)  O sistema deve contabilizar o número de agendamentos do dia.
 
Pós-condições: 
1)  No próximo dia de refeição o sistema faz o mesmo procedimento.
 
Fluxo Principal: 
1.  Alunos/servidores realizam o agendamento no sistema;
2. O sistema processa e contabiliza o total de agendamentos;
3. O sistema entrega para a cozinha o número total de agendamentos;
 
Fluxos Alternativos: 
 
1. Caso se não houver janta: 
	O sistema enviará uma notificação com antecedência a todos os usuários.




#Caso de Uso:  Receber notificações
Descrição: Este caso de uso tem como objetivo notificar os Alunos/Servidores que usam o refeitório se caso no dia em questão não houver janta. 
 
Ator Principal:  Aluno/Servidor
Ator Secundário: Cozinha
 
Pré-condições: 
1)  A cozinha deve ter identificado com antecedência que será um dia atípico (feriado ou eventos especiais) e ter decidido que não deverá ter janta
 
Pós-condições: 
1)  Alunos/Servidores não farão o agendamento.
 
Fluxo Principal: 
1.  A cozinha deverá, com antecedência, notificar os Alunos/Servidores que não haverá janta
 
 


#Caso de Uso:  Modificar cardápio
 
Descrição: Este caso de uso será chamado pela cozinha sempre que houver alguma alteração no cardápio.
 
Ator Principal:  Administração
Ator Secundário: Aluno/Servidor
 
Pré-condições: 
1)  A administração deve ir ao sistema e modificar o que for necessário.
 
Pós-condições: 
1)  Os Alunos/Servidores serão notificados.
 
Fluxo Principal: 
1.  A Administração atualiza o cardápio no sistema.
2.  O sistema notifica os Alunos/Servidores sobre as mudanças do cardápio.
 
Fluxos Alternativos: 
1. Caso haja um evento especial na escola:
	Poderá ser criado um calendário específico para a ocasião(ex: semana farroupilha).


#Caso de Uso:  Gerenciar bloqueio de usuário
Descrição:  Este caso de uso será chamado pela secretaria sempre que for necessário desbloquear um usuário do refeitório.
 
Ator Principal:  Secretaria
Ator Secundário: Aluno/Servidor 
 
Pré-condições: 
1)  Aluno/Servidor recebe o bloqueio parcial do refeitório.
 
Pós-condições: 
1)  Aluno/Servidor é liberado e volta a usar o refeitório normalmente.
 
Fluxo Principal: 
1.  A secretaria verifica a lista de Alunos/Servidores com bloqueios parciais.
2.  A secretaria remove o bloqueio do Aluno/Servidor.
3. O Aluno/Servidor volta a ter acesso normal ao refeitório.
 
Fluxos Alternativos: 
 
1. Se um Aluno/Servidor contestar uma punição, a secretaria pode revisar o caso e ajustar o status de bloqueio conforme necessário.


#Caso de Uso:  Validar QR codes
Descrição: Este caso de uso é chamado pelo porteiro para validar os Alunos/Servidores quando estiverem na fila do refeitório para que eles possam confirmar que fizeram o agendamento.
 
Ator Principal: Porteiro
Ator Secundário: Alunos/Servidores
 
Pré-condições: 
1)  Aluno/Servidor deve ter o seu QR code de validação em mãos.
 
Pós-condições: 
1)  O sistema faz a verificação e o porteiro libera o  Aluno/Servidor.
 
Fluxo Principal: 
1. O Aluno/Servidor, através do sistema deve ter feito o agendamento até o horário previsto e recebe o QR code.
2. O Aluno/Servidor deverá apresentar o QR code ao porteiro do refeitório.
3. O porteiro faz a leitura do QR code e libera o Aluno/Servidor.
 
Fluxos Alternativos: 
1.  Se um Aluno/Servidor não puder exibir o QR code, o porteiro pode usar uma lista do sistema para verificar a identidade do mesmo.
2.  Caso o QR code seja inválido, o Porteiro informa ao Aluno/Servidor sobre o problema.
