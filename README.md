# Scraper SalesBud (Ruby) — coleta automatizada + conformidade

> 📌 Case study. Projeto desenvolvido em ambiente profissional — este repositório descreve a solução; **não contém código nem dados proprietários**.

Pipeline em **Ruby** que automatiza o login seguro (SRP), coleta de forma **incremental** reuniões, transcrições e avaliações do **SalesBud**, gera um painel de conformidade e integra os dados ao Portal de Customer Success via **webhook com validação HMAC**.

## Problema
Coleta manual de reuniões e avaliações era lenta, sujeita a erro e sem visão de conformidade.

## Solução
- Autenticação **SRP** e sessão persistente
- Coleta **incremental** (apenas o que mudou)
- Normalização e envio via **webhook assinado (HMAC)** ao Portal CS
- Painel de conformidade

## Stack & conceitos
`Ruby` · `API SalesBud` · `Webhooks` · `HMAC` · automação · idempotência

## Resultado
Coleta manual substituída por um fluxo **automático e auditavel**.

