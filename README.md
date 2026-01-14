<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1291642266829459487/1458875321141952756/orbyon-pay-logo.png?ex=69613b05&is=695fe985&hm=450c69ac9e0d2e39dde407fd83d75847478972e9ddebd53d97a86f699974bb9e&" alt="Orbyon Pay" width="280" />
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
  <img src="https://img.shields.io/badge/Efí_Bank-Pix_&_Cartão-00D4AA?style=flat-square" alt="Efí Bank" />
  <img src="https://img.shields.io/badge/mTLS-Secured-00D4AA?style=flat-square" alt="mTLS" />
  <img src="https://img.shields.io/badge/PCI_DSS-Compliant-success?style=flat-square" alt="PCI DSS" />
  <img src="https://img.shields.io/badge/LGPD-Compliant-success?style=flat-square" alt="LGPD" />
</p>

---

## 📌 Apresentação

A **Orbyon Pay** é uma plataforma de pagamentos digitais desenvolvida para atender vendedores, empreendedores e negócios que operam no ambiente digital brasileiro. Nossa solução oferece processamento de pagamentos via **Pix** e **Cartão de Crédito** através da integração exclusiva com a **Efí Bank**, com foco em segurança, velocidade e experiência do usuário.

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

### Integração de Pagamentos — Efí Bank

| Modalidade | Recursos |
|------------|----------|
| **Pix** | Cobrança imediata, QR Code dinâmico, Pix Copia e Cola, Webhooks em tempo real |
| **Cartão de Crédito** | Tokenização segura, parcelamento, antifraude integrado, 3D Secure |
| **Infraestrutura** | mTLS (Mutual TLS), certificados de produção, ambiente sandbox para testes |

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
┌─────────────────────────────────────────────┐  ┌───────────────────┐
│              Efí Bank API                   │  │    Infobip API    │
│   (Pix + Cartão de Crédito via mTLS)        │  │    (WhatsApp)     │
└─────────────────────────────────────────────┘  └───────────────────┘
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

## 🗺️ Mapa de Operação — Integração Efí Bank

### Visão Geral do Fluxo

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                           ORBYON PAY × EFÍ BANK                             │
│                        Mapa de Operação Completo                            │
└─────────────────────────────────────────────────────────────────────────────┘

                              ┌─────────────────┐
                              │   CLIENTE       │
                              │   (Pagador)     │
                              └────────┬────────┘
                                       │
                    ┌──────────────────┼──────────────────┐
                    ▼                  ▼                  ▼
            ┌───────────────┐  ┌───────────────┐  ┌───────────────┐
            │  Checkout     │  │  Link de      │  │  QR Code      │
            │  Integrado    │  │  Pagamento    │  │  Dinâmico     │
            └───────┬───────┘  └───────┬───────┘  └───────┬───────┘
                    │                  │                  │
                    └──────────────────┼──────────────────┘
                                       ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                         ORBYON PAY BACKEND                                  │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │                    CAMADA DE ORQUESTRAÇÃO                           │    │
│  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐  ┌────────────┐  │    │
│  │  │  Validação  │  │ Idempotência│  │  Antifraude │  │   Ledger   │  │    │
│  │  │  de Dados   │  │   (Keys)    │  │  (Scoring)  │  │  (Balance) │  │    │
│  │  └─────────────┘  └─────────────┘  └─────────────┘  └────────────┘  │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
│                                       │                                     │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │                    PROXY mTLS (AWS EC2)                             │    │
│  │  ┌─────────────────────────────────────────────────────────────┐    │    │
│  │  │  Certificados de Produção Efí (client.p12 + ca.pem)         │    │    │
│  │  │  Autenticação Mútua TLS 1.2+                                │    │    │
│  │  │  Retry com Backoff Exponencial                              │    │    │
│  │  └─────────────────────────────────────────────────────────────┘    │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────────────────┘
                                       │
                                       ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                            EFÍ BANK API                                     │
│  ┌───────────────────────────────┐  ┌───────────────────────────────────┐   │
│  │         PIX                   │  │       CARTÃO DE CRÉDITO           │   │
│  │  • Cobrança Imediata (cob)    │  │  • Tokenização Segura             │   │
│  │  • QR Code Dinâmico           │  │  • Parcelamento (1-12x)           │   │
│  │  • Pix Copia e Cola           │  │  • 3D Secure 2.0                  │   │
│  │  • Devolução (refund)         │  │  • Antifraude Integrado           │   │
│  │  • Consulta de Status         │  │  • Captura/Cancelamento           │   │
│  └───────────────────────────────┘  └───────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
                                       │
                                       ▼
                              ┌─────────────────┐
                              │   WEBHOOKS      │
                              │   (Callbacks)   │
                              └────────┬────────┘
                                       │
                                       ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                      PROCESSAMENTO DE WEBHOOKS                              │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────────────────┐  │
│  │  Validação de   │  │  Idempotência   │  │  Atualização de Status      │  │
│  │  Assinatura     │  │  (webhook_inbox)│  │  (transactions + balances)  │  │
│  └─────────────────┘  └─────────────────┘  └─────────────────────────────┘  │
│                                       │                                     │
│                                       ▼                                     │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │                    NOTIFICAÇÕES                                     │    │
│  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐                  │    │
│  │  │  WhatsApp   │  │   E-mail    │  │    SMS      │                  │    │
│  │  │  (Infobip)  │  │  (Zenvia)   │  │  (Zenvia)   │                  │    │
│  │  └─────────────┘  └─────────────┘  └─────────────┘                  │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Fluxo de Pagamento Pix

```
┌──────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ Cliente  │───▶│ Orbyon Pay   │───▶│ Proxy mTLS   │───▶│  Efí Bank    │
│ (Payer)  │    │ (Backend)    │    │ (EC2)        │    │  (API Pix)   │
└──────────┘    └──────────────┘    └──────────────┘    └──────────────┘
     │                 │                   │                   │
     │  1. Solicita    │                   │                   │
     │     pagamento   │                   │                   │
     │────────────────▶│                   │                   │
     │                 │  2. POST /v2/cob  │                   │
     │                 │   (mTLS auth)     │                   │
     │                 │──────────────────▶│                   │
     │                 │                   │  3. Cria cobrança │
     │                 │                   │──────────────────▶│
     │                 │                   │                   │
     │                 │                   │  4. txid + QR     │
     │                 │                   │◀──────────────────│
     │                 │  5. QR Code       │                   │
     │                 │◀──────────────────│                   │
     │  6. Exibe QR    │                   │                   │
     │◀────────────────│                   │                   │
     │                 │                   │                   │
     │  7. Paga via    │                   │                   │
     │     app banco   │                   │                   │
     │─────────────────────────────────────────────────────────▶
     │                 │                   │                   │
     │                 │                   │  8. Webhook       │
     │                 │                   │     PIX_RECEIVED  │
     │                 │◀──────────────────────────────────────│
     │                 │                   │                   │
     │                 │  9. Atualiza      │                   │
     │                 │     status +      │                   │
     │                 │     saldo         │                   │
     │                 │                   │                   │
     │  10. Notifica   │                   │                   │
     │◀────────────────│                   │                   │
```

### Fluxo de Pagamento Cartão de Crédito

```
┌──────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ Cliente  │───▶│ Orbyon Pay   │───▶│ Proxy mTLS   │───▶│  Efí Bank    │
│ (Payer)  │    │ (Backend)    │    │ (EC2)        │    │  (API Card)  │
└──────────┘    └──────────────┘    └──────────────┘    └──────────────┘
     │                 │                   │                   │
     │  1. Dados do    │                   │                   │
     │     cartão      │                   │                   │
     │────────────────▶│                   │                   │
     │                 │  2. Tokeniza      │                   │
     │                 │     cartão        │                   │
     │                 │──────────────────▶│                   │
     │                 │                   │  3. Gera token    │
     │                 │                   │──────────────────▶│
     │                 │                   │  4. payment_token │
     │                 │◀──────────────────────────────────────│
     │                 │                   │                   │
     │                 │  5. Autoriza      │                   │
     │                 │     pagamento     │                   │
     │                 │──────────────────▶│                   │
     │                 │                   │  6. Processa      │
     │                 │                   │──────────────────▶│
     │                 │                   │                   │
     │                 │                   │  7. Resposta      │
     │                 │                   │     (approved/    │
     │                 │                   │      declined)    │
     │                 │◀──────────────────────────────────────│
     │                 │                   │                   │
     │  8. Resultado   │                   │                   │
     │◀────────────────│                   │                   │
     │                 │                   │                   │
     │                 │  9. Webhook       │                   │
     │                 │     (status)      │                   │
     │                 │◀──────────────────────────────────────│
```

### Endpoints Efí Bank Utilizados

| Categoria | Endpoint | Método | Descrição |
|-----------|----------|--------|-----------|
| **Auth** | `/oauth/token` | POST | Geração de access_token (OAuth 2.0) |
| **Pix** | `/v2/cob` | POST | Criar cobrança imediata |
| **Pix** | `/v2/cob/:txid` | GET | Consultar cobrança |
| **Pix** | `/v2/pix/:e2eid/devolucao/:id` | PUT | Solicitar devolução |
| **Pix** | `/v2/webhook/:chave` | PUT | Configurar webhook |
| **Cartão** | `/v1/card/payment` | POST | Criar pagamento com cartão |
| **Cartão** | `/v1/card/payment/:id` | GET | Consultar pagamento |
| **Cartão** | `/v1/card/payment/:id/refund` | POST | Estornar pagamento |

### Configuração mTLS

| Componente | Descrição |
|------------|-----------|
| **Certificado Cliente** | `client.p12` (PKCS#12) fornecido pela Efí |
| **CA Efí** | `ca.pem` para validação do servidor |
| **Ambiente** | Produção: `pix.api.efipay.com.br` / Sandbox: `pix-h.api.efipay.com.br` |
| **Proxy** | Nginx + Node.js em EC2 com PM2 |
| **Porta** | 443 (HTTPS com mTLS) |

### Webhooks Processados

| Evento | Origem | Ação na Orbyon Pay |
|--------|--------|-------------------|
| `pix.received` | Efí Pix | Confirma pagamento, credita saldo, notifica vendedor |
| `pix.refund` | Efí Pix | Registra devolução, debita saldo |
| `card.approved` | Efí Cartão | Confirma transação, agenda liberação de saldo |
| `card.declined` | Efí Cartão | Marca como falha, notifica cliente |
| `card.refunded` | Efí Cartão | Processa estorno, ajusta saldo |
| `card.chargeback` | Efí Cartão | Abre disputa, bloqueia valor, notifica vendedor |

### Gestão de Saldo

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         LEDGER DE SALDO (Double-Entry)                      │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐         │
│   │  SALDO BRUTO    │    │ SALDO DISPONÍVEL│    │ SALDO BLOQUEADO │         │
│   │  (Recebido)     │───▶│  (Liberado)     │    │  (Disputas)     │         │
│   └─────────────────┘    └─────────────────┘    └─────────────────┘         │
│          │                       │                      │                   │
│          │   Período de          │   Saque              │   Resolução       │
│          │   Liberação           │   (Turbo/Flex)       │   de Disputa      │
│          │   (D+14/D+30)         │                      │                   │
│          ▼                       ▼                      ▼                   │
│   ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐         │
│   │  Taxa Orbyon    │    │  Conta Bancária │    │  Liberação ou   │         │
│   │  (Deduzida)     │    │  do Vendedor    │    │  Perda          │         │
│   └─────────────────┘    └─────────────────┘    └─────────────────┘         │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Ciclo de Vida de uma Transação

| Status | Descrição | Próximos Estados |
|--------|-----------|------------------|
| `pending` | Aguardando pagamento | `paid`, `expired`, `cancelled` |
| `paid` | Pagamento confirmado | `available`, `disputed` |
| `available` | Saldo liberado para saque | `withdrawn` |
| `disputed` | Em contestação | `resolved_seller`, `resolved_buyer` |
| `withdrawn` | Saldo sacado | (final) |
| `refunded` | Devolvido ao pagador | (final) |
| `expired` | Expirou sem pagamento | (final) |

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
| **Dados de Cartão** | Tokenização via Efí Bank, nunca armazenamos PAN completo |
| **Comunicação** | HTTPS obrigatório, mTLS para webhooks críticos |
| **Validação** | Schemas Zod em todas as entradas, sanitização de dados |
| **Idempotência** | Chaves de idempotência em transações e webhooks |
| **Auditoria** | Logs imutáveis com `request_id` para rastreabilidade |

### Conformidade

- ✅ **PCI DSS** — Padrões de segurança para dados de cartão
- ✅ **LGPD** — Lei Geral de Proteção de Dados Pessoais
- ✅ **BACEN** — Normas do Banco Central para arranjos de pagamento
- ✅ **3D Secure 2.0** — Autenticação forte em transações de cartão via Efí Bank

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
  <strong>Orbyon Pay</strong> — Um produto da <strong>ORBYON PAY LTDA</strong>
</p>

<p align="center">
  CNPJ: 64.387.452/0001-50 | Maringá/PR, Brasil
</p>

<p align="center">
  <sub>Documento atualizado em Janeiro de 2026</sub>
</p>
