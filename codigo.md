# código e explicação :


## Codigo médias 
```
nota1 = float (input("Digite o valor da primeira nota"))
nota2 = float (input("Digite o valor da segunda nota"))
nota3 = float (input("Digite o valor da terceira nota"))
nota4 = float (input("Digite o valor da quarta nota"))

media = int(nota1+nota2+nota3+nota4)/4

print(f"o aluno : {nome} sua media foi de :{media}")
```

>Este código esta calculando médias de notas em python

este código possui ligação direta com o código abaixo

---


## Codigo :

```
import pandas as pd
df = pd.read_excel("base.xlsx") 
df['Average'] = df[['Grade1', 'Grade2', 'Grade3']].mean(axis=1)
df.to_excel('grade_student.xlsx', index=False)
```



---


# explicação :
import pandas as pd: Isso importa a biblioteca Pandas e a renomeia como pd para facilitar a referência a ela no código.

---

## df = pd.read_excel("base.xlsx"):
Essa linha carrega os dados de um arquivo Excel chamado "base.xlsx" para um DataFrame do Pandas, 
que é basicamente uma estrutura de dados tabular semelhante a uma planilha do Excel. O DataFrame é atribuído à variável df.

---

## df['Average'] = df[['Grade1', 'Grade2', 'Grade3']].mean(axis=1): 

Aqui, está sendo calculada uma nova coluna chamada 'Average' (média) no DataFrame df. Essa coluna recebe a média das colunas 
'Grade1', 'Grade2' e 'Grade3'. df[['Grade1', 'Grade2', 'Grade3']] seleciona as colunas específicas do DataFrame e .mean(axis=1) 
calcula a média ao longo das linhas (ou seja, para cada linha, é calculada a média das notas nas colunas 'Grade1', 'Grade2' e 'Grade3').

---

## df.to_excel('grade_student.xlsx', index=False):
Por fim, essa linha salva o DataFrame atualizado no arquivo Excel
'grade_student.xlsx'. O parâmetro index=False indica que não queremos salvar o índice do DataFrame como uma coluna no arquivo Excel.
