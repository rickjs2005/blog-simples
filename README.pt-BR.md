# blog-simples

[English](README.md)

Página estática de blog em HTML e CSS, reproduzindo o layout de uma imagem de referência ("Brixtons Lounge"). Foi meu terceiro projeto como iniciante, feito com ajuda do ChatGPT.

> **Tipo:** projeto de estudo (2023)

![Topo da página do blog](docs/screenshots/blog.jpg)

## O que tem

- Barra de navegação com links de exemplo e ícones de redes sociais.
- Título, subtítulo com linhas duplas e três cards de artigos com imagem.
- Seção "Brand new selection of fashion" e bloco "About Me" com texto lorem ipsum.
- Rodapé com link para o perfil do GitHub do autor.

## Como abrir

Não há dependências nem build. Abra `rjs/blog/indexx.html` no navegador ou sirva a pasta:

```bash
cd rjs/blog
python3 -m http.server 8000   # depois acesse http://localhost:8000/indexx.html
```

## Estrutura

- `rjs/blog/indexx.html`: a página.
- `rjs/blog/style.css`: estilos.
- `rjs/blog/imagens/`: fotos e ícones.
- `rjs/blog/blog copia.png`: imagem de referência do layout.

## Limitações

- Sem responsividade (largura fixa pensada para desktop).
- Os itens do menu são placeholders (`href=""`, a maioria com o texto fora do link) e os ícones sociais não têm links.
- Diferenças em relação à referência, como "Brixtons Lourge" no título e "about is" no menu.

## Créditos e origem das imagens

- O layout segue a imagem `blog copia.png`, um mockup de tema de blog de terceiros; autoria não documentada.
- Fotos e ícones foram obtidos na web e a origem não está documentada. `imagens/img1.jpg` tem marca d'água do iStock (prévia, não licenciada). Substitua as imagens por material licenciado antes de qualquer reutilização.

## Segurança

Veja [SECURITY.md](SECURITY.md).

## Licença

Ainda não há licença definida; todos os direitos reservados ao autor (isso não cobre as imagens de terceiros citadas acima).
