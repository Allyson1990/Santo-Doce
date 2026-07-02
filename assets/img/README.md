# Imagens — Santo Doce

Coloque aqui as imagens do site. Diretrizes da marca: luz natural, tons quentes,
madeira, cozinha, ingredientes naturais e confeitaria artesanal. Nunca imagens
muito saturadas ou frias.

## Arquivos esperados pelo `index.html`

| Arquivo                     | Uso                                      | Onde trocar no `index.html`                          |
| --------------------------- | ---------------------------------------- | ---------------------------------------------------- |
| `logo-santo-doce.svg`       | Logo da marca (header, esquerda)         | Substituir o bloco `.header__logo-placeholder`       |
| `bruna-santo-doce.png`      | Imagem principal do header (direita)     | Substituir o bloco `.header__image-slot` por `<img>` |

## Como aplicar

**Logo:**

```html
<a class="header__logo" href="index.html" aria-label="Santo Doce — início">
  <img src="assets/img/logo-santo-doce.svg" alt="Santo Doce" />
</a>
```

**Imagem principal do header:**

```html
<img class="header__image" src="assets/img/bruna-santo-doce.png"
     alt="Bruna Hash saboreando um doce Santo Doce" />
```

## Recomendações

- Formatos: `.svg` para logo; `.webp` ou `.png` para fotos (com fundo transparente quando possível).
- Otimize as fotos (largura máx. ~1200px, compressão) para carregamento rápido.
- Sempre inclua `alt` descritivo para acessibilidade (WCAG AA).
