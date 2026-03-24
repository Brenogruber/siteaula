CSS Interno vs. Externo

CSS Interno: Os estilos são escritos dentro da tag <style>, que fica inserida no <head> do próprio arquivo HTML. É ideal para páginas únicas ou quando você quer aplicar estilos rápidos sem criar novos arquivos.

CSS Externo: O código fica em um arquivo separado (com extensão .css). Você o conecta ao HTML usando a tag <link rel="stylesheet" href="estilo.css"> no <head>. É o padrão da indústria, pois permite controlar o visual de centenas de páginas editando apenas um arquivo. 


Seletores CSS

Seletor de Tipo (Tag): Aplica o estilo a todas as tags de um tipo (ex: p { ... } para todos os parágrafos).

Seletor de Classe: Identificado por um ponto (ex: .botao { ... }). É usado para aplicar o mesmo estilo a vários elementos diferentes.

Seletor de ID: Identificado por uma cerquilha (ex: #topo { ... }). Deve ser único e aplicado a apenas um elemento na página.

Seletores Compostos e Pseudo-classes: Permitem maior precisão, como selecionar um link apenas quando o mouse está sobre ele (a:hover) ou um item específico dentro de uma lista. 
