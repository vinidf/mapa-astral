# Mapa Astral Natal

SPA em arquivo único (`index.html`) que calcula mapa natal completo no navegador, sem backend:

- Posições geocêntricas aparentes (zodíaco tropical) via teoria VSOP87 / algoritmos de Jean Meeus — biblioteca [astronomia](https://github.com/commenthol/astronomia) (MIT), empacotada no arquivo.
- Fuso horário histórico IANA (incl. horários de verão brasileiros da época) via [Luxon](https://github.com/moment/luxon) (MIT) — CDN com fallback embutido.
- Ascendente, Meio do Céu e casas Placidus (iteração dos semi-arcos).
- Sol, Lua, Mercúrio–Plutão, Nodo Norte verdadeiro; aspectos maiores; mandala SVG; tabelas.

Uso: abra `index.html` (ou a página publicada), preencha nome, data, hora e cidade, e clique em **Gerar Mapa Astral**.

Licenças de terceiros: ver `THIRD-PARTY-LICENSES.md`.
