<h2>Organização e Sistemas de Arquivos 2024/2</h2>

<h3>Sobre a Atividade</h3>
Esta implementação contém uma estrutura de Árvore B, uma árvore balanceada com operações eficientes de inserção, busca e remoção. A Árvore B é amplamente utilizada em sistemas de arquivos e bancos de dados devido à sua alta performance em operações de grandes volumes de dados.

## Funcionalidades

- **Inserção**: Insere pares (chave, endereço) na árvore. Quando um nó atinge o limite, ele é dividido.
- **Busca**: Pesquisa recursivamente pela chave e retorna o nó e o índice onde a chave foi encontrada.
- **Remoção**: Remove chaves da árvore e usa operações de `fill`, empréstimo (borrow) e mesclagem (merge) para manter as propriedades da Árvore B.
- **Exibição**: Imprime a estrutura da árvore, mostrando os níveis hierárquicos através de recuo.

## Como Executar

Para testar a implementação, execute o arquivo `Btree.py` utilizando o Python:
    
```sh
python [Btree.py](http://_vscodecontentref_/0)
