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

## Métricas de Sucesso

| Métrica | Meta |
|---------|------|
| PageSpeed Mobile | >85 |
| PageSpeed Desktop | >90 |
| Tempo de carregamento | <3s |
| Taxa de rejeição (meta) | <60% |
| Tempo na página | >1:30min |

---

## Sites Pulso Entregues (Referência)

### Clínica Modelo Ortopédica
**URL:** https://oguidomingos.github.io/site-clinica-modelo/
**Stack:** HTML5 + CSS customizado
**Seções:** 8 (Hero → Serviços → Diferenciais → Sobre → Depoimentos → Localização → Footer)
**Destaque:** Scroll-snap suave, mobile-first, agendamento WhatsApp integrado
**PageSpeed mobile:** >85 | Desktop: >90

### Santa Isabel Fisioterapia
**URL:** https://oguidomingos.github.io/trion-intelligence/site-santa-isabel.html
**Stack:** HTML5 semântico + TailwindCSS
**Seções:** Institucional completo (8 seções + página de serviços)
**Destaque:** Identidade verde sage + dourado aplicada com consistência, 46 anos de história como prova social
**Foco:** Maior centro privado de reabilitação do DF — comunicação de autoridade

### Diferença: Site vs. Landing Page (estratégia Pulso)

| Critério | Site Institucional | Landing Page |
|---------|-------------------|-------------|
| Objetivo | Branding + autoridade | Conversão direta |
| Navegação | Sim (menu completo) | Não (1 CTA único) |
| Conteúdo | Completo (história, equipe, serviços) | Foco absoluto em 1 serviço |
| Tráfego ideal | Orgânico, direto, referência | Pago (Meta Ads, Google Ads) |
| Conversão esperada | 2–5% | 5–12% |

**Regra prática:** Para campanhas de tráfego pago, SEMPRE mande para LP específica, nunca para o site.

---

## Lições dos POCs

| Lição | Base | Detalhe |
|-------|------|---------|
| Site + LP são papéis diferentes — entregue os dois | Todos os cases | Site = hub da marca. LP = motor de conversão |
| Fotos reais do espaço aumentam credibilidade | Santa Isabel | Mockups ficam genéricos. Fotos reais de instalações convertem mais |
| CTA WhatsApp na hero converte mais que formulário | Ortopedia + Santa Isabel | Paciente prefere conversar antes de "preencher formulário" |
| Depoimentos com nome + tratamento específico > depoimentos genéricos | Santa Isabel | "Maria S. — Recuperação pós-cirurgia de quadril" bate "Ótimo atendimento" |
| Mobile-first não é opcional — 70% do tráfego é mobile | Todos | Site bonito no desktop que quebra no celular perde a maioria dos visitantes |

---

## Próxima Etapa

→ **Playbook 04 — Landing Pages**

O site é para branding. A LP é para conversão.

---

*Pulso — Assessoria de Marketing para Clínicas | Framework v2.0 | Atualizado 2026-04*
