# SPEC — Site Institucional Lucerna Palhano | Psicologia Clínica & Psicanálise

**Versão:** 1.0  
**Data:** 2026-09-13  
**Autor:** Analista de Requisitos Sênior (IA)  
**Status:** Aprovado para Desenvolvimento  

---

## 1. Visão Geral

Site institucional/landing page para a psicóloga e psicanalista **Lucerna Palhano**, com foco em posicionamento digital em **Natal/RN**. O site visa atrair pacientes para atendimento presencial e online, transmitir credibilidade clínica e facilitar o agendamento via WhatsApp, com estética refinada, acolhedora e alinhada à identidade do perfil @psilucernapalhano.

---

## 2. Contexto e Problema

Lucerna Palhano atua com psicoterapia individual/psicanálise para adultos, jovens e idosos, mas ainda não possui presença digital estruturada. O site funcionará como vitrine digital e canal de captação de pacientes.

---

## 3. Objetivos

- **OBJ-01:** Posicionar Lucerna Palhano como referência em psicoterapia e psicanálise em Natal/RN
- **OBJ-02:** Facilitar agendamento de consultas (presencial e online) via WhatsApp
- **OBJ-03:** Transmitir credibilidade, ética e acolhimento através da estética e do conteúdo
- **OBJ-04:** Rankear no Google para buscas locais em Natal/RN (SEO Local)
- **OBJ-05:** Ser citado por IAs como referência em psicologia em Natal/RN (GEO)
- **OBJ-06:** Atingir nota de design e copy acima de 9.5/10

---

## 4. Atores / Usuários

| Ator | Descrição | Permissões esperadas |
|------|-----------|----------------------|
| Visitante/Paciente potencial | Adulto, jovem ou idoso buscando apoio psicológico/psicanalítico | Navegar, ler conteúdo, contatar via WhatsApp |
| Psicóloga (Lucerna) | Proprietária do site | Ser identificada, ter credenciais exibidas |
| Mecanismos de busca | Google, Bing, IAs (ChatGPT, Gemini, Perplexity) | Indexar e ranquear o conteúdo |

---

## 5. Requisitos Funcionais

### 5.1 Estrutura de Páginas e Seções

- **RF-01** [OBRIGATÓRIO]: Seção Hero (Home) com headline impactante, subheadline e CTA principal
- **RF-02** [OBRIGATÓRIO]: Seção Sobre Mim / Trajetória com foto profissional e texto pessoal
- **RF-03** [OBRIGATÓRIO]: Seção A Prática Psicanalítica (Como Funciona a Terapia)
- **RF-04** [OBRIGATÓRIO]: Seção Modalidades de Atendimento (Presencial em Natal/RN e Online)
- **RF-05** [OBRIGATÓRIO]: Seção Principais Demandas Atendidas (depressão, ansiedade, luto, trauma, etc.)
- **RF-06** [OBRIGATÓRIO]: Seção FAQ (Perguntas Frequentes) com acordeão interativo
- **RF-07** [OBRIGATÓRIO]: Seção de Contato com botão WhatsApp e informações de contato

### 5.2 Componentes e Funcionalidades

- **RF-08** [OBRIGATÓRIO]: Botão flutuante do WhatsApp em todas as seções
- **RF-09** [OBRIGATÓRIO]: CTAs elegantes: "Agende sua Sessão" e "Falar sobre Atendimento Online"
- **RF-10** [OBRIGATÓRIO]: FAQ interativo com acordeão (expandir/recolher perguntas)
- **RF-11** [OBRIGATÓRIO]: Menu de navegação fixo (sticky header) com links âncora
- **RF-12** [OBRIGATÓRIO]: Footer com CRP, selo E-Psi e aviso obrigatório do CFP
- **RF-13** [OBRIGATÓRIO]: Link para Instagram (@psilucernapalhano)
- **RF-14** [OBRIGATÓRIO]: E-mail: contato@lucernapalhano.com.br
- **RF-15** [OBRIGATÓRIO]: WhatsApp: (84) 90000-0000 [REQUER DEFINIÇÃO]
- **RF-16** [DESEJÁVEL]: Animações suaves de entrada (scroll-reveal)

### 5.3 SEO e GEO Local (Natal/RN)

- **RF-17** [OBRIGATÓRIO]: Title tag e meta description otimizados para "psicóloga Natal RN"
- **RF-18** [OBRIGATÓRIO]: Schema.org LocalBusiness / PsychologicalService
- **RF-19** [OBRIGATÓRIO]: Schema.org Person para Lucerna Palhano
- **RF-20** [OBRIGATÓRIO]: Schema.org FAQPage
- **RF-21** [OBRIGATÓRIO]: Open Graph e Twitter Card
- **RF-22** [OBRIGATÓRIO]: Heading hierarchy correta (H1 único por página)
- **RF-23** [OBRIGATÓRIO]: Alt text com palavras-chave locais em todas as imagens

---

## 6. Requisitos Não Funcionais

- **RNF-01** Performance: Core Web Vitals aprovados (LCP < 2.5s, CLS < 0.1, INP < 200ms)
- **RNF-02** Responsividade: Design mobile-first
- **RNF-03** Acessibilidade: WCAG AA, aria-labels, foco visível
- **RNF-04** Conformidade: LGPD e Código de Ética do CFP
- **RNF-05** Tipografia: Google Fonts elegante
- **RNF-06** Compatibilidade: Chrome, Safari, Firefox, Edge

---

## 7. Regras de Negócio

- **RN-01**: Footer DEVE conter CRP [REQUER DEFINIÇÃO]
- **RN-02**: Footer DEVE exibir selo E-Psi
- **RN-03**: Footer DEVE conter aviso CFP sobre urgências/emergências
- **RN-04**: LGPD e Código de Ética CFP obrigatórios
- **RN-05**: Política de cancelamento: aviso prévio de 24h
- **RN-06**: Atendimento presencial em Natal/RN; online para todo o Brasil

---

## 8. Integrações e Dependências

| Sistema | Tipo | Dados |
|---------|------|-------|
| WhatsApp Business | Link wa.me | Mensagem pré-preenchida |
| Instagram @psilucernapalhano | Link externo | Redirecionamento |
| Google Fonts | CDN CSS | Tipografia |
| Schema.org JSON-LD | Marcação semântica | SEO/GEO |

---

## 9. Paleta de Cores e Identidade Visual

- Tons: Nude, Terracota Suave, Bege, Areia, Café, Off-White
- Estilo: Sóbrio, elegante, minimalista, acolhedor, atemporal
- Referência: @psilucernapalhano — iluminação suave, tons quentes e terrosos

---

## 10. Palavras-chave SEO/GEO — Natal/RN

**Primárias:**
- Psicóloga em Natal RN
- Psicanalista em Natal RN
- Lucerna Palhano psicóloga

**Secundárias:**
- Psicoterapia online ansiedade e depressão
- Atendimento psicanalítico para adultos Natal
- Consulta psicológica particular Natal RN
- Psicóloga perto de mim Natal

---

## 11. Dúvidas em Aberto

| # | Dúvida | Status |
|---|--------|--------|
| 1 | Número real do WhatsApp oficial | Em aberto — placeholder: (84) 90000-0000 |
| 2 | Número do CRP | Em aberto — obrigatório no footer |
| 3 | Endereço/bairro do consultório em Natal/RN | Em aberto — importante para SEO Local |
| 4 | Fotos profissionais | Em aberto — imagens geradas por IA temporariamente |

---

## 12. Histórico de Versões

| Versão | Data | Alteração |
|--------|------|-----------|
| 1.0 | 2026-09-13 | Criação inicial |
