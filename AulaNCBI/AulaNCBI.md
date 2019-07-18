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

#### [BLASTP](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome)

* Pesquise pela sequência de aminoácidos.

```
melswhvvfi allsfscwgs dwesdrnfis tagpltndll hnlsgllgdq ssnfvagdkd
myvchqplpt flpeyfsslh asqithykvf lswaqllpag stqnpdektv qcyrrllkal
ktarlqpmvi lhhqtlpast lrrteafadl fadyatfafh sfgdlvgiwf tfsdleevik
elphqesras qlqtlsdahr kayeiyhesy afqggklsvv lraedipell leppisalaq
dtvdflsldl syecqneasl rqklsklqti epkvkvfifn lklpdcpstm knpasllfsl
feainkdqvl tigfdinefl scsssskksm scsltgslal qpdqqqdhet tdsspasayq
riweafanqs raerdaflqd tfpegflwga stgafnvegg waeggrgvsi wdprrplntt
egqatlevas dsyhkvasdv allcglraqv ykfsiswsri fpmghgssps lpgvayynkl
idrlqdagie pmatlfhwdl pqalqdhggw qnesvvdafl dyaafcfstf gdrvklwvtf
hepwvmsyag ygtgqhppgi sdpgvasfkv ahlvlkahar twhhynshhr pqqqghvgiv
lnsdwaepls perpedlras erflhfmlgw fahpvfvdgd ypatlrtqiq qmnrqcshpv
aqlpefteae kqllkgsadf lglshytsrl isnapqntci psydtiggfs qhvnhvwpqt
ssswirvvpw girrllqfvs leytrgkvpi ylagngmpig esenlfddsl rvdyfnqyin
evlkaikeds vdvrsyiars lidgfegpsg ysqrfglhhv nfsdssksrt prksayffts
iiekngfltk gakrllppnt vnlpskvraf tfpsevpska kvvwekfssq pkferdlfyh
gtfrddflwg vsssayqieg awdadgkgps iwdnfthtpg snvkdnatgd iacdsyhqld
adlnmlralk vkayrfsisw srifptgrns sinshgvdyy nrlinglvas nifpmvtlfh
wdlpqalqdi ggwenpalid lfdsyadfcf qtfgdrvkfw mtfnepmyla wlgygsgefp
pgvkdpgwap yriahavika harvyhtyde kyrqeqkgvi slslsthwae pkspgvprdv
eaadrmlqfs lgwfahpifr ngdypdtmkw kvgnrselqh latsrlpsft eeekrfirat
advfclntyy srivqhktpr lnppsyeddq emaeeedpsw pstamnraap wgtrrllnwi
keeygdipiy itengvgltn pntedtdrif yhktyineal kayrldgidl rgyvawslmd
nfewlngytv kfglyhvdfn ntnrprtara saryytevit nngmplared eflygrfpeg
fiwsaasaay qiegawradg kglsiwdtfs htplrvenda igdvacdsyh kiaedlvtlq
nlgvshyrfs iswsrilpdg ttryineagl nyyvrlidtl laasiqpqvt iyhwdlpqtl
qdvggwenet ivqrfkeyad vlfqrlgdkv kfwitlnepf viayqgygyg taapgvsnrp
gtapyivghn likahaeawh lyndvyrasq ggvisitiss dwaeprdpsn qedveaarry
vqfmggwfah pifkngdyne vmktrirdrs laaglnksrl peftesekrr ingtydffgf
nhyttvlayn lnyataissf dadrgvasia drswpdsgsf wlkmtpfgfr rilnwlkeey
ndppiyvten gvsqreetdl ndtariyylr tyinealkav qdkvdlrgyt vwsamdnfew
atgfserfgl hfvnysdpsl pripkasakf yasvvrcngf pdpatgphac lhqpdagpti
spvrqeevqf lglmlgttea qtalyvlfsl vllgvcglaf lsykyckrsk qgktqrsqqe
lspvssf
```

* Pesquise pelo *RefSeq ID* NP_002290

> Um resultado importante dos resultados de pesquisa do BLASTP são os Domínios Conservados encontrados para a proteína

#### [BLASTN](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome)

* Pesquise pela sequência de nucleotídeos. 
> A qual gene esta sequência pertence?

```
gt accttgattt cgtattctga gaggctgctg cttagcggta gccccttggt 
ttccgtggca acggaaaagc gcgggaatta cagataaatt aaaactgcga ctgcgcggcg 
tgagctcgct gagacttcct ggacggggga caggctgtgg ggtttctcag ataactgggc 
ccctgcgctc aggaggcctt caccctctgc tctgggtaaa g
```



#### [BlastX](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastx&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome) e [tBlastN](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=tblastn&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome)

* Pesquise pela sequência de nucleotídeos. 

> Que tipo de molécula é essa DNA, mRNA ou proteína? 
> Qual proteína retornou melhor similaridade? 
> Quantos aminoácidos a proteína similar alinhou com a sequência acima?

``` 
actcttctgg tccccacaga ctcagagaga acccaccatg gtgctgtctc ctgccgacaa
gaccaacgtc aaggccgcct ggggtaaggt cggcgcgcac gctggcgagt atggtgcgga
ggccctggag aggatgttcc tgtccttccc caccaccaag acctacttcc cgcacttcga
cctgagccac ggctctgccc aggttaaggg ccacggcaag aaggtggccg acgcgctgac
caacgccgtg gcgcacgtgg acgacatgcc caacgcgctg tccgccctga gcgacctgca
cgcgcacaag cttcgggtgg acccggtcaa cttcaagctc ctaagccact gcctgctggt
gaccctggcc gcccacctcc ccgccgagtt cacccctgcg gtgcacgcct ccctggacaa
gttcctggct tctgtgagca ccgtgctgac ctccaaatac cgttaagctg gagcctcggt
ggccatgctt cttgcccctt gggcctcccc ccagcccctc ctccccttcc tgcacccgta
cccccgtggt ctttgaataa agtctgagtg ggcggca
```

* Pesquise pela sequência de aminoácidos

> Qual foi a sequência mais similar?
> Qual é o tamanho em aminoácidos?

```
mgdvekgkki fimkcsqcht vekggkhktg pnlhglfgrk tgqapgysyt aanknkgiiw
gedtlmeyle npkkyipgtk mifvgikkke eradliaylk katne
```

### [Structure](https://www.ncbi.nlm.nih.gov/structure)

* Acesse o banco de dados [Structure](https://www.ncbi.nlm.nih.gov/structure) e pesquise pelo gene LCT


### Bancos de Variantes Genéticas

O NCBI fornece vários recursos de banco de dados para informações sobre variantes genéticas.
