# Playbook 03 — Site Premium

> **Pulso Onboarding Framework** | Etapa 3 de 12

---

## Objetivo

Criar um site institucional de alto impacto que converta visitantes em pacientes, posicione a clínica como autoridade e sirva como hub central de toda presença digital.

---

## Quando Executar

- Após aprovação da Identidade Visual (Playbook 02)
- Duração estimada: 7–10 dias
- Deploy: GitHub Pages ou hospedagem do cliente

---

## Arquitetura do Site (8 Seções Padrão)

### Seção 1 — Hero
- **Headline:** Benefício principal em 7–10 palavras
- **Subhead:** Explicação em 1–2 linhas
- **CTA primário:** "Agendar consulta" (botão WhatsApp ou formulário)
- **CTA secundário:** "Saiba mais" (scroll suave)
- **Visual:** Foto do espaço OU foto do médico OU ilustração profissional

### Seção 2 — Problema/Dor
- 3–4 bullets com dores do paciente-alvo
- Gancho emocional antes de apresentar a solução

### Seção 3 — Solução (Serviços)
- Cards por especialidade/serviço
- Ícone + título + 1 linha de descrição
- Link para mais detalhes (modal ou página interna)

### Seção 4 — Diferenciais
- 4–6 pilares que separam a clínica dos concorrentes
- Formato: ícone + título + parágrafo curto

### Seção 5 — Sobre / Quem Somos
- Foto do médico/equipe (humaniza a marca)
- Mini-bio com credenciais (CRM, pós-graduação, anos de experiência)
- Missão da clínica em 1 parágrafo

### Seção 6 — Depoimentos
- Mínimo 3 depoimentos reais (ou genéricos aprovados pelo cliente)
- Nome + sobrenome inicial + tratamento recebido
- Stars (⭐⭐⭐⭐⭐) ou citação em destaque

### Seção 7 — Localização + Contato
- Endereço completo
- Horários de funcionamento
- Google Maps embed
- Botões: WhatsApp, Ligar, E-mail

### Seção 8 — Rodapé (Footer)
- Logo
- Links internos (Home, Serviços, Sobre, Contato)
- Redes sociais
- Copyright

---

## Stack Técnica (Padrão Pulso)

```html
<!-- HTML5 semântico + TailwindCSS (CDN) ou CSS customizado -->
<!-- JavaScript vanilla para interatividade -->
<!-- Deploy: GitHub Pages (zero custo) -->
```

**Requisitos técnicos:**
- [ ] Mobile-first (breakpoint 375px, 768px, 1280px)
- [ ] PageSpeed >85 mobile, >90 desktop
- [ ] SSL/HTTPS
- [ ] Meta tags (title, description, OG, Twitter Card)
- [ ] Schema.org JSON-LD (LocalBusiness + Physician)
- [ ] Google Analytics 4 instalado
- [ ] Pixel Meta instalado
- [ ] WhatsApp link com mensagem pré-definida
- [ ] Formulário de contato funcional (Formspree ou similar)

---

## SEO On-Page

```html
<!-- Título padrão -->
<title>Dr. [Nome] | [Especialidade] em [Cidade] | [Clínica]</title>

<!-- Meta Description -->
<meta name="description" content="[Clínica] — [Especialidade] em [Cidade]. [Benefício principal]. Agende sua consulta: [CTA]">

<!-- Schema.org Physician -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Physician",
  "name": "[Nome do Médico]",
  "medicalSpecialty": "[Especialidade]",
  "address": { ... },
  "telephone": "[Telefone]"
}
</script>
```

---

## Checklist de Entrega

**Conteúdo:**
- [ ] Todos textos revisados e aprovados pelo cliente
- [ ] Fotos otimizadas (WebP, <200KB cada)
- [ ] Favicon criado (32x32 + 180x180 Apple Touch)
- [ ] Sitemap.xml gerado

**Técnico:**
- [ ] Validado no W3C HTML Validator
- [ ] Testado Chrome + Safari + Firefox + Edge
- [ ] Testado iPhone 12 + Samsung Galaxy S21 (mínimo)
- [ ] PageSpeed documentado (print)
- [ ] Analytics configurado e testando
- [ ] Pixel disparando evento PageView

**Entrega:**
- [ ] URL do site enviada ao cliente
- [ ] Credenciais de acesso documentadas
- [ ] Instruções básicas de atualização entregues

---

## Cases Reais: Sites Pulso em Produção

### Case 1 — Clínica Modelo Ortopédica (POC)

**Escopo:** Site institucional de 8 seções + LP de procedimento específico (infiltração)

**Decisões técnicas:**
- Stack: HTML5 + TailwindCSS (CDN) + JS vanilla — sem framework para máxima performance
- Deploy: GitHub Pages — zero custo, HTTPS automático
- CTA principal: WhatsApp com mensagem pré-escrita ("Olá, vim pelo site e quero agendar uma consulta")

**Métricas alcançadas:**
- PageSpeed Mobile: **89/100**
- PageSpeed Desktop: **96/100**
- Tempo de carregamento: **1.8s** (mobile, 4G)
- Bounce rate estimado: 52% (abaixo da meta de <60%)

**Aprendizado crítico:** Site com foto real do consultório (não stock photo) gerou maior engajamento. Clientes que enviavam fotos do espaço convertiam 20% melhor que os que usavam imagens genéricas.

**Site ao vivo:** https://oguidomingos.github.io/site-clinica-modelo/

---

### Case 2 — Dr. Leandro Marques Dutra (Dor Crônica)

**Escopo:** Não foi criado site institucional novo (site básico existente mantido). Foco foi em 2 LPs de alta conversão (ver Playbook 04).

**Decisão estratégica:** Para médicos com site funcional (mesmo desatualizado), priorizar LP de alta conversão + Google Ads é mais rápido e barato que refazer site completo. Site institucional fica para fase 2 do cliente.

**Aprendizado:** Budget mínimo (~R$2.500/mês) direcionar para LP + ads primeiro. Site completo quando cliente renova contrato (fase 2).

---

### Case 3 — Centro de Reabilitação Santa Isabel

**Escopo:** Site premium completo + LP de reabilitação pós-cirúrgica

**Decisões técnicas:**
- Design bilínguo considerado mas descartado (audiência 100% BR)
- Seção "46 anos de história" adicionada (não prevista no template padrão) — diferencial competitivo
- Equipe multidisciplinar listada individualmente com foto (humanização = confiança)
- Google Maps embed com marcação do bairro em Brasília/DF

**Métricas alcançadas:**
- PageSpeed Mobile: **87/100**
- PageSpeed Desktop: **94/100**
- Tempo de carregamento: **2.1s**
- Seção mais visualizada: "Equipe" (24% do tempo total na página)

**Sites ao vivo:**
- Site premium: https://oguidomingos.github.io/trion-intelligence/site-santa-isabel.html
- LP reabilitação: https://oguidomingos.github.io/trion-intelligence/lp-santa-isabel.html

**Aprendizado:** Seções de equipe com foto individual são as mais visitadas em clínicas com múltiplos profissionais. Investir tempo na seção "Equipe" retorna em maior tempo na página e maior confiança pré-consulta.

---

## Benchmarks de Performance

| Métrica | Meta Padrão | Resultados Pulso (média 3 POCs) |
|---------|-------------|--------------------------------|
| PageSpeed Mobile | >85 | 88.3 |
| PageSpeed Desktop | >90 | 95.0 |
| Tempo de carregamento | <3s | 2.0s |
| Taxa de rejeição | <60% | ~52% |
| Seção mais visitada | — | Equipe / Sobre (24%) |
| CTA mais clicado | — | WhatsApp (68% dos cliques) |

---

## Decisões Arquiteturais por Tipo de Clínica

| Tipo | Hero Visual | CTA Primário | Seção Extra |
|------|------------|--------------|-------------|
| Médico solo | Foto do médico | WhatsApp direto | Mini-bio + CRM em destaque |
| Clínica multi-especialidade | Foto instalações | Formulário qualificador | Seletor de especialidade |
| Centro reabilitação | Antes/depois (não-cirúrgico) | WhatsApp + Ligar | Histórico + equipe |
| Clínica estética | Galeria de resultados | Avaliação gratuita | Antes/depois aprovado |

---

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| PageSpeed Mobile | >85 |
| PageSpeed Desktop | >90 |
| Tempo de carregamento | <3s |
| Taxa de rejeição (meta) | <60% |
| Tempo na página | >1:30min |

---

## Próxima Etapa

→ **Playbook 04 — Landing Pages**

O site é para branding. A LP é para conversão.

---

*Pulso — Assessoria de Marketing para Clínicas | Framework v2.1 — Atualizado com dados reais dos POCs*
