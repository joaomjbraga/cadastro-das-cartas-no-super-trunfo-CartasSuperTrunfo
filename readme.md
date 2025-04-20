# 🃏 Super Trunfo - Países

Este projeto é uma atividade acadêmica do curso de Análise e Desenvolvimento de Sistemas da Universidade Estácio de Sá. Ele simula parte do jogo **Super Trunfo**, com foco no cadastro e comparação de cartas representando **cidades de diferentes estados** fictícios de um país.

## 📌 Objetivo

Desenvolver, em linguagem C, o sistema de cadastro e comparação de cartas com base em atributos das cidades. O projeto está dividido em três níveis de dificuldade: **Novato**, **Aventureiro** e **Mestre**.

---

## 🧩 Níveis do Projeto

### 🎮 Nível Novato: Cadastro Básico

- Cadastra **duas cartas** manualmente via terminal.
- Cada carta representa uma cidade e possui os atributos:
  - População (`int`)
  - Área (`float`)
  - PIB (`float`)
  - Número de pontos turísticos (`int`)
- A entrada é feita com `scanf` e a saída com `printf`.
- **Sem uso de laços ou condicionais.**

### ⚔️ Nível Aventureiro: Cálculo de Atributos

- Expande o nível Novato com o cálculo automático de:
  - **Densidade Populacional**: População / Área
  - **PIB per Capita**: PIB / População
- Os novos atributos são exibidos junto aos demais.
- **Continua sem laços ou condicionais.**

### 🏆 Nível Mestre: Comparação e Super Poder

- Implementa a comparação entre as duas cartas.
- Calcula o **Super Poder**:
  - Soma de todos os atributos, com a densidade populacional **invertida** (`1/densidade`).
- Comparações:
  - **Maior valor vence**, exceto para Densidade Populacional (**menor valor vence**).
- Saída mostra qual carta venceu em cada atributo.
- A População agora é do tipo `unsigned long int`.

---

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Terminal (CLI)
- `scanf` / `printf` para entrada e saída

---

## 📚 Estrutura do Código

- `main.c`: Arquivo principal contendo a lógica de cadastro, cálculo e comparação.
- Separação por funções conforme o nível implementado (ex: cálculo de densidade, super poder etc.).
- Comentários explicativos para facilitar entendimento e manutenção.

---

## 👨‍🎓 Autor

João M J Braga  
Estudante de Análise e Desenvolvimento de Sistemas
[LinkedIn](https://www.linkedin.com/in/joaomjbraga) | [GitHub](https://github.com/joaomjbraga)

---

## 📅 Última atualização

Abril de 2025
