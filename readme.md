# Naruto Banco de Dados em JavaScript

Este projeto é uma aplicação web que utiliza a API do Naruto para buscar informações sobre personagens do anime Naruto.

## Capturas de Tela

![Captura de Tela 1](https://blogger.googleusercontent.com/img/a/AVvXsEi6vVHFfj_LA98dT_6XSpu4sNNYEdRWvoAEDvWith5lV7vvrlPz1mUnyIRI2UBWDJ4krCjhSqBsWerN3RdHqVTWS1skQ2V2xhtpguYTaX9BAAaaQuqkBXolVOCVY_zkWE1eRMHh17P1HsGkPLJVWVMOTQfHMVfvh45AK5dCsYkNsq0PX4fsg_OujHLmXUBo)

![Captura de Tela 2](https://blogger.googleusercontent.com/img/a/AVvXsEjR88I4KUUjQmbshX78Sbx0o1CaOiBL1MORP7rIF45qTEGTmgG86H3GDqIHz2Zqo46d-xcJRcar4NPkb0tEGMX03TXvck_GqKODb7UbzTKz65CtMywM_POEC9vptSvF7buktsr40Wn0rSe-LvJstRkAPm6g-AHOk9KEyG9VNVOE1A5iUTX7Kc_HMY2c_cf0)

![Captura de Tela 3](https://blogger.googleusercontent.com/img/a/AVvXsEhLLySnSODpFGybXPVOXWY5TqTCfRPM6ECt7Vzg8-EU7_jKGSn-dfWpVqKEju1TXfdcelEKHaqqiIY7HfqOfxsMCQo57cfvvdb57Hr1nUBAAjI7Xp0D96GEiEKZ5GCjVxP4WC7tLLrCHieKKjHWsa4GvcK4cuDXYLe8tS4h9sVlPbC5hZ-jpMfuCrAmchSl)

## Funcionalidades

- Permite buscar um personagem pelo nome completo ou parte do nome ou ID do Personagem.
- Exibe informações detalhadas sobre o personagem encontrado, como seu nome, ID, estreia no anime, jutsu, tipo de natureza, gênero, classificação, ocupação, afiliação e ferramentas.
- Responsivo, adaptado para dispositivos móveis.

## Tecnologias Utilizadas

- JavaScript
- Fetch API
- HTML
- CSS

**Observação**: API do Naruto não oferece suporte para busca por parte do nome. Para contornar esse problema, foi implementada uma função no JavaScript que busca o personagem em todas as páginas disponíveis da API até encontrá-lo. Caso o personagem não seja encontrado em nenhuma página, será exibida uma mensagem indicando que o personagem não foi encontrado.

## Como Usar

1. Clone este repositório para o seu ambiente local.
2. Abra o arquivo `index.html` em um navegador web.
3. Insira o nome do personagem que deseja buscar no campo de busca e pressione o botão "Buscar" ou pressione a tecla "Enter".
4. Aguarde a busca ser concluída e as informações do personagem serão exibidas abaixo do campo de busca.

## Estrutura do Projeto

- `index.html`: Arquivo HTML principal que contém a estrutura da página.
- `styles.css`: Arquivo CSS para estilização da página.
- `script.js`: Arquivo JavaScript contendo as funcionalidades da aplicação.

## API Utilizada

O projeto utiliza a API do Naruto para buscar informações sobre os personagens. A URL base da API é `https://narutodb.xyz`.

## Como Contribuir

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou solicitações de alteração (pull requests) para sugerir melhorias, relatar bugs ou adicionar novas funcionalidades.

## Créditos

Desenvolvido por [Paulo Levi]()
