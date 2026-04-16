# Relatório de Resgate de Projeto Mobile
**Aluno:** Kauã Albuquerque

## 1. Descrição dos Erros Encontrados
Após realizar o clone do projeto e utilizar as ferramentas de inspeção (Console F12), identifiquei os seguintes problemas deixados pelo desenvolvedor anterior:
* **Endpoint Inválido:** A URL de busca estava incorreta ou sem protocolo seguro.
* **Erro de Sintaxe JS:** O script possuía blocos de função abertos sem o devido fechamento com chaves `}`, impedindo o funcionamento do botão.
* **Falta de Limpeza de DOM:** O programa não limpava a lista antes de uma nova busca, gerando acúmulo de dados na interface.

## 2. Correções Realizadas
* **Correção da API:** Ajuste para o endpoint oficial `https://jsonplaceholder.typicode.com/posts`.
* **Tratamento de Erros:** Implementação de `.catch()` para tratar falhas de requisição.
* **Organização de Código:** O código JavaScript foi refatorado e movido para um arquivo externo (`script.js`) para melhor manutenção.

## 3. Melhorias na Interface (PLUS)
* **Design Moderno:** Adicionado um container centralizado com sombra (`box-shadow`) e bordas arredondadas.
* **Feedback Visual:** Implementado efeito de escala e cor no botão (`hover`).
* **Estilização de Itens:** Cada post agora aparece em um card com borda destacada para facilitar a leitura.
* **Limitação de Resultados:** Definido o limite de 10 itens para manter o layout limpo.

---
*Atividade desenvolvida para a Avaliação do 1º Bimestre.*