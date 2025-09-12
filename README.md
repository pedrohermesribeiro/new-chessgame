# new-chessgame
Repositório criado em **Spring Boot (Java 21)** com front-end em **HTML/JavaScript**, onde todas as regras de xadrez já estão implementadas (movimentação, cheque, xeque-mate, roque, etc.). O foco deste novo repositório é **incrementar a inteligência artificial no nível `hard-computer`**, tornando-a mais avançada e estratégica.

## 🎯 Objetivo

O objetivo principal é aprimorar o comportamento do computador no modo difícil, para que ele:
- **Evite capturas desvantajosas** (ex.: capturar um peão e perder a dama na sequência).
- **Avalie riscos antes de executar movimentos**, considerando trocas de peças.
- **Aplique heurísticas posicionais** que melhorem a performance a longo prazo.
- **Evolua em direção a um motor de xadrez mais robusto**, simulando jogadas futuras.

---

## 🛠️ Tecnologias Utilizadas

- **Java 21**
- **Spring Boot 3.x**
- **WebSocket** para comunicação em tempo real
- **H2 Database** para persistência leve
- **Lombok**
- **Front-end**: HTML, CSS e JavaScript puro
