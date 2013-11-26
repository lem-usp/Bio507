template: page.html

##Aula 8

###Plantão de dúvidas.

Teremos plantão de dúvidas a tarde toda no laboratório. Tragam duvidas da monografia final.

##Aula 7

###Roteiro Prático

Reconstruindo vetores de gradiente de seleção.

1. Utilize os $\Delta z$ por ramo e as matrizes ancestrais para reconstruir os $\beta$s por ramo ao longo da filogenia.
1. Calcule a correlação entre os vetores de resposta ($\Delta z$) e os gradientes de seleção ($\beta$). Esse vetores são alinhados? O que isso significa?
1. *Opcional* Calcule os gradientes de seleção controlando para ruido
na estimativa da matriz de covariância. Para isso, decomponha a matriz
em auto-valores e auto-vetores, substitua o ultimo auto-valor pelo
penúltimo, e reconstrua a matriz. Utilize essa matriz reconstruída
para estimar os $\beta$s Leia o artigo [Modularity, noise, and natural
selection](http://onlinelibrary.wiley.com/doi/10.1111/j.1558-5646.2011.0
1555.x/abstract)([pdf](/static/Marroig_Melo_Garcia-2012.pdf))

##Aula 6

###Roteiro Prático

Reconstruindo matrizes ancestrais.

1. Calcule as matrizes ancestrais, fazendo a média ponderada pela amostra das matrizes atuais.
1. Calcule os auto-vetores das matrizes ancestrais e compare os $\Delta
z$ por ramo com o primeiro e segundo componente principal (auto-vetor)
da matriz do nó ancestral correspondente, utilizando correlação de vetores.

##Aula 5

### Leitura

Leia o artigo [The road to modularity](http://www.nature.com/nrg/journal/v8/n12/abs/nrg2267.html)
([pdf](/bio507/static/Wagner_etal-2007.pdf))

A verificação de leitura desse artigo será em aula, no dia 14/11

###Roteiro Prático

Passamos agora para o estudo da covariação entre os caracteres e suas
consequências evolutivas.

1. Calcule as matrizes de covariância entre os caracteres, para cada espécie;
1. Calcule as matrizes de correlação entre os caracteres, para cada espécie;
1. Calcule os componentes principais das matrizes de covariância, e
seus autovalores (variâncias) associadas.

##Aula 4

### Leitura

Leia o artigo [Size as a line of least evolutionary resistance:
Diet and adaptive morphological radiation in New World
Monkeys](http://onlinelibrary.wiley.com/doi/10.1111/j.0014-3820.2005.tb01049.x/abstract)
([pdf](/bio507/static/Marroig_Cheverud-2005.pdf))

A verificação de leitura desse artigo será em aula, no dia 07/11.

###Roteiro Prático

A filogenia proposta para nossas espécies é: (E,((C, B), (A, D)))

1. Calcule o $\Delta z$ ao longo da filogenia, usando a diferença entre
os estados derivados e os estados ancestrais, calculados por uma média
ponderada, para todos os ramos.
2. Calcule a magnitude (norma) dos $\Delta z$ para todos os ramos da filogenia.

## Aula 3

### Leitura

Leia o artigo [The Evolution of Modularity in the
Mammalian Skull I: Morphological Integration Patterns and
Magnitudes](http://link.springer.com/article/10.1007%2Fs11692-008-9038-3) ([pdf](/bio507/static/Porto-2009.pdf))

A verificação de leitura desse artigo será apenas no dia 31/10.

###Roteiro Prático

Essa semana não teremos roteiro prático. Mesmo com o fim da greve, a
aula do dia 24/10 será utilizada para plantão de dúvidas, a ser
realizado no laboratório de evolução de mamíferos, prédio do minas,
andar do estacionamento, interfone 3.

## Aula 2

### Leitura

Leia o artigo [The Ecological Significance of
Correlation Pleiades](http://www.jstor.org/stable/2405824)

### Roteiro prático

Em anexo está a [base de dados](/bio507/static/dados.csv) (no Excel)
a ser analisada ao longo do curso, composta de quatro medidas, nessa
ordem: comprimento do úmero, comprimento da ulna, comprimento do
fêmur e comprimento da tíbia. Essas medidas foram tomadas para cinco
espécies distintas (A até E), cada espécie contendo 60 indivíduos.

A seguir estão as estatísticas a serem obtidas para cada espécie e a
serem apresentadas em forma de tabelas e gráficos:

 1. Média de cada caráter;
 2. Variância de cada caráter;
 3. Gráfico da distribuição de cada caráter;
 4. Coeficiente de variação de cada caráter;

Com as respostas dos itens acima, elaborar um breve texto comparando
(qualitativamente) as espécies segundo essas estatísticas.

### Tarefas

Compile as análises pedidas acima em um arquivo, junto com eventuais
gráficos, e utilize o seguinte [formulário](https://docs.google.com/forms/d/1fVCLIK8DTiR5GswDtbHooH0h_5a5yxkoqwQVhhCAUgU/viewform) para
responder perguntas sobre o artigo, e o email do seu monitor responsável para enviar o arquivo de respostas de
aula prática.

##Material de apoio

[Apostila teórica](https://github.com/lem-usp/apostila-bio-evol/blob/master/apostila-Bio507.pdf?raw=true)

##Contatos

<A HREF="mailto:&#103;&#109;&#097;&#114;&#114;&#111;&#105;&#103;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;">Gabriel Marroig </A>

Monitora Integral: <A HREF="mailto:&#109;&#111;&#110;&#105;&#113;&#117;&#101;&#046;&#110;&#111;&#117;&#097;&#105;&#108;&#104;&#101;&#116;&#097;&#115;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;&#032;">Monique</A>

Monitor Noturno: <A HREF="mailto:&#100;&#105;&#111;&#103;&#114;&#111;&#064;&#103;&#109;&#097;&#105;&#108;&#046;&#099;&#111;&#109;">Diog(r)o </A>

