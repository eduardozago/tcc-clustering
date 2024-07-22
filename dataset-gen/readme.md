# Dataset Generator
O gerador do dataset carrega os arquivos do tipo ".csv" contendo os registros de atividades dos alunos e irá organizar em uma tabela com os alunos e suas interações diárias no período. O arquivo responsável por gerar o dataset é o "anonymize-datasets.ipynb" e o dataset gerado é salvo em um arquivo ".csv". 

### Bibliotecas
Para executar o gerador serão necessárias as seguintes bibliotecas:
- os
- uuid
- datetime
- pandas
- numpy

## Utilização
O Dataset pode ser gerados através de semanas ou dias, onde são determinados no uso da função "process_dfs". 
```sh
process_dfs(df_list, weeks_to_keep, truncate_to_week=False)
```
Cada parâmetro é detalhado a seguir.

- df_list: lista com o nome dos arquivos a serem carregados
- weeks_to_keep: quantidade de semanas consideradas
- truncate_to_week: separar por semanas (True) ou dias (False)