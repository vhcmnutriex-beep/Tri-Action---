# Calculadora de Tratamento – Tri Action e Confort

Calculadora web (Rennova Intimate) para compor o valor de venda do tratamento e simular condições de pagamento.

## Como usar
Abra `index.html` no navegador ou publique via **GitHub Pages** (Settings → Pages → Branch `main`, pasta `/root`).

## Estrutura
```
index.html                        # página da calculadora (HTML + CSS + JS)
assets/logo-rennova-intimate.png  # logo
```

## Regras de cálculo
- **Custo do tratamento** = soma dos insumos e produtos (qtde × valor unitário)
- **Receita bruta** = horas clínicas + aplicação/honorários
- **Imposto de renda** = (custo + receita bruta) × 16%
- **Taxa de cartão** = (custo + receita bruta + IR) × 5%
- **Valor de venda** = custo + receita bruta + IR + taxa de cartão
- **Condições de pagamento**: entrada = valor de venda × % de entrada; parcela = (valor de venda − entrada) ÷ nº de parcelas

Percentuais, itens, quantidades, valores e condições podem ser editados na própria página.
