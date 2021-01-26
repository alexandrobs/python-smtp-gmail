# Python SMTP Gmail
Envio de email usando servidor SMTP do Gmail em Python 
Serve para outros clientes SMTP, basta alterar as configurações, remova a do Gmail e substitua por outro SMTP de sua preferência.

No código procure #Configuração

ATENÇÃO: Altere <user> e <password> com o email e senha de uma conta gmail, ou leia isso de um arquivo ou banco de dados, protegendo suas credenciais.
user = '<user>'
password = '<password>'
 
e habilite ON em https://www.google.com/settings/security/lesssecureapps permitindo o acesso a app menos seguro na sua conta google, você pode desativar isso quando terminar de enviar a mensagem.

Nota: altere o email do destinatário em
email_msg['To'] = '<mail@mail.com>'


Depois de editar e confogurar execute seu arquivo .py no console.
