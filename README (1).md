# Análise de Funil e Tráfego Pago para um Negócio Local

Projeto de Extensão do curso de Análise e Desenvolvimento de Sistemas (ADS).
Estudo de caso de um pequeno negócio do setor de beleza, com dados anonimizados e uso autorizado.

## Contexto
Um pequeno empreendimento do setor de beleza passava meses com poucos atendimentos e dependia
quase exclusivamente de datas comemorativas para gerar demanda.

## Problema
Como aumentar o fluxo de clientes fora das datas comemorativas, entendendo onde o negócio
perdia oportunidades: alcance, atendimento e conversão de contatos em clientes?

## O que foi feito
1. **Diagnóstico:** análise da presença digital, do processo de atendimento e da forma de divulgação dos serviços.
2. **Oportunidades identificadas:** alcance nas redes sociais, conversão de contatos em clientes e produção de conteúdo.
3. **Ações:** estudo de boas práticas de tráfego pago e atendimento digital, e implementação de melhorias.
4. **Acompanhamento:** medição dos resultados no gerenciador de anúncios e no atendimento.

## Resultados
| Indicador | Resultado | Fonte |
| --- | --- | --- |
| Investimento em tráfego pago | R$ 100,16 | Gerenciador de anúncios |
| Conversas por mensagem iniciada | 30 | Gerenciador de anúncios |
| Custo por conversa | R$ 3,34 | Gerenciador de anúncios |
| Período da campanha | início de maio de 2026 *[confirme as datas exatas]* | Gerenciador de anúncios |
| Clientes atendidos após as melhorias | ~17 | Acompanhamento da autora |
| Seguidores e alcance do perfil | *[inclua antes/depois, se tiver]* | Insights do Instagram |

Além das vendas imediatas, pessoas que não fecharam o serviço passaram a seguir o perfil,
formando uma audiência que pode se tornar cliente no futuro.

## Métricas calculadas
| Métrica | Cálculo | Resultado |
| --- | --- | --- |
| Custo por conversa | R$ 100,16 ÷ 30 | R$ 3,34 |
| Conversão (conversa → cliente) | 17 ÷ 30 | ≈ 57% |
| CAC (custo por cliente) | R$ 100,16 ÷ 17 | ≈ R$ 5,89 |
| ROAS | receita ÷ investimento | *[preencher com o ticket médio]* |

> Nota sobre os dados: investimento, conversas e custo por conversa vêm do gerenciador de anúncios.
> Os ~17 clientes são atribuídos às ações implementadas com base no acompanhamento da autora durante
> o período. Não há registro formal que separe a origem de cada cliente, então conversão e CAC são estimativas.

## O que os dados mostram
- **Instagram concentrou quase todo o resultado.** Das 30 conversas, cerca de 29 vieram do Instagram e
  cerca de 1 do Facebook. O WhatsApp teve o maior alcance (~5,6 mil), mas praticamente nenhuma conversa
  (valores lidos do gráfico, aproximados).
- **Custo por conversa em linha com o mercado.** O gerenciador indicou custo 1,2% acima da mediana de
  conjuntos de anúncios semelhantes. O ganho do projeto veio mais do atendimento e da conversão do que de
  um anúncio mais barato.
- **Público de 25 a 44 anos recebeu cerca de 58% do investimento** (R$ 29,55 em 25–34 e R$ 28,39 em 35–44).
  Esse é o share de verba, não a conversão por faixa etária.
- **As conversas se concentraram nos primeiros dias** e caíram ao longo do período, o que vale investigar
  em campanhas futuras (cansaço do criativo, fim da verba).



## Limitações
- A atribuição dos clientes às ações é baseada no acompanhamento da autora, sem comprovação documental da origem de cada um.
- O projeto não tem grupo de comparação, então não é possível afirmar que as melhorias foram a única causa.
- Amostra pequena (R$ 100,16 de investimento, 30 conversas) e período curto.
- Não há resultado por faixa etária, apenas a distribuição da verba.

## Próximos passos
- Registrar a origem de cada cliente (anúncio, orgânico, indicação).
- Testar dois anúncios diferentes (teste A/B) e comparar custo por conversa.
- Concentrar o investimento no Instagram e medir o efeito.
- Acompanhar a recompra e a conversão de seguidores em clientes.

## Estrutura do repositório
```
├── README.md
├── evidencias/   # prints do gerenciador de anúncios
├── dados/        # planilha anonimizada (sem nomes nem telefones)
└── analise/      # notebook ou consultas SQL
```

## Tecnologias
Gerenciador de anúncios da Meta · Excel / Google Sheets *(inclua SQL, Python ou Power BI só se for usar)*

## Privacidade
Nenhum nome de cliente, telefone ou identificação do negócio foi publicado.
Os números foram usados com autorização da proprietária.

## Autora
Isabele Rodrigues · [LinkedIn](https://www.linkedin.com/in/isabelerodrigues-dados)
