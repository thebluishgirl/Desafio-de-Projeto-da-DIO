# ***Objetos do Git***

No Git é utilizado 3 tipos de objetos, sendo esses:

1. *Blobs*
2. *Trees (Árvores)* 
3. *Commit*




## *Blobs*
#
Os Blobs podem ser representados como os arquivos, nele são encontrado metadados do Git como o *tamanho da string* e até o *tipo de dado*.
## *Trees (Árvores)*
#

Já a Árvores podem ser representadas como as pastas, nela são armazenadas os **Blobs** e assim como eles posssuem metadados a mais, como por exemplo o *nome do árquivo*.

## *Commit*
#

Aqui é onde tudo é juntado. Um commit aponta uma Árvore, seu parente *(Commit anterior a ele)*, uma mensagem e seu autor e conta, também, com um *timestamp (ou carimbo de tempo)* que possui informações como a data completa e hora do commit.