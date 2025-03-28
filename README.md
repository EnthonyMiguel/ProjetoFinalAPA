# Projeto Final APA - Otimização de Pousos e Decolagens em Aeroportos

## Descrição do Projeto
Este projeto visa desenvolver algoritmos para otimizar o escalonamento de pousos e decolagens em um aeroporto com múltiplas pistas, minimizando as penalidades por atrasos e respeitando restrições de segurança.

## Conhecimentos Necessários em Análise e Projeto de Algoritmos

### 1. Algoritmos Gulosos (Greedy Algorithms)
- **Aplicação**: Geração da solução inicial viável
- **Conceitos-chave**:
  - Seleção por critérios gananciosos (ex: ordenar por horário de liberação)
  - Análise de subestrutura ótima
  - Limitações de soluções gulosas

### 2. Busca Local e Vizinhança
- **Aplicação**: Implementação do VND (Variable Neighborhood Descent)
- **Conceitos-chave**:
  - Definição de espaços de vizinhança
  - Movimentos de troca, inserção e permutação
  - Critérios de parada

### 3. Metaheurísticas (Opcional)
- **Aplicação**: GRASP ou ILS para melhorar soluções
- **Conceitos-chave**:
  - Componentes estocásticos
  - Mecanismos de diversificação
  - Balanceamento entre intensificação e diversificação

### 4. Complexidade Computacional
- **Aplicação**: Análise de desempenho
- **Conceitos-chave**:
  - Notação Big-O
  - Análise de casos médios e piores
  - Trade-offs entre tempo e qualidade da solução

### 5. Estruturas de Dados
- **Aplicação**: Armazenamento e manipulação de dados
- **Conceitos-chave**:
  - Matrizes para tempos de espera
  - Listas para sequências de voos
  - Dicionários para mapeamento de voos

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Python 3.x ou Java (dependendo da implementação)
   - Bibliotecas: numpy, pandas (para Python)

2. **Execução**:
   ```bash
   python main.py <arquivo_entrada.txt> <arquivo_saida.txt>