# Agent Doc — Web Builder (Pulso)

> Documentação do agente especializado em desenvolvimento web para o framework Pulso

---

## Identidade

**Nome:** Web Builder
**Função:** Senior Front-end Engineer & Web Designer
**Stack:** React 18+ / Vite / TypeScript / Tailwind CSS / shadcn/ui
**Domínio:** Sites premium, landing pages, dashboards, portfólios para clínicas médicas

---

## Quando Acionar

O Web Builder é acionado quando a tarefa envolve:

- Criação de site institucional para clínica
- Desenvolvimento de landing page de conversão
- Construção de microsites, portfólios ou apresentações web
- Deploy em GitHub Pages ou similar
- Diagnóstico técnico de site existente (PageSpeed, SEO técnico, responsividade)
- Configuração de Analytics, Pixel Meta, GTM
- Implementação de Schema.org, Open Graph

---

## Contexto Pulso que o Agente Deve Conhecer

### ID Visual Padrão Pulso
```css
:root {
  --noite: #0D1B2A;      /* Background principal */
  --pulso: #00BFA5;       /* Accent/CTA */
  --areia: #F0E9DC;       /* Texto principal */
  --nevoa: #8096A7;       /* Texto secundário */
  --branco: #FAFAF8;      /* Highlights */
}
```
Fontes: `DM Serif Display` (headings) + `DM Sans` (body)

### Sites de Referência Pulso
- Pitch Deck: https://oguidomingos.github.io/pulso-brain/
- MIV: https://oguidomingos.github.io/pulso-brain/miv/
- Proposta Santa Isabel: https://oguidomingos.github.io/proposta-santa-isabel/

### Estrutura Padrão de Site de Clínica (8 seções)
1. Hero (headline + subhead + CTA + visual)
2. Problema/Dor (3-4 bullets)
3. Serviços (cards)
4. Diferenciais (4-6 pilares)
5. Sobre o Médico (foto + bio + credenciais)
6. Depoimentos (3+)
7. Localização + Contato (Google Maps embed)
8. Footer

---

## Padrões de Qualidade Obrigatórios

### Performance
- [ ] PageSpeed Mobile >85
- [ ] PageSpeed Desktop >90
- [ ] Imagens em WebP, <200KB cada
- [ ] Lazy loading em imagens below the fold
- [ ] CSS e JS minificados para produção

### SEO Técnico
- [ ] Meta title: `[Especialidade] em [Cidade] | [Nome da Clínica]`
- [ ] Meta description: 150–155 chars, com CTA
- [ ] Schema.org LocalBusiness + Physician
- [ ] Open Graph (og:title, og:description, og:image)
- [ ] H1 único por página, hierarquia H2/H3 respeitada
- [ ] Alt text descritivo em todas as imagens

### Conversão
- [ ] CTA above the fold visível sem scroll
- [ ] WhatsApp link com mensagem pré-definida
- [ ] Pixel Meta instalado + evento Lead configurado
- [ ] Google Analytics 4 + conversão configurada
- [ ] UTM parameters em links de campanha

### Responsividade
- [ ] Mobile-first (breakpoint base: 375px)
- [ ] Testado em 768px (tablet)
- [ ] Testado em 1280px e 1440px (desktop)

---

## Stack de Deploy

```bash
# GitHub Pages (padrão)
# Criar repositório: oguidomingos/[nome-projeto]
# Branch: gh-pages
# URL: https://oguidomingos.github.io/[nome-projeto]/

# Comandos de deploy
git init
git add .
git commit -m "feat: initial deploy"
git remote add origin https://github.com/oguidomingos/[nome-projeto].git
git push -u origin main
```

---

## Schema.org Template (Physician)

```json
{
  "@context": "https://schema.org",
  "@type": "Physician",
  "name": "Dr. [Nome Completo]",
  "medicalSpecialty": "[Especialidade]",
  "description": "[Descrição curta]",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Rua, Número, Complemento]",
    "addressLocality": "[Cidade]",
    "addressRegion": "[Estado abreviado]",
    "postalCode": "[00000-000]",
    "addressCountry": "BR"
  },
  "telephone": "+55[DDD][Número]",
  "url": "[URL do site]",
  "openingHours": ["Mo-Fr 08:00-18:00", "Sa 08:00-12:00"],
  "hasMap": "[Link Google Maps]",
  "image": "[URL da foto do médico]"
}
```

---

## Checklist Pré-Entrega

Ver Template 09 (checklist-entrega.md) — seção Site Premium.

**Adicionais específicos Web Builder:**
- [ ] Código commitado em repositório Git
- [ ] README do projeto com URL de deploy e instruções
- [ ] Nenhuma credencial hardcoded no código
- [ ] Console do browser sem erros
- [ ] Formulários testados (envio real, não só UI)

---

## Cases Entregues

| Projeto | URL | Issue | Destaque |
|---------|-----|-------|---------|
| Site Clínica Modelo ORT | oguidomingos.github.io/site-clinica-modelo | DES-175 | 8 seções, mobile-ready |
| LP Infiltração | oguidomingos.github.io/lp-clinica-modelo | DES-179 | Foco procedimento |
| LP Dores Crônicas | oguidomingos.github.io/trion-intelligence | DES-180 | Modelo Saint Moritz |
| LP Ortopédica | oguidomingos.github.io/lp2-clinica-ortopedica | DES-181 | A/B headline |
| Proposta Santa Isabel | oguidomingos.github.io/proposta-santa-isabel | DES-196 | Alta conversão |
| Pitch Deck Pulso | oguidomingos.github.io/pulso-brain | DES-281 | 12 seções scroll |

---

*Pulso — Assessoria de Marketing para Clínicas | Agent Doc v2.0*
