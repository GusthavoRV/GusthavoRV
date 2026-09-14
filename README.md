# Gusthavo Rangel

**Full-Stack Developer** — Sorocaba/SP, Brasil
Tecnólogo em Análise e Desenvolvimento de Sistemas, FATEC Sorocaba (2024)

Desenvolvo um portfólio de SaaS e sistemas corporativos na
[FLAI Informática e Administração](https://www.flai.tec.br). Já coloquei
**mais de 10 produtos em produção** e opero a infraestrutura que sustenta
todos eles: ~40 VPS e 8 servidores on-premise.

---

## Domínios que eu conheço a fundo

Não se aprendem em tutorial. Cada um custou meses de caso de borda e incidente real.

| Domínio                    | O que eu já resolvi em produção                                                                             |
| -------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Fiscal brasileiro**      | NF-e, MDF-e, NFS-e, SEFAZ e Focus NFe, rejeições, DIFAL, import de XML, reforma tributária IBS/CBS          |
| **Pagamentos**             | Stripe, Asaas, Celcoin, PIX, escrow, conciliação, split                                                     |
| **Open Finance**           | Pluggy e Klavi: consentimento, sincronização de extrato, duplicata por troca de ID, fatura aberta de cartão |
| **Marketplaces**           | Mercado Livre, Shopee, Amazon                                                                               |
| **Logística**              | Correios, Melhor Envio                                                                                      |
| **IA aplicada**            | RAG multi-tenant com pgvector, agentes com Mastra, pipeline de voz (Deepgram + Claude + ElevenLabs)         |
| **Multi-tenant em escala** | Plataforma de assistência técnica autorizada rodando em 30 VPS, uma por rede credenciada                    |

---

## Stack

```
Backend         TypeScript · Fastify · NestJS · Drizzle · Zod · BullMQ · Argon2
                Go · Fiber
Frontend        Next.js · React 19 · TanStack Start · oRPC · Better Auth · Tailwind
Mobile          React Native · Expo Router · Zustand · Reanimated
                Flutter · Riverpod
Desktop         Electron · Tauri 2 · Wails
Dados           PostgreSQL · pgvector · SQLite · Redis · Cloudflare R2
IA              Mastra · Vercel AI SDK · Claude · OpenAI embeddings · Deepgram · ElevenLabs
Infra           Docker Compose · Kong · Traefik · Nginx · WireGuard · Pulumi
                Cloudflare Workers · AWS ECS Fargate + RDS
Observabilidade Grafana Alloy · Prometheus · Loki · SigNoz · Wazuh · CrowdSec
Automação       n8n · Chatwoot · Evolution API · Typebot
Tooling         pnpm workspaces · Turborepo · Biome · Vitest · Trigger.dev · EAS Build
Legado          Delphi 7 · SQL Server
```

---

## O que eu já construí

Uma amostra do que passou por mim, com o problema real de cada um:

**Plataforma multi-tenant para assistências técnicas autorizadas.**
Trinta VPS, uma por rede credenciada de fabricante. Inclui um app desktop em
Electron que preenche formulários de portais de terceiros por automação, e uma
ferramenta Android que lê Key Attestation com ES256 para emitir certificado de
apagamento de dados em conformidade com a LGPD.

**[Fintech de fluxo de caixa com Open Finance](https://mdfacil.net).**
Next.js e Fastify sobre Postgres com pgvector, dois VPS atrás de load balancer da
Cloudflare com WireGuard entre eles. Integração com Pluggy, Celcoin homologado
para iniciação de pagamento, e um copiloto de IA com RAG isolado por tenant.

**Plataforma DOOH de mídia em movimento.**
Backend em Go com Fiber, painel em Next.js, app em Flutter e um aplicativo
desktop em Wails. RBAC com 18 permissões.

**Microserviço multi-agente de análise de crédito com voz.**
Claude Haiku com fallback para Sonnet, orquestração em Mastra, ECS Fargate em
São Paulo, RDS Postgres com pgvector, observabilidade em SigNoz. Sessão de voz de
quatro minutos custando cerca de vinte centavos de dólar.

**Monorepo de observabilidade.**
Alloy, Prometheus e Loki com retenção em R2, Wazuh e CrowdSec para segurança,
WireGuard em topologia hub-and-spoke, tudo provisionado com Pulumi em TypeScript.

**SaaS de manutenção residencial.**
Fastify e Expo, publicado na Play Store. A App Store rejeitou duas vezes, por
5.1.1(v) e 5.1.2(i); as duas foram corrigidas e a submissão passou.

---

## Como eu trabalho

**Regra que importa vira trava de CI.** Padrão que só existe no acordo verbal
apodrece. Se a regra vale, ela ganha lint próprio com auto-teste provando que
dispara. Guarda que nunca falhou não é guarda, é decoração.

**Comentário explica o porquê, não o quê.** O código já diz o que faz. O que se
perde é a armadilha que a linha evita e o incidente que a originou.

**Uma auditoria não basta.** A segunda rodada sempre acha o que a primeira não
viu, inclusive regressões introduzidas pelas correções da primeira. Correção de
auditoria é mudança como qualquer outra e precisa da mesma revisão.

**Eu opero o que escrevo.** Runbook, monitoramento e postmortem fazem parte da
entrega. Boa parte do que sei de Docker, Nginx e rede veio de incidente, não de
documentação.

**Documentação junto do código.** Wiki versionada no repositório, ADRs numerados,
log de decisões. Nada fecha sem o registro do que mudou e por quê.

---

## Sobre os repositórios desta conta

O que aparece público aqui é, em boa parte, material de faculdade e de curso. O
trabalho que representa o que eu faço hoje é privado ou vive sob a organização da
empresa.

Se você chegou por um processo seletivo e quer ver código de verdade, me chame.
Consigo apresentar arquitetura, decisões e trechos do que está sob acordo de
confidencialidade.

---

## Contato

- **E-mail** — <gusthavorangel@gmail.com>
- **LinkedIn** — [gusthavo-rangel-vieira](https://www.linkedin.com/in/gusthavo-rangel-vieira-760527211/)
- **Conta corporativa** — [@gusthavo-rangel](https://github.com/gusthavo-rangel)
