



# hackathon-MS-Azure

## Equipe

<a href="https://github.com/rockiir/hackathon-MS-Azure/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=rockiir/hackathon-MS-Azure" />
</a>

Made with [contributors-img](https://contrib.rocks).

## Exercício proposto

#### Desafio 1 - (3 pontos) Existe alguma correlação entre as notas das provas objetivas? Comente.

#### Tarefa

Quem é bom em matemática, também vai bem em ciências da natureza? Nesse problema, você selecionará os campos da prova objetiva:

NU_NOTA_CN Nota da prova de Ciências da Natureza NU_NOTA_CH Nota da prova de Ciências Humanas NU_NOTA_LC Nota da prova de Linguagens e Códigos NU_NOTA_MT Nota da prova de Matemática

Você deverá realizar uma análise de regressão para descobrir se é possível prever a nota da prova de Ciências da Natureza caso se saiba a nota de outra.

### Passo 1 - Criar grupo de recursos



![](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/1-Criando%20grupo%20de%20recursos.jpg)

### Passo 2-  Criando uma instancia de computação
Logo após criar o grupo de execussões fora criada a intância de computação com a unidade de processamento CPU e a Maquina virtual Standard_DS11_v2

![Criando uma instancia de computação](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/2-Criando%20uma%20instancia%20de%20computa%C3%A7%C3%A3o.png)

### Passo 3 -  Criação de um cluster de calculo
Em seguida criamos o cluster de cálculo com unidade de processamento em CPU e novamente maquina virtual Standard_DS11_v2

![Criação de um cluster de calculo](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/3%20-%20Cria%C3%A7%C3%A3o%20de%20um%20cluster%20de%20calculo.png)

### Passo 4 -  Criação de um pipeline
Com os clusters prontos seguimos para a criação de pipeline

![Criação de um pipeline](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/4%20-Cria%C3%A7%C3%A3o%20de%20um%20pipeline.png)

### Passo 5 -Criação de um conjunto de dados 
Mas antes disso não podemos esquecer do conjunto de dados, que se revelou o maior desafio de todo o projeto, pois o conjunto de dados do enem 2019 era muito grande, então tivemos repetidos problemas ao fazer upload do arquivo e ao analisá-los.


![-Criação de um conjunto de dados](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/5-%20Cria%C3%A7%C3%A3o%20de%20um%20conjunto%20de%20dados.png)

Detalhes

![Detalhes](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/5.2-%20Detalhes.png)



![Detalhes](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/5.3-%20Detalhes.png)

5.4 - Selecionando as colunas com notas

![Selecionando as colunas com notas](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/5.4-%20Selecionando%20as%20colunas%20com%20notas.png)

### Passo 6 - Selecionando as colunas

![Selecionando as colunas](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/6.2-Selecionando%20as%20colunas.png) 

Limpando dados

![Limpando dados](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/6.3-%20Limpando%20dados.png)

Normalizando dados (MinMax)

![image-20210618205441431](C:\Users\Raquel de matos\Documents\github\hackathon-MS-Azure\image-20210618205441431.png)



### Passo 7 -  Pipeline parte1 completo

![Pipeline parte1 completo](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/7-%20Pipeline%20parte1%20completo.png)

![]()

### Passo 8 -Avaliando o modelo

![Avaliando o modelo](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/15-%20Avaliando%20o%20modelo.jpg)

### Passo 9 -Resultados parciais obtidos

![Resultados parciais obtidos](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/15.1-Resultados%20parciais%20obtidos.jpg)

### Passo 10  -- Pipeline de Inferencia sem alterações

![Pipeline de Inferencia sem alterações](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/17-%20Pipeline%20de%20Inferencia%20sem%20altera%C3%A7%C3%B5es.jpg)

### Passo 11 -dados CSV

![dados CSV](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/18-%20dados%20CSV.jpg)

### Passo 12 - script Python

![script Python](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/22-%20script%20Python.jpg)

### Passo 13 - Pipeline de inferencia_finalizado

![Pipeline de inferencia_finalizado](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/23-%20Pipeline%20de%20inferencia_finalizado.jpg)

### Passo 14 - resultado continuação

![resultado continuação](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/24.1-%20resultado%20continua%C3%A7%C3%A3o.jpg)

24.2- resultado continuação

![resultado continuação](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/24.2-%20resultado%20continua%C3%A7%C3%A3o.jpg)

24.3-resultado continuação

![resultado continuação](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/24.3-resultado%20continua%C3%A7%C3%A3o.jpg)

24-resultado

![resultado](https://github.com/rockiir/hackathon-MS-Azure/blob/main/images/24-resultado.jpg)
