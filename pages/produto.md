---
layout: default
title: Produto
---

- ![Computer](../images/prints/computer.png)
  - ![Print](../images/prints/04-produto.png)

# PRODUTO

| Ícone               | Legenda                                            |
| ------------------- | -------------------------------------------------- |
| :large_blue_circle: | Campo funcional                                    |
| :no_entry:          | Não possui o campo ou apenas para controle interno |
| :black_circle:      | Campo obrigatório no admin                         |

&nbsp;

**_Informações:_**

| Dúvida                       | Instrução                                                          |
| ---------------------------- | ------------------------------------------------------------------ |
| **Onde cadastrar**           | Produtos                                                           |
| **Onde será exibido**        | Página do produto                                                  |
| **Cadastro exemplo**         | [Admin](https://inobvia.vnda.dev/)                           |
| **Página para visualização** | [Página](https://inobvia.vnda.dev/)                          |

&nbsp;

**_Orientações sobre os campos:_**

## DESCRIÇÃO

Aceita Markdown.

&nbsp;

### COLLAPSES

- Os collapses são divididos por `- - -`
- O título dos collapses vai com `##` antes
- Modelo de descrição com collapses em Markdown:
- **Obrigatório emover as barras antes dos jogos da velha (hashtag) do exemplo em markdown**.

&nbsp;

```markdown
Ad duis nulla consectetur magna consequat incididunt non sit eu culpa officia consequat eiusmod. In dolor excepteur excepteur adipisicing non est nostrud nulla mollit elit amet elit nostrud. Ipsum veniam ut cupidatat duis commodo fugiat sunt irure amet irure proident pariatur dolor. Minim minim occaecat esse eu. Dolore cillum eiusmod et tempor velit id cupidatat eu exercitation irure anim. Aliqua amet est irure eiusmod pariatur sit elit occaecat non qui quis consequat quis sit.

---

\#\# Título 1

Ad duis nulla consectetur magna consequat incididunt non sit eu culpa officia consequat eiusmod. In dolor excepteur excepteur adipisicing....

Ad duis nulla consectetur magna consequat incididunt non sit eu culpa officia consequat eiusmod. In dolor excepteur excepteur adipisicing....

---

\#\# Título 2

Ad duis nulla consectetur magna consequat incididunt non sit eu culpa officia consequat eiusmod. In dolor excepteur excepteur adipisicing....
```

&nbsp;

## VARIANTES

### ATRIBUTO 1 - COR

Para mostrar a cor em quadradinho/bolinha no campo onde vai o nome da cor colocar o hexadecimal depois do título da cor divido por `|`

Exemplo: `Amarelo | #ECE681`

&nbsp;

### ATRIBUTO 2 - TAMANHO

Tamanho do produto

&nbsp;

### ATRIBUTO 3

Escolher terceiro atributo do produto.

**_Observação:_**
Se desejar ativar atributo três, pedir para o desenvolvedor colocar o título correto no filtro

&nbsp;

## GUIA DE MEDIDAS

**_Informações:_**

| Dúvida                | Instrução                                                                      |
| --------------------- | ------------------------------------------------------------------------------ |
| **Onde cadastrar**    | Tags                                                                           |
| **Onde será exibido** | Popup de guia de medidas na página de produto                                  |
| **Cadastro exemplo**  | [Admin](https://inobvia.vnda.dev/)                                       |

&nbsp;

**_Informações sobre os campos_**

| Campo         | Funcional?          | Orientação                                                  |
| ------------- | ------------------- | ----------------------------------------------------------- |
| **Nome**      | :black_circle:      | Inserir nome da tag, que também será o link para a listagem |
| **Título**    | :large_blue_circle: | Não será exibido no front                                   |
| **Subtítulo** | :no_entry:          |                                                             |
| **Descrição** | :large_blue_circle: | Conteúdo da coluna da direita da popup                      |
| **Tipo**      | :black_circle:      | `guia-de-medidas`                                           |
| **Imagem**    | :large_blue_circle: | Imagem da coluna da esquerda da popup                       |

&nbsp;


&nbsp;

## TAG BANNER

**_Observações:_**

Inserir a tag nos produtos nos quais deseja-se banners. A tag é utilizada para indicar a posição do banner.

&nbsp;

**_Informações:_**

| Dúvida                | Instrução                                                                       |
| --------------------- | ------------------------------------------------------------------------------- |
| **Onde cadastrar**    | Tags                                                                            |
| **Onde será exibido** | Utilizada para indicar a posiçãos dos banners de produto               |
| **Cadastro exemplo**  | [Admin](https://inobvia.vnda.dev/admin/tags/editar?id=banner-produto-exemplo) |

&nbsp;

**_Informações sobre os campos_**

| Campo         | Funcional?          | Orientação                               |
| ------------- | ------------------- | ---------------------------------------- |
| **Nome**      | :black_circle:      | Posição dos banners da página de produto |
| **Título**    | :no_entry:          |                                          |
| **Subtítulo** | :no_entry:          |                                          |
| **Descrição** | :no_entry:          |                                          |
| **Tipo**      | :large_blue_circle: | `banner`                                 |
| **Imagem**    | :no_entry:          |                                          |

&nbsp;

## BANNERS DE PRODUTO

**_Informações:_**

| Dúvida                          | Instrução                                                     |
| ------------------------------- | ------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                       |
| **Onde será exibido**           | Banners espelhados na página de produto                       |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.dev/)                      |

&nbsp;

**_Orientações sobre os campos:_**

| Campo         | Funcional?          | Orientação                                                |
| ------------- | ------------------- | --------------------------------------------------------- |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 1000x625 pixels                         |
| **Título**    | :black_circle:      | Alt da imagem                                             |
| **Subtítulo** | :large_blue_circle: | Texto do botão. Só será exibido se uma url for cadastrada |
| **Descrição** | :large_blue_circle: | Texto do banner. Exemplo abaixo                           |
| **Externo?**  | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba    |
| **URL**       | :large_blue_circle: | Link de direcionamento                                    |
| **Posição**   | :black_circle:      | Definido no nome da tag do tipo `banner`                  |
| **Cor**       | :no_entry:          |                                                           |

**_Exemplo de descrição:_**

```md
\#\# TÍTULO DA SEÇÃO

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```

**OBSERVAÇÃO**: Obrigatório remover as barras antes dos jogos da velha (hashtag).

&nbsp;

## SEÇÃO COMPRE JUNTO (até 3 produtos)

**_Observações_**

- A tag agrupa os produtos.
- A seção vai aparecer na página de todos os produtos onde ela estiver.
- Adicionar a tag no mínimo em 2 (contanto o produto principal da página) e no máximo em 3 produtos.

&nbsp;

**_Informações:_**

| Dúvida                | Instrução                                                                          |
| --------------------- | ---------------------------------------------------------------------------------- |
| **Onde cadastrar**    | Tags                                                                               |
| **Onde será exibido** | Seção de compre junto                                                              |
| **Cadastro exemplo**  | [Admin](https://inobvia.vnda.dev/admin/tags/editar?id=comprejunto-produto-teste) |

&nbsp;

**_Informações sobre os campos_**

| Campo         | Funcional?          | Orientação                                                  |
| ------------- | ------------------- | ----------------------------------------------------------- |
| **Nome**      | :black_circle:      | Inserir nome da tag, que também será o link para a listagem |
| **Título**    | :large_blue_circle: | Título da seção                                             |
| **Subtítulo** | :no_entry:          |                                                             |
| **Descrição** | :no_entry:          |                                                             |
| **Tipo**      | :black_circle:      | `compre-junto`                                              |
| **Imagem**    | :no_entry:          |                                                             |


&nbsp;

## PRODUTOS RELACIONADOS

São um grupo de produtos agrupados por tag que são exibidos no final da página de produto

&nbsp;

**_Informações:_**

| Dúvida                | Instrução                                                            |
| --------------------- | -------------------------------------------------------------------- |
| **Onde cadastrar**    | Tags                                                                 |
| **Onde será exibido** | No final da interna de produto                                       |
| **Cadastro exemplo**  | [Admin](https://inobvia.vnda.dev/admin/tags/editar?id=relacionado) |

&nbsp;

**_Informações sobre os campos_**

| Campo         | Funcional?          | Orientação                 |
| ------------- | ------------------- | -------------------------- |
| **Nome**      | :black_circle:      | Inserir nome da tag        |
| **Título**    | :large_blue_circle: | Inserir o título da sessão |
| **Subtítulo** | :no_entry:          |                            |
| **Descrição** | :no_entry:          |                            |
| **Tipo**      | :black_circle:      | `relacionado`       |
| **Imagem**    | :no_entry:          |                            |

&nbsp;

**_Observação:_**

Os relacionados são carregados através da primeira tag do tipo `categoria` encontrada no produto. Caso o produto possua uma tag do tipo `relacionado`, essa tag tem prioridade no carregamento e é utilizada no lugar.


***
