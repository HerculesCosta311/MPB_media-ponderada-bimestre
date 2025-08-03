# MPB_media-ponderada-bimestre
Calculadora de média ponderada para alunos com base em provas bimestrais. Projeto pensado para ajudar professores a organizar notas de forma simples.

# 📘 Calculadora de Média Ponderada (5 Provas)

Este projeto é uma calculadora simples desenvolvida em Python que simula o cálculo da média final de um aluno com base em **5 provas**, cada uma com 5 questões e peso fixo. A ideia surgiu pensando na minha mãe, que é professora, como uma forma de ajudar a organizar e visualizar melhor o desempenho dos alunos.

---

## ✨ Funcionalidades

- Recebe o **nome e sobrenome do aluno**
- Permite o cadastro de **vários alunos**
- Coleta os **acertos de cada uma das 5 provas**
- Calcula:
  - A **nota final** com base em pesos fixos
  - O **aproveitamento (%)**
  - A **situação final** (aprovado ou reprovado)
- Mostra um resumo com os dados de todos os alunos

---

## 🧮 Como funciona o cálculo?

- Cada prova tem **5 questões** e vale **2 pontos**
- Cada acerto vale **0.4 pontos** → 5 acertos = 2.0 pontos
- A nota final é a **soma das notas das 5 provas**, com máximo de **10 pontos**
- O aluno precisa de **mínimo 6 pontos** para ser aprovado
- Aproveitamento é calculado com base no total de acertos sobre 25 questões

---

## 🛠️ Como usar

1. Certifique-se de ter o Python instalado em sua máquina (ou use um ambiente online como o Google Colab).
2. Este projeto ainda está **em desenvolvimento**, mas já pode ser **testado normalmente**.
3. Execute o arquivo `.ipynb` em um ambiente como **Google Colab** ou **Jupyter Notebook** para interagir com o código e ver os resultados.
4. Siga as instruções exibidas no terminal ou na célula do notebook.

---

## 💡 Exemplo de uso

```bash
Quantos alunos deseja cadastrar? 2

=== Cadastro do Aluno 1 ===
Nome do Aluno: Ana
Sobrenome do Aluno: Silva
Prova 1 - Acertos: 5
Prova 2 - Acertos: 4
...

--- Resultado Final ---
Aluno: Ana Silva
Nota Final: 8.40 / 10.00
Aproveitamento: 88.00%
Situação: Aprovado
````

---

## ❤️ Motivação

> Fiz esse projeto pensando na minha mãe, que é professora. Quis criar uma ferramenta simples, mas funcional, que ajudasse a visualizar o desempenho dos alunos de forma objetiva.

---

## 📂 Estrutura do Projeto

```
calculadora-media/
├── calculadora_de_média_ponderada_(5_provas).ipynb
├── calculadora_de_média_ponderada_(5_provas).py
└── README.md
```

---

## 📌 Tecnologias utilizadas

* Python 3
* Estruturas de dados: listas e dicionários
* Laços, condicionais, e formatação com `f-strings`
* Entrada e saída via `input()` e `print()`

---

## 📈 Possíveis melhorias futuras

* Exportar os resultados para Excel (`.xlsx`)
* Interface gráfica com Tkinter ou PyQt
* Integração com formulários web
* Validação de dados mais avançada

---

## 🧑‍💻 Autor

**HerculesCosta**

Se quiser conversar, colaborar ou sugerir algo, fique à vontade para entrar em contato ou abrir uma issue aqui no repositório.

---

```
