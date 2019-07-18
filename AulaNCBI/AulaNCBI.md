# Introdução aos Recursos de Bioinformática do NCBI

O Centro Nacional de Informação Biotecnológica ([NCBI](https://www.ncbi.nlm.nih.gov/)) fornece uma riqueza de informações nas áreas de medicina e ciências biológicas. A maioria das pessoas está familiarizada com o banco de dados do [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/). Mas este é apenas um pequeno subconjunto dos recursos disponíveis.

Você pode acessar o NCBI diretamente pelo link http://www.ncbi.nlm.nih.gov/

### Acesse o site do [NCBI](http://www.ncbi.nlm.nih.gov/) e click na opção *Search*

Serão listados todos os Bancos de Dados disponíveis do NCBI. Como pode ser visto, o [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/) é apenas uma pequena fração dos recursos disponíveis.

Os vários bancos de dados estão interconectados, com o banco de dados *Gene* sendo o principal recurso. A maioria das buscas começará no [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/) com um salto para *Gene* ou iniciando no *Gene* diretamente.

### Conta do NCBI

Embora não seja estritamente necessário, é uma boa ideia criar sua própria conta do [NCBI](https://www.ncbi.nlm.nih.gov/). Assim é possível manter um histórico de pesquisas.

### Pesquisa Avançada

Todos os bancos de dados que permitem pesquisa possuem um recurso adicional que permite uma pesquisa mais estruturada.

### Banco de dados [Gene](https://www.ncbi.nlm.nih.gov/gene/)

Vamos ilustrar a utilização do banco de dados [Gene](https://www.ncbi.nlm.nih.gov/gene/) descobrindo o que podemos sobre o gene que controla a digestão de lactose.

* Pesquise pelo termo *Lactose Intolerance* no [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/).
* Em seguida, na caixa *Find Related Data* selecione o Banco [Gene](https://www.ncbi.nlm.nih.gov/gene/) e clique em *Find items*

> Se já conhecêssemos o nome do gene, poderíamos ter começado com uma pesquisa direta no banco de dados [Gene](https://www.ncbi.nlm.nih.gov/gene/)

### [GenBank](https://www.ncbi.nlm.nih.gov/genbank/)

Navegando para a Sequência de Referência do [NCBI](https://www.ncbi.nlm.nih.gov/), podemos clicar no número *RefSeq* para ver o registro do *Nucleotide GenBank* para este gene.

É importante usar o *RefSeq ID* para pesquisar no banco de dados [Nucleotide](https://www.ncbi.nlm.nih.gov/nuccore/) porque os dados de sequência podem ser alterados. Queremos estar usando sempre a última sequência disponível. 

* Selecione o *RefSeq ID* do gene

Agora temos as últimas informações detalhadas e curadas sobre a sequência do gene, bem como dados de sequência para seus produtos.


### Banco de dados [Protein](https://www.ncbi.nlm.nih.gov/protein/)

Agora que sabemos o nome do gene vamos pesquisar diretamente pelo nome do gene LCT

* Pesquise pelo gene LCT no banco de dados [Protein](https://www.ncbi.nlm.nih.gov/protein/)

> A maneira de escolher o registro correto é procurar o item curado. Neste caso o item que começa com [NP_](https://en.wikipedia.org/wiki/RefSeq).


### [BLAST](http://blast.ncbi.nlm.nih.gov/)

O [NCBI](https://www.ncbi.nlm.nih.gov/) fornece a ferramenta para busca de sequências - *Basic Local Alignment Sequence Tool* (BLAST) - que pode ser usada para:

1. Encontrar registros de banco de dados semelhantes para sequências de proteínas ou de ácidos nucléicos
2. Encontrar Domínios Conservados dentro das sequências
3. Comparar e alinhar sequências

