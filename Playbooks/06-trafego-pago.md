# Playbook 06 — Tráfego Pago (Meta Ads + Google Ads)

> **Pulso Onboarding Framework** | Etapa 6 de 12

---

## Objetivo

Gerar fluxo previsível e escalável de pacientes qualificados através de campanhas pagas no Meta (Facebook/Instagram) e Google Ads, com ROAS positivo desde o mês 1.

---

## Estratégia Dual de Tráfego

```
DEMANDA QUENTE (Google Ads)
  └── Paciente procura ativamente
  └── Palavras-chave: "ortopedista [cidade]", "fisioterapia [bairro]"
  └── Conversão mais alta, CPC mais alto

DEMANDA FRIA (Meta Ads)
  └── Paciente ainda não sabe que precisa
  └── Segmentação por interesse + comportamento + lookalike
  └── Volume maior, conversão precisa de nurturing
```

---

## Meta Ads — Estrutura de Campanha

### Funil Completo (padrão Pulso)

**ToFu (Topo de Funil) — Awareness**
- Objetivo: Alcance ou Visualizações de Vídeo
- Público: Interesse em saúde + localização (raio 10–20km)
- Criativo: Vídeo educativo 15–30s ou carrossel informativo
- Orçamento: 20% do budget total
- Meta: CPM <R$15, Alcance máximo

**MoFu (Meio de Funil) — Interesse**
- Objetivo: Tráfego para LP ou Engajamento
- Público: Pessoas que assistiram 50%+ do vídeo ToFu
- Criativo: Depoimento de paciente ou procedimento explicado
- Orçamento: 30% do budget total
- Meta: CPC <R$2.50

**BoFu (Fundo de Funil) — Conversão**
- Objetivo: Conversões (Lead) ou Mensagens (WhatsApp)
- Público: Visitantes da LP + Lookalike de clientes
- Criativo: Oferta clara (consulta avaliação, 1ª consulta)
- Orçamento: 50% do budget total
- Meta: CPL <R$30

---

## Google Ads — Estrutura de Campanha

### Rede de Pesquisa (prioridade)

**Campanha 1 — Marca + Especialidade**
```
Palavras-chave:
+ "fisioterapia [cidade]"
+ "fisioterapeuta [bairro]"
+ "clínica fisioterapia [cidade]"
Correspondência: Exata + Frase
Lance: CPC manual ou Maximizar Conversões
```

**Campanha 2 — Problema/Sintoma**
```
Palavras-chave:
+ "dor nas costas tratamento"
+ "fisioterapia para hérnia de disco"
+ "tratamento dor lombar"
Correspondência: Frase
```

**Campanha 3 — Concorrentes (opcional)**
```
Palavras-chave:
+ [Nome do concorrente 1] fisioterapia
+ [Nome do concorrente 2]
Correspondência: Exata
```

### Extensões obrigatórias
- [ ] Sitelinks (Agendar, Serviços, Sobre, Localização)
- [ ] Ligação (número direto)
- [ ] Localização (GMB vinculado)
- [ ] Frases de destaque ("Atendemos planos de saúde", "Sem fila de espera")

---

## Método SUBIDO (Pulso)

Framework para gerenciamento contínuo de campanhas:

**S — Segmentação:** Revisar públicos semanalmente
**U — UTM:** Todos os links com parâmetros rastreados
**B — Budget:** Realocar para campanhas com melhor ROAS
**I — Imagens/Criativos:** Rotacionar a cada 2 semanas
**D — Dados:** Analisar métricas 2x/semana
**O — Otimização:** Pausar anúncios com CPC >2x média

---

## Criativos por Formato

### Meta Ads — Formatos Eficazes

**Imagem Estática (1:1 ou 4:5)**
- Fundo: Cor da identidade visual
- Texto: Headline curta + CTA
- Visual: Foto do médico ou instalações
- Texto na imagem: <20% da área (regra Meta)

**Vídeo (9:16 vertical, 15–30s)**
```
0–3s:  Gancho visual + headline
3–15s: Desenvolvimento/benefício
15–25s: Depoimento ou demonstração
25–30s: CTA + telefone/WhatsApp
```

**Carrossel (3–5 cards)**
- Card 1: Headline provocativa
- Cards 2-4: Benefícios/argumentos
- Card final: CTA

---

## KPIs e Benchmarks

| Métrica | Meta Ads | Google Ads |
|---------|----------|-----------|
| CTR | >1.5% | >5% |
| CPC | <R$2.50 | <R$4.00 |
| CPL | <R$35 | <R$50 |
| Taxa de conversão LP | >5% | >8% |
| ROAS (receita/investimento) | >3:1 | >4:1 |
| Frequência (Meta) | <3x/semana | — |

---

## Budget Mínimo Recomendado

| Porte da Clínica | Budget/mês | Distribuição |
|-----------------|-----------|-------------|
| Pequena (1-2 médicos) | R$1.500–3.000 | 60% Meta / 40% Google |
| Média (3-5 médicos) | R$3.000–6.000 | 50% Meta / 50% Google |
| Grande (6+ médicos) | R$6.000+ | 40% Meta / 60% Google |

---

## Rastreamento e Atribuição

### Setup Obrigatório
- [ ] Pixel Meta instalado na LP
- [ ] Evento "Lead" configurado no CTA
- [ ] Google Analytics 4 com metas de conversão
- [ ] Google Tag Manager ativo
- [ ] UTM padrão em todos os anúncios:
  ```
  utm_source=meta/google
  utm_medium=cpc
  utm_campaign=[nome-campanha]
  utm_content=[variacao-criativo]
  ```

---

## Próxima Etapa

→ **Playbook 07 — Copywriting**

Todo anúncio é fraco sem copy forte.

---

*Pulso — Assessoria de Marketing para Clínicas | Framework v2.0*
