# 🧩 Desafio Técnico — Desenvolvedor Python (Júnior/Pleno)

## 📌 Contexto

Você foi contratado para desenvolver um sistema simples de linha de comando (CLI) para ajudar usuários a **monitorar e manter hábitos diários**.

O sistema deve ser desenvolvido em **Python puro**, sem uso de frameworks externos.

---

## 🎯 Objetivo

Construir um sistema funcional que permita:

* Cadastro de hábitos
* Registro de progresso diário
* Visualização de dados
* Controle de fluxo de execução
* Manipulação de dados com diferentes tipos

---

# 📦 Requisitos Funcionais

## 1. Cadastro de hábitos

O sistema deve permitir que o usuário:

* Informe o nome do hábito
* Defina uma meta (quantidade por período)
* Defina se o hábito está ativo (`True` ou `False`)

---

## 2. Entrada e saída de dados

* Todas as interações devem ocorrer via terminal
* Utilize entrada do usuário (`input`)
* Exiba informações formatadas (`print`, f-strings)

---

## 3. Validação de dados

O sistema deve validar:

* Tipos de dados corretos (ex: número inteiro para metas)
* Valores inválidos (ex: números negativos)
* Entradas vazias

---

## 4. Controle de fluxo

O sistema deve conter um **menu interativo**, com opções como:

* Criar hábito
* Listar hábitos
* Registrar progresso
* Sair

A navegação deve ser feita utilizando estruturas de decisão (`if`, `elif`, `else`).

---

## 5. Estruturas de repetição

* O sistema deve permanecer em execução até o usuário escolher sair
* Utilize `while` para manter o programa ativo
* Utilize `for` para percorrer coleções de dados

---

## 6. Manipulação de dados

Você deve utilizar:

* Listas (`list`)
* Dicionários (`dict`)
* Conjuntos (`set`), quando aplicável

---

## 7. Registro de progresso

O usuário deve poder:

* Marcar um hábito como concluído em um determinado dia
* Evitar duplicidade de registros no mesmo dia

---

## 8. Controle de execução

Utilize:

* `break` para encerrar o programa
* `continue` para pular iterações inválidas
* `pass` onde necessário

---

## 9. Conversão de tipos

O sistema deve converter corretamente entradas do usuário, como:

* `int()`
* `float()`
* `str()`

---

## 10. Comprehensions

Utilize:

* List comprehension
* Dict comprehension
* Set comprehension

Para manipulação e filtragem de dados

---

# ⚙️ Requisitos Técnicos

* Código organizado e legível
* Nomenclatura seguindo boas práticas (PEP 8)
* Uso correto de indentação
* Separação lógica de responsabilidades (quando possível)

---

# 🧪 Critérios de Avaliação

Você será avaliado com base em:

### ✔️ Domínio dos fundamentos

* Tipos de dados
* Conversão de tipos
* Entrada/saída

### ✔️ Lógica

* Uso correto de condicionais
* Uso correto de operadores

### ✔️ Controle de fluxo

* Uso adequado de loops
* Controle com `break`, `continue`, `pass`

### ✔️ Estruturas de dados

* Uso apropriado de listas, dicionários e conjuntos

### ✔️ Clareza do código

* Legibilidade
* Organização

---

# 🧩 Desafios Extras (Diferencial)

Caso queira se destacar, implemente:

* Cálculo de sequência de dias consecutivos (streak)
* Filtros de hábitos (ativos/inativos)
* Estatísticas simples (ex: total concluído)
* Menu mais robusto e amigável
* Tratamento de erros mais avançado

---

# 🚨 Restrições

* ❌ Não utilizar bibliotecas externas
* ❌ Não utilizar interface gráfica
* ❌ Não copiar soluções prontas

---

# 🧠 O que está sendo testado (sem te falar diretamente)

Este desafio foi desenhado para avaliar seu domínio de:

* Tipos (`int`, `float`, `str`, `bool`)
* Entrada/saída (`input`, `print`, f-strings)
* Conversão de tipos
* Condicionais (`if`, `elif`, `else`)
* Loops (`while`, `for`)
* Controle de fluxo (`break`, `continue`, `pass`)
* Estruturas (`list`, `dict`, `set`)
* Comprehensions

---

# 🏁 Entrega

Você deve entregar:

* Código funcional
* Executável via terminal
* Com instruções de uso (README opcional, mas recomendado)
