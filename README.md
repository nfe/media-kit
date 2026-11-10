# [Media Kit NFE.io](https://nfe.io/media-kit/)

Arquivos do sistema de identidade visual da NFE.io. Fonte: Manual de Identidade Visual v3.0 e Design System Web (Figma).

## Manual de Identidade Visual

| Formato | Link |
|---------|------|
| PDF     | <a href="manual-de-identidade-visual/manual-de-identidade-visual.pdf" download target="_blank">Manual de Identidade Visual (PDF)</a> |


## [Elementos da Marca](elementos-da-marca/README.md)

### [Logos](elementos-da-marca/logos/README.md)

| Preview | Formato | Link |
|---------|---------|------|
| ![Logo Branco Transparente (Email)](elementos-da-marca/logos/logo-branco-transparente-vemail.png) | PNG | <a href="elementos-da-marca/logos/logo-branco-transparente-vemail.png" download target="_blank">Logo Branco Transparente (Email)</a> |
| ![Logo Branco Transparente](elementos-da-marca/logos/logo-branco-transparente.png) | PNG | <a href="elementos-da-marca/logos/logo-branco-transparente.png" download target="_blank">Logo Branco Transparente</a> |
| ![Logo BW Tiny Quadrado Fundo Branco](elementos-da-marca/logos/logo-bw-tiny-quadrado-fundo-branco.jpg) | JPG | <a href="elementos-da-marca/logos/logo-bw-tiny-quadrado-fundo-branco.jpg" download target="_blank">Logo BW Tiny Quadrado Fundo Branco</a> |
| ![Logo Colorido Fundo Transparente](elementos-da-marca/logos/logo-colorido-fundo-transparente.png) | PNG | <a href="elementos-da-marca/logos/logo-colorido-fundo-transparente.png" download target="_blank">Logo Colorido Fundo Transparente</a> |
| ![Logo Quadrado Branco Transparente (SVG)](elementos-da-marca/logos/logo-quadrado-branco-transparente.svg) | SVG | <a href="elementos-da-marca/logos/logo-quadrado-branco-transparente.svg" download target="_blank">Logo Quadrado Branco Transparente (SVG)</a> |
| ![Logo Quadrado Fundo Branco](elementos-da-marca/logos/logo-quadrado-fundo-branco.jpg) | JPG | <a href="elementos-da-marca/logos/logo-quadrado-fundo-branco.jpg" download target="_blank">Logo Quadrado Fundo Branco</a> |
| ![Logo Quadrado Transparente 100px](elementos-da-marca/logos/logo-quadrado-transparente-100px.png) | PNG | <a href="elementos-da-marca/logos/logo-quadrado-transparente-100px.png" download target="_blank">Logo Quadrado Transparente 100px</a> |
| ![Logo Quadrado Transparente](elementos-da-marca/logos/logo-quadrado-transparente.jpg) | JPG | <a href="elementos-da-marca/logos/logo-quadrado-transparente.jpg" download target="_blank">Logo Quadrado Transparente</a> |
| ![Logo Small Quadrado Fundo Branco (GIF)](elementos-da-marca/logos/logo-small-quadrado-fundo-branco.gif) | GIF | <a href="elementos-da-marca/logos/logo-small-quadrado-fundo-branco.gif" download target="_blank">Logo Small Quadrado Fundo Branco (GIF)</a> |
| ![Logo Tiny Quadrado Fundo Branco (JPEG)](elementos-da-marca/logos/logo-tiny-quadrado-fundo-branco.jpeg) | JPEG | <a href="elementos-da-marca/logos/logo-tiny-quadrado-fundo-branco.jpeg" download target="_blank">Logo Tiny Quadrado Fundo Branco (JPEG)</a> |

### Wallpapers

| Preview | Formato | Link |
|---------|---------|------|
| ![Wallpaper OBS V2](elementos-da-marca/wallpaper/wallpaper-obs-v2.jpg) | JPG | <a href="elementos-da-marca/wallpaper/wallpaper-obs-v2.jpg" download target="_blank">Wallpaper OBS V2</a> |
| ![Wallpaper V2 (JPG)](elementos-da-marca/wallpaper/wallpaper-v2.jpg) | JPG | <a href="elementos-da-marca/wallpaper/wallpaper-v2.jpg" download target="_blank">Wallpaper V2 (JPG)</a> |
| ![Wallpaper V2 (PNG)](elementos-da-marca/wallpaper/wallpaper-v2.png) | PNG | <a href="elementos-da-marca/wallpaper/wallpaper-v2.png" download target="_blank">Wallpaper V2 (PNG)</a> |
| ![Wallpaper V3 (JPG)](elementos-da-marca/wallpaper/wallpaper-v3.jpg) | JPG | <a href="elementos-da-marca/wallpaper/wallpaper-v3.jpg" download target="_blank">Wallpaper V3 (JPG)</a> |
| ![Wallpaper V3 (PNG)](elementos-da-marca/wallpaper/wallpaper-v3.png) | PNG | <a href="elementos-da-marca/wallpaper/wallpaper-v3.png" download target="_blank">Wallpaper V3 (PNG)</a> |
| ![Wallpaper (PNG)](elementos-da-marca/wallpaper/wallpaper.png) | PNG | <a href="elementos-da-marca/wallpaper/wallpaper.png" download target="_blank">Wallpaper (PNG)</a> |

### Outros Elementos

| Arquivo | Descrição |
|---------|-----------|
| <a href="elementos-da-marca/styles.css" download target="_blank">`elementos-da-marca/styles.css`</a> | Tokens de cor (tema claro e escuro), tipografia responsiva, espaçamento, raio, sombra, layout e componentes |
| <a href="elementos-da-marca/wave-pattern.png" download target="_blank">`elementos-da-marca/wave-pattern.png`</a> | Malha da marca no degradê (PNG transparente, 2519 px) |

#### Favicon

- Favicon SVG para uso em todas as páginas do site:

```html
<link rel="icon" href="elementos-da-marca/logos/favicon.svg" type="image/svg+xml">
```

- Favicon ICO para uso em navegadores que não suportam SVG:

```html
<link rel="icon" href="elementos-da-marca/logos/favicon.ico" type="image/x-icon">
```

> Tamanho mínimo do símbolo: 16 px. No cabeçalho e no rodapé, use o logotipo completo.

#### Como usar o styles.css

```html
<link rel="stylesheet" href="styles.css">

<section data-theme="dark" class="section has-mesh">
  <div class="mesh mesh--tr" aria-hidden="true"></div>
  <p class="t-overline">Sobretítulo</p>
  <h1 class="t-display">Título com <span class="highlight">destaque</span></h1>
  <a class="btn" href="#">Criar conta grátis</a>
</section>
```

- Use os tokens semânticos (`--nfe-text-primary`, `--nfe-action-primary` etc.). Os primitivos (`--nfe-*`) guardam só os valores.
- O tema claro é o padrão. Aplique `data-theme="dark"` na seção ou no `<html>`.
- O degradê (`--nfe-gradient`, #5DD0F2 → #7AEA53) é exclusivo do logotipo, do símbolo e da malha.
- A malha deve ser posicionada em um canto superior ou inferior, sem sobrepor texto e sem mostrar as extremidades. Opacidade: 20% no claro, 30% no escuro, 42% em capa e contracapa.


## Download do Repositório

Você pode baixar o repositório completo como um arquivo zip através do link abaixo:

<a href="https://github.com/nfe/media-kit/archive/refs/heads/main.zip" download target="_blank">Baixar Repositório (ZIP)</a>

Aproveite os recursos e sinta-se à vontade para baixar o que precisar!
