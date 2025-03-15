<h2>Organização e Sistemas de Arquivos 2024/2</h2>

<h3>Sobre a Atividade</h3>
Esta atividade envolve a implementação de uma estrutura de índice utilizando uma Árvore B para gerenciar registros de livros. Inicialmente, os dados são lidos a partir de um arquivo CSV (dados.csv) e convertidos para um formato binário (.bin), onde cada registro é armazenado juntamente com delimitadores e um descritor de tamanho. Em seguida, é gerado um arquivo de índice (index.txt) que registra o id de cada livro e o endereço de seu respectivo registro no arquivo binário.

O código apresentado exemplifica a inserção, busca e remoção de elementos na Árvore B, onde cada chave representa o id do livro e o endereço associado indica a posição do registro no arquivo binário. A adoção da Árvore B possibilita a atualização dinâmica dos dados, permitindo que as operações de inserção e busca sejam realizadas de maneira eficiente, mesmo com um grande volume de registros.

Além disso, a atividade contempla a implementação de um índice invertido em formato .bin, que permite a busca rápida por palavras ou frases contidas nos títulos dos livros. Esse processo é facilitado pela remoção de stopwords e pontuações, garantindo que apenas as palavras-chave relevantes sejam armazenadas e utilizadas para a pesquisa. Dessa forma, o sistema aprimora a eficiência na recuperação de informações a partir tanto dos registros numéricos (através da Árvore B) quanto das buscas textuais (através do índice invertido).
