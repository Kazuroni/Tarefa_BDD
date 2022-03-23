# Tarefa_BDD
Crie um banco de dados com esta estrutura: CREATE SCHEMA tarefas DEFAULT CHARACTER SET utf8 ; CREATE TABLE IF NOT EXISTS tarefas.tarefa ( id INT NOT NULL AUTO_INCREMENT, descricao VARCHAR(200) NOT NULL, concluida TINYINT(1) NOT NULL DEFAULT 0, PRIMARY KEY (id)) ENGINE = InnoDB; Implemente as funções indicadas no menu, salvando no banco de dados criado.
