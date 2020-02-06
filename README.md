# Trabalho de Ordenação e Estatísticas de Ordem

## Técnicas de Programação Avançada - Bach. Sistemas de Informação
## Prof. Dr. Jefferson O. Andrade

## Ewerson Vieira Nascimento, Paulo Ricardo Viana e Willian Vaneli

### Conteúdo

A estrutura do conteúdo do presente trabalho está disposta da seguinte forma:
```
tpa-trab2
|_ codigo-fonte
   |_ data
   |_ notebook
   |_ output
   |_ src
|_ codigo-latex
   |_ images
   |_ main.tex
|_ relatorio.pdf
```

Dentro da pasta ```data```, em ```codigo-fonte```, foi onde optamos por deixar os arquivos .CSV fornecidos pelo professor para a execução dos testes deste trabalho. Para utilizar o arquivo [mainAuto.py](codigo-fonte/src/mainAuto.py) o usuário dispõe de duas opções: inserir os arquivos de entrada na pasta em questão ou alterar o código do arquivo para que a variável ```dataPath``` aponte para a pasta em que os arquivos .CSV estão presentes.

O diretório ```output``` contém o resultado dos testes realizados pelo grupo. Existe um arquivo para cada algoritmo, contendo os resultados dos testes em todos os arquivos de entrada, e um arquivo de nome ```tests_.csv``` que possui todos os resultados, de todos os algoritmos.

### Execução

Para executar os programas realizados neste trabalho, navegue até ```src``` dentro do diretório ```codigo-fonte``` e faça:
```bash
$ python3 main.py [nome-do-algoritmo] [nome-do-csv-entrada] [nome-do-csv-saida]
```

Exemplo:

```bash
$ python3 main.py quicksort data_25e2.csv qk_25e2.csv
```

Os nomes dos algoritmos e dos arquivos .CSV de entrada estão dispostos nas tabelas abaixo.

#### Algoritmos

| Algoritmo | Identificador |
|-----------|----------------------------------|
| Selection Sort | selectionsort |
| Insertion Sort | insertionsort |
| Merge Sort | mergesort |
| Quick Sort | quicksort |
| Heap Sort | heapsort |
| Intro Sort | introsort |
| Patience Sort | patiencesort |

#### Arquivos de entrada

| Nome | Nº de elementos |
|------|-----------------|
| data_10e0.csv | 10 |
| data_10e1.csv | 100 |
| data_10e2.csv | 1000 |
| data_10e3.csv | 10000 |
| data_10e4.csv | 100000 |
| data_10e5.csv | 1000000 |
| data_25e0.csv | 25 |
| data_25e1.csv | 250 |
| data_25e2.csv | 2500 |
| data_25e3.csv | 25000 |
| data_25e4.csv | 250000 |
| data_25e5.csv | 2500000 |
| data_50e0.csv | 50 |
| data_50e1.csv | 500 |
| data_50e2.csv | 5000 |
| data_50e3.csv | 50000 |
| data_50e4.csv | 500000 |
| data_50e5.csv | 5000000 |
| data_75e0.csv | 75 |
| data_75e1.csv | 750 |
| data_75e2.csv | 7500 |
| data_75e3.csv | 75000 |
| data_75e4.csv | 750000 |
| data_75e5.csv | 7500000 |