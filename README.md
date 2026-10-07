# welbersouza.com

Site acadêmico de Welber S. de Souza, hospedado no GitHub Pages. Mesmo template do site da Dani (daniellesimoes.com); muda a cor de destaque, a figura do topo e a seção Work.

## Arquivos

- `index.html`: a página inteira (HTML, CSS e as figuras em SVG no mesmo arquivo).
- `CNAME`: contém `welbersouza.com`. Não apague, é o que liga o domínio ao site.
- `.nojekyll`: diz ao GitHub para publicar os arquivos como estão.
- `Welber_Souza_CV_tex.pdf`: o CV. Para atualizar, suba o novo PDF com o mesmo nome; o link `welbersouza.com/Welber_Souza_CV_tex.pdf` continua valendo.
- `images/`: fotos do site.

## Como editar

Abra `index.html` no próprio GitHub (ícone de lápis), altere o texto e clique em **Commit changes**. O site atualiza em 1 a 2 minutos.

Trechos com fundo amarelo (`<span class="todo">`) ainda precisam ser completados: ORCID, fotos e a seção Media.

A cor de destaque fica na variável `--accent` no início do CSS.

## Fotos

Os quadros tracejados (`<div class="ph">`) são espaços reservados. Para trocar por uma foto:

1. Comprima a imagem (até 300 KB, 1600 px de largura) e suba em `images/` (ex.: `images/linha15.jpg`).
2. Troque o `<div class="ph ...">...</div>` por `<img src="images/linha15.jpg" alt="descrição da foto">`.

Use fotos de áreas públicas ou imagens já publicadas; obras do Metrô costumam ter restrição de divulgação.

## DNS (no registrador do domínio)

| Tipo  | Nome | Valor                     |
|-------|------|---------------------------|
| A     | @    | 185.199.108.153           |
| A     | @    | 185.199.109.153           |
| A     | @    | 185.199.110.153           |
| A     | @    | 185.199.111.153           |
| CNAME | www  | simoeswelber.github.io    |

Depois, em *Settings → Pages → Custom domain*, informe `welbersouza.com` e marque **Enforce HTTPS** quando o certificado aparecer.
