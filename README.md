# Desafio Final Imersão Dados

Este estudo é uma introdução ao data Science, com o tema Drug Discovery. Foram utilizados dois arquivos. O primeiro contém informações de expressão de genes e viabilidade em experimentos com diferentes doses, moléculas e tempos de ação. O segundo, contém informações sobre os mecanismos de ação ativados em cada experimento.

As perguntas a serem respondidas utilizando a análise de dados e o machine learning são:

- As amostras estão balanceadas com relação aos parâmetros? (Tempo, dose, tratamento, droga)?
- Há drogas utilizadas em apenas uma amostra?
- As características de tempo e dose são uniformes nessas amostras?
- Há correlação entre as expressões dos genes, para os primeiros 50 genes?
- Há correlação entre as viabilidades das celulas, para aos 50 primeiros tipos de células?
- A correlação de viabilidade é maior ao analisar para cada droga (analisar controle e 2 drogas mais usadas)
- É possível obter um bom modelo para predizer a ocorrência de mecanismos de ativação com base nos dados?
- As informações de viabilidade celular melhoram ou pioram o modelo?
- É possível pum modelo de predição para a ativação de mecanismos específicos com base na expressão de genes e viabilidade?
- A expressão de genes seriam bons preditores da viabilidade celular?

##Modelos utilizados na pesquisa:
LogisticRegression
DecisionTreeClassifier
RadomForestClassifier
LinearRegression

##referências
- [Drug discovery: passado, presente e futuro](https://docs.google.com/document/d/10EhrQBChlyYIcff3to7PrCQi5HcNk2r-zd2ZCKPtcz8/edit?usp=sharing)
- [Expressão gênica: o caminho da informação biológica](https://drive.google.com/file/d/1VNP08ffCiGD8cqaBkdHATWSX8Yxfm3dj/view?usp=sharing)
 - [Documentação da biblioteca Pandas](https://pandas.pydata.org/docs/user_guide/index.html)
 - [Documentação da biblioteca Seaborn](https://seaborn.pydata.org/api.html)
- [Documentação do ScikitLearn](https://scikit-learn.org/stable/about.html#citing-scikit-learn)
- [Multiple Linear Regression Using Python and Scikit-learn](https://www.analyticsvidhya.com/blog/2021/05/multiple-linear-regression-using-python-and-scikit-learn/)
- [R-Squared Definition](https://www.investopedia.com/terms/r/r-squared.asp)

