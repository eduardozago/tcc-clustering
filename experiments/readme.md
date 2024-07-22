# Clustering Experiments

Os experimentos de clustering são realizados com o resultado do pré-processamento, onde são realizados 3 experimentos com as combinações dos pré-processamentos:

- **E1:** P1 e P2
- **E2:** P2 e P3
- **E3:** P1 e P3

Os experimentos consistem na importação dos resultados dos pré-processamentos, seguido pelo cálculo do número ideal de cluster com o Método Elbow e o agrupamento nos clusters e por fim são analisados os resultados. As imagens contendos os resultados são salvas no diretório "results".

### Bibliotecas
Para executar os experimentos serão necessárias as seguintes bibliotecas:
- pandas
- matplotlib
- sklearn
- seaborn