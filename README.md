# CS50W - Project 0: Search 🔍

Um clone funcional das páginas de busca do Google (Pesquisa Normal, Pesquisa de Imagens e Pesquisa Avançada), desenvolvido como o primeiro projeto do curso **CS50’s Web Programming with Python and JavaScript** de Harvard.

## 🎯 Objetivo do Projeto
O objetivo deste projeto é construir uma interface front-end que não apenas replique a estética minimalista do Google, mas que também funcione na prática, enviando as consultas corretas (parâmetros de URL) diretamente para os servidores reais do Google.

## ✨ Funcionalidades
* **Pesquisa Normal (`index.html`):** Barra centralizada, botão de "Pesquisa Google" e o botão "Estou com sorte" (redirecionando diretamente para o primeiro resultado usando o parâmetro `btnI`).
* **Pesquisa de Imagens (`image.html`):** Redireciona a busca especificamente para a aba do Google Imagens utilizando parâmetros ocultos (`tbm="isch"`).
* **Pesquisa Avançada (`advanced.html`):** Interface alinhada à esquerda contendo quatro campos complexos de busca (todas as palavras, frase exata, qualquer palavra, nenhuma palavra), construindo a query string exata que o Google utiliza.
* **Navegação Integrada:** Links no canto superior direito permitindo transição fluida entre as três páginas.

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica e manipulação avançada de formulários (`<form>`, `<input type="hidden">`, atributos `name` e `action`).
* **CSS3:** Posicionamento de elementos, componentização visual e uso intensivo de **Flexbox** para alinhamentos (centralização absoluta, grids de busca avançada e espaçamentos no rodapé/cabeçalho).

## 🚀 Como Executar o Projeto
Como o projeto é puramente Front-End (não requer servidor ou banco de dados), executá-lo é extremamente simples:

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)