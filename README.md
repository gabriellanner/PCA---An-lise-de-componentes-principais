A Análise de Componentes Principais (PCA) é uma técnica usada para detectar padrões nos dados e reduzir a dimensionalidade,
sendo geralmente classificada como um método de aprendizado não supervisionado (pois não utilizamos uma variável alvo).
Embora a redução de variáveis possa implicar em uma pequena perda de informação, essa técnica melhora o desempenho do modelo e facilita a visualização e a interpretação dos dados.

O PCA é especialmente útil em conjuntos de dados com muitas variáveis, pois extrai os componentes principais que retêm uma alta porcentagem da informação original.

Neste projeto, desenvolvi duas versões do PCA para fins didáticos.
Na primeira versão, implemento o algoritmo utilizando apenas conceitos matemáticos com as bibliotecas Numpy e Pandas.
Na segunda versão, utilizo a biblioteca Scikit-learn, que oferece uma implementação pronta do PCA, facilitando a aplicação da técnica.

Segue imagens dos resultados:

Na primeira versão, os 10 componentes principais acumulados explicam  95,783 dos dados

![image](https://github.com/user-attachments/assets/381d89c9-4b0e-43de-9aed-0a3211ee3df7)

Na segunda versão, utilizando o sklearn temos o valor total de 95,787

![image](https://github.com/user-attachments/assets/223f862e-a815-4f51-8e93-7532be96c33b)


