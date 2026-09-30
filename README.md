# Funil de vendas

Funil de vendas completo em uma única página HTML, sem dependências. O produto de exemplo é o **Método Fermento Vivo**, um curso online de pão de fermentação natural.

**Ver online:** https://vitoriamir.github.io/funil-de-vendas/

## Etapas

| # | Etapa | O que faz |
|---|-------|-----------|
| 1 | Captura | Coleta nome e e-mail em troca de uma aula gratuita |
| 2 | Página de vendas | Vídeo de vendas, dores, módulos, depoimentos, oferta, garantia e FAQ |
| 3 | Checkout | Dados do cliente, forma de pagamento e order bump de R$ 27 |
| 4 | Upsell | Mentoria ao vivo de R$ 297, oferecida logo após a compra |
| 4b | Downsell | Gravações da mentoria por R$ 97, se o upsell for recusado |
| 5 | Obrigado | Resumo do pedido e próximos passos |

Cada etapa tem um endereço próprio: `#captura`, `#vendas`, `#checkout`, `#upsell`, `#downsell`, `#obrigado`.

## Antes de vender de verdade

- **Pagamento:** o checkout é um modelo e não cobra nada. Ligue o botão "Pagar" ao checkout da sua plataforma (Hotmart, Kiwify, Eduzz, Mercado Pago ou Stripe).
- **Leads:** os dados da captura ficam só no navegador do visitante. Conecte o formulário à sua ferramenta de e-mail marketing.
- **Depoimentos:** substitua os exemplos por depoimentos reais de alunos.
- **Vídeo e rodapé:** insira o vídeo de vendas e o CNPJ.
- **Barra "Visão do funil":** serve para navegar entre as etapas durante os testes. Remova o bloco `<nav class="funnelbar">` antes de divulgar.

## Rodar localmente

Abra o `index.html` no navegador. Não precisa de instalação.
