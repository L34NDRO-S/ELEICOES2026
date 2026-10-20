# Replay do 1º turno de 2026 com os modelos do 2º turno

Reencenação, no **painel de produção** (as mesmas tabelas e gráficos), da apuração
presidencial de 04/10/2026 quadro a quadro, com os dois modelos preparados para o
2º turno de 25/10/2026. A foto do TSE é filtrada para Lula e Flávio, como o painel
recebe no 2º turno:

- **hier**: swing por município com encolhimento hierárquico (TAU de 100 mil
  votos), sobre os arquivos de zona do TSE.
- **fine**: projetor por seção, a partir dos boletins de urna, com tamanho do que
  falta por comparecimento e faixa de 95% calibrada no 2º turno de 2002–2022.

Sem mercado, trading nem saúde do pipeline. Abra `index.html` (ou a página do GitHub Pages) e use o botão **tocar** ou a barra
de tempo. `#19h00` na URL abre direto nesse horário.

## Limites desta reencenação

- No 2º turno os modelos usam o 1º turno de 2026 como referência. Aqui isso seria
  vazamento, então ambos usam a presidencial de **2022**.
- A chegada dos boletins na CDN do TSE usa um atraso **estimado** (mediana de 17
  min), não medido ao vivo.
- A faixa de incerteza é a do fine; o hier aparece sem faixa.
- As projeções não são as que o painel mostrou na noite: são as que estes modelos
  produziriam hoje. Não garantem o desempenho em 25/10.

Dados: arquivos públicos de resultados do TSE. Gráficos: [Plotly.js](https://plotly.com/javascript/)
2.35.2 (licença MIT), incluído como `plotly.min.js`.
