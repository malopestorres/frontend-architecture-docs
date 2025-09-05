# 🏛️ Frontend Architecture Docs (`frontend-architecture-docs`)

> 🌐 **Idioma Padrão / Standard Language:** **Português (Brasil)** 🇧🇷

---

## 📌 Visão Geral

Bem-vindo ao repositório central de **Arquitetura e Governança de Frontend**. Este repositório serve como a **única fonte da verdade (Single Source of Truth)** para padrões de código, decisões arquiteturais (ADRs), guia de governança e boas práticas de engenharia frontend da organização.

O objetivo deste repositório é garantir que todos os times e aplicações sigam padrões consistentes de manutenibilidade, resiliência, performance e excelente experiência de desenvolvimento (DX).

---

## 📚 Índice de Módulos e Diretrizes

Abaixo estão os pilares de arquitetura documentados e disponíveis para consulta:

### 1. 🚩 Governança e Padronização de Feature Flags
* **Documento Oficial:** [Documentação de Feature Flags](file:///Users/marcustorres/Desktop/curso-aws-com-terraform/frontend-architecture-docs/docs/feature-flags.md)
* **Resumo:** Define o ciclo de vida, taxonomia (`release_`, `experiment_`, `ops_`), convenção de nomes (`snake_case`), tipagem em TypeScript, fallback fail-safe e política de eliminação de débito técnico (limpeza em até 30 dias).

### 2. 🏛️ Princípios de Arquitetura Frontend
* **Documento Oficial:** [Visão Geral de Arquitetura](file:///Users/marcustorres/Desktop/curso-aws-com-terraform/frontend-architecture-docs/docs/architecture-overview.md)
* **Resumo:** Princípios fundamentais de design de software, encapsulamento, camadas de abstração, resiliência e separação de responsabilidades nas aplicações web.

---

## 🔮 Próximos Tópicos no Radar (Em Construção)

À medida que a engenharia evolui, novos módulos serão integrados a este repositório:

- [ ] 🎨 **Design System & UI Components:** Padronização de componentes reutilizáveis, tokens visuais e acessibilidade (a11y).
- [ ] ⚡ **Performance & Web Vitals:** Estratégias de carregamento, code splitting, otimização de bundle e métricas LCP/FID/CLS.
- [ ] 🧪 **Estratégia de Testes:** Pirâmide de testes frontend (Unitários, Integração e End-to-End com Playwright/Cypress).
- [ ] 🔒 **Segurança no Frontend:** Proteção contra XSS, CSRF, sanitização de inputs e gestão segura de tokens JWT/Cookies.
- [ ] 🔄 **Gestão de Estado:** Diretrizes para estados locais vs globais vs servidor (React Query / RTK / Zustand).

---

## 🤝 Como Contribuir

Todas as alterações nos padrões de arquitetura devem passar por discussão via **Architecture Decision Records (ADR)** ou Pull Request neste repositório.

1. Faça um fork/branch deste repositório.
2. Escreva as alterações em **Markdown em Português (Brasil)**.
3. Certifique-se de preencher o [Template de Pull Request](file:///Users/marcustorres/Desktop/curso-aws-com-terraform/frontend-architecture-docs/.github/PULL_REQUEST_TEMPLATE.md).
4. Submeta o PR para revisão do time de Arquitetura / Tech Leads.
