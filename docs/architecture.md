# Arquitetura da landing page — INSPEM Avaliação Neuropsicológica

**Versão:** 1 — aguardando aprovação  
**Diretriz:** manter o ritmo, a identidade e a maior parte dos componentes do site de psicoterapia, alterando a narrativa para a avaliação neuropsicológica.

## Ordem das seções

### 1. Header

**Função:** orientar a navegação e manter o WhatsApp acessível.

**Links recomendados:**

- Para quem é
- Como funciona
- Investimento
- Equipe
- Localização
- Dúvidas

**Ação:** `Solicitar avaliação`

---

### 2. Hero

**Função:** reconhecer a busca por respostas, apresentar o benefício central e levar ao contato.

**Conteúdo necessário:**

- identificação: avaliação neuropsicológica presencial em Porto Alegre;
- H1 curto, centrado em compreensão e clareza;
- apoio que explique que história, observações e testes são integrados;
- CTA principal para o WhatsApp;
- nota 5,0 no Google;
- informação curta sobre estagiários e supervisão de Simone;
- mesma fotografia atual do hero.

**Pergunta respondida:** “Este serviço pode me ajudar a entender o que está acontecendo?”

---

### 3. Para quem é

**Função:** permitir reconhecimento sem transformar sinais em diagnóstico.

**Quatro grupos de situações:**

1. atenção, organização e memória;
2. aprendizagem, raciocínio e inteligência;
3. comunicação, interação e desenvolvimento;
4. personalidade, emoções e comportamento.

**Fechamento obrigatório:** essas situações não confirmam TDAH, TEA ou qualquer outra condição; a avaliação organiza informações para examinar hipóteses.

**Componente-base:** `ParaQuem.astro`, preservando os quatro cartões e os ícones semanticamente adaptados.

---

### 4. O que a avaliação ajuda a compreender

**Função:** apresentar a proposta de valor antes de explicar o cronograma.

**Estrutura:**

- introdução sobre funcionamento cognitivo e emocional;
- metáfora visual do quebra-cabeça;
- três resultados possíveis:
  - compreender pontos fortes e dificuldades;
  - sustentar, afastar ou redirecionar hipóteses;
  - orientar próximos passos e apoios;
- nota técnica curta: os instrumentos variam conforme idade, demanda e finalidade.

**Pergunta respondida:** “O que vou saber ao final?”

**Componente-base:** adaptação de `ComoFunciona.astro`, mantendo seu ritmo editorial e o bloco de evidência, sem estatísticas promocionais.

---

### 5. Como funciona o processo

**Função:** tornar o pacote concreto e reduzir insegurança sobre duração e etapas.

**Abertura:** aproximadamente oito sessões semanais de 50 minutos.

**Linha do tempo:**

1. **1ª sessão — anamnese:** compreensão da demanda e da história;
2. **2ª à 6ª sessões — testes:** aplicação dos instrumentos selecionados;
3. **7ª sessão — consulta médica opcional:** incluída sem custo adicional, quando necessária;
4. **8ª sessão — devolutiva:** explicação dos resultados, entrega do laudo e recomendações.

**Ressalva:** o número de encontros é aproximado e pode variar conforme a necessidade da avaliação.

**CTA intermediário:** `Tirar uma dúvida pelo WhatsApp`.

**Componente-base:** novo componente construído com os padrões visuais de `ComoComecar.astro`.

---

### 6. Como solicitar a avaliação

**Função:** explicar o início do contato sem repetir o processo clínico.

**Três passos:**

1. enviar uma mensagem pelo WhatsApp;
2. conversar sobre a demanda e a disponibilidade;
3. agendar a primeira sessão.

**Ação:** `Solicitar avaliação pelo WhatsApp`.

**Componente-base:** `ComoComecar.astro`, com a mesma estrutura de três cartões.

---

### 7. Investimento

**Função:** apresentar preço e condições sem ambiguidade.

**Conteúdo:**

- R$ 880 pelo pacote completo;
- pagamento à vista;
- parcelamento no cartão com juros;
- aproximadamente oito sessões;
- consulta médica opcional incluída, quando necessária;
- devolutiva e laudo técnico incluídos.

**Pendência para o FAQ:** confirmar nota fiscal, reembolso por plano e dedução no Imposto de Renda antes de reutilizar essas afirmações do site atual.

**Componente-base:** `Investimento.astro`.

---

### 8. Equipe e supervisão

**Função:** explicar claramente quem conduz e quem responde tecnicamente pelo processo.

**Conteúdo:**

- mesma foto da equipe;
- estagiários de Psicologia conduzem as etapas;
- supervisão das avaliações por Simone Regina Sandri, CRP 07/2433;
- credenciais públicas selecionadas de Simone;
- explicação simples de como a supervisão participa da avaliação;
- não apresentar Simone como especialista em Neuropsicologia sem comprovação do título.

**Decisão recomendada:** destacar apenas Simone como supervisora da avaliação. Ingrid pode aparecer na foto coletiva, mas não receber um cartão individual nesta página se não supervisionar esse serviço.

**Componente-base:** `Equipe.astro`.

---

### 9. Reconhecimento

**Função:** usar a reputação geral da clínica como prova institucional, sem atribuir depoimentos especificamente à avaliação neuropsicológica.

**Conteúdo:**

- nota 5,0 no Google;
- avaliações atuais sobre profissionalismo e atendimento;
- link para verificar as avaliações.

**Restrição:** remover ou revisar a afirmação de que profissionais encaminham pacientes se não houver comprovação publicável.

**Componente-base:** `Reconhecimento.astro`.

---

### 10. Localização

**Função:** mostrar onde ocorre o serviço presencial e reduzir dúvidas logísticas.

**Conteúdo:**

- Av. Osvaldo Aranha, 1022, sala 1610;
- Edifício Baltimore, Bom Fim, Porto Alegre;
- em frente ao Parque da Redenção;
- mapa;
- fachada e carrossel com todas as fotos atuais das salas.

**Componente-base:** `Localizacao.astro` sem mudança estrutural relevante.

---

### 11. Perguntas frequentes

**Função:** resolver objeções práticas antes da decisão.

**Perguntas iniciais recomendadas:**

1. Como saber se uma avaliação neuropsicológica pode ajudar?
2. A avaliação confirma um diagnóstico?
3. O que é avaliado?
4. O processo dura exatamente oito sessões?
5. Crianças, adolescentes, adultos e idosos podem ser avaliados?
6. Quem aplica os testes?
7. O que está incluído nos R$ 880?
8. Quando a consulta médica é realizada?
9. O que recebo ao final?
10. Posso parcelar o pagamento?
11. A avaliação é presencial?
12. Como solicito um horário?

**Componente-base:** `Faq.astro`, mantendo todos os itens fechados inicialmente.

---

### 12. CTA final e footer

**Função:** encerrar com o próximo passo e os dados institucionais.

**CTA:** `Solicitar avaliação pelo WhatsApp`.

**Mensagem:** não é necessário chegar com certeza sobre um diagnóstico; a conversa inicial verifica se o serviço corresponde à demanda.

**Footer:** logo, endereço, telefone, CNPJ, registro da clínica no CRP e links legais atuais.

**Componentes-base:** `CtaFinal.astro` e `Footer.astro`.

## Navegação narrativa

`Dúvida persistente → reconhecimento → compreensão do benefício → processo concreto → início simples → preço → confiança na equipe → reputação → local → objeções → WhatsApp`

## Componentes

### Reutilização direta ou quase direta

- `Header.astro`
- `Photo.astro`
- `WhatsAppButton.astro`
- `Investimento.astro`
- `Reconhecimento.astro`
- `Localizacao.astro`
- `Faq.astro`
- `CtaFinal.astro`
- `Footer.astro`

### Adaptação de conteúdo e semântica

- `Hero.astro`
- `ParaQuem.astro`
- `ComoFunciona.astro`
- `ComoComecar.astro`
- `Equipe.astro`

### Novo componente

- `ProcessoAvaliacao.astro`

## Critérios para aprovar a arquitetura

- O benefício aparece antes do cronograma e do preço.
- O visitante entende que sinais não equivalem a diagnóstico.
- O pacote e suas etapas ficam claros sem depender do FAQ.
- A função dos estagiários e a supervisão de Simone não ficam ambíguas.
- A consulta médica aparece como opcional e incluída sem custo adicional.
- Psicoterapia não aparece como oferta.
- Há apenas uma ação dominante: solicitar avaliação pelo WhatsApp.
