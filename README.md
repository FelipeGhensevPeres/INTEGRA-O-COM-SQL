# INTEGRACAO COM SQL

aplicativo de controle de estoque feito em Python utilizando:

Tkinter na interface gráfica 

SQLite usando Pyodbc para a conexao com o banco de dados

Funcionalidades: Adicionar insumo - registra um novo produto no estoque com nome, quantidade, validade e lote
                 Deletar insumo - remove um produto do estoque pelo nome e lote.
                 Consumir insumo - atualiza a quantidade de um insumo, diminuindo de acordo com a quantidade consumida.
                 Visualizar insumo - consulta os dados de um produto específico no banco e exibe suas informações de nome,quantidade,validade e lote.



Estrutura: Faço a conexao com o banco Estoque.db.
           A manipulacao da tabela é feita utilizando CRUD (CREATE,READ,UPDATE,DELETE)
           A interface gráfica contém campos de entrada e botões para executar as ações no banco
           Há uma caixa de texto na variavel caixa_texto que mostra mensagens de sucesso, erro ou informações dos insumos
