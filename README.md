# [Semana da Biologia Marinha e do Gerenciamento Costeiro - 2021, UNESP - IB CLP, São Vicente, SP](https://www.even3.com.br/xviisbmgc)
<img src="unesp_logos.png" align="right" width = "250px"/>

## Workshop "Fundamentos básicos do R: aplicação na biologia"

### Francesca B. L. Palmeira, Maísa Ziviani Alves e Janne Lis H. de Santis

EMENTA: O objetivo deste curso é oferecer um treinamento teórico-prático no uso da linguagem de programação R com aplicação na biologia marinha, no gerenciamento costeiro e na conservação da biodiversidade.

No primeiro dia do curso, teremos uma aula teórica sobre o uso do R e sua aplicação biológica utilizando exemplos dentro de três níveis de organização biológica (organismos, populações e comunidades). Também faremos uma introdução rápida ao R, apresentando os principais conceitos.

No segundo dia, teremos uma aula totalmente prática utilizando o RStudio Cloud, uma versão online que dispensa a instalação do R no computador. O objetivo desta aula será construir uma rede de interações tróficas predador-presa. Conheceremos alguns pacotes básicos do R para a visualização gráfica de redes tróficas e mutualísticas. Aprenderemos a construir matrizes de dados simétrica e assimétrica. Estudaremos alguns parâmetros estatísticos e matemáticos como o grau de conectância e as interações possíveis, a distância e a centralidade, a modularidade e o aninhamento, entre outros. Faremos a interpretação dos resultados gerados pelas análises e discutiremos as suas aplicações biológicas.

Não é necessário ter conhecimento prévio de R ou estatística.

PÚBLICO-ALVO: Estudantes de graduação, pós-graduação e profissionais interessados em redes ecológicas.

MATERIAIS:

- [Ementa do curso `.pdf`](https://github.com/fblpalmeira/SBMGC_2021/blob/main/1_Ementa_SBMGC_2021.pdf)

- [Tutorial do RStudio Cloud `.pdf`](https://github.com/fblpalmeira/SBMGC_2021/blob/main/2_Tutorial_RStudioCloud_Pronta_Cientista_2021.pdf)

- [Aula teórica  `.pdf`]()

EXERCÍCIO:

- [Código `.Rmd`]()

- [Planilha `.csv`]()

## Instalação

Instale o pacote 'foodweb' do `R`:

``` r
# install.packages("foodweb")
library(foodweb)
```

<img src="jaguar_foodweb.gif">

REFERÊNCIAS:

[Palmeira FBL, 2015.](https://www.teses.usp.br/teses/disponiveis/11/11150/tde-17092015-111206/publico/Francesca_Belem_Lopes_Palmeira_versao_revisada.pdf) Coocorrência, interações tróficas e distribuição potencial da onça-pintada (Panthera onca) no bioma Amazônia. Tese de Doutorado, Universidade de São Paulo (USP).

[Perdomo G, 2012.](https://cran.r-project.org/web/packages/foodweb/foodweb.pdf) Package 'foodweb'.
