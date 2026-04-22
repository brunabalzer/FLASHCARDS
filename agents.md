# agents.md

## Project Overview

* **Project:** Classmaster.io
* **Goal:** flashcards de francês por unidade, com importação de listas e estatísticas por lição
* **Stack:** HTML + CSS + JavaScript puro, em um único arquivo
* **Storage:** `localStorage` para unidades e stats

---

## Arquivos Importantes

* `src/index.html` — app principal
* `README.md` — instruções rápidas de uso

---

## Do

* Leia `src/index.html` antes de mexer em lógica ou UI
* Mantenha tudo em um único HTML
* Preserve o estilo azul `#3daee9`, cards brancos e layout mobile-first
* Trate erros de importação sem quebrar a tela
* Teste o fluxo de estudo e a aba Stats após mudanças

---

## Don't

* Não adicione dependências externas sem pedir
* Não troque as chaves `cm_units1` e `cm_stats3` sem necessidade
* Não reescreva o CSS do zero
* Não mexa em `localStorage` de forma destrutiva sem confirmar

---

## Fluxo

* `Import` recebe blocos por unidade
* `Home` lista lições e inicia o estudo
* `Study` mostra o flashcard e registra acertos/erros
* `Stats` soma acertos, erros, sessões e tempo de uso por lição

---

## Resposta

* Responda em frases curtas
* Diga o que mudou e por quê
* Se houver risco para dados salvos, avise antes
