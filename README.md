# Elementos de formulário de cadastro

![código.do.projeto](img/codigo.png) 

## `form`
O elemento HTML "form" representa uma seção do documento contendo controles interativos para envio de informações.


## `method`
* encontrado na linha 12

O método HTTP para enviar o formulário. Os únicos métodos/valores permitidos são (sem distinção entre maiúsculas e minúsculas):

### `post`
* encontrado na linha 12

O método POST; dados do formulário enviados como o corpo da solicitação.

### `action`
* encontrado na linha 12

A URL que processa o envio do formulário. Este valor pode ser substituído por um atributo formaction em um elemento <button>, <input type="submit"> ou <input type="image">. Este atributo é ignorado quando method="dialog" é definido.

## `label for`
* encontrado nas linhas 14, 19 e 23

O ID de um elemento de formulário relacionados com labelable no mesmo documento como o elemento label. O primeiro elemento tal no documento com uma ID correspondente ao valor do atributo é o controle marcado for este elemento etiqueta.

## `input type`
* encontrado nas linhas 15 e 20

O tipo de controle a ser exibido. O tipo padrão é text, se este atributo não for especificado. Os valores possíveis são:

  ### `email`
  * encontrado nas linhas 14 e 15

  Um campo para editar um endereço de e-mail. O valor do campo é validado para estar vazio ou ter um único endereço de e-mail válido antes de ser enviado. As pseudoclasses CSS :valid e :invalid são aplicadas apropriadamente.

  ### `id`
* encontrado nas linhas 15, 20 e 24

  Atributo global válido para todos os elementos, incluindo todos os tipos de entrada, define um identificador único (ID) que deve ser único em todo o documento. Sua finalidade é identificar o elemento durante a vinculação. O valor é usado como o valor do atributo <label>' forpara vincular o rótulo ao controle de formulário. tem menu de contexto

  ### `name`
* encontrado na linha 15

O nome do controle, que é enviado junto com os dados do formulário.

## `span`
* encontrado na linha 16

O elemento HTML <span> é um conteiner generico em linha para conteúdo fraseado , que não representa nada por natureza. Ele pode ser usado para agrupar elementos para fins de estilo (usando os atributos class ou id ), ou para compartilhar valores de atributos como lang. 

## `textarea`
* encontrado na linha 24
O elemento HTML <textarea> representa um controle de edição para uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre, como um comentário ou formulário de retorno.

### `id`
* encontrado na linha 24

Um atributo id para permitir que <textarea> seja associado a um elemento <label> para fins de acessibilidade.

## `button`
* encontrado na linha 26

O Elemento HTML <button> representa um botão clicável.





