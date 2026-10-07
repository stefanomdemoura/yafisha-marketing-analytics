# Y.Afisha — análise de marketing e economia unitária

Projeto de business analytics voltado à eficiência de aquisição e à otimização de despesas de marketing.

## Objetivo

Entender como usuários chegam ao produto, quando convertem, quanto valor geram e quais fontes de aquisição apresentam melhor relação entre custo e retorno.

## Ferramentas

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Principais análises

- DAU, WAU e MAU;
- sessões e duração de uso;
- retenção por coorte;
- tempo até a primeira compra;
- pedidos e ticket médio;
- Lifetime Value (LTV);
- investimento por fonte;
- CAC e ROMI;
- comparação por dispositivo, com ressalvas sobre a ausência de custo observado por device.

## Principais achados

- a maior parte das primeiras compras ocorre no mesmo dia da primeira visita;
- a retenção após o primeiro mês fica abaixo de 10%;
- a fonte 1 apresenta o melhor ROMI entre as origens analisadas;
- a fonte 3 combina alto investimento com retorno negativo e é o principal ponto de atenção;
- com o LTV corrigido por tamanho inicial da coorte, a média acumulada das coortes com pelo menos seis meses de observação fica próxima de 8;
- CACs de algumas fontes superam esse valor de referência, reforçando a necessidade de reavaliar a distribuição do orçamento.

## Dados

Os datasets não são redistribuídos neste repositório. Para executar o notebook localmente, coloque os arquivos indicados em `data/`.

Os outputs foram mantidos no notebook para permitir a leitura completa da análise diretamente no GitHub.
