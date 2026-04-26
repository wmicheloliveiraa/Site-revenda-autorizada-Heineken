# Próximos Passos

## Curto Prazo
1. Extrair scripts inline de `code.html` para `assets/js/app.js`.
2. Extrair dados de produto para arquivo dedicado (`assets/data/products.js` ou JSON).
3. Parametrizar número oficial de WhatsApp em configuração central.

## Médio Prazo
1. Adicionar validação de telefone mais robusta e mensagem de erro contextual.
2. Implementar integração com CRM (captura de lead antes do redirecionamento).
3. Criar testes E2E para os fluxos:
   - adicionar/remover item,
   - persistência em reload,
   - envio de cotação via WhatsApp.

## Qualidade
1. Rodar auditoria Lighthouse (Performance, Acessibilidade e SEO).
2. Revisar contraste em todos os estados de botão.
3. Validar layout em breakpoints reais (360, 768, 1024, 1280+).
