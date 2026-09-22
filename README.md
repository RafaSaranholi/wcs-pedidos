# WCS Pedidos

Estrutura inicial da plataforma:

- `index.html` — tela inicial: cliente ou proprietário.
- `cliente.html` — cardápio público, sem login.
- `admin.html` — login do proprietário via Supabase Auth.
- `painel.html` — painel inicial autenticado.

## Configuração atual

Supabase:
- Projeto: WCS PEDIDOS
- URL: https://ikhwsuofjmsqtjmjytzg.supabase.co
- Bucket público: `store-assets`

O arquivo `cliente.html` usa a loja de teste `loja-teste`.

## Próximas etapas

1. Validar login e sessão.
2. Criar painel real da loja.
3. Gerenciar categorias.
4. Gerenciar produtos, fotos e preços.
5. Receber pedidos.
6. Integrar checkout/Mercado Pago posteriormente.

A chave usada no frontend é a chave publicável do Supabase. Chaves secretas/service-role e credenciais de pagamento não devem ser colocadas em HTML público.
