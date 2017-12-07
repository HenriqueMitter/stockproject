# stockproject 
Baixar o arquivo stockproject.jar e o arquivo query stock Project. 
Abrir o SQL SERVER Configuration Manager e ir em configuração do SQL Native Client 10.0 
Em seguida ir em protocolos de cliente e habilitar Pipes Nomeados com o botão direito. 
Reinicie o computador. 

Abrir o SQL Management Studio ir em pasta Segurança>Logon>botão direito> novo logon>selecionar Autenticação do SQL SERVER  
Clicar ao lado Funções do Servidor e habilitar todas as funções > clique OK 
Faça o logon com usuário “admin” e senha “admin” 
Clique em Nova consulta copie e cole a query e execute. 

Abra o Stock Project 2.0.jar e divirta-se!  
Os campos tela e valor são do tipo inteiro (o banco só aceitara se os dados forem inseridos assim).
Os modelos são unicos(PKs).
O estoque consulta os produtos por meio do Modelo(PK).
