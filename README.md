# Análise de Algoritmos de Ordenação com Implementação de Novas Estruturas de Dados

Este projeto tem como objetivo analisar a execução de algoritmos de ordenação a partir de uma base de dados com mais de 600 mil linhas, onde cada linha representa informações sobre as senhas mais utilizadas no mundo.
Para melhorar a eficiência e a organização do código, foram implementadas novas estruturas de dados, além do array que era exclusivamente exigido anteriormente. Essas novas estruturas foram introduzidas com o intuito de aprimorar a execução dos algoritmos de ordenação e otimizar outras partes do código, visando uma melhor performance geral do projeto.

## Conteúdo

- [Informações Adicionais](#informações-adicionais)
- [Como Executar](#como-executar)
- [Pré-requisitos](#pré-requisitos)
- [Instruções de Execução](#instruções-de-execução)
- [Saída Esperada](#saida-esperada)

## Informações Adicionais

O intuito desse projeto é fazer as ordenações e análises a partir do arquivo "passwords_formated_data.csv" que será criado, no entanto, levaria muito tempo para que ao executar você tivesse algum resultado breve, portanto,
construi um novo arquivo intitulado "passwords_test.csv" que contém partes aleatórias do arquivo principal, dessa forma, o retorno da execução desse código levará poucos minutos.

Caso queira utilizar o arquivo principal, siga os passos abaixo:
- Navegue até src
- Vá ate a pasta services
- Abra o arquivo GetVariables.java
- Localize o método readDataToArray
- Altere o campo que possue uma string representando o "filename" para "dataset/passwords_formated_data.csv"

## Como Executar

Siga as instruções abaixo para executar o projeto na sua máquina, seja utilizando MacOs ou Windows.

### Pré-requisitos

- JDK (Java Development Kit) instalado na sua máquina
- IntelliJ IDEA ou qualquer IDE Java de sua preferência

### Instruções de Execução

1. Clone este repositório:

```bash
git clone https://github.com/LucasProg-FS/Projeto1LedaPasswords.git
````

2. Abra o projeto na sua IDE Java (IntelliJ IDEA, Eclipse, etc.).
3. Execute a classe Main.

## Saída Esperada

Após a execução da classe Main, será criado alguns arquivos formatados do "passwords.csv", em seguida, será mostrado todos os arquivos .csv para cada algoritmo, bem como para cada caso desse algoritmo, o qual foram criados logo após a ordenação, além disso o console mostrará o tempo que levou para cada execução.
