# Notas 2ª Fase - FUVEST 2027 (estimativa)

Calculadora que mostra quanto você precisa tirar na 2ª fase da FUVEST 2027 para atingir os pontos finais de uma carreira, a partir do número de acertos na 1ª fase (agora com **80 questões**).

## Fórmula (Guia de Provas FUVEST 2027)

Notas normalizadas na base 100 e nota final convertida para escala de 1000:

- Sem Competências Específicas: `NF = (F1 + D1 + D2) / 3`
- Com Competências Específicas: `NF = (F1 + D1 + D2 + 2 × CE) / 5`
- `Pontos finais = NF × 10`, com `F1 = acertos / 80 × 100`

Soma necessária na 2ª fase (D1 + D2, máximo 200):

- Sem CE: `3 × PF / 10 − F1`
- Com CE: `PF / 2 − F1 − 2 × CE`

Eliminações consideradas: menos de 24 acertos na 1ª fase, nota 0 em qualquer dia da 2ª fase (ou na redação) e menos de 50% em Competências Específicas.

## Como publicar no GitHub Pages

1. Crie um repositório (ex.: `notas-fuvest-2027`) e envie `index.html` e `README.md`.
2. Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
3. O site fica em `https://SEU-USUARIO.github.io/notas-fuvest-2027/`.

Não há dependências nem etapa de build: é um único arquivo HTML.

## Aviso

Estimativa não oficial. Confira sempre o Guia de Provas em [fuvest.br](https://www.fuvest.br).



