#  MGPEB - Sistema de Gerenciamento de Pouso em Marte

##  Descrição do Projeto
Este projeto simula um **Módulo de Gerenciamento de Pouso e Estabilização de Base (MGPEB)**, responsável por controlar a chegada e autorização de pouso de módulos em uma missão espacial.

O sistema considera fatores como:
- Prioridade de pouso
- Nível de combustível
- Tipo de carga
- Ordem de chegada

Além disso, aplica **estruturas de dados clássicas** e **algoritmos fundamentais** para tomada de decisão.

---

## Objetivo
Aplicar conceitos de:
- Estruturas lineares (Fila, Pilha, Lista Encadeada)
- Algoritmos de busca
- Algoritmos de ordenação
- Lógica condicional

Tudo isso em um cenário prático inspirado em engenharia aeroespacial.

---

##  Estruturas de Dados Utilizadas

### Fila (FIFO)
Responsável por organizar a ordem de pouso dos módulos.

### Pilha (LIFO)
Simula o histórico ou ordem reversa de eventos (último a entrar, primeiro a sair).

### Lista Encadeada
Representa a ordem de chegada em órbita dos módulos.

---

## Algoritmos Implementados

###  Busca
- Menor nível de combustível
- Maior prioridade
- Busca por tipo de carga

### Ordenação
- **Selection Sort** para ordenar módulos por prioridade

---

## Lógica de Decisão

O sistema define três estados:

- **Pouso Imediato** → prioridade muito alta  
- **Pouso Urgente** → combustível baixo  
- **Aguardar** → condições normais  

---

## Tecnologias Utilizadas
- Python 3
- Estruturas nativas (listas)
- Enum
- Programação orientada a objetos (básica)

---

## 📊 Possíveis Melhorias
- Uso de `deque` para otimização da fila (O(1))
- Integração com dados em tempo real (simulação)
- Interface gráfica
- Persistência de dados

---

## Autoria
Mayara Luisa Vicente Rosa
Gabriel Coutinho Barcelos
Gabriel Luis de Lima Ramos
Lisandra Araújo
Yury Alexander Tavares
