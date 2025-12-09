
# Sistema de Rastreio de Validade e Estoque

Sistema completo em produção pra rede de supermercados. Automatiza coleta, análise e fiscalização de produtos.

## Arquitetura
- **Backend**: Node.js + Express + TypeScript + Prisma ORM + PostgreSQL (hospedado na nuvem com Docker/Render)
- **Dashboard Desktop**: Tauri (Rust + JS) pra análise de dados, gráficos e relatórios fiscais
- **App Coletor**: Mobile/desktop pra scan de mercadorias (integração com câmera/barcode) e sync em tempo real pro server

## Funcionalidades
- Coleta de dados de produtos (validade, lote, quantidade)
- Alertas automáticos de vencimento próximo
- Dashboard com métricas fiscais (export PDF/Excel)
- Sync seguro com nuvem (API RESTful + autenticação)

Prints: [Adiciona imagens do dashboard, app coletor e fluxograma]
