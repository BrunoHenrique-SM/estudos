# PHP
O PHP é uma linguagem de [[script]] de finalidade geral, usada principalmente aliada com [[HTML]] para desenvolvimento [[WEB]]. Por ser uma linguagem **script** o **PHP** é usado em sites e seu funcionamento se dá após o acionamento de algum botão ou o clique em algum link, porém hoje em dia já é possível usa-lo para desenvolver aplicativos.
Uma diferença notável entre o PHP e o [[JavaScript]], outra linguagem de script, é que enquanto o primeiro roda num [servidor](Servidor) o [[JavaScript]] roda no navegador, no entanto com node é possível fazer com o JS também rode no servidor.

## Como o PHP Funciona
Como já foi dito, o PHP é uma linguagem do lado servidor. Isso significa que o código escrito no PHP reside em computador host, o **servidor**, que envia as páginas para os visitantes. Diferente do HTML, no PHP o cliente faz uma solicitação (request) e no servidor os dados são processados e enviados(response) como uma página HTML, para o usuário não há diferença entre  `home.php` ou `home.html`, mas há diferença na forma como o conteúdo foi gerado.
A partir do momento que o interpretador PHP começa a agir, todo o código inserido dentro do documento começa a ser processado. Esse processamento gera um arquivo HTML e nesse arquivo vai existir somente _tags_ HTML ou qualquer outra tecnologia _client-side_, que será retornado para quem solicitou o arquivo.
O cliente faz um request, através do URL,  o servidor recebe como DNS e devolve um IP para o cliente acessar os arquivos, no [[cliente-side]] o servidor envia os arquivos para o cliente (response e o navegador faz o processamento dos arquivos, enquanto no [[server-side]] o servidor processa os scripts , gera arquivos HTML e CSS e os envia para o cliente.

## O que criar com o PHP
É importante entender quais os principais uso dessa linguagem, assim é possível ser mais eficiente em seu uso. Os usos mais comuns para o PHP:
- Websites;
- E-commerce;
- Plataforma EAD:

## Abrindo um arquivo PHP
É importante entender o funcionamento do server-side, pois para executar os scripts PHP é necessário um servidor, então vamos transformar nossa máquina em um. Portanto, será necessário o [[Apache]], [[MySQL]] e o PHP. Por serem comumente usadas em conjunto, a tríade ficou conhecida como solução **AMP** e por ser popular, tem uma versão para cada [[Sistema Operacional]] (SO). O [[Linux]], LAMP,  o [[Windows]], WAMP e o [[MAC]], MAMP. Utilizaremos o [[XAMPP]], que funciona em qualquer SO. Após baixar e instalar o XAMPP é necessário fornecer permissões de administrador para que o arquivo funcione corretamente.

## Tags
- `<?php ?>` : A super tag é a mais utilizada na versão 8.2 do PHP
- `<?   ?>`: short open tag
- `<%   %>`: asp tag
- `<script language:"php">`: o script é usado pra JavaScript, e até a versão 5 do PHP também era válido

A short open tag

























## Bibliografia
https://www.php.net/manual/pt_BR/
