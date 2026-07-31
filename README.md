# Importando Dados
Extração de dados de diferentes origens.

## Trabalhando com arquivos .CSV (arquivos de texto com separação de valores por vírgulas)

 ### Baixando Bibliotecas
 
```import pandas as pd```

 ### Importando dados de forma off-line

```tabela = pd.read_csv(filepath_or_buffer = "NOME DA PASTA/NOME DO ARQUIVO")```

 ### Importando dados de forma on-line

```tabela = pd.read_csv(filepath_or_buffer = "Link da URL")```

 ### Importando dados e ajeitando separadores

```tabela = pd.read_csv(filepath_or_buffer = "NOME DA PASTA/NOME DO ARQUIVO", sep = ";", decimal = ",")```

 ### Importando dados com codificações diferentes

```tabela = pd.read_csv(filepath_or_buffer = "NOME DA PASTA/NOME DO ARQUIVO, sep = ";", encoding = "latin_1")```

## Trabalhando com arquivos Excel (.xls/.xlsx)

### Baixando Biblioteca

```import pandas as pd```

### Importando dados de forma offline

```tabela = pd.read_excel(io = "NOME DA PASTA/NOME DO ARQUIVO")```

### Importando dados de forma online

```tabela = pd.read_excel(io = "Link da URL")```

