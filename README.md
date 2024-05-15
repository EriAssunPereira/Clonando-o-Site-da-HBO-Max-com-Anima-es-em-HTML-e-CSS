# Clonando-o-Site-da-HBO-Max-com-Anima-es-em-HTML-e-CSS

Clonar o site da HBO Max com animações em HTML e CSS é um projeto que combina várias habilidades de front-end. Vamos abordar este projeto em módulos, detalhando cada etapa e fornecendo exemplos práticos.

### Módulo 1: Estrutura HTML
Comece com a estrutura HTML do site. Crie uma `<header>` para o menu, uma `<main>` para o conteúdo principal, e um `<footer>` para o rodapé. Dentro de `<main>`, inclua seções para os diferentes tipos de conteúdo, como filmes em destaque, séries e categorias.

### Módulo 2: Estilos CSS Básicos
Defina os estilos básicos, como fontes, cores e botões. Use variáveis CSS para manter a consistência e facilitar mudanças futuras.

### Módulo 3: Layout com Flexbox e Grid
Use Flexbox para estruturar o layout principal e Grid para áreas mais complexas, como galerias de filmes. Isso proporcionará um design responsivo e organizado.

### Módulo 4: Animações com CSS
Implemente animações para melhorar a interatividade do site. Use `@keyframes` para definir animações e aplique-as a elementos específicos com a propriedade `animation`.

### Módulo 5: Responsividade
Garanta que o site seja responsivo com media queries. Ajuste o layout, tamanho dos elementos e animações para diferentes tamanhos de tela.

### Módulo 6: Publicação no GitHub
Após finalizar o projeto, publique-o em um repositório público no GitHub. Inclua um `README.md` com instruções e detalhes do projeto.

### Exemplo Prático: Animação de Destaque
Aqui está um exemplo de como criar uma animação para os destaques do site:

```html
<div class="highlight">
  <img src="filme-destaque.jpg" alt="Filme Destaque">
</div>
```

```css
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.highlight img {
  animation: fadeIn 2s ease-in-out;
}
```

Com esses módulos e o exemplo prático, você tem um guia completo para clonar o site da HBO Max com animações em HTML e CSS. Lembre-se de testar as animações em diferentes navegadores e dispositivos para garantir a compatibilidade.
