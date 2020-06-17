# Análise de uma Matriz de Insumo-Produto Brasileira

Análise intersetorial simples de uma Matriz Insumo-Produto de Leontieff [retirada do IBGE](https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9085-matriz-de-insumo-produto.html).

## Conceitos 

- **Matriz Insumo-Produto:** um modelo que representa os setores da economia de um país ou de uma região através de uma matriz, para prever o impacto de alterações de um setor sobre os outros e de consumidores, do governo e de fornecedores estrangeiros sobre a economia, desenvolvido por [Wassily Leontief](https://pt.wikipedia.org/wiki/Wassily_Leontief). Cada coluna da matriz representa o valor monetário de insumos (*inputs*) de um setor e cada linha representa o valor monetário das saídas (*outputs*) de um setor, mostrando as relações de dependência dos setores da economia. 

- **Demanda Intermediária (DI):** É a soma das demandas internas dos setores da economia, consumida pelos setores. A produção total de setor, isto é, a soma dos valores de uma linha, equivale à Demanda Intermediária daquele setor.

- **Demanda Final (DF):** Demanda dos consumidores finais (população, governo e mercado externo), exlui-se o que é consumido para confecção de novos produtos (a demanda intermediária).

- **Consumo Intermediário: (CI)** É o consumo total de insumos de cada setor. Em outras palavras, equivale à soma dos valores de uma determinada coluna.

- **Valor Adicionado da Produção (VAB):** É o valor que cada setor da economia acresce ao valor final de tudo que foi produzido em uma região. Uma das formas de calcular o Produto Interno Bruto (PIB) de uma economia é pela soma dos VABs setoriais e dos impostos. É a principal medida do tamanho total de uma economia.

- **Valor Bruto da Produção (VBP):** O Valor Bruto da Produção equivale à soma da produção total (DI) com a demanda final: *VBP = DI + DF*. Também pode ser calculado pela soma do Consumo Intermediário com o Valor Adicionado da Produção de cada setor: *VBP = CI + VAB*. Com isso, temos que a soma das demandas equivale à soma das produções: *DI + DF = CI + VAB*.

- **Ligações:** relações entre os diferentes setores da economia.

- **Ligações para a frente:** relações de um setor A com outros setores como fornecedor.

- **Ligações para trás:** relações de um setor C com outros setores como demandante.

## Referências

- MODELO INPUT-OUTPUT. Disponível em <<https://pt.wikipedia.org/wiki/Modelo_input-output>>. Acesso em: 17 de junho de 2020.

## Licença

- GNU General Public License v3.0. Detalhes [aqui](https://github.com/ArthurPavezzi/analise-matriz-leontieff/blob/master/LICENSE).