```
import pandas as pd
# carregando o arquivo Excel
df = pd.read_excel("base_notas.xlsx")

# calculando a média das notas e adicionado uma coluna 'média'
df['média'] = df [['Nota1','Nota2','Nota3','Nota4']].mean(axis=1)

# salvando em um novo arquivo Excel
df.to_excel('nota_aluno.xlsx', index=false)
```

```
import pandas as pd
```

Este trecho do código importa uma extensão para o python que fornece ferramentas 
com grande poder para manipulação e análise de dados, de maneira simples 
e eficiente, conferindo alta performance aos códigos.

```
df = pd.read_excel("base_notas.xlsx")
```
Aqui neste trecho ele está lendo os dados do arquivo Excel.

```
df['média'] = df [['Nota1','Nota2','Nota3','Nota4']].mean(axis=1)
```
Neste trecho ele está calculando a média e adiconando a coluna média.

```
df.to_excel('nota_aluno.xlsx', index=false)
```
Neste trecho o codigo está salvando os dados em um novo arquivo.




