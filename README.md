![image](https://www.deviantart.com/wb51417/art/Wolverine---Transparent-4-851360042) # Sistema de Desconto Progressivo

## Sobre o projeto

Este projeto foi desenvolvido como atividade do curso para implementar um sistema de desconto progressivo para uma loja online.

O programa solicita ao usuário o valor total da compra, identifica a porcentagem de desconto de acordo com o valor informado e apresenta o valor do desconto e o valor final a pagar.

## Regras de desconto

| Valor da compra | Desconto |
|---|---:|
| Menor que R$ 200,00 | 5% |
| De R$ 200,00 até menor que R$ 300,00 | 10% |
| Maior ou igual a R$ 300,00 | 15% |

## Fórmula utilizada

O valor do desconto é calculado utilizando a seguinte fórmula:

**Valor do desconto = Valor da compra × Percentual de desconto**

Depois, o valor final é calculado:

**Valor final = Valor da compra − Valor do desconto**

### Exemplo

Para uma compra de R$ 250,00:

~~~text
Valor do desconto = 250 × 0,10
Valor do desconto = R$ 25,00

Valor final = 250 − 25
Valor final = R$ 225,00
~~~

## Como executar

### Pré-requisito

É necessário ter o Python 3.x instalado no computador.

### Execução pelo VS Code

1. Abra o projeto no Visual Studio Code.
2. Abra o arquivo `Pedro_Ag6_DS_I.py`.
3. Execute o programa pelo botão **Run/Executar** ou pelo terminal.
4. Informe o valor total da compra quando solicitado.
5. Confira o valor do desconto e o valor final da compra.

### Execução pelo terminal

No terminal, dentro da pasta do projeto, execute:

~~~bash
python Pedro_Ag6_DS_I.py
~~~

## Exemplos de teste

O programa pode ser testado utilizando diferentes valores de compra:

| Valor da compra | Desconto | Valor final |
|---|---:|---:|
| R$ 100,00 | R$ 5,00 | R$ 95,00 |
| R$ 250,00 | R$ 25,00 | R$ 225,00 |
| R$ 400,00 | R$ 60,00 | R$ 340,00 |

## Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)   
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-%23ffffff?style=for-the-badge&logo=markdown&logoColor=black)


## Conceitos utilizados

Neste projeto foram utilizados conceitos de:

- Entrada de dados com `input()`;
- Conversão de dados com `float()`;
- Estrutura de decisão `if`, `elif` e `else`;
- Operações matemáticas;
- Saída de dados com `print()`;
- Formatação de valores utilizando f-string.

## Autor

**Pedro das Virgens Moura Alves**

Projeto desenvolvido como atividade acadêmica da Agenda 06 - Desenvolvimento de Sistemas I.
