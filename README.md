<!-- Modelo do roadmap: troque cada <…>. O topo nasce da ficha (F1), na F1; o resto cresce em cada fase. -->
# <nome> · <o que muda> pra <quem>

Hoje <a alternativa e a dor>. Com isso, <o antes × depois>.

No ar: <link> · Demo (2 min): <link> · estado: em construção | em evolução | em manutenção | aposentado · Prova: <número do laudo ou depoimento>

## Como rodar

<!-- testado clonando numa pasta limpa -->

## Como funciona

<!-- o desenho das partes e o fluxo da story principal (Mermaid); o detalhe está em docs/planta.md -->

## Decisões

<!-- uma linha por decisão, com link pro registro em docs/decisoes/ -->

## O que a IA fez

<!-- o resumo honesto do "meu × IA" dos commits -->

## Segurança

<!-- o checklist do Blindar (F3) -->
- [ ] consultas sempre parametrizadas
- [ ] saída escapada no front (contra XSS, Cross-Site Scripting)
- [ ] CORS (Cross-Origin Resource Sharing) só pra minha origem
- [ ] proteção contra CSRF (Cross-Site Request Forgery)
- [ ] headers de segurança
- [ ] rate limit (limite de pedidos) no login e em endpoint que custa dinheiro
- [ ] nenhum segredo no histórico do Git
- [ ] `npm audit` limpo

## Se tocar

<!-- o que é frágil (F4) -->

## Resultado

<!-- o link pro último laudo: docs/laudo-v1.md -->
