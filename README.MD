# Estudo da Biblioteca Seaborn

<div>

<p align="center"> Estudo da Biblióteca Seaborn com base no curso da Alura <br/> 
                   Python para Data Science.
</p>

</div>

<div>

<p align="center">
<a href="#sobre"> Sobre - </a>
<a href="#tecnologias">Tecnologias - </a>
<a href="#bibliotecas">Bibliotecas - </a>
<a href="#analises">Análises - </a>
<a href="#autor">Autor</a>

</div>



 
<h4 align = "center">
🚧Projeto Em Contrução🚧


# Sobre


<p> 
Esse projeto se trata de gorjetas, e sabemos que no Brasil as pessoas pagam 10% do valor da conta como gorjeta ou caixinha dos funcionários, de forma opcional. Em outros países, este valor é livre e fica a critério do cliente, ou seja, não há uma porcentagem exata estabelecida.

Como não existe a possibilidade de  analisar as gorjetas dadas por todas as pessoas do mundo, será feita uma nálise com uma  amostra com um grupo de pessoas ou registros na base de dados.
Serão Realizadas 04 análises.

</p>

# Tecnlogias
* Python
* Jupyter Notebook

# Bibliotecas
* Pandas
* Seaborn
* Ranksums

# Analises

## Análise 01

![Gráfico de Dispeção 1](graphics/grap1.png)

<p> Segundo o Gráfico de disperção, é possível notar que o valor da gorjeta é maior <br> em contas com valores altos</p> 

### Verificando se o valor da gorjeta é proporcional ao da conta

![Gráfico de Dispeção 2](graphics/grap2.png)

<p> Apesar do primeiro gráfico indicar que conforme o valor da conta sobe, o valor da gorjeta também sobe <br> o segundo gráfico indica que essa característica não é proporcional! </p> 

## Análise 02
Pedir sobremesa altera o valor sa gorjeta ?

![Gráfico de Dispeção Categórico 1](graphics/grap3.png)

<p> Infelizmente o gráfico categórico não retornou nenhum dado relevante sobre a infliuência da <br> sobremesa na gorjeta. </p> 

![Gráfico de Dispeção Categórico 2](graphics/grap4.png)
<p> Esse gráfico já aponta uma disperção maior nas gorjetas de contas com sombremesa <br> 
Validar essa análise através de mais 02 gráficos seguintes:</p>

![Gráfico de Dispeção Categórico 3](graphics/grap5.png)

![Gráfico de Dispeção Categórico 4](graphics/grap6.png)

<p> Visualemnte existe uma diferença da gorjeta daqueles que pediram sobremesa para aqueles<br> 
que não pediram sobremesa</p>

### Teste de Hipótese

**H<sup>null**
**A distribuição da taxa da gorjeta é a mesma nos dois grupos (Grupo que compra sobremesa e grupo que não compra sobremesa)**

**H<alt>null**
**A distribuição da taxa da gorjeta não é a mesma nos dois grupos (Grupo que compra sobremesa e grupo que não compra sobremesa)**

**Resultado do  pvalue=0.5. Como esse valor é muito alto, a hipótese alternativa é decartada, logo a hipótese nula prevalece**

- **A distribuição da taxa da gorjeta é a mesma nos dois grupos (Grupo que compra sobremesa e grupo que não compra sobremesa)**

# Autor

* Gabriel Barbosa
* 27 Anos
* Estudante de Data Science
* Analista e Desenvolvedor de Sistemas
* Linkedin: https://www.linkedin.com/in/gabriel-barbosa-j/
* Instagram: https://www.instagram.com/gabrielbarbosa.j/