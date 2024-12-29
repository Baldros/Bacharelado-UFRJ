# AnaliseRegressao-UFRJ

## Introdução:
A **análise de regressão** é uma técnica estatística essencial na área de dados e **aprendizagem estatística**, permitindo a modelagem e compreensão das relações entre variáveis. Ela desempenha um papel crucial na previsão e inferência sobre o comportamento dos dados, facilitando a identificação de padrões e a tomada de decisões fundamentadas.

### Uma pontuação importante:
Note que eu optei por usar **aprendizagem estatística** à **Machine Learning**. Isso se dá porque **análise de regressão** é um curso de **estatística**, ou seja, toda a terminologia aqui utilizada estará sob o viés não só do vocabulário, mas também da forma com a qual a estatística lida com esses modelos. Muitas vezes vamos ver durante os códigos e explicações, situações que alguém já familiarizado com área de Machine Learning terá uma terminologia/definição pronta para aquilo, mas nem sempre os vocabulários e, principalmente, a forma de abordar o problema irão coincidir. Acho importante fazer esse *disclaimer* agora, para o melhor entendimento da abordagem metodológica aqui implementada.

## Linguagem de Programação Utilizada:
Aqui, todos os códigos implementados estaram na [linguagem R](https://www.r-project.org/other-docs.html), independente da extensão que os arquivos estejam, (".r",".Rmd",".ipynb", etc.). A **linguagem R** é uma linguagem criada com o propósito de ser uma ferramenta para análises estatísticas, o que a difere de [python](https://www.python.org/), que não tem um escopo de tarefas como propósito nativo. Apesar de ambas serem usadas no mesmo contexto, por ser nativamente projetado para atuar no contexto, o **R** tem a vantagem que podem facilitar algumas coisas, sobretudo para alguém que entenda bem da ferramenta.

É valido dizer também que durante a construção dos códigos, não pretendo ficar fazendo paralelo entre as linguagens. Acredito que a melhor forma de se aprender uma linguagem nova, seja ela de programação ou de linguagem natural, como inglês, português, etc... É caindo de cabeça num mergulho profundo dentro da cultura daquela linguagem e meu objetivo aqui é justamente utilizar essa tarefa de entender esses modelos pela ótica estatística para também aprender sobre a linguagem de programação utilizada, então aqui **não vamos falar python em R, vamos falar R**.

## EMENTA:
Regressão linear simples. Análise de ajuste. Estudo dos resíduos. Regressão múltipla. Correlação múltipla. Violações de
hipóteses básicas. Transformações de variáveis. Modelos lineares generalizados. Tratamento, por meio de exemplos, de
questões relacionadas ao meio ambiente e de questões étnico-raciais.

## OBJETIVOS GERAIS:
Definir modelo linear, ajustar modelos de regressão linear simples e múltiplos. Avaliar os resultados do ajuste e propor
medidas remediadoras, em caso de violação das suposições básicas. Definir, ajustar e analisar modelos lineares
generalizados.

## CONTEÚDO PROGRAMÁTICO:

**UNIDADE I**
Regressão Linear Simples. Parâmetros do modelo, estimador de mímimos quadrados (EMQ); análise de variância (ANOVA);
coeficiente de determinação R2; erros e resíduos; normalidade dos erros, estimador de máxima verossimilhança (EMV);
Intervalos de confiança (IC) e testes de hipóteses: para os parâmetros, para predições e para valores ajustados; análise dos
resíduos.

**UNIDADE II**
Regressão Múltipla. Interpretação geométrica dos EMQ; adicionando mais umpreditor, correlação parcial; ortogonalidade;
notação matricial, ANOVA; gráficos de variáveis adicionadas; gráfico dos resíduos parciais; regressão passando pela origem.
Mínimos quadrados ponderados, teste de falta de ajuste (variância conhecida e desconhecida);.teste F generalizado e
comparação de modelos; e elipsóides de confiança.

**UNIDADE III - Diagnostico**
I – análise dos resíduos: Matriz H; a distância de Mahalanobis; resíduosstudentizados; “outliers”;
casos influentes, distância de Cook, Di e sua magnitude.
II – sintomas e terapias: Gráfico de dispersão; variância não constante; não linearidade; transformação dos preditores e da
variável resposta; falta de suposição de normalidade, papel de probabilidade.

**UNIDADE IV – Construção de modelos**
I – definição de novos preditores: Regressão polinomial, polígonos com vários preditores, superfície de resposta; variáveis
indicadoras; propriedades de locação e escala; transformação linear e componentes principais.
II colinearidade e seleção de variáveis: Medindo colinearidade; seleção de variáveis; algoritmos: de seleção para frente, de
eliminação para traz e do método stepwise; criação de seleção de sub-grupos de variáveis, Cp e todas as possíveis
regressões.
III – Predição: Fazendo predições, interpolação versus extrapolação.

**UNIDADE V – GLIM (modelos lineares generalizados)**
Introdução: componentes do GLIM; notação; distribuições derivadas da normal.
Família de distribuição exponencial e o GLIM.
Estimação: EMV; EMQ; estimação dos parâmetros do GLIM.
Inferência: Distribuição amostral da função scores; distribuição amostral do EMQ; IC para os parâmetros do modelo;
comparação de modelos, distribuição amostral da verossimilhança; testes de hipóteses. Variáveis binomiais e regressão
logística.


## BIBLIOGRAFIA RECOMENDADA:
[1] Montgomery, Douglas C. [et al.]. Introduction to linear regression analysis — 5.ed. — Neu Jersey : J. Wiley & Sons, 2012
(livro texto).

[2] DRAPER, Norman R. Applied Regression Analysis. — 02 — New York: J. Wiley; Chichester : J. Wiley, c1981.

[3] DOBSON, Annette J., BARNETT, Adrian G. An introduction to generalized linear models / –. — 3.ed.– — Boca Raton : CRC
Press, c2008.

[4] Gelman, Andrew e HILL, Jennifer. Data analysis using regression and multilevel/hierarchical models. — Cambridge (ENK)
: Cambridge University Press, 2007.

[5] WEISBERG, Sanford. Applied Linear REgression- — New York : J. Wiley; Chichester : J. Wiley, C1980.

[6] Rawlings, john O. [et al.] Applied regression analysis : a research tool– — 2. ed.– — New York : Springer-Verlag, c1998

[7] NETER, J. [et al.]. Applied linear regression models. — HOMEWOOD : R. D. IRWIN, s1983.

### Bibliografia adicional:
T. Hastie, R. Tibshirani, and J. Friedman (2009). The Elements of Statistical Learning (2a ed.), Springer Series in Statistics
Springer New York Inc., New York, NY, USA.

Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani (2013). An Introduction to Statistical Learning : with
Applications in R. New York :Springer.

Trevor Hastie, Robert Tibshirani , Martin Wainwright (2015). Statistical Learning with Sparsity: The Lasso and eneralizations.
Chapman & Hall/CRC
