- ![Computer](../images/prints/computer.png)
  - ![Print](../images/prints/02-home.png)

# HOME

| Ícone               | Legenda                                            |
| ------------------- | -------------------------------------------------- |
| :large_blue_circle: | Campo funcional                                    |
| :no_entry:          | Não possui o campo ou apenas para controle interno |
| :black_circle:      | Campo obrigatório no admin                         |


&nbsp;

## FULLBANNER PRINCIPAL

**_Informações:_**

| Dúvida                | Instrução                                                        |
| --------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**    | Banners                                                          |
| **Onde será exibido** | Banner principal abaixo do header, ocupa 100% da largura da tela |
| **Cadastro exemplo**  | [Admin](https://inobvia.vnda.dev/admin/midias/editar?id=1) |

&nbsp;

**_Orientações sobre os campos:_**

| Campo               | Funcional?          | Orientação                                                            |
| ------------------- | ------------------- | --------------------------------------------------------------------- |
| **Imagem**          | :large_blue_circle: | Dimensão sugerida Desktop: 2200x1012 pixels, Mobile: 1000x1460 pixels |
| **Título**          | :black_circle:      | Alt da imagem                                                         |
| **Subtítulo**       | :large_blue_circle: | Título do botão e posição do texto do banner. Opções a baixo!         |
| **Descrição**       | :large_blue_circle: | Título e descrição do banner                                          |
| **Externo?**        | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba                |
| **URL**             | :large_blue_circle: | Link de direcionamento                                                |
| **Posição Desktop** | :black_circle:      | `home-banner-principal`                                        |
| **Posição Mobile**  | :black_circle:      | `home-banner-principal-mobile`                                 |
| **Cor**             | :large_blue_circle: |  Cor dos textos                                                       |

&nbsp;

**_Exemplo de subtítulo:_**

```md
CALL TO ACTION | left-center
```

**_Exemplo de descrição:_**

```md
\#\#\# UPPER TITLE
\#\# Título do Banner

Descrição do banner alinhado à esquerda.
```

**OBSERVAÇÃO**: Obrigatório remover as barras antes dos jogos da velha (hashtag).

&nbsp;

**_Posições do botão possíveis para colocar no campo subtítulo:_**

- left-top
- left-center
- left-bottom

- center-top
- center-center
- center-bottom

- right-top
- right-center
- right-bottom


&nbsp;

## GRID

***Informações:***

| Dúvida                          | Instrução                                                        |
| ------------------------------- | ---------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                          |
| **Onde será exibido**           | Banner principal abaixo do header, ocupa 100% da largura da tela |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.dev/admin/midias/editar?id=24)    |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                                        |
| ------------- | ------------------- | ----------------------------------------------------------------- |
| **Imagem**    | :large_blue_circle: | As duas imagens laterais devem ter 750 x 1125 pixels. Já as imagens centrais devem ter 750 x 650 pixels. |
| **Título**    | :black_circle:      | Alt da imagem                                                     |
| **Subtítulo** | :large_blue_circle: | Texto sobre a imagem                                              |
| **Descrição** | :no_entry:          |                                                                   |
| **Externo?**  | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba            |
| **URL**       | :large_blue_circle: | Link de direcionamento                                            |
| **Posição**   | :black_circle:      | `home-banner-apoio`                                               |
| **Cor**       | :no_entry:          |                                                                   |

&nbsp;

## TÍTULO DA GRID

***Informações:***

| Dúvida                          | Instrução                                                          |
| ------------------------------- | ------------------------------------------------------------------ |
| **Onde cadastrar**              | Banners                                                            |
| **Onde será exibido**           | Título da seção de grid                                            |
| **Cadastro exemplo em staging** | [Admin]([#](https://inobvia.vnda.dev/admin/midias/editar?id=32)) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação           |
| ------------- | ------------------- | -------------------- |
| **Imagem**    | :black_circle:      |                      |
| **Título**    | :black_circle:      | Não exibido no front |
| **Subtítulo** | :large_blue_circle: | Título da seção      |
| **Descrição** | :no_entry:          |                      |
| **Externo?**  | :no_entry:          |                      |
| **URL**       | :no_entry:          |                      |
| **Posição**   | :black_circle:      | `home-titulo-apoio`  |
| **Cor**       | :no_entry:          |                      |


&nbsp;

## SLIDER DE PRODUTOS

***Informações:***

| Dúvida                          | Instrução                                                               |
| ------------------------------- | ----------------------------------------------------------------------- |
| **Onde cadastrar**              | Tags                                                                    |
| **Onde será exibido**           | Seção com slider de produtos e fundo colorido                           |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/tags/editar?id=slider-home) |

&nbsp;

***Informações sobre os campos***

| Campo         | Funcional?          | Orientação                                |
| ------------- | ------------------- | ----------------------------------------- |
| **Nome**      | :black_circle:      | `home-slider`                             |
| **Título**    | :large_blue_circle: | Título da sessão                          |
| **Subtítulo** | :large_blue_circle: | Hexadecimal da cor de fundo da seção      |
| **Descrição** | :no_entry:          |                                           |
| **Tipo**      | :no_entry:          |                                           |
| **Imagem**    | :large_blue_circle: | Dimensões recomendadas: 800 x 1200 pixels |


&nbsp;

## TABS DE CATEGORIAS

***Informações:***

| Dúvida                          | Instrução                                              |
| ------------------------------- | ------------------------------------------------------ |
| **Onde cadastrar**              | Menu                                                   |
| **Onde será exibido**           | Tabs de categoria da home                              |
| **Níveis**                      | 1 nível                                                |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/navegacao) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?     | Orientação                                 |
| ------------- | -------------- | ------------------------------------------ |
| **Título**    | :black_circle: | Título da tab                              |
| **Tooltip**   | :no_entry:     |                                            |
| **Descrição** | :no_entry:     |                                            |
| **Posição**   | :black_circle: | `home-produtos`                            |
| **Externo?**  | :no_entry:     |                                            |
| **URL**       | :black_circle: | Selecionar a tag que irá puxar os produtos |

&nbsp;

## TITULO TABS DE CATEGORIAS

***Informações:***

| Dúvida                          | Instrução                                                       |
| ------------------------------- | --------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                         |
| **Onde será exibido**           | Título da seção de tabs                                         |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/midias/editar?id=4) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação           |
| ------------- | ------------------- | -------------------- |
| **Imagem**    | :no_entry:          |                      |
| **Título**    | :black_circle:      | Não exibido no front |
| **Subtítulo** | :large_blue_circle: | Título da seção      |
| **Descrição** | :no_entry:          |                      |
| **Externo?**  | :no_entry:          |                      |
| **URL**       | :no_entry:          |                      |
| **Posição**   | :black_circle:      | `home-titulo-tabs`   |
| **Cor**       | :no_entry:          |                      |


&nbsp;

## QUOTE

***Informações:***

| Dúvida                          | Instrução                                                       |
| ------------------------------- | --------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                         |
| **Onde será exibido**           | Seção de depoimentos                                            |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/midias/editar?id=5) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                                           |
| ------------- | ------------------- | -------------------------------------------------------------------- |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 150x150 pixels                                     |
| **Título**    | :black_circle:      | Alt da imagem                                                        |
| **Subtítulo** | :large_blue_circle: | Nome da pessoa do depoimento e texto abaixo separado por `-` (hífen) |
| **Descrição** | :large_blue_circle: | Texto do depoimento                                                  |
| **Externo?**  | :no_entry:          | Selecionar se o link do banner deve abrir em outra aba               |
| **URL**       | :no_entry:          | Link de direcionamento                                               |
| **Posição**   | :black_circle:      | `home-frase`                                                         |
| **Cor**       | :no_entry:          | Selecionar a cor do texto e do botão                                 |


&nbsp;

## POSTS

***Informações:***

| Dúvida                          | Instrução                                                       |
| ------------------------------- | --------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                         |
| **Onde será exibido**           | Listagem de posts da home                                       |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/midias/editar?id=6) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação                                             |
| ------------- | ------------------- | ------------------------------------------------------ |
| **Imagem**    | :large_blue_circle: | Dimensão sugerida 750 x 750 pixels                     |
| **Título**    | :black_circle:      | Título do post                                         |
| **Subtítulo** | :large_blue_circle: | Subtítulo do post                                      |
| **Descrição** | :large_blue_circle: | Resumo                                                 |
| **Externo?**  | :large_blue_circle: | Selecionar se o link do banner deve abrir em outra aba |
| **URL**       | :large_blue_circle: | Link de direcionamento                                 |
| **Posição**   | :black_circle:      | `home-post`                                            |
| **Cor**       | :no_entry:          |                                                        |

&nbsp;

## TITULO DA SESSÕES DE POSTS

***Informações:***

| Dúvida                          | Instrução                                                       |
| ------------------------------- | --------------------------------------------------------------- |
| **Onde cadastrar**              | Banners                                                         |
| **Onde será exibido**           | Título de seção de posts                                        |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.com.br/admin/midias/editar?id=9) |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?          | Orientação           |
| ------------- | ------------------- | -------------------- |
| **Imagem**    | :no_entry:          |                      |
| **Título**    | :black_circle:      | Não exibido no front |
| **Subtítulo** | :large_blue_circle: | Título da seção      |
| **Descrição** | :no_entry:          |                      |
| **Externo?**  | :no_entry:          |                      |
| **URL**       | :no_entry:          |                      |
| **Posição**   | :black_circle:      | `home-titulo-posts`  |
| **Cor**       | :no_entry:          |                      |

&nbsp;

## INSTAGRAM - TEXTO CENTRALIZADO

**_Informações:_**

| Dúvida                          | Instrução                                           |
| ------------------------------- | --------------------------------------------------- |
| **Onde cadastrar**              | Banners                                             |
| **Onde será exibido**           | Texto da seção do instagem                          |
| **Cadastro exemplo em staging** | [Admin](https://inobvia.vnda.dev)             |

&nbsp;

***Orientações sobre os campos:***

| Campo         | Funcional?     | Orientação             |
| ------------- | -------------- | ---------------------- |
| **Imagem**    | :large_blue_circle: | Ícone exibido ao lado do título. Dimensões sugeridas de 64x64 pixels |
| **Título**    | :black_circle:      | Utilizado para controle interno |
| **Subtítulo** | :large_blue_circle: | @ da marca \| texto do botão. Ex.: "@marcainstagram \| Seguir +" |
| **Descrição** | :large_blue_circle: | Breve texto exibido abaixo do título  |
| **Externo?**  | :no_entry:          |                        |
| **URL**       | :black_circle:      | Link para redirecionamento |
| **Posição**   | :black_circle:      | `home-instagram-texto` |
| **Cor**       | :no_entry:          |                        |

&nbsp;

**_Observações:_**

As imagens utilizadas no ambiente de desenvolvimento e pré produção, são apenas para demarcar a seção.
Para está seção aparecer em produção é necessário realizar a integração com o instagram. Caso deseje está opção, entrar em contato com o atendimento.

***

***
