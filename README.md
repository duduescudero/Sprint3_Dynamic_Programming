# Dynamic Programming - Controle de Consumo de Insumos

## 👨‍💻 Integrantes
- Arthur Felipe - RM: 553320  
- Eduardo Pires - RM: 556527  
- Luca Monteiro - RM: 556906  
- Leonardo Munhoz - RM: 556824  
- Davi Vieira - RM: 556798  

---

## 🎯 Objetivo
Este projeto tem como objetivo **simular o consumo diário de insumos hospitalares** 
(reagentes e materiais descartáveis), utilizando **estruturas de dados e algoritmos clássicos** 
para organizar e analisar as informações de forma eficiente.

O desafio principal é a **baixa visibilidade no controle de estoque**, que pode resultar em:
- Falta de insumos essenciais
- Excesso de materiais
- Dificuldade no planejamento de reposição
- Aumento de custos e redução de eficiência operacional

---

## 🛠️ Estruturas e Algoritmos Utilizados

### 1. Fila (Queue)
- Implementada para registrar o consumo em ordem **cronológica**.
- Permite visualizar o histórico de uso de insumos de forma sequencial.

### 2. Pilha (Stack)
- Implementada para consultas em ordem **inversa** (últimos consumos primeiro).
- Útil para verificar rapidamente os insumos mais recentemente consumidos.

### 3. Estruturas de Busca
- **Busca Sequencial**: percorre a lista para localizar determinado insumo.
- **Busca Binária**: aplicada em listas ordenadas para localizar insumos de forma mais eficiente.

### 4. Algoritmos de Ordenação
- **Merge Sort** e **Quick Sort** foram implementados para organizar os insumos:
  - Por quantidade consumida
  - Ou por validade (se aplicável)

### 5. Relatório
- Consolida os resultados e explica como cada estrutura e algoritmo 
  contribuem para melhorar o controle de estoque.

---

## 🚀 Conclusão
Com o uso de estruturas de dados clássicas, foi possível:
- Melhorar a **precisão do registro de consumo**  
- Facilitar a **previsão de reposição**  
- Reduzir falhas manuais no controle  
- Aumentar a **eficiência operacional** nas unidades de diagnóstico  

---

## 📂 Como Executar
Este projeto foi desenvolvido para rodar no **Google Colab**:
1. Abra o notebook no Colab.  
2. Execute as células em sequência.  
3. Veja os resultados das filas, pilhas, buscas, ordenações e relatório.  

---
