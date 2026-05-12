# Análise Técnica — Landing Page Fama Odonto

**URL analisada:** https://famaodontonovomundo.com/
**Data da análise:** 12/05/2026
**Foco:** Índice de Qualidade do Google Ads e Relevância no Meta Ads (Instagram/Facebook)

---

## Resumo executivo

| Plataforma | Nota estimada | Status |
|---|---|---|
| **Google Ads — Quality Score** | 4 a 6 / 10 | Abaixo da média do nicho odontológico |
| **Meta Ads — Quality Ranking** | Médio | Sem prova social forte, sem antes/depois |
| **SEO On-page** | Fraco | Title duplicado, H2/H3 ausentes |
| **Conversão (UX)** | Médio | CTA direto p/ WhatsApp é bom, mas falta redutor de risco |
| **LGPD / Compliance** | Crítico | Sem política de privacidade nem cookie consent |

**Conclusão geral:** A página funciona como "cartão de visitas digital", mas **não está otimizada para receber tráfego pago**. Rodando anúncios para essa LP no estado atual, o CPC será mais caro, o Quality Score baixo vai limitar entregas e o custo por lead será 30-60% maior do que poderia ser.

---

## 1. Análise pelo Google Ads Quality Score

O Quality Score do Google é composto por **3 pilares**. Avaliação de cada um:

### 1.1 Expected CTR (Taxa de cliques esperada) — ⚠️ Baixo

- **Title tag duplicado:** "Fama Odonto Novo Mundo - Sorriso Saudável | Fama Odonto Novo Mundo" → o nome aparece duas vezes, desperdiça caracteres preciosos e prejudica o CTR nos SERPs.
- **Sem palavras-chave de procedimento no title:** não menciona "implantes", "próteses", "lentes", "Curitiba" — o que reduz match com a intenção de busca.
- **Meta description ausente** — o Google gera uma automática, geralmente fraca.

### 1.2 Ad Relevance (Relevância do anúncio) — ⚠️ Médio-baixo

- **Página única e genérica** atendendo todos os procedimentos. Quando o anúncio for de "implante dentário Curitiba" e cair numa LP que fala de clareamento, canal e prótese ao mesmo tempo, o Google entende baixa correspondência.
- **Necessário:** uma LP por procedimento principal (implante, prótese, lente/faceta), com copy e criativos alinhados ao anúncio.

### 1.3 Landing Page Experience (Experiência na LP) — ⚠️ Crítico em alguns pontos

| Item | Status | Observação |
|---|---|---|
| HTTPS | OK | Domínio Zyro tem SSL nativo |
| Mobile-friendly | OK | Design responsivo |
| Velocidade | OK | CDN Zyro entrega imagens otimizadas |
| Conteúdo original e relevante | Médio | Textos curtos e genéricos |
| Navegação clara | OK | Menu enxuto, fluxo direto |
| **Política de Privacidade** | **AUSENTE** | Risco direto de reprovação no Google Ads (política obrigatória para anúncios de serviços de saúde) |
| **Política de Cookies / LGPD** | **AUSENTE** | Não conformidade legal |
| Erros de copy | Encontrado | Descrição de "Tratamento de Canal" menciona "alinhamento" (provável erro) |
| Estrutura semântica (H1, H2, H3) | Fraco | Tem 1 H1 e pula direto para H6 — Google não entende hierarquia |

---

## 2. Análise pelo Meta Ads (Instagram / Facebook)

O Meta avalia anúncios por **3 rankings**: Quality, Engagement e Conversion. A LP impacta principalmente o **Conversion Rate Ranking**.

### 2.1 Pixel e rastreamento — ⚠️ Faltando o principal

- **Google Tag Manager detectado** (ID: AW-17965608068) — Google Ads OK
- **Pixel do Meta (Facebook):** NÃO IDENTIFICADO no código da página

**Impacto:** sem o pixel do Meta instalado, é impossível:
- Otimizar campanhas por conversão (vai rodar só por cliques ou visualizações)
- Criar públicos de remarketing
- Criar Lookalike Audiences baseados em quem agendou
- Medir o ROI real das campanhas no Instagram/Facebook

**Esse é o ponto técnico mais urgente.**

### 2.2 Prova social — ⚠️ Frágil

| Elemento | Status | Recomendação |
|---|---|---|
| Depoimentos | Apenas 2, genéricos (Ana M., João P.) | Mínimo 6-8, com nome completo e foto real |
| **Fotos antes/depois** | **AUSENTES** | Item crítico em nicho odontológico — o público compra com os olhos |
| Avaliações Google integradas | Não há | Embedar widget do Google Reviews |
| Selos de confiança | Não há | CRO do dentista, certificações, parcerias |
| Vídeos da equipe / clínica | Não há | Vídeo curto da estrutura aumenta tempo de página e conversão |
| Métricas declaradas | "+2.000 sorrisos", "+1.000 clientes" | Bom, mas precisa de prova visual ao lado |

### 2.3 Relevância do criativo → LP

Anúncios no Meta costumam ter alta carga visual e emocional. Se o anúncio mostra um "antes e depois de lente de contato dental" e a LP não tem nenhuma foto desse tipo, o usuário sente quebra de promessa → baixa conversão → ranking de qualidade despenca → CPC sobe.

---

## 3. Problemas críticos (ordem de prioridade)

### Severidade ALTA — corrigir antes de subir qualquer anúncio

1. **Adicionar Política de Privacidade e Cookies** — exigência do Google Ads para o nicho de saúde. Sem isso, há risco de reprovação ou suspensão de conta.
2. **Instalar o Pixel do Meta (Facebook)** — sem ele, qualquer real investido em Instagram/Facebook é cego.
3. **Corrigir o title tag** — eliminar duplicação e incluir palavras-chave principais (ex: "Fama Odonto — Implantes, Próteses e Lentes em Curitiba").
4. **Criar meta description** otimizada com CTA.

### Severidade MÉDIA — corrigir em até 30 dias

5. **Estrutura H1/H2/H3** — refazer hierarquia semântica (hoje pula H1 → H6).
6. **Adicionar 4-6 fotos antes/depois reais** com consentimento dos pacientes.
7. **Substituir depoimentos genéricos** por 6-8 reais com nome completo e foto.
8. **Integrar widget de avaliações do Google** na página.
9. **Adicionar redutor de risco:** garantia de avaliação gratuita, "primeira consulta sem compromisso", etc.
10. **Corrigir erro de copy** na descrição de Tratamento de Canal.

### Severidade BAIXA — otimizações de performance

11. **Adicionar urgência sutil:** "agenda da semana" ou "vagas limitadas para avaliação".
12. **Criar página de "obrigado"** pós-agendamento (essencial para mensurar conversão).
13. **Adicionar selos:** CRO do responsável técnico, anos de mercado, certificações.

---

## 4. Recomendação estratégica — Landing pages dedicadas

Manter UMA única página tentando vender todos os procedimentos é o que mais derruba o Quality Score em campanhas segmentadas.

**Plano sugerido:**

| Campanha | Landing Page Dedicada | Foco do criativo |
|---|---|---|
| Implantes dentários — Curitiba | `/implantes-curitiba` | Antes/depois, garantia, parcelamento |
| Próteses dentárias | `/proteses-curitiba` | Conforto, estética, tipos disponíveis |
| Lentes de contato / facetas | `/lentes-de-contato-dental` | Antes/depois, "em 2 sessões", harmonia do sorriso |
| HOF — Harmonização Orofacial | `/harmonizacao-orofacial` | Resultados, naturalidade |

Cada LP com title, H1, copy e imagens 100% alinhados ao anúncio que traz o tráfego. Isso é o que vai destravar Quality Score 8-10 no Google e ranking "Above Average" no Meta.

---

## 5. Estimativa de impacto

Aplicando as correções de severidade ALTA + MÉDIA, a expectativa realista é:

- **CPC no Google Ads:** redução de 25 a 40%
- **Custo por Lead (CPL):** redução de 30 a 50%
- **Taxa de conversão da LP:** subir de ~1-2% (estimado atual) para 4-7%
- **Relevância no Meta:** sair de "Médio" para "Above Average / Acima da Média"

Esses ganhos significam, na prática, que com o **mesmo orçamento de mídia** é possível trazer o dobro (ou mais) de leads qualificados.
