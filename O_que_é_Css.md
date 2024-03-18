# O que é o Css?

**CSS (Cascading Style Sheets)** é uma linguagem de estilo usada para controlar a aparência e o layout dos elementos em uma página da web. Ele permite que você defina como os elementos HTML devem ser apresentados visualmente, como cor, tamanho de fonte, margens, espaçamento e muito mais.

A versão mais atual do CSS é o CSS3, que introduziu muitos recursos novos e avançados para estilização, como gradientes, sombras, animações e transformações.

Para estilizar os elementos HTML usando CSS, você precisa primeiro selecionar esses elementos usando seletores CSS e, em seguida, aplicar estilos a eles. Aqui estão algumas maneiras de selecionar elementos HTML e estilizá-los:

1. **Selecionar por Tipo de Elemento**: Você pode selecionar todos os elementos de um tipo específico usando o nome do elemento. Por exemplo, para estilizar todos os parágrafos `<p>` em uma página, você pode usar `p { }`.

2. **Selecionar por Classe**: Você pode atribuir uma classe a um ou mais elementos HTML e estilizá-los em conjunto. Para selecionar elementos por classe, use um ponto (`.`) seguido do nome da classe. Por exemplo, ` .destaque { }` seleciona todos os elementos com a classe "destaque".

3. **Selecionar por ID**: Cada elemento HTML pode ter um ID único. Para selecionar um elemento por ID, use uma hashtag (`#`) seguida do ID do elemento. Por exemplo, `#cabecalho { }` seleciona o elemento com o ID "cabecalho".

4. **Seletores Avançados**: CSS também suporta seletores mais avançados, como seletores de atributos, seletores de filho, seletores de descendente, etc., que permitem maior controle sobre quais elementos são estilizados.

Depois de selecionar os elementos HTML, você pode definir os estilos dentro das chaves `{ }`, especificando as propriedades de estilo (como cor, tamanho da fonte, margens, etc.) e seus valores. Por exemplo:

```css
.destaque {
    color: red; /* Define a cor do texto como vermelho */
    font-size: 20px; /* Define o tamanho da fonte como 20 pixels */
}

#cabecalho {
    background-color: black; /* Define a cor de fundo como preto */
    padding: 10px; /* Adiciona espaçamento interno de 10 pixels */
}
```

Documentação do CSS em: https://developer.mozilla.org/pt-BR/docs/Web/CSS
