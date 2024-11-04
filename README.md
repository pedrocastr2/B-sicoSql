Um simples repositório com o conteúdo básico de sql 
Como criar tabelas , adcionar dados a uma tabela , combinar tabelas , apagar ,Atualizar , visualizar tabelas.

exemplo:
SELECT * FROM CLIENTES // Para selecionar os dados ,visualizando eles.

SELECT * FROM CLIENTES where id = 12131;

SELECT * FROM ClIENTES WHERE PERCENTUAL_COMISSAO < 0.17 AND id = 12131;

DROP TABLE CLIENTES; //para excluir tabelas 

UPDATE CLIENTES SET NOME = Jose WHERE ID= '1121242';  //Para alterar tabelas

