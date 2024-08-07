# Lista de Comandos Markdown
Markdown Syntax é uma sintaxe usada para padronizar e facilitar formatação de texto na web, utilizada em aplicativos como Slack e GitHub. Textos estilizados com Markdown são, na maioria dos casos, apenas texto com caracteres não-alfabéticos, como `#`, `\*` e `!` `[]` `()`, usados para a configuração de títulos, listas, itálico, negrito e inserção de imagens.  

O Markdown funciona como um conversor de texto para HTML: os caracteres não-alfabéticos são traduzidos como `<b>`, `<i>` e `<a href>`, etc. Já os textos sem formatação entram como parágrafo simples <p>

# Título
## Título
### Título
#### Título
##### Título
###### Título


# Ênfase
Para adicionar ênfase ao conteúdo que será escrito, usa-se o asterisco `*` ou traço-baixo (underline) `_`:

**Negrito**: adicione dois asteriscos **texto** ou dois traços-baixos __texto__ no início e no fim do conteúdo.

*Itálico*: adicione apenas um asterisco *texto* ou um traço-baixo _texto_ no início e no fim do conteúdo.


# Links
Existem duas formas de inserir link em Markdown, através de um link direto ou usando um texto-âncora:

**Texto-âncora**: Utilize os caracteres `[]` `()`, adicionando entre chaves o texto que você quer que apareça, e entre os parênteses, o endereço de destino, no formato `[exemplo](https://exemplo.com/)`.

[Google](google.com)

**Link direto**: Envolva o endereço da web em chaves `<>`. O endereço ficará visível e será clicável pelo usuário.
O endereço em forma de link direto tem o formato <https://exemplo.com/>.

# Listas de itens
Para listas não ordenadas, utilize um asterisco `*` na frente to item da lista:

* Item 1
- Item 2
+ Item 3

Para listas ordenadas, utilize o número do item seguido de ponto . :

1. Item 1
2. Item 2
3. Item 3

# Imagens
O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação `!` no início do código, como no exemplo abaixo:

`![Alt ou título da imagem](URL da imagem)`

Coelho:
![Coelho](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPbu-DRAeq30BZY75OYVO0fKp4JOgqFtCg0A&s)

Imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.


# Citação (Quote)
Para transformar um texto em uma citação ou comentário, semelhante ao código `HTML <blockquote>`, utilize o sinal > no início da linha que será formatada:

>Este é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
>código sinal. Isso gerará um novo parágrafo dentro do *blockquote*.
>Códigos de **negrito**, _itálico_ e <https://links.com> funcionam aqui.
Como aparece no HTML:


# Código (Code Highlight)
Há dois modos de adicionar trechos de código ao Markdown:

**Código em linha (inline):** adicione um acento grave ˋ no início e no final do código.

**Múltiplas linhas de código:** envolva as linhas de código com três acentos graves` ˋˋˋ ` ou três tils `~~~`.

 Esta é uma linha que contém um ˋcódigoˋ.

ˋˋˋ
Esta é uma linha de código
ˋˋˋ
 
Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o` ˋˋˋ `ou `~~~`, por exemplo ` ~~~javascript` ou `~~~ruby `. Veja nos exemplos abaixo:

~~~ javascript
Esta é uma linha de código em Javascript.
~~~

``` php
Esta é uma linha de código em PHP.
``` 

``` html
Esta é uma linha de código em HTML.
```

```sql
-- Criar o banco de dados
CREATE DATABASE meuBanco;

-- Usar o banco de dados criado
USE meuBanco;

-- Criar a tabela persoas
CREATE TABLE persoas (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(50) NOT NULL
);
```

# Tabela
Escolha os títulos das colunas e use | para delimitar as colunas. Depois, utilize hífen `-` na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o | para delimitar colunas. Veja um exemplo abaixo:

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize : ao lado do campo horizontal de hífens `---`, na segunda linha da sua tabela. Veja abaixo:

Alinhado a esquerda: usar : no lado esquerdo (alinhamento padrão);
Alinhado a direita: usar : no lado direito;
Centralizado: usar : dos dois lados.
Veja no exemplo:

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor

###### Resumo dos Comandos:

# Este é um Título

### E este um subtítulo

**Escrevendo em negrito**

*Escrevendo em Itálico*

[Texto clicável](https://umlink.com/)

<https://link.com/>

* Item 1
* Item 2

```sql
-- Criar o banco de dados
CREATE DATABASE meuBanco;
```
