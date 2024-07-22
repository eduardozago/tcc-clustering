# TCC Clustering

Este repositório é referente ao Trabalho de Conclusão de Curso (TCC) do curso de Engenharia de Computação da Universidade Federal de Santa Catarina (UFSC), no qual consiste na elaboração de experimentos voltados a predição de acadêmicos em situação de risco baseados em suas interações no Ambiente Virtual de Aprendizagem (AVA) Moodle. Neste trabalho são considerados a contagem de interações diárias dos alunos com o ambiente para a realização de experimentos utilizando o método de aprendizagem de máquina não-supervisionado, clustering (agrupamento).

Assim, foram considerados registros de 12 disciplinas cursadas na Universidade Federal de Santa Catarina (UFSC) entre os anos de 2018 à 2023, com um total de 103 estudantes num período de 20 semanas. Além disso, também foram consideradas as notas finais dos alunos na disciplina para verificar os experimentos.

As etapas do trabalho ocorrem conforme mostra a imagem abaixo.
![](https://github.com/eduardozago/tcc-clustering/blob/main/method.png)

Iniciando com a coleta de dados é gerado o dataset, seguido pelo pré-processamento, para então determinar o número ideal de clusters como o Método Elbow para o conjunto de dados e por fim realizado o agrupamento com o algoritmo K-means. Além disso, foram analisados os resultados dos grupos gerados em relação as notas finais dos alunos para verificar os experimentos.