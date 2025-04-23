# 🃏 Super Trunfo - Países (Comparação Avançada)

Este projeto é uma atividade acadêmica do curso de Análise e Desenvolvimento de Sistemas. Ele simula parte do jogo **Super Trunfo**, com foco na **comparação de cartas representando países**, usando múltiplos atributos e lógica condicional em linguagem C.

## 📌 Objetivo

Desenvolver um sistema interativo em C para comparar cartas de países com base em **dois atributos numéricos distintos**, aplicando **regras específicas** para cada tipo de dado e utilizando estruturas como `switch`, `if-else`, e operador ternário.

---

## 🧩 Níveis do Projeto

### 🧭 Nível Mestre: Comparação Avançada

- Permite ao jogador escolher **dois atributos diferentes** para comparar.
- Os atributos disponíveis incluem:
  - População (`int`)
  - Área (`float`)
  - PIB (`float`)
  - Número de pontos turísticos (`int`)
  - Densidade demográfica (`float`, calculada automaticamente)
- Implementa lógica de comparação:
  - **Maior valor vence**, exceto para Densidade Demográfica (**menor valor vence**)
- Calcula a **soma dos atributos** para definir a carta vencedora.
- Exibe o resultado com clareza, incluindo empates.
- Garante que o mesmo atributo não possa ser escolhido duas vezes (menus dinâmicos com `switch`).

---

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Terminal (CLI)
- `scanf`, `printf`, `switch`, `if-else`, operador ternário

---

## 📚 Estrutura do Código

- `main.c`: Contém toda a lógica de cadastro das cartas, escolha de atributos, comparação e exibição de resultados.
- Utiliza funções auxiliares para cálculos e validações.
- Comentários explicativos facilitam o entendimento do fluxo.

---

## 👨‍🎓 Autor

João M J Braga  
Estudante de Análise e Desenvolvimento de Sistemas  
[LinkedIn](https://www.linkedin.com/in/joaomjbraga) | [GitHub](https://github.com/joaomjbraga)

---

## 📅 Última atualização

Abril de 2025
