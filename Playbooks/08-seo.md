# Playbook 08 — SEO para Clínicas

> **Pulso Onboarding Framework** | Etapa 8 de 12

---

## Objetivo

Posicionar a clínica nas primeiras posições do Google para buscas locais relevantes, gerando tráfego orgânico gratuito e previsível a longo prazo.

---

## SEO Local é a Prioridade

Para clínicas médicas, **SEO Local** gera 70%+ do tráfego qualificado. Pacientes buscam:
- "fisioterapeuta perto de mim"
- "ortopedista [cidade]"
- "clínica de fisioterapia [bairro]"

---

## Pilares de SEO para Clínicas

### 1. Google Meu Negócio (GMB) — Maior impacto

**Configuração completa:**
- [ ] Nome exato da clínica (sem palavras-chave artificiais)
- [ ] Categoria principal: ex. "Clínica de fisioterapia"
- [ ] Categorias secundárias: especialidades atendidas
- [ ] Endereço completo + rastreável no mapa
- [ ] Área de atendimento definida (se casa/empresa)
- [ ] Horários corretos (incluindo feriados)
- [ ] Telefone verificado
- [ ] Site linkado
- [ ] Fotos: mínimo 10 (fachada, recepção, sala, equipe)
- [ ] Serviços listados (todos os procedimentos)
- [ ] Perguntas e Respostas (Q&A) preenchidas

**Estratégia de Reviews:**
- [ ] Pedir review a todo paciente satisfeito (WhatsApp pós-consulta)
- [ ] Responder 100% dos reviews (positivos e negativos) em 24h
- [ ] Meta: 4.7+ estrelas, 50+ reviews nos primeiros 3 meses

**Posts GMB (1x/semana):**
```
Tipos:
• Novidade (novo equipamento, serviço, médico)
• Evento (palestra, dia de conscientização)
• Oferta (consulta de avaliação - verificar CFM)
• COVID update (se aplicável)
```

---

### 2. SEO On-Page do Site

**Estrutura de URL:**
```
Boa: /ortopedia-joelho-sp
Ruim: /servicos?id=42&cat=ortop
```

**Title Tags (padrão):**
```
Página Home:      [Especialidade] em [Cidade] | [Nome da Clínica]
Página Serviço:   [Procedimento] em [Cidade] — Dr. [Nome] | [Clínica]
Página Sobre:     Dr. [Nome] — [Especialidade] em [Cidade]
```

**Meta Descriptions:**
```
Padrão: [Clínica] oferece [serviço] em [cidade]. [Benefício principal].
Agende sua consulta: [CTA]. ☎ [Telefone]
Máximo: 155 caracteres
```

**Schema.org Obrigatório:**
```json
{
  "@type": "Physician",
  "name": "Dr. [Nome]",
  "medicalSpecialty": "[Especialidade]",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Rua, Número]",
    "addressLocality": "[Cidade]",
    "addressRegion": "[UF]",
    "postalCode": "[CEP]"
  },
  "telephone": "+55[DDD][Número]",
  "url": "[URL do site]",
  "openingHours": "Mo-Fr 08:00-18:00"
}
```

---

### 3. Pesquisa de Palavras-Chave

**Metodologia:**
1. Listar especialidades e procedimentos
2. Adicionar qualificadores locais (cidade, bairro)
3. Adicionar sintomas (como o paciente pesquisa)
4. Priorizar por volume + intenção de conversão

**Exemplo Fisioterapia:**
```
Volume Alto (difícil rankear):
• fisioterapia (50k+/mês)
• fisioterapeuta (30k+/mês)

Volume Médio (oportunidade):
• fisioterapia [cidade] (500–2k/mês)
• fisioterapia para coluna (1k–5k/mês)

Long-tail (fácil + alta conversão):
• fisioterapia para hérnia de disco [cidade]
• fisioterapeuta especialista em coluna [bairro]
• clínica de fisioterapia aceita [plano de saúde]
```

---

### 4. Estratégia de Conteúdo (Blog)

**Frequência:** 2–4 posts/mês

**Tipos de post:**
1. **Educativo:** "O que é hérnia de disco e como tratar"
2. **FAQ:** "Perguntas mais frequentes sobre fisioterapia"
3. **Sintoma → Solução:** "Dor no joelho ao descer escadas: causas e tratamentos"
4. **Especialidade local:** "Melhor fisioterapeuta em [Cidade] — o que avaliar"

**Template de Post:**
```markdown
# [Palavra-chave principal] — [Benefício] | Título H1

Meta: [155 chars para meta description]

## Introdução (3 parágrafos)
[Contexto + dor do paciente]

## O que é [condição]?
[Explicação técnica acessível]

## Sintomas de [condição]
- Sintoma 1
- Sintoma 2

## Como é o tratamento?
[Descrição do processo]

## Por que escolher [Clínica]?
[Diferenciais + credenciais]

## Agende sua consulta
[CTA + WhatsApp + formulário]
```

---

## Ferramentas Recomendadas

| Ferramenta | Uso | Custo |
|-----------|-----|-------|
| Google Search Console | Monitorar posições + cliques | Grátis |
| Google Analytics 4 | Tráfego + conversões | Grátis |
| Ubersuggest | Pesquisa de palavras-chave | Freemium |
| SEMrush | Análise competitiva | Pago |
| Screaming Frog | Auditoria técnica | Freemium |
| Yoast SEO (WordPress) | On-page optimization | Freemium |

---

## Métricas de SEO por Fase

| Métrica | Mês 1–3 | Mês 4–6 | Mês 7–12 |
|---------|---------|---------|---------|
| Posição GMB (local pack) | Top 10 | Top 5 | Top 3 |
| Impressões orgânicas/mês | 200–500 | 500–1k | 1k–3k |
| Cliques orgânicos/mês | 20–50 | 50–150 | 150–500 |
| Reviews GMB | 10+ | 25+ | 50+ |

---

## SEO Aplicado nos POCs Pulso

### Clínica Modelo Ortopédica
**Ação:** Schema.org LocalBusiness + Physician implementado no site
**GMB:** Configurado com categorias ortopedia + serviços de infiltração
**Meta tags:** Title + description com especialidade + cidade em todas as páginas
**Resultado esperado:** Posição Top 10 local em 60–90 dias

### Santa Isabel Fisioterapia (DF — contexto específico)
**Diferencial de SEO:** 46 anos de operação + "maior centro privado de reabilitação do DF" — dados únicos que aumentam autoridade nos motores de busca
**Ação:** Esses dados foram inseridos em todas as meta tags e Schema.org como proof points
**GMB:** Perfil completo com fotos das instalações, equipe, salas
**Insight:** Para clínicas com histórico longo, anos de operação + número de pacientes atendidos são keywords informais que aumentam cliques no GMB

### Dr. Leandro Marques Dutra
**Foco:** LPs otimizadas para buscas de sintoma específico
**URLs usadas:** `/lp-dores-cronicas` + `/lp-clinica-ortopedica` — friendly e com keyword
**Title padrão:** "Tratamento Dores Crônicas [Cidade] | Dr. Leandro Marques Dutra"

---

## Próxima Etapa

→ **Playbook 09 — Proposta Comercial & Pitch**

Com toda a estratégia digital montada, apresentamos os resultados ao cliente.

---

*Pulso — Assessoria de Marketing para Clínicas | Framework v2.0 | Atualizado 2026-04*
