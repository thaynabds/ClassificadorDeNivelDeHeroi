# Classificador de Nível de Herói 🦸‍♂️

Projeto simples em Python que classifica o nível de um herói com base na sua quantidade de experiência (XP).

## 🎯 Objetivo

Criar um programa que:
- Recebe o **nome** do herói
- Recebe a quantidade de **XP**
- Classifica o herói em um **nível** de acordo com a tabela abaixo
- Exibe a mensagem com o resultado

## 📊 Tabela de Classificação

| XP                           | Nível       |
|------------------------------|-------------|
| Menor que 1.000              | Ferro       |
| 1.001 – 2.000               | Bronze      |
| 2.001 – 5.000               | Prata       |
| 5.001 – 7.000               | Ouro        |
| 7.001 – 8.000               | Platina     |
| 8.001 – 9.000               | Ascendente  |
| 9.001 – 10.000              | Imortal     |
| Maior ou igual a 10.001     | Radiante    |

## 🧠 Lógica Utilizada

- Variáveis
- Entrada de dados
- Estruturas condicionais (`if`, `elif`, `else`)
- Exibição formatada

## 💻 Código

```python
nome = input("Digite o nome do herói: ")
xp = int(input("Digite a quantidade de experiência (XP) do herói: "))

if xp < 1000:
    nivel = "Ferro"
elif 1001 <= xp <= 2000:
    nivel = "Bronze"
elif 2001 <= xp <= 5000:
    nivel = "Prata"
elif 5001 <= xp <= 7000:
    nivel = "Ouro"
elif 7001 <= xp <= 8000:
    nivel = "Platina"
elif 8001 <= xp <= 9000:
    nivel = "Ascendente"
elif 9001 <= xp <= 10000:
    nivel = "Imortal"
else:
    nivel = "Radiante"

print(f"O Herói de nome {nome} está no nível de {nivel}")
```

## ▶️ Exemplo de Execução

```
Digite o nome do herói: Arthur
Digite a quantidade de experiência (XP) do herói: 7500
O Herói de nome Arthur está no nível de Platina
```

## 📌 Como usar

1. Copie o código
2. Cole em um arquivo `.py`
3. Execute com Python 3

---

Projeto desenvolvido como parte do desafio da DIO.
