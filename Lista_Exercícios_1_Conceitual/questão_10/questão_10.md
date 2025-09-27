Sistema para biblioteca pessoal, considerando a organização dos livros em estantes, por gênero literário.

Entidades: 
1.Livro
    -ISBN (chave primária)
    -título
    -autor
    -editora
    -edição
    -idioma
    -país_origem
Ao considerar uma biblioteca particular, podem haver mais edição de um livro por outras editoras ou por seu idioma e país de origem.

2.Gênero
    -id_gênero (chave primária)
    -nome_gênero
3.Estante
    -id_estante (chave primária)
    -id_gênero
Em caso de as estantes não estarem todas em um cômodo somente:
    -local
4.Organização (entidade associativa livro com estante)
    -ISBN (chave primária)
    -id_estante (chave primária)
    -posição_na_estante

Um livro só pode estar em uma estante (1,1), um livro pode pertencer a mais de um gênero (1,N) e um gênero pode ter vários livros (1,N).