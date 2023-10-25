# Controle de Finanças

Este é um projeto simples de controle de finanças desenvolvido em HTML, CSS e JavaScript. 
Ele permite que você registre suas entradas e saídas financeiras e acompanhe o saldo total.
Abaixo estão as instruções de como usar o projeto e uma visão geral do código.

## Como Usar 

1. Abra o arquivo index.html em seu navegador para acessar o aplicativo de controle de finanças.
2. Na seção "Novo Item", preencha os campos:
   * `Descrição`: Digite uma breve descrição para a transação.
   * `Valor`: Insira o valor da transação.
   * `Tipo`: Selecione se é uma entrada ou uma saída.
3. Clique no botão "Incluir" para adicionar a transação à lista.
4. Na seção "Resumo", você verá o total de entradas, saídas e o saldo geral.
5. Abaixo do resumo, a tabela exibe todas as transações registradas.
   Você pode remover uma transação clicando no ícone de lixeira correspondente a essa transação.

## Visão Geral do Código

O código-fonte deste projeto é dividido em HTML, CSS e JavaScript.

* HTML `(index.html)`: Este arquivo HTML define a estrutura do aplicativo de controle de finanças.
 Ele contém os elementos da interface do usuário, como entradas, saídas, total, formulário de adição de item e a tabela de transações.

* CSS `(style.css)`: O arquivo CSS fornece estilos para tornar o aplicativo mais atraente e usável.
  Ele formata os elementos, cria a aparência geral e define o layout da página.

* JavaScript `(script.js)`: Este é o coração do aplicativo. Ele lida com a lógica de adicionar, excluir e calcular transações.
  Aqui estão as principais funções:

  * `btnNew.onclick`: Captura o clique no botão "Incluir" e adiciona uma nova transação à lista.
  * `deleteItem(index)`: Remove uma transação da lista.
  * `insertItem(item, index)`: Cria uma nova linha na tabela para exibir uma transação.
  * `loadItens()`: Carrega as transações da memória local e exibe na tabela.
  * `getTotals()`: Calcula e exibe o total de entradas, saídas e o saldo geral.
  * Funções `getItensBD` e `setItensBD`: Lidam com o armazenamento de transações na memória local.
 
  ## Importante

  Este é um projeto de exemplo para controle de finanças e não persiste os dados de forma permanente.
  Os dados são armazenados localmente no navegador. Para uma aplicação real,
  você deve considerar o uso de um servidor ou banco de dados para armazenar dados de forma   segura e permanente.
  
   
### Acessar -> https://miltonnn.github.io/Controle-de-financas/
