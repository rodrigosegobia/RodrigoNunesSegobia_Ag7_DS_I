# 💧 Classificador de Consumo de Água

![Python](https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?style=for-the-badge&logo=github&logoColor=white)
![Agenda 7](https://img.shields.io/badge/Agenda-7-0A66C2?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-2EA44F?style=for-the-badge)
![Água](https://img.shields.io/badge/Consumo-Água-00AEEF?style=for-the-badge)

## 📌 Sobre o projeto

Este projeto foi desenvolvido para a **Agenda 7 de Desenvolvimento de Sistemas I**.

A proposta é simular um sistema simples de uma companhia de saneamento. O programa recebe o tipo de imóvel e o consumo mensal de água e, a partir dessas informações, apresenta uma classificação com uma orientação ao morador.

O exercício trabalha principalmente com **estruturas de decisão** e com os operadores lógicos `and` e `or` em Python.

## 🧠 Regras utilizadas

O programa segue as regras propostas na atividade:

- Imóvel **comercial** recebe a informação sobre tarifa comercial.
- **Apartamento** com consumo abaixo de **10 m³** é classificado como consumo econômico.
- **Apartamento**, ou **casa** com consumo de até **25 m³**, recebe a classificação de consumo moderado.
- Nos demais casos, o programa informa consumo excessivo e recomenda economia de água.

## 🐍 Linguagem

O projeto foi feito em **Python 3**, utilizando entrada de dados com `input()`, conversão para `float` e estruturas condicionais com `if`, `elif` e `else`.

## ▶️ Como executar

1. Tenha o Python 3 instalado no computador.
2. Baixe ou clone este repositório.
3. Abra a pasta do projeto no VS Code.
4. Entre na pasta `consumo-agua`.
5. Execute o arquivo `app.py`.

Pelo terminal:

```bash
cd consumo-agua
python app.py
```

Depois, informe o tipo de imóvel e o consumo mensal de água quando o programa solicitar.

## 💻 Exemplo de uso

```text
Digite o tipo de imóvel (comercial, casa ou apartamento): apartamento
Digite o consumo mensal de água em m³: 8.5

Consumo econômico – excelente controle de água!
```

## 📁 Estrutura do repositório

```text
RodrigoNunesSegobia_Ag7_DS_I/
├── README.md
└── consumo-agua/
    └── app.py
```

## 👨‍💻 Autor

**Rodrigo Nunes Segobia**

Atividade desenvolvida para a disciplina **Desenvolvimento de Sistemas I** do curso Técnico em Desenvolvimento de Sistemas.