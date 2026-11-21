# Calculadora de Renda Passiva

Ferramenta educacional em HTML puro para responder a pergunta mais comum de quem quer viver de renda:
**quanto preciso ter investido para receber X por mês?**

https://vitorsouzabnh.github.io/calculadora-renda-passiva/

## O que calcula

- Patrimônio necessário para a renda mensal desejada, em valores de hoje (taxa real)
- Tempo até a meta com aporte mensal
- Renda que o patrimônio atual já gera
- Comparação de patrimônio exigido em 5 tipos de investimento
- Gráfico da evolução do patrimônio até a meta

## Método

Patrimônio necessário = renda mensal × 12 ÷ taxa anual líquida real.

A taxa usada é real: o rendimento já descontada a inflação. Assim os R$ 10 mil de renda mantêm o poder
de compra de hoje. A evolução é simulada mês a mês, com o saldo rendendo e o aporte entrando.

Parâmetros padrão: CDI 13,65% a.a. (B3, 18/11/2026), IPCA 4,63% em 12 meses até outubro/2026 (IBGE).
Ambos editáveis na tela.

## Limites

Simulação educacional. Não é recomendação, não considera perfil, objetivos ou situação tributária real,
e não projeta volatilidade, taxas de administração nem variação de mercado.

## Uso

Arquivo único, sem dependência. Abra o `index.html` no navegador ou publique em qualquer host estático.
