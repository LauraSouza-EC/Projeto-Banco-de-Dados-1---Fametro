1. A modelagem conceitual representa de modo abstrato a estrutura de um banco de dados, independente de um SGBD (Sistema Gerenciador de Banco de Dados), a partir de um levantamento de requisitos com o usuário.

2. Uma entidade forte possui uma chave primária, que é única, como o CPF de um aluno ou sua matrícula.
Uma entidade fraca não possui uma chave primária, dependendo de uma entidade forte para ser identificada, como "historico_academico" que vai depender da matrícula do aluno e um id_disciplina.

3.Chave Primária é um identificador único de cada registro em uma tabela, também serve como referência em relacionamentos com outras tabelas
Chave Candidata são atributos que poderiam ser usados como chave primária, mas apenas um é escolhido como chave primária.
Superchave é qualquer conjunto de atributos que garante a unicidade de um registro e pode incluir atributos extras além da chave primária.
A escolha correta da chave primária e essencial para a integridade dos dados, evitar problemas de duplicidade e inconsistências.

4.Um relacionamento ternário consiste em uma relação entre três entidades. Como na venda de medicamentos que necessitam de receita médica, ou seja, as entidades Venda, Medicamento e Receita médica se relacionam.

5.Atributos multivalorados possuem mais de um valor, como o número de telefone, uma pessoa pode ter mais de um número. Os atributos derivados calculado a apartir de outros atributos, exemplo, IDADE que deriva da Data_de_nascimento.