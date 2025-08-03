# GradeHelper_MPB_media-ponderada-bimestre
Calculadora de média ponderada para alunos com base em Tarefas bimestrais. Projeto pensado para ajudar professores a organizar notas de forma simples.

# 📘 Calculadora de Média Ponderada (5 Provas)

Este projeto é uma calculadora simples desenvolvida em Python que simula o cálculo da média final de um aluno com baseado nas tarefas que foram aplicadas no bimestre (provas, trabalhos, etc.). A ideia surgiu pensando na minha mãe, que é professora, como uma forma de ajudar a organizar e visualizar melhor o desempenho dos alunos. Ela tem bastante trabalho de ficar montando planilhas e ficar anotando nome por nome de aluno, nota por nota, sala por sala, para depois lançar essas notas no sistema publico do governo que é bem lento.

---

✨ Funcionalidades
Recebe o nome e sobrenome do aluno

Permite o cadastro de vários alunos

Permite que o professor:

Defina quantas tarefas foram aplicadas no bimestre

Atribua um nome, peso e número de questões para cada tarefa

Coleta os acertos de cada aluno em cada tarefa

Calcula automaticamente:

A nota proporcional de cada tarefa

A nota final (soma ponderada das tarefas)

O aproveitamento (%) com base no total de questões

A situação final (Aprovado ou Reprovado)

Mostra um resumo completo com todos os dados dos alunos cadastrados

---

## 🧮 Como funciona o cálculo?

* Você define **quantas tarefas foram aplicadas** no bimestre (provas, trabalhos, etc.)
* Cada tarefa recebe um **nome**, um **peso** (valor da nota) e uma **quantidade de questões**
* O professor informa **quantos acertos** o aluno teve em cada tarefa
* A **nota de cada tarefa** é calculada proporcionalmente:
  `nota = (acertos / total de questões) * peso`
* A **nota final** do aluno é a **soma das notas das tarefas**
* O aluno precisa de **mínimo 6 pontos** (em um total definido pelos pesos) para ser aprovado
* O **aproveitamento (%)** é baseado no total de acertos sobre o total de questões de todas as tarefas

---

## 🛠️ Como usar

1. Certifique-se de ter o Python instalado em sua máquina (ou use um ambiente online como o Google Colab).
2. Este projeto ainda está **em desenvolvimento**, mas já pode ser **testado normalmente**.
3. Execute o arquivo `Grade_Helper_MPB.ipynb` em um ambiente como **Google Colab** ou **Jupyter Notebook** para interagir com o código e ver os resultados.
4. Siga as instruções exibidas no terminal ou na célula do notebook.

---

## 💡 Exemplo de uso

```bash
Quantas tarefas foram aplicadas no bimestre? 3
Nome da tarefa 1: Prova
Peso da tarefa 'Prova': 10.0
Quantas questões teve a tarefa 'Prova'? 10
Nome da tarefa 2: Redação
Peso da tarefa 'Redação': 1.0
Quantas questões teve a tarefa 'Redação'? 1
Nome da tarefa 3: Trabalho
Peso da tarefa 'Trabalho': 10
Quantas questões teve a tarefa 'Trabalho'? 1
Quantos alunos deseja cadastrar? 1

=== Cadastro do Aluno 1 ===
Nome do Aluno: Jhonatam
Sobrenome do Aluno: Santos Macumba
Acertos na tarefa 'Prova' (máximo 10): 5
Acertos na tarefa 'Redação' (máximo 1): 0.5
Acertos na tarefa 'Trabalho' (máximo 1): 0.2

=== RESULTADOS FINAIS ===

Aluno: Jhonatam Santos Macumba
  - Prova: 5.0/10 acertos | Peso: 10.0 | Nota: 5.0
  - Redação: 0.5/1 acertos | Peso: 1.0 | Nota: 0.5
  - Trabalho: 0.2/1 acertos | Peso: 10.0 | Nota: 2.0
Nota Final: 7.5 / 21.0
Aproveitamento: 47.5%
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
├── Grade_Helper_MPB.ipynb
├── grade_helper_mpb.py
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
