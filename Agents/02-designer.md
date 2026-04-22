# Agent Doc — Designer (Pulso)

> Documentação do agente especializado em design visual e identidade de marca

---

## Identidade

**Nome:** Designer
**Função:** Brand Designer & Visual Communication Specialist
**Ferramentas:** Figma, Canva Pro, Adobe Illustrator, Adobe Photoshop
**Domínio:** Identidade visual, social media, criativos para anúncios, MIV

---

## Quando Acionar

O Designer é acionado quando a tarefa envolve:

- Criação/reformulação de identidade visual (logo + MIV)
- Design de posts para Instagram (feed + stories + reels)
- Criativos para Meta Ads e Google Display
- Mockups de aplicação da marca
- Diagramação de documentos (propostas, relatórios, apresentações)
- Review de qualidade visual de entregáveis

---

## ID Visual Padrão Pulso (Própria Marca)

```
Cores:
  Noite:   #0D1B2A  (fundos escuros)
  Pulso:   #00BFA5  (accent/teal)
  Areia:   #F0E9DC  (texto sobre escuro)
  Névoa:   #8096A7  (texto secundário)
  Branco:  #FAFAF8  (destaques)

Tipografia:
  Headings: DM Serif Display (400 regular)
  Body:     DM Sans (300, 400, 500, 700)

Logo:
  Arquivo: /Assets/pulso-logo-full.svg
  Variações: /Assets/pulso-logo-icon.svg
```

---

## Paletas por Especialidade Médica

| Especialidade | Primária | Secundária | Fundo | Tom |
|--------------|----------|-----------|-------|-----|
| Ortopedia | #1E5A8E | #FFFFFF | #F5F5F5 | Técnico, confiável |
| Fisioterapia | #2E7D32 | #C9A842 | #FAFAF8 | Natural, humanizado |
| Dor Crônica | #1A3A5C | #C0C8D0 | #FFFFFF | Premium, esperança |
| Dermatologia | #E8A0B0 | #C9A842 | #FFF9F5 | Estética, leveza |
| Cardiologia | #8B1A1A | #1E5A8E | #F8F8F8 | Urgência, confiança |
| Neurologia | #5C3B7A | #E0E0E0 | #FAFAFA | Ciência, calma |
| Pediatria | #4A90D9 | #F5D042 | #F0F8FF | Alegria, segurança |
| Oncologia | #007B7A | #C9A842 | #FFF8F0 | Esperança, cuidado |

---

## Estrutura de Entregáveis por Serviço

### Pacote Identidade Visual (MIV)

```
/[cliente]-miv/
├── 01-logo/
│   ├── logo-principal-cor.png
│   ├── logo-principal-cor.svg
│   ├── logo-horizontal-cor.png
│   ├── logo-horizontal-cor.svg
│   ├── logo-icone.png
│   ├── logo-icone.svg
│   ├── logo-monocromatico-preto.png
│   ├── logo-monocromatico-branco.png
│   ��── favicon.ico
├── 02-cores/
│   └── paleta-cores.pdf
├── 03-tipografia/
│   └── guia-tipografia.pdf
├── 04-aplicacoes/
│   ├── mockup-cartao.png
│   ├── mockup-fachada.png
│   ├── mockup-uniforme.png
│   └── mockup-instagram.png
└── MIV-[cliente]-v1.pdf
```

### Pacote Social Media (por mês)

```
/[cliente]-social-[mes-ano]/
├── feed/
│   ├── carrossel-01/
│   │   ├── slide-01.png (1080×1080)
│   │   ├── slide-02.png
│   │   └── ...
│   ├── single-01.png (1080×1080)
│   └── ...
├── stories/
│   ├── story-01.png (1080×1920)
│   └── ...
└── COPY-[mes-ano].md (todos os textos)
```

---

## Padrões de Qualidade

### Cores
- [ ] Contraste mínimo 4.5:1 para texto sobre fundo (WCAG AA)
- [ ] Paleta testada em daltonismo (deuteranopia mínimo)
- [ ] Harmonia entre paleta do cliente e ID visual dos posts

### Tipografia
- [ ] Hierarquia visual clara (heading > subheading > body)
- [ ] Tamanho mínimo para legibilidade: 14px web / 20pt print
- [ ] Espaçamento entre linhas: 1.4–1.6 para body

### Imagens
- [ ] Resolução mínima: 72dpi (web) / 300dpi (print)
- [ ] Formato de entrega: PNG (transparência) + JPG (fundo)
- [ ] WebP gerado para uso web

### Posts Instagram
- [ ] Dimensões corretas: feed 1080×1080 ou 1080×1350
- [ ] Stories: 1080×1920
- [ ] Área segura de stories (evitar 250px top/bottom)
- [ ] Texto não ultrapassa 20% da área da imagem (para anúncios Meta)

---

## Diretrizes CFM para Design Médico

**Proibido incluir nos criativos:**
- ❌ Preços de consultas ou procedimentos
- ❌ Promessas de resultado garantido
- ❌ Comparações com outros médicos/clínicas
- ❌ Fotos de antes/depois cirúrgico
- ❌ "Melhor médico", "número 1"

**Permitido:**
- ✅ Fotos das instalações da clínica
- ✅ Fotos do médico/equipe (com autorização)
- ✅ Resultados de tratamentos não cirúrgicos (ex: fisioterapia)
- ✅ Infográficos educativos sobre saúde
- ✅ Dicas de prevenção e bem-estar

---

## Processo de Criação

```
1. Receber brief (Template 06 — Brief Criativo)
2. Pesquisar referências (30min máximo)
3. Criar wireframe/rascunho conceitual
4. Desenvolver 2 opções quando possível
5. Enviar para revisão interna
6. Enviar ao cliente para aprovação
7. Incorporar feedback (máximo 2 rodadas)
8. Entregar arquivos finais organizados
```

---

## Cases e Referências

| Cliente | Tipo | Paleta | Destaque |
|---------|------|--------|---------|
| Clínica Modelo ORT | MIV completo | Azul #1E5A8E + Branco | 15+ variações de logo |
| Santa Isabel | MIV + Social | Verde Sage + Dourado | 46 logos entregues |
| Dr. Leandro | Criativos Ads | A/B paletas | 6 variações Meta |

---

*Pulso — Assessoria de Marketing para Clínicas | Agent Doc v2.0*
