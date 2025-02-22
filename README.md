## Projeto_Automacao_Buscas

## Projeto Automação Web - Busca de Preços

## Sobre o Projeto

Eu criei este projeto para praticar automação web com Selenium, buscando informações de preços em sites como Google Shopping e Buscapé. A ideia é simular o trabalho de um profissional de compras que precisa comparar preços de diferentes fornecedores para insumos e produtos.

## Objetivo

- Automatizar a pesquisa de produtos em sites de comparação de preços.
- Filtrar os resultados para considerar apenas aqueles com preços dentro de uma faixa definida (usando preço máximo e mínimo).
- Atualizar uma planilha com os produtos que atendem aos critérios.
- Enviar um e-mail com a lista dos produtos encontrados e seus respectivos links de compra.

## O Que Está Disponível

- Uma planilha com:
  - Nome do produto.
  - Preço máximo (para identificar se o produto está dentro do orçamento).
  - Preço mínimo (para evitar produtos com preços que não façam sentido).
  - Termos que devem ser evitados nas buscas.

## Funcionamento

1. **Busca:** Utilizo o Selenium para realizar buscas automatizadas nos sites.
2. **Filtragem:** Os resultados são filtrados com base na faixa de preço definida.
3. **Atualização:** A planilha é atualizada com os produtos que atendem aos critérios.
4. **Notificação:** Um e-mail é enviado (estou usando o email `pythonimpressionador@gmail.com` para testes; use seu e-mail para verificar se a mensagem está chegando).

## Alternativa com APIs

Embora este projeto foque em automação com Selenium, também é possível implementar a busca utilizando APIs de alguns serviços, se disponível.

Este projeto foi desenvolvido como parte de um desafio proposto pelo curso da Hashtag, com o objetivo de aplicar conceitos de automação e análise de dados em um cenário realista.# Projeto_Automacao_Buscas
