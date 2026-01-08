<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1291642266829459487/1458875321141952756/orbyon-pay-logo.png" alt="Orbyon Pay" width="280" />
</p>


<h1 align="center">Orbyon Pay</h1>

<p align="center">
  <strong>Plataforma de Pagamentos Digitais para o Mercado Brasileiro</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.3-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.6-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-6.0-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind-3.4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Supabase-Cloud-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Fastify-5.x-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Stripe-Payments-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe" />
  <img src="https://img.shields.io/badge/Efí_Bank-Pix-00D4AA?style=flat-square" alt="Efí Bank" />
  <img src="https://img.shields.io/badge/PCI_DSS-Compliant-success?style=flat-square" alt="PCI DSS" />
  <img src="https://img.shields.io/badge/LGPD-Compliant-success?style=flat-square" alt="LGPD" />
</p>

---

## 📌 Apresentação

A **Orbyon Pay** é uma plataforma de pagamentos digitais desenvolvida para atender vendedores, empreendedores e negócios que operam no ambiente digital brasileiro. Nossa solução oferece processamento de pagamentos via **Pix** e **Cartão de Crédito**, com foco em segurança, velocidade e experiência do usuário.

### O que a Orbyon Pay resolve?

O mercado de pagamentos digitais no Brasil ainda enfrenta desafios como taxas elevadas, processos burocráticos, suporte ineficiente e falta de transparência. A Orbyon Pay foi criada para oferecer uma alternativa moderna, acessível e confiável para quem precisa receber pagamentos online.

### Para quem foi criada?

| Perfil | Descrição |
|--------|-----------|
| **Vendedores Digitais** | Infoprodutores, criadores de conteúdo, afiliados |
| **Empreendedores** | Lojas virtuais, prestadores de serviço, freelancers |
| **Empresas** | Negócios que precisam de uma solução robusta e escalável |
| **Players e Creators** | Comunidades, gamers, streamers e produtores de conteúdo |

### Diferenciais

- ✅ **Taxas competitivas e transparentes** — sem surpresas ou cobranças ocultas
- ✅ **Liberação rápida de saldo** — opções flexíveis de saque (Turbo e Flex)
- ✅ **Suporte humanizado** — atendimento real, não robôs
- ✅ **Painel completo** — gestão de vendas, relatórios, disputas e operações financeiras
- ✅ **Política FairPlay Pró-Vendedor** — proteção contra abusos de contestação

---

## 🛠️ Stack Tecnológica

### Frontend

| Tecnologia | Versão | Propósito |
|------------|--------|-----------|
| **React** | 18.3 | Biblioteca de UI reativa e componentizada |
| **TypeScript** | 5.6 | Tipagem estática para maior segurança e manutenibilidade |
| **Vite** | 6.0 | Build tool de alta performance com HMR |
| **Tailwind CSS** | 3.4 | Framework CSS utilitário para design consistente |
| **shadcn/ui** | Latest | Componentes acessíveis baseados em Radix UI |
| **React Query** | 5.x | Gerenciamento de estado de servidor e cache |
| **React Router** | 6.x | Navegação SPA com lazy loading |
| **React Hook Form** | 7.x | Formulários performáticos com validação Zod |
| **Framer Motion** | Latest | Animações fluidas e micro-interações |
| **Recharts** | 2.x | Gráficos e visualização de dados |

### Backend & Database

| Tecnologia | Propósito |
|------------|-----------|
| **Supabase (PostgreSQL)** | Banco de dados relacional com RLS (Row Level Security) |
| **Supabase Auth** | Autenticação JWT com 2FA e refresh automático |
| **Supabase Edge Functions** | Funções serverless em Deno para lógica de negócio |
| **Supabase Realtime** | Atualizações em tempo real via WebSocket |
| **Supabase Storage** | Armazenamento seguro de documentos KYC |
| **Fastify** | API REST de alta performance (Node.js) |
| **Prisma** | ORM type-safe para interação com banco de dados |
| **Zod** | Validação de schemas e sanitização de dados |

### Integrações de Pagamento

| Provedor | Modalidade | Recursos |
|----------|------------|----------|
| **Stripe** | Cartão de Crédito | Payment Intents, 3D Secure 2.0, Webhooks |
| **Efí Bank** | Pix | Cobrança imediata, QR Code dinâmico, mTLS |

### Infraestrutura & DevOps

| Tecnologia | Propósito |
|------------|-----------|
| **AWS EC2** | Hospedagem de API e Proxy |
| **Nginx** | Reverse proxy, SSL termination, load balancing |
| **PM2** | Process manager para Node.js com auto-restart |
| **GitHub Actions** | CI/CD automatizado para deploys |
| **Certbot** | Certificados SSL/TLS automáticos (Let's Encrypt) |

### Segurança & Compliance

| Tecnologia | Propósito |
|------------|-----------|
| **mTLS (Mutual TLS)** | Autenticação mútua para webhooks críticos |
| **reCAPTCHA v3** | Proteção contra bots em formulários sensíveis |
| **TOTP (2FA)** | Autenticação de dois fatores via app |
| **AES-256-GCM** | Criptografia de dados sensíveis |
| **SHA-256** | Hashing seguro de senhas e tokens |
| **HMAC** | Validação de assinaturas de webhooks |

### Comunicação

| Provedor | Canal | Recursos |
|----------|-------|----------|
| **Infobip** | WhatsApp Business | Templates, bot automatizado, notificações |
| **Zenvia** | E-mail | Alertas de login, notificações transacionais, recuperação de senha |
| **Zenvia** | SMS | OTP, alertas de segurança, confirmações |
| **Umbler Mail** | Atendimento | E-mail corporativo para suporte e comunicação institucional |
---

## 🏗️ Arquitetura da Plataforma

```
┌───────────────────────────────────────────────────────────────┐
│                          USUÁRIOS                             │
│               (Vendedores, Admins, Clientes)                  │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                      FRONTEND (React SPA)                     │
│  ┌─────────────┐  ┌─────────────┐  ┌───────────────────────┐  │
│  │  Dashboard  │  │   Landing   │  │   Checkout Público    │  │
│  │  (Merchant) │  │    Page     │  │   (Pix + Cartão)      │  │
│  └─────────────┘  └─────────────┘  └───────────────────────┘  │
└───────────────────────────────┬───────────────────────────────┘
                                │
            ┌───────────────────┼───────────────────┐
            ▼                   ▼                   ▼
┌───────────────────┐  ┌───────────────────┐  ┌───────────────────┐
│   Supabase Auth   │  │  Edge Functions   │  │    Fastify API    │
│    (JWT + 2FA)    │  │   (Serverless)    │  │    (REST API)     │
└─────────┬─────────┘  └─────────┬─────────┘  └─────────┬─────────┘
          │                      │                      │
          └──────────────────────┼──────────────────────┘
                                 │
                                 ▼
┌───────────────────────────────────────────────────────────────┐
│                    SUPABASE (PostgreSQL)                      │
│  ┌───────────┐  ┌───────────┐  ┌───────────┐  ┌───────────┐   │
│  │  Profiles │  │   Orgs    │  │  Payments │  │   Audit   │   │
│  │  (Users)  │  │  (Tenant) │  │    (Tx)   │  │   Logs    │   │
│  └───────────┘  └───────────┘  └───────────┘  └───────────┘   │
│                                                               │
│  ┌───────────────────────────────────────────────────────┐    │
│  │            Row Level Security (RLS) + RBAC            │    │
│  └───────────────────────────────────────────────────────┘    │
└───────────────────────────────────────────────────────────────┘
                                │
            ┌───────────────────┼───────────────────┐
            ▼                   ▼                   ▼
┌───────────────────┐  ┌───────────────────┐  ┌───────────────────┐
│    Stripe API     │  │   Efí Bank API    │  │    Infobip API    │
│    (Cartões)      │  │   (Pix + mTLS)    │  │    (WhatsApp)     │
└───────────────────┘  └───────────────────┘  └───────────────────┘
```

### 🖥️ Frontend (Single Page Application)

Interface moderna construída com React e otimizada para performance:

- **Dashboard Merchant** — gestão completa de operações, saldo, transações e relatórios
- **Painel Administrativo** — controle total para equipe interna (KYC, suporte, antifraude)
- **Checkout Público** — páginas de pagamento otimizadas para conversão
- **Landing Page** — apresentação institucional com tema dinâmico (Dark Premium)
- **Status Page** — transparência sobre disponibilidade dos serviços

### ⚙️ Backend (Edge Functions + API)

Processamento distribuído entre funções serverless e API dedicada:

| Componente | Responsabilidade |
|------------|------------------|
| **Edge Functions** | Operações rápidas: auth, webhooks, notificações, validações |
| **Fastify API** | Lógica de negócio complexa, integrações financeiras, antifraude |
| **Proxy mTLS** | Comunicação segura com Efí Bank (certificados mútuos) |

### 🗄️ Banco de Dados

Estrutura multi-tenant com isolamento por organização:

```
profiles          → Dados de usuário, KYC status, preferências
organizations     → Tenants (empresas/vendedores)
memberships       → Vínculos RBAC (CEO, ADMIN, MERCHANT, SUPPORT)
transactions      → Histórico de pagamentos Pix
credit_card_*     → Transações, tokens, disputas, ledger de cartão
balances          → Saldo disponível, bloqueado, pendente
disputes          → Contestações e evidências
audit_logs        → Registro imutável de ações
```

---

## 🔐 Segurança e Proteção de Dados

### Camadas de Proteção

```
┌──────────────────────────────────────────────────────────────┐
│  1. WAF + DDoS Protection (Cloudflare)                       │
├──────────────────────────────────────────────────────────────┤
│  2. SSL/TLS + mTLS (Nginx + Certbot)                         │
├──────────────────────────────────────────────────────────────┤
│  3. reCAPTCHA v3 (Proteção contra bots)                      │
├──────────────────────────────────────────────────────────────┤
│  4. JWT + 2FA (Autenticação e sessões)                       │
├──────────────────────────────────────────────────────────────┤
│  5. RBAC + RLS (Controle de acesso granular)                 │
├──────────────────────────────────────────────────────────────┤
│  6. Antifraude (Regras de velocidade, blocklist, scoring)    │
├──────────────────────────────────────────────────────────────┤
│  7. Criptografia AES-256 (Dados sensíveis em repouso)        │
├──────────────────────────────────────────────────────────────┤
│  8. Audit Trail (Logs imutáveis com request_id)              │
└──────────────────────────────────────────────────────────────┘
```

### Práticas Implementadas

| Área | Implementação |
|------|---------------|
| **Autenticação** | JWT com refresh automático, 2FA via TOTP, lockout progressivo |
| **Autorização** | RBAC multi-tenant com isolamento por `org_id` |
| **Dados de Cartão** | Tokenização via Stripe, nunca armazenamos PAN completo |
| **Comunicação** | HTTPS obrigatório, mTLS para webhooks críticos |
| **Validação** | Schemas Zod em todas as entradas, sanitização de dados |
| **Idempotência** | Chaves de idempotência em transações e webhooks |
| **Auditoria** | Logs imutáveis com `request_id` para rastreabilidade |

### Conformidade

- ✅ **PCI DSS** — Padrões de segurança para dados de cartão
- ✅ **LGPD** — Lei Geral de Proteção de Dados Pessoais
- ✅ **BACEN** — Normas do Banco Central para arranjos de pagamento
- ✅ **3D Secure 2.0** — Autenticação forte em transações de cartão

---

## 🧾 Compliance e Conformidade

### Prevenção à Lavagem de Dinheiro (AML)

- Monitoramento de transações suspeitas em tempo real
- Regras de velocidade e limites por perfil de risco
- Bloqueio preventivo e comunicação às autoridades quando aplicável
- Relatórios de atividades atípicas

### Verificação de Identidade (KYC/KYB)

| Tipo | Documentos Exigidos |
|------|---------------------|
| **Pessoa Física (16+)** | Documento de identidade com foto, selfie, comprovante de endereço |
| **Menor (16-18 anos)** | Documentos do menor + formulário de consentimento do responsável |
| **Pessoa Jurídica** | Contrato Social, Cartão CNPJ, CCMEI (se MEI) |

### Auditoria e Rastreabilidade

- Trilha de auditoria completa com `request_id` único
- Histórico imutável de todas as operações
- Logs de acesso e alterações de configuração
- Relatórios para conformidade regulatória

---

## 📜 Regras de Uso

### Atividades Permitidas

- ✅ Comercialização de produtos e serviços digitais legítimos
- ✅ Infoprodutos, cursos, mentorias, consultorias
- ✅ Assinaturas e recorrências
- ✅ Serviços de tecnologia e software

### Atividades Proibidas

- ❌ Fraudes, golpes ou esquemas financeiros ilícitos
- ❌ Lavagem de dinheiro ou financiamento de atividades ilegais
- ❌ Produtos ou serviços proibidos por lei brasileira
- ❌ Uso de identidades falsas ou documentos fraudulentos
- ❌ Abuso de mecanismos de contestação ou estorno

### Consequências de Violações

1. Bloqueio temporário da conta para investigação
2. Retenção de saldo conforme análise
3. Comunicação às autoridades quando aplicável
4. Encerramento definitivo do relacionamento comercial

---

## 🤝 Compromisso com Parceiros e Clientes

### Transparência Operacional

- Taxas e prazos claros, sem cobranças ocultas
- Status Page pública para acompanhamento de serviços
- Comunicação proativa sobre mudanças e atualizações

### Suporte

- Atendimento humanizado via WhatsApp e tickets
- Tempo de resposta médio: 2 horas (horário comercial)
- Escalonamento automático para casos críticos

### SLA de Disponibilidade

| Componente | Meta |
|------------|------|
| **API de Pagamentos** | 99.9% uptime |
| **Dashboard** | 99.5% uptime |
| **Webhooks** | Retry automático com backoff exponencial |

---

## 🚀 Visão de Futuro

### Roadmap

- 🔜 **Pix Parcelado** — Parcelamento via Pix com antecipação
- 🔜 **Split de Pagamentos** — Divisão automática entre vendedores
- 🔜 **Marketplace** — Suporte a múltiplos vendedores
- 🔜 **SDK Mobile** — Integração nativa para apps iOS/Android
- 🔜 **Open Finance** — Integração com ecossistema bancário aberto

### Posicionamento

Foco no segmento de vendedores digitais e creators, com diferenciação por:

- Qualidade técnica e segurança
- Suporte humanizado e transparência
- Política FairPlay pró-vendedor
- Taxas competitivas sem surpresas

---

## 📞 Contato

| Canal | Endereço |
|-------|----------|
| **Suporte** | suporte@orbyonpay.com |
| **Comercial** | comercial@orbyonpay.com |
| **DPO (Proteção de Dados)** | dpo@orbyonpay.com |
| **Jurídico** | juridico@orbyonpay.com |
| **Tutela (Menores)** | tutela@orbyonpay.com |

---

## 📄 Documentos Legais

- [Termos de Uso](https://orbyonpay.com/terms)
- [Política de Privacidade](https://orbyonpay.com/privacy)
- [Política FairPlay](https://orbyonpay.com/fairplay)
- [Compliance e Segurança](https://orbyonpay.com/compliance)
- [Status dos Serviços](https://orbyonpay.com/status)

---

<p align="center">
  <strong>Orbyon Pay</strong> — Um produto do grupo <strong>PlayHub Tecnologia LTDA</strong>
</p>

<p align="center">
  CNPJ: 60.634.208/0001-94 | Maringá/PR, Brasil
</p>

<p align="center">
  <sub>Documento atualizado em Janeiro de 2026</sub>
</p>
