# PILN

Este trabalho buscou avaliar comentários fornecidos pelos usuários do site de críticas AdoroCinema, usando métodos de PLN foi feita uma análise de um corpus que continha as críticas do último filme da saga Star Wars: “A Ascensão de Skywalker”. Foi feito em primeiro momento, uma análise de todas as críticas pertencentes ao corpus, averiguando quantos tokens e types o conjunto de 110 textos possuía. Após isso, foram analisadas as classes de palavras do corpus, para averiguar quais eram os substantivos, adjetivos, verbos e advérbios mais abundosos nesse conjunto de textos. Buscando uma maneira de diferenciar críticas positivas e negativas, montamos dois sub-corpus, o corpus de polaridade positiva que possuía críticas 4,5 e 5, e um de polaridade negativa que possuía críticas de 1,5 para baixo,a montagem foi dessa maneira, isso porque assim poderíamos encontrar diferenças mais acentuadas entre eles, o que permitiria construir um algoritmos de diferenciação entre as críticas no futuro.
Nesse repositório se encontra o artigo científico que é produto do trabalho final. Temos também os 2 arquivos notebook usados no projeto para fazer o tratamento dos comentários.
 
 -OBS:Crie dois repositórios chamados:negativo_polarizado e positivo_polarizado, para que a última célula do notebook teste funcione. Ignore as células 4,5,6 e 7 do notebook teste.
 
 -OBS2:Se quiser usar o etiquetador Cogroo no DeepNote,você precisará fazer alguns comandos em um prompt do DeepNote,esse arquivo com as intruções também se encontra aqui. Caso não consiga, recomendo replicar esse notebook no Google Collab.
 
 -Documentação do Cogroo: https://github.com/cogroo/cogroo4/wiki/API-CoGrOO-4
