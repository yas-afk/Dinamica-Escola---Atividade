Documentação do Banco de Dados da Escola
Visão Geral
Este banco de dados simula um sistema de gestão de alunos e suas notas em uma escola. Ele é composto por duas tabelas principais: Alunos e Notas.
A tabela Alunos armazena informações sobre os estudantes, enquanto a tabela Notas contém os dados de desempenho acadêmico de cada aluno.
Estrutura do Banco de Dados
• Banco de Dados: O banco de dados é denominado Escola, sendo criado e selecionado para uso.
• Tabela Alunos: Contém dados como nome, sobrenome, email, telefone e a turma em que o aluno está matriculado. Cada aluno é identificado de forma única pelo campo id_aluno, que é auto-incrementado.
• Tabela Notas: Guarda as notas dos alunos, divididas em dois semestres, além da nota final.
A tabela também inclui um campo que vincula cada registro de notas a um aluno específico através da chave estrangeira id, que referencia o campo id_aluno da tabela Alunos.
Relacionamento entre as Tabelas
A tabela Notas tem uma chave estrangeira que referencia a tabela Alunos. Isso permite que as notas sejam associadas aos alunos corretos, criando um relacionamento entre as duas tabelas.
Operações Realizadas
• Inserção de Dados: Foram adicionados registros tanto para os alunos quanto para as notas, utilizando os campos apropriados em cada tabela.
• Consultas de Dados: Realizaram-se consultas para visualizar os dados dos alunos, das notas e também para buscar informações específicas, como, por exemplo, alunos com determinado sobrenome ou a junção de dados de ambas as tabelas para ver as notas de cada aluno.
Esse banco de dados é simples, mas serve como base para um sistema de gestão de alunos, facilitando o armazenamento e a consulta de informações de estudantes e suas avaliações acadêmicas.
