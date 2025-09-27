1. A modelagem conceitual representa de modo abstrato a estrutura de um banco de dados, independente de um SGBD (Sistema Gerenciador de Banco de Dados), a partir de um levantamento de requisitos com o usuário.

2. Uma entidade forte possui uma chave primária, que é única, como o CPF de um aluno ou sua matrícula.
Uma entidade fraca não possui uma chave primária, dependendo de uma entidade forte para ser identificada, como "historico_academico" que vai depender da matrícula_do_aluno e um id_disciplina.

3.Chave Primária é um identificador único de cada registro em uma tabela, também serve como referência em relacionamentos com outras tabelas
Chave Candidata são atributos que poderiam ser usados como chave primária, mas apenas um é escolhido como chave primária.
Superchave é qualquer conjunto de atributos que garante a unicidade de um registro e pode incluir atributos extras além da chave primária.
A escolha correta da chave primária é essencial para a integridade dos dados, para evitar problemas de duplicidade e inconsistências.

4.Um relacionamento ternário consiste em uma relação entre três entidades. Como na venda de certos medicamentos onde é necessário apresentar uma receita médica, ou seja, as entidades Venda, Medicamento e Receita_médica se relacionam.

5.Atributos multivalorados possuem mais de um valor, como o número de telefone, uma pessoa pode ter mais de um número, com ele pode-se representar variações ou múltiplas ocorrências de uma mesma característica sem duplicar a entidade, no MER é representado por elipses duplas e sua normalização é recomendada quando houver a necessidade de consultas frequentes sobre valores individuais e para evitar redundância. 

Atributos derivados são calculados a apartir de outros atributos, exemplo, IDADE que deriva da Data_de_nascimento, eles evitam armazenamento redundante, é representado por elipses tracejada, sua normalização é recomendada quando não precisa ser armazenado permanentemente, ajudado na cosistência dos dados, evitando divergênciass entre o valor armazendo e o valor real.