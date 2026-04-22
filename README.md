# Classmaster.io

Flashcards de francês por unidade, em um único arquivo HTML.

## Como usar

1. Abra `src/index.html` no navegador.
2. Vá em `Import`.
3. Cole sua lista de palavras francesa/inglesa, separada por unidade.
4. Clique em `Substituir unidades` ou `Adicionar unidades`.
5. Estude em `Home` e veja os resultados em `Stats`.

## Formato de entrada

Aceito:

- um título de unidade por bloco
- uma linha por card
- separadores como `tab`, `|`, `;` ou dois espaços

Exemplo:

```text
Level 3
Plants – Level 3
la clématite	clematis
l'églantine (f)	wild rose
la glycine	wisteria
```

## Dados salvos

- `cm_units1` armazena as unidades importadas
- `cm_stats3` armazena acertos, erros e tempo de uso por lição

## Observação

O projeto segue sem build tool e sem backend.
