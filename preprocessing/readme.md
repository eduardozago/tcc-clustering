# Pre Processing

Os arquivos de pré-processamento são utilizadas para preparar o dataset gerado para os experimentos de clustering. Nesta etapa são considerados combinações entre as interações no dataset gerado. Sendo assim, são considerados 3 pré-processamentos:
- **P1:** Soma total de interações no período
- **P2:** Soma total de dias sem interações no período
- **P3:** Máxima quantidade de dias sem interações no período

O resultado será salvo em um arquivo ".csv" na pasta "preprocessing-results".

### Bibliotecas
Para executar o pré-processamento serão necessárias as seguintes bibliotecas:
- os
- glob
- datetime
- pandas