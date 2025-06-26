# 🌿 Análise e Previsão de Desmatamento no Cerrado com IA

Este projeto tem como objetivo aplicar algoritmos de aprendizado de máquina, como **Random Forest** e **Regressão Não Linear**, para analisar e prever padrões de desmatamento no bioma Cerrado brasileiro. Utilizando dados geoespaciais públicos e bibliotecas de ciência de dados em Python, a análise busca identificar tendências espaço-temporais e áreas com maior risco de desmatamento.

## 📁 Dados Utilizados

Os dados foram extraídos de bases públicas disponibilizadas pelo governo federal, contendo mais de 35 mil registros de alertas de desmatamento e queimadas no Cerrado. Os arquivos shapefiles (`.shp`, `.dbf`, `.prj`, `.shx`) contêm informações georreferenciadas sobre localidade, data e tipo de ocorrência.

Além disso, foram incorporadas variáveis contextuais, como presença em Unidades de Conservação, para enriquecer a modelagem.

## 🧠 Algoritmos Aplicados

- Random Forest (Classificação e Regressão)
- Regressão Linear
- Tentativas com modelos não lineares
- Exploração futura com:
  - XGBoost
  - LightGBM
  - Redes neurais com embeddings espaciais/temporais

## 📊 Análises Realizadas

- Exploração estatística dos dados
- Visualização em mapas (alertas georreferenciados)
- Análise temporal e sazonal de ocorrências
- Engenharia de atributos espaciais, temporais e contextuais
- Avaliação da performance preditiva dos modelos

## 🔎 Principais Conclusões

A modelagem com Random Forest demonstrou potencial para detectar regiões críticas de desmatamento, embora limitada pela ausência de variáveis ambientais mais robustas. A previsão da magnitude das áreas desmatadas mostrou-se desafiadora devido à alta variabilidade e presença de outliers. Resultados indicam a necessidade de incorporar dados de uso do solo, clima e pressão humana para maior precisão.

## 🚀 Próximos Passos

- Adicionar dados climáticos e de uso do solo (ex: MapBiomas, TerraClass)
- Relacionar alertas com focos de calor (ex: MODIS, VIIRS)
- Experimentar algoritmos mais complexos e explicáveis (SHAP, GWR)
- Criar dashboards interativos para uso público e tomada de decisão

## 🛠️ Tecnologias e Ferramentas

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- GeoPandas, Shapely
- QGIS (para apoio visual geográfico)

## 📚 Referências

- BREIMAN, L. *Random forests*. Machine Learning, v. 45, n. 1, p. 5–32, 2001.
- PEDREGOSA, F. et al. *Scikit-learn: Machine Learning in Python*. Journal of Machine Learning Research, v. 12, p. 2825–2830, 2011.
- CHEN, T.; GUESTRIN, C. *XGBoost: A Scalable Tree Boosting System*. KDD ’16, 2016.
- KE, G. et al. *LightGBM: A Highly Efficient Gradient Boosting Decision Tree*. NeurIPS 2017.
- FOTHERINGHAM, A. S. et al. *Geographically Weighted Regression*. Wiley, 2002.
- MORAN, P. A. P. *Notes on Continuous Stochastic Phenomena*. Biometrika, 1950.

## 👨‍💻 Autor

Este projeto foi desenvolvido como prova 2 da máteria de Inteligência Artificial e Aprendizado de Máquina.

---

