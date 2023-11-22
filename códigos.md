```
import pandas as pd
# carregando o arquivo Excel
df = pd.read_excel("base_notas.xlsx")

# calculando a média das notas e adicionado uma coluna 'média'
df['média'] = df [['Nota1','Nota2','Nota3','Nota4']].mean(axis=1)

# salvando em um novo arquivo Excel
df.to_excel('nota_aluno.xlsx', index=false)
```
