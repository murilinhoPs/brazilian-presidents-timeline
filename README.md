# Quem governou o Brasil?

Página de entrada da pesquisa sobre os 35 governos do Brasil, de 1889 até hoje, por era e posição política. É um site estático: um `index.html` com CSS e JS embutidos e a pasta `img/`, sem dependências e sem build.

## Publicar no GitHub Pages

1. Suba `index.html` e a pasta `img/` na raiz do repositório.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, a branch `main` e a pasta `/ (root)`.
3. O site fica em [murilinhops.github.io/brazilian-presidents-timeline](https://murilinhops.github.io/brazilian-presidents-timeline/).

As duas linhas do tempo, a estática e a interativa, estão dentro do próprio `index.html`. Os botões abrem cada uma por cima da página inicial, com os endereços `#linha-do-tempo` e `#governo-a-governo`. O botão "← Início", o voltar do navegador e a tecla Esc retornam ao início.

## Fontes

- [Os presidentes da República Velha](https://www.camara.leg.br/noticias/93698-os-presidentes-da-republica-velha), Agência Câmara
- [Os presidentes da Era Vargas](https://www.camara.leg.br/noticias/93696-os-presidentes-da-era-vargas/), Agência Câmara
- [Quem mais governou o Brasil: esquerda ou direita?](https://revistaforum.com.br/historia/quem-mais-governou-o-brasil-esquerda-ou-direita/), Revista Fórum
