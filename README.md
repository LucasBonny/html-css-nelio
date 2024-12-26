## Flexbox

Para a utilização do flexbox basta utilizar o `display: flex` no elemento pai e apartir disso utilizar as propriedades `flex-direction`, `flex-wrap`, `justify-content`, `align-items` e `align-content`.

Ao utilizar o display flex os elementos filhos ficam um ao lado do outro, mas ao utilizar o `flex-wrap: wrap` eles ficam um abaixo do outro dependendo da largura da tela.

> [!IMPORTANT]
> O align-items define o alinhamento vertical dos elementos filhos, mas se a direção dos elementos não for a principal ele não funcionará e o ideal seria utilizar o justify-content.

```css
display: flex;
flex-wrap: wrap;
flex-direction: column;
justify-content: center;
```

