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

## Como mostrar o BI no GitHub

### Opção recomendada: publicar imagens do dashboard

Exporte uma imagem ou captura de cada página no Power BI e salve os arquivos, por exemplo, em `docs/imagens/`:

```text
docs/
└── imagens/
    ├── dashboard-visao-geral.png
    └── dashboard-detalhamento.png
```

Depois, inclua as imagens no README:

```markdown
## Prévia

![Visão geral do dashboard](docs/imagens/dashboard-visao-geral.png)
```

Essa é a forma mais simples e estável de apresentar o resultado no GitHub. Para boa leitura, use imagens em resolução adequada e, se necessário, adicione uma imagem por página ou por seção do relatório.

### Opção interativa: Power BI Service

Publique o relatório no **Power BI Service** e coloque no README um link para o relatório ou para um vídeo demonstrativo. Um relatório incorporado só funcionará para pessoas que tenham as permissões, licença e acesso ao ambiente do Power BI.

Não coloque no repositório um link de incorporação que exponha dados internos. A opção **Publicar na Web** torna o relatório acessível publicamente e deve ser usada somente com dados que possam ser divulgados sem restrições.

Exemplo de link no README:

```markdown
[Abrir dashboard interativo no Power BI](COLE_AQUI_O_LINK_DO_POWER_BI)
```

### Opção complementar: vídeo ou GIF

Grave uma navegação curta pelo dashboard e adicione o arquivo ao repositório ou a uma release. O README pode apontar para ele:

```markdown
[Assistir à demonstração do dashboard](docs/demo/dashboard.mp4)
```

Para um portfólio, a combinação mais eficaz costuma ser: **imagem estática no README + link interativo protegido + arquivo `.pbix` para download**.

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