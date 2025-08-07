# Bootcamp Santander 2025 - Back-End com Java

## Projeto: Processo Seletivo

Este projeto simula um **processo seletivo** para uma vaga de emprego, utilizando conceitos básicos de Java como:

- Estruturas de controle (if, while, do-while, for, for-each)
- Métodos
- Arrays
- Geração de números aleatórios

### 📌 Objetivo

Treinar a lógica de programação com Java por meio da simulação de etapas de um processo seletivo: análise de salário, seleção, contato com os candidatos, entre outros.

---

### 📂 Estrutura do Código

O código está organizado em uma única classe: `ProcessoSeletivo`.

#### 🔹 Métodos principais

- `main(String[] args)`:  
  Executa o método `entrandoEmContato` para cada candidato.

- `entrandoEmContato(String candidato)`:  
  Simula até 3 tentativas de contato com o candidato. Usa o método `atender()` para simular se o candidato atendeu ou não.

- `atender()`:  
  Retorna aleatoriamente `true` ou `false` simulando a chance do candidato atender uma ligação.

- `imprimirSelecionados()`:  
  Imprime a lista de candidatos selecionados com dois tipos de laços (`for` com índice e `for-each`).

- `selecaoCandidatos()`:  
  Avalia uma lista de candidatos simulando um processo de análise salarial. Seleciona até 5 candidatos com salário pretendido dentro do orçamento.

- `valorPretendido()`:  
  Gera aleatoriamente um valor de salário entre R$1800 e R$2200.

- `analisarCandidato(double salarioPretendido)`:  
  Analisa se o salário pretendido é viável para contato, contra proposta ou rejeição.

---

### 🛠️ Tecnologias Utilizadas

- Java 17+
- IDE recomendada: IntelliJ IDEA ou Eclipse
- Terminal/Console para execução

---

### ✅ Como Executar

1. Clone o repositório ou copie o código.
2. Abra em sua IDE Java preferida.
3. Execute a classe `ProcessoSeletivo`.
4. Observe os resultados no console simulando o processo seletivo.

---

### ✍️ Autor

Projeto desenvolvido como parte do **Bootcamp Santander 2025 - Back-End com Java** da [DIO.me](https://www.dio.me/).

---


