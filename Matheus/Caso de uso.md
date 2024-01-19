# Caso de Uso:  Sistema de agendamento para restaurante de escola.
 

## Descrição: este caso de uso será chamado pelo usuário para agendar uma refeição.


**Ator Principal:** Aluno/Servidor;

**Ator Secundário:** Professores e funcionários;

 

## Pré-condições: 

1) O servidor deve estar funcionando perfeitamente;

## Pós-condições: 

1) Site mostrando a interface.

 

## Fluxo Principal: 

1. O usuário abre o site;

2. O sistema começa a carregar o site;

3. Mostra a tela de login do usuário;

4. O usuário realiza seu login, colocando CPF e senha;

5. O sistema valida CPF e senha;

6. O Sistema leva para o menu de agendamento;

7. O usuário clica em "Realizar agendamento."

8. O sistema gera um QRCode, para que o aluno comprove seu agendamento.

 
## Fluxos Alternativos: 


1.  *O usuário insere um CPF não cadastrado ou insiriu errado, assim como a senha:* É mostrado uma notificação de senha incorreta, pedindo pra redigitar caso algo esteja errado.
 

2.  *Caso o usuário esqueça a senha:* Terá uma opção para caso isso ocorra, ele terá que entrar em contato com a secretaria.
