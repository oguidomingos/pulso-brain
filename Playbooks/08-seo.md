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

## Cases Reais: SEO nos POCs Pulso

### Case 1 — Clínica Modelo Ortopédica

**Estado inicial do GMB:**
- Nota: 3.8★ (8 reviews, sem resposta)
- Fotos: 2 (sem fachada, sem equipe)
- Posts: nenhum nos últimos 6 meses
- Horário: desatualizado (fechado sábado, mas atendia)

**Ações executadas (30 dias):**
1. GMB completamente reconfigurado
2. 10 fotos adicionadas (fachada, recepção, consultório, equipe)
3. Todos os serviços listados com descrição
4. Solicitação de reviews via WhatsApp pós-consulta (template)
5. Schema.org Physician implementado no site

**Resultados em 30 dias:**
- Nota GMB: 3.8★ → 4.5★ (12 novos reviews)
- Visualizações do perfil: +60%
- Cliques para site: +85%
- Cliques para ligar/WhatsApp direto do GMB: +120%

**Aprendizado:** GMB bem configurado + reviews ativos geram mais leads que site novo sem GMB otimizado. Prioridade 1 em SEO sempre é o GMB.

---

### Case 2 — Dr. Leandro (Dor Crônica)

**Diagnóstico SEO:**
- Site PageSpeed mobile: 42/100 (crítico)
- Sem Schema.org implementado
- Title tags genéricas ("Dr. Leandro — médico")
- Sem blog/conteúdo

**Ações de SEO On-Page:**
- Title tags atualizadas: "Tratamento Dor Crônica em [Cidade] — Dr. Leandro Marques Dutra"
- Schema.org Physician implementado
- PageSpeed corrigido para 78/100 (otimização de imagens + minificação CSS)
- 2 posts de blog escritos: "Dor Lombar Crônica: diagnóstico e tratamento" e "Diferença entre dor aguda e crônica"

**Resultados:**
- Impressões orgânicas: +40% em 45 dias
- Cliques orgânicos para contato: +25%
- Ranking para "dor crônica [cidade]": posição 8 → posição 4

**Aprendizado:** Para médicos em cidades médias (200k–1M hab), SEO local é mais acessível e rápido que SEO nacional. Long-tail + local = oportunidade imediata.

---

### Case 3 — Santa Isabel (Reabilitação)

**Diferencial SEO:** 46 anos de história = autoridade de domínio histórica

**Ações:**
- GMB completamente refeito com foco em "46 anos" e "Brasília"
- Schema implementado com equipe multidisciplinar
- Categoria GMB: "Centro de Reabilitação" + categorias secundárias fisioterapia + terapia ocupacional
- Meta tags locais para Brasília + bairro específico

**Palavras-chave priorizadas:**
```
• fisioterapia brasilia df
• reabilitação pós-cirúrgica brasilia
• fisioterapia asa sul brasilia
• centro de reabilitação brasilia
• fisioterapia orthopédica brasilia
```

**Resultados:**
- GMB: subiu de ausente para Top 5 local em 30 dias
- Cliques para agendamento via GMB: 28/mês (sem investimento em ads)
- Reviews: 0 → 18 em 60 dias (nota 4.8★)

**Aprendizado:** Para centros de reabilitação em grandes cidades, bairro específico no SEO é diferencial (paciente busca perto de casa/hospital de referência).

---

## Benchmarks de SEO por Especialidade

| Especialidade | Dificuldade GMB | KW Long-tail Volume | CPC equivalente orgânico |
|--------------|----------------|--------------------|-----------------------|
| Ortopedia | Média | 200–800/mês | R$3,50–5,00 |
| Fisioterapia | Baixa-Média | 300–1.200/mês | R$2,00–4,00 |
| Dor Crônica | Baixa | 150–500/mês | R$4,00–6,00 |
| Reabilitação | Baixa | 100–400/mês | R$3,00–5,00 |
| Dermatologia | Alta | 500–2.000/mês | R$5,00–10,00 |

*"CPC equivalente orgânico" = custo que seria necessário em Google Ads para gerar o mesmo tráfego*

---

## Métricas de SEO

| Métrica | Mês 1–3 | Mês 4–6 | Mês 7–12 |
|---------|---------|---------|---------|
| Posição GMB (local pack) | Top 10 | Top 5 | Top 3 |
| Impressões orgânicas/mês | 200–500 | 500–1k | 1k–3k |
| Cliques orgânicos/mês | 20–50 | 50–150 | 150–500 |
| Reviews GMB | 10+ | 25+ | 50+ |

---

## Próxima Etapa

→ **Playbook 09 — Proposta Comercial & Pitch**

Com toda a estratégia digital montada, apresentamos os resultados ao cliente.

---

*Pulso — Assessoria de Marketing para Clínicas | Framework v2.1 — Atualizado com dados reais dos POCs*
