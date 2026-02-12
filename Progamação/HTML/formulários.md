Para a criação de formulários usando o [[HTML]] é essencial o uso dos seguintes comandos:
```
<form> </form> ---->> Usado para criar um formulário HTML
   action="..." ---->> Para onde vai a informação
   method="..." ---->> Forma que as informações vão ser enviados (get= enviado pela URI, post=não aparece informações na URL)
   
<label> </label> ---->> Define o nome para elementos do formulário
   for="nome">Text: ---->> Indica a qual atributo está relacionado
   
<input> ---->> Define a entrada de dados e como vai ser
   type="..." ---->> Tipo de dados que está sendo enviado: text,password, etc.
   id
   name
*  required ---->> Marcar um campo como obrigatório
   value ---->> Deixar um valor padrão, opção como padrão
   readonly ---->> Somente leitura sem edição
   Placeholder ---->> Campo pré-preenchido que ao click desaparece
   
<select> </select> ---->>  Menu suspenso com opção de lista pre-definida
   id
   name
 <option> </option> ---->> Faz e mostra cada uma das opções do Select.
    value="..." ---->> Opção padrão e como irá aparecer.
    selected="..." ---->> Quando quer que seja carregado com opção pré-determinada.
    
<textarea> </textarea> ---->> Faz uma caixa com grande área de texto.
   id
   name
   cols="20" ---->> Quantas colunas será visível.
   rows="20" ---->> Quantas linhas será visível.
   
<buttom> </buttom> ---->> Botão cliclável que pressionado executará ação.
   type="..." ---->> buttom=botão sem ação; reset=limpar dados do formulário; submit=enviar dados para o servidor.
   
*required ---->> Obrigatório.
*minlegth ---->> Número mínimo de letras.
*maxlegth ---->> Número máximo de letras.
*type ---->> Tipos de dados esperados.
```