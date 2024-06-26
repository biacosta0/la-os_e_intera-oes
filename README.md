# Sistema de contagem de músicas

## Detalhamento do HTML
&lt;DOCTYPE html&lt;: Declara o tipo de documento como HTML5.  
• &lt;html&gt;: Define o início do documento HTML.  
• &lt;head&gt;: Contém informações sobre o documento, como o título da página, metadados e links para arquivos externos.  
• &lt;meta charset='utf-8'&lt;: Define a codificação de caracteres como UTF-8 para suportar caracteres especiais.
• &lt;meta http-equiv='X-UA-Compatible' content='IE=edge'&gt;: Define a versão mais recente do Internet Explorer como o modo de renderização.  
• &lt;title>Page Title</title&lt;: Define o título da página exibido na barra de título do navegador.
• &lt;meta name='viewport' content='width=device-width, initial-scale=1'&gt;: Controla a escala e a largura da página para dispositivos móveis.
• &lt;link rel='stylesheet' type='text/css' media='screen' href='musica.css'>: Vincula um arquivo CSS externo chamado "musica.css" para estilizar a página.
• &lt;script src='main.js'></script&lt;: Vincula um arquivo JavaScript externo chamado "main.js" para adicionar funcionalidades à página.
• &lt;body>: Contém o conteúdo visível da página.
• &lt;form name="selectForm"&lt;: Define um formulário com o nome "selectForm".   
• &lt;h1>Escolha alguns tipos de música, em seguida, clique no botão abaixo:</h1>: Um cabeçalho indicando ao usuário o que fazer.  
• &lt;select class="select" id="tipoMusica" name="tipoMusica" multiple="multiple"&lt;: Define um campo de seleção múltipla com a classe "select" e o nome "tipoMusica".    
• &lt;option selected="selected"&lt;: Define opções dentro do campo de seleção, com algumas opções já selecionadas por padrão.    
• &lt;input id="btn" type="button" value="Quantos foram selecionados?" /&lt;: Um botão com o ID "btn" que, quando clicado, exibirá quantas opções foram selecionadas no campo de seleção múltipla.  
• O script JavaScript define uma função chamada "howMany" para contar quantas opções foram selecionadas no campo de seleção. Em seguida, adiciona um evento de clique ao botão que chama essa função e exibe um alerta com o número de opções selecionadas.  
tem menu de contexto

## Detalhamento do CSS
*::before, *::after { box-sizing: content-box; }: Define o modelo de caixa para os pseudo-elementos ::before e ::after como content-box, o que significa que as dimensões desses pseudo-elementos não incluirão o preenchimento e a borda do elemento pai.  
• :root { ... }: Define variáveis CSS personalizadas usando a pseudo-classe :root. Essas variáveis são usadas posteriormente no código para definir cores e estilos.  
• select { ... }: Estiliza os elementos select. Remove os estilos padrão do navegador, como borda e seta de seleção, e define estilos personalizados, incluindo a aparência do elemento, cores, tamanho da fonte e outras propriedades.  
• select:focus + .focus { ... }: Estiliza um elemento com a classe .focus que vem após um elemento select quando o select está em foco. Isso cria um efeito visual de foco ao redor do elemento select.  
• select[multiple] { ... }: Estiliza elementos select que possuem o atributo multiple, como o campo de seleção múltipla no código HTML fornecido. Define o tamanho e o comportamento específicos para esses elementos.  
• .select--disabled { ... }: Estiliza elementos com a classe .select--disabled, que são usados para desativar elementos select, alterando a aparência e o comportamento para indicar que estão desativados.  
• label { ... }: Estiliza elementos label, definindo o tamanho da fonte e o peso da fonte.  
• body { ... }: Estiliza o corpo da página, definindo o tamanho mínimo da altura da visualização (min-height), o alinhamento do conteúdo, a família da fonte, a cor de fundo e o preenchimento.

## Fonte consultada

[MDN Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Loops_and_iteration )

## Autora

[Beatriz Farias Costa](https://github.com/biacosta0)