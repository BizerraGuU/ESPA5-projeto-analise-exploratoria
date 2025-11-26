# 📊 Projeto – Análise Exploratória de Dados

IFSP – TADS – ESPA5 (Estatística e Probabilidade)
Professora: Profa. Dra. Josceli Maria Tenorio
Turma: Quinta-feira

## 🧩 Descrição Geral

Repositório criado para o Projeto da disciplina ESPA5, ministrada pela Profa. Dra Josceli Maria Tenorio, como critério de avaliação da disciplina.

O objetivo do projeto é realizar análises estatísticas e probabilísticas sobre dois conjuntos de dados em formato CSV, utilizando a linguagem Python e as bibliotecas vistas em aula (como pandas, matplotlib, seaborn, numpy e scipy).

## 🧠 Objetivo do Projeto

1. Desenvolver uma análise exploratória de dados (EDA) a partir de dois arquivos CSV.

Os arquivos CSV escolhidos foram:

| Nome do Dataset                    | Link para acesso                                                                                                                       |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Motor Vehicle Collisions - Crashes | [https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes](https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes) |
| Electric Vehicle Population Data   | [https://catalog.data.gov/dataset/electric-vehicle-population-data](https://catalog.data.gov/dataset/electric-vehicle-population-data) |

> ***OBS: Os datasets foram salvos em uma pasta no drive, dado que o tamanho deles impossibilitava subí-los no repositório GitHub***

2. Produzir um relatório em PDF explicando o processo analítico e incluindo gráficos, medidas estatísticas e testes de hipótese.

## 📦 Uso do Git LFS (Large File Storage)

Este projeto utiliza **Git LFS** para versionamento de arquivos grandes, como datasets CSV que ultrapassam o limite padrão do GitHub.

### 🔧 Como configurar o Git LFS no seu ambiente

1. Instale o Git LFS (caso ainda não tenha):

```bash
git lfs install
```

2. Configure o rastreamento para arquivos CSV (ou outros formatos necessários):

```bash
git lfs track "archives/*"
```

3. Confirme a criação/atualização do arquivo `.gitattributes`:

```bash
cat .gitattributes
```

Ele deve conter algo como:

```
archives/* filter=lfs diff=lfs merge=lfs -text
```

4. Adicione, faça commit e envie normalmente:

```bash
git add .
git commit -m "Adicionando arquivos grandes com Git LFS"
git push
```

## 👥 Grupo

| Nome                             | Prontuário |
| -------------------------------- | ---------- |
| Gustavo Bezerra de Andrade       | SP313475X  |
| Jefferson Bispo de Lima de Jesus | SP3139328  |
| Seung Jin Jicá Casierra          | SP3134229  |
| Vitor Augusto dos Santos         | SP3132048  |
