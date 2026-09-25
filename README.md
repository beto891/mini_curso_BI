# Dashboard de Vendas Cacau

Dashboard desenvolvido em **Microsoft Power BI** para análise do desempenho de vendas da Cacau. O relatório consolida o histórico de pedidos, relaciona os produtos às suas categorias e permite explorar os resultados por período, produto e região.

## Visão geral

O arquivo `Mini_cursoBI.pbix` contém uma página com os seguintes elementos:

- cartões com os principais indicadores;
- gráfico de área para acompanhar o faturamento ao longo do tempo;
- mapa para análise por região;
- gráfico de rosca com a representatividade das vendas;
- ranking de produtos ou lojas;
- tabela detalhada;
- segmentação para filtrar a análise.

## Fontes de dados

| Arquivo | Conteúdo |
| --- | --- |
| `Historico Vendas.xlsx` | 100.000 registros de vendas, com pedido, data, produto, loja, quantidade, valor unitário e valor total. |
| `Cadastro Produtos.xlsx` | Cadastro de produtos, categorias e valores unitários. |
| `Lojas.pdf` | Material de referência das lojas utilizadas na análise regional. |

## Estrutura do repositório

```text
.
├── Cadastro Produtos.xlsx
├── Historico Vendas.xlsx
├── Lojas.pdf
├── Mini_cursoBI.pbix
├── Background.png
├── Background Editável.pptx
├── Logo Cacau.png
└── README.md
```

## Tecnologias

- Microsoft Power BI Desktop
- Power Query
- Microsoft Excel
- PDF

## Observações

- Para compartilhar dados confidenciais, prefira imagens sem dados sensíveis ou um link do Power BI Service com autenticação.