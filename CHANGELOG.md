# Changelog

## 2026-04-25

### Fase 0 - Governança e Base
- Criado `.cursorrules` com princípios de semântica, acessibilidade e stack.
- Criada pasta `docs/` com:
  - `ARCHITECTURE.md`
  - `DESIGN_SYSTEM.md`
  - `PRODUCT_CATALOG.md`

### Fase 1 - Estrutura e UX Base
- Refatorado `code.html` para estrutura semântica com `header`, `main` e `footer`.
- Implementado menu mobile funcional com `aria-expanded`, clique externo e fechamento por `ESC`.
- Revisados CTAs e microcopy para navegação orientada à conversão.

### Fase 2 - Motor de Cotação
- Implementado estado global de cotação (`quoteState`) em JavaScript Vanilla.
- Adicionados controles de quantidade por card de produto.
- Criado resumo flutuante com contador total de itens.
- Persistência do estado via `localStorage`.

### Fase 3 - Drawer e WhatsApp
- Implementado drawer lateral para revisão da cotação.
- Adicionadas ações de remover item e limpar cotação.
- Conectado formulário de lead ao carrinho para envio via `wa.me`.
- Incluído estado vazio com orientação ao usuário.

### Fase 4 - Conversão, Acessibilidade e Performance
- Instrumentados eventos básicos de interação em `window.portalMetrics`.
- Reforçados labels, controles de foco e comportamento via teclado.
- Aplicado `loading="lazy"` e `decoding="async"` para imagens não críticas.

### Fase 5 - Encerramento
- Documentada entrega desta sprint e próximos passos operacionais.
