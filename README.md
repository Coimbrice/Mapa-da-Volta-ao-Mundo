# A volta ao mundo de Phileas Fogg

Mapa interativo de *A volta ao mundo em 80 dias*, de Júlio Verne (1872), para acompanhar a leitura capítulo a capítulo.

**Acesse:** https://coimbrice.github.io/Mapa-da-Volta-ao-Mundo/

## Por que fiz

Li o livro num clube de leitura e queria acompanhar a viagem no mapa enquanto lia. As ferramentas de mapa que encontrei online não permitiam tantas paradas e mostravam só o trajeto estático. Então fiz o meu.

## O que o mapa mostra

- **O plano:** o itinerário de 80 dias calculado pelo Morning Chronicle, que Fogg segue à risca.
- **O caminho real de Fogg:** o que ele de fato percorre, com as paradas, os desvios (o elefante na Índia, a Tankadère, o trenó a vela, o Henrietta) e as datas que o livro dá.
- **Passepartout sozinho:** os trechos em que ele está separado do patrão.
- **Adiantado ou atrasado:** a folga de Fogg em horas, nos pontos em que o próprio livro faz a conta.
- **Dinheiro:** o que Fogg gasta ao longo da viagem, com uma conversão aproximada para valores de hoje.

O mapa abre no capítulo I e só mostra o que aconteceu até o capítulo escolhido, então dá para usar durante a leitura sem levar spoiler.

## Fontes

- Romance: Jules Verne, *Le Tour du monde en quatre-vingts jours* (1872), em domínio público. Texto em francês do Project Gutenberg, eBook nº 800: https://www.gutenberg.org/ebooks/800
- Os títulos dos capítulos foram traduzidos por mim do original francês. Os nomes dos personagens seguem o original (Passepartout, Fix, Aouda).
- Trajetos, datas, resumos e valores foram tirados do texto do romance. Kholby e o pagode de Pillaji são lugares inventados por Verne; esses e alguns outros pontos (as tempestades, os bisões) estão em posição aproximada.
- Valores de hoje: inflação britânica pelo officialdata.org (base 1870; £1 de 1872 ≈ £147 em 2026) e câmbio de 17 de outubro de 2026 (R$ 6,79 e US$ 1,33 por libra). Os dólares de 1872 foram convertidos pelo câmbio-ouro da época, US$ 4,86 por libra.

## Bibliotecas e dados

- [d3](https://d3js.org/) 7.9.0, [topojson-client](https://github.com/topojson/topojson-client) 3.1.0 e o mapa-múndi do [Datamaps](https://datamaps.github.io/) 0.5.9, com contornos do Natural Earth (domínio público). Se o Datamaps não carregar, a página usa o mapa-múndi do [ECharts](https://echarts.apache.org/) 4.9.0.
- Fontes IM Fell English e Spectral, do Google Fonts (SIL Open Font License).
