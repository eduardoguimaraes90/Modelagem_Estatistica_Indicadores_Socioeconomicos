# Análise da Expectativa de Vida com Modelagem Estatística

Este repositório apresenta um projeto de análise de dados e modelagem estatística utilizando Python e o pacote **Statsmodels** para identificar as variáveis mais relevantes que influenciam a expectativa de vida dos cidadãos.

## Objetivo
O objetivo deste projeto é construir um modelo estatístico capaz de explicar a expectativa de vida a partir de um conjunto de variáveis quantitativas, através de um processo rigoroso de limpeza, análise exploratória, tratamento de dados e regressão estatística.

## Etapas do Projeto

1. **Dicionário de Dados e Análise Exploratória**
   - Definição das variáveis presentes no dataset.
   - Visualização de estatísticas descritivas.

2. **Tratamento de Dados**
   - Remoção de valores nulos.
   - Preenchimento de valores ausentes com a mediana.
   - Tratamento de outliers utilizando o método dos interquartis.
   - Remoção de variáveis categóricas.

3. **Engenharia de Atributos**
   - Criação de novas variáveis, como uma combinação entre **alcohol** e **bmi**.
   - Categorizamos a população em grupos para melhor análise.

4. **Análise de Correlação e Multicolinearidade**
   - Identificação de colunas altamente correlacionadas.
   - Remoção de variáveis redundantes para evitar multicolinearidade.

5. **Modelagem Estatística**
   - Utilização do método de **Mínimos Quadrados Ordinários (OLS)**.
   - Ajuste do modelo estatístico aos dados.
   - Análise de coeficientes para identificar variáveis significativas.

6. **Diagnóstico e Validação**
   - Análise dos resíduos.
   - Verificação das suposições do modelo.
   - Ajuste fino para otimização do desempenho.

7. **Conclusão**
   - Apresentação dos principais insights obtidos.
   - Interpretação dos resultados para apoio à tomada de decisões.

## Tecnologias Utilizadas

- **Python**
- **Pandas** para manipulação de dados
- **NumPy** para operações matemáticas
- **Matplotlib & Seaborn** para visualização dos dados
- **Statsmodels** para modelagem estatística
- **Scikit-learn** para pré-processamento dos dados

## Contribuição

Fique à vontade para enviar sugestões de melhorias no email edulguimaraes@gmail.com.

---

Se gostou deste projeto, não esqueça de deixar uma ⭐ no repositório!
