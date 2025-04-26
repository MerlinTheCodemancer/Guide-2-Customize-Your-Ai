# 🤖 AI Assistant Personalization Guide | Guia de Personalização de Assistentes de IA

<a href="#personalizing-ai-assistants"><img src="https://www.datamyne.com.br/wp-content/blogs.dir/1/files/2022/04/united-states-1.png" width="30" height="20" alt="English"></a><a href="#personalizing-ai-assistants"> English</a> | <a href="#personalizando-assistentes-de-ia"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" width="30" height="20" alt="Português"></a> <a href="#personalizando-assistentes-de-ia"> PortuguesBR</a>
---

## Personalizing AI Assistants

### 👋 Introduction
Welcome to the AI Assistant Personalization Guide! This manual will help you customize popular AI assistants like GPT, Copilot, Gemini, and Claude to better suit your needs. Personalization improves your interaction with AI by making responses more relevant, structured, and aligned with your preferences.

### 🧠 What is AI Personalization?
AI personalization is the process of customizing how an AI assistant responds to your prompts. This is done through special instructions that tell the AI how to format answers, what tone to use, what languages to prioritize, and what structure to follow. Think of it as setting your preferences before starting a conversation!

### 🎯 Why Personalize AI Assistants?
- **Consistency:** Get similarly structured responses each time
- **Efficiency:** Receive information in your preferred format
- **Relevance:** Focus on topics and styles that matter to you
- **Clarity:** Establish clear communication patterns

### ⚙️ How to Personalize Different AI Assistants

#### GitHub Copilot
**Create a personalization file:**
1. Create a file named `.github/copilot-instructions.md` in your repository
2. Add your personalization template (see examples below)

**Format to use:**
```markdown
# Copilot Custom Instructions

[Your personalization instructions here]
```

**Activation:**
- Once saved, Copilot will use these instructions when providing assistance in this repository

#### ChatGPT (GPT)
**Custom Instructions:**
1. Go to your profile settings
2. Select "Custom Instructions"
3. Fill in the "What would you like ChatGPT to know about you?" and "How would you like ChatGPT to respond?" sections
4. Add your personalization template

**Per-conversation basis:**
- Start any conversation with your personalization template
- Example: "I'd like you to respond following these guidelines: [paste template]"

#### Google Gemini
**Session Preferences:**
- Start your conversation with a clear instruction
- Format: "For this conversation, please follow these guidelines: [paste template]"

**In Gemini Advanced:**
- Create a custom Gem with your personalization preferences
- Access it whenever you need that specific personalization style

#### Anthropic Claude
**Session Setup:**
- Begin your conversation by establishing your preferences
- "Hi Claude, please follow these instructions for our conversation: [paste template]"

**Claude Pro:**
- Save frequently used personalization templates as prompts
- Quickly access them to start new conversations

### 📝 Universal Personalization Template
Here's a universal template you can adapt for any AI assistant:

```
😊 *Objective:* Answer in clear topics, with empathy and professionalism.
🗣 Use Portuguese BR and English preferencial languages
📝 *Question Skeleton:*
1. 🤔 What is X?
2. 💡 How to apply X?
3. 🛠 Practical examples of X.
🔧 *Style Rules:*
- Use *bold, *italics and titles.
- Separate each group of code into distinct blocks.
- End with a *Sources & References* section:
- [Official Documentation](URL/file/repository)
- [Related Article](URL/file/repository)
- *Always specifically address the subject matter* in your response, making it clear what topic you're discussing.
🔍 *Self-explanation:*
Copilot should explain the logic of each answer after presenting it. & Be true to the answer
```

### 🔗 "Simple" XML Template
For more structured responses, you can use this XML template [Only substitute text]:

```xml
<prompt>
  <objective>Answer with clarity, empathy and professionalism</objective>
  <language>English and Portuguese</language>
  <structure>
    <section id="concept">What is [TOPIC]?</section>
    <section id="application">How to apply [TOPIC]?</section>
    <section id="examples">Practical examples of [TOPIC]</section>
  </structure>
  <style>
    <formatting>Use bold for key concepts, italics for emphasis</formatting>
    <code>Separate code blocks by language</code>
    <references>Include official sources and documentation</references>
  </style>
  <output>Explain reasoning after providing the answer</output>
</prompt>
```

### 🔄 Advanced XML-Based Prompt Template
For more structured responses, you can use this XML-enhanced template:

```xml
<template>
  <objective>
    Answer with clarity, empathy and professionalism, organizing content in well-defined topics.
  </objective>
  
  <languages>
    <primary_language>Portuguese (Brazil)</primary_language>
    <secondary_language>English</secondary_language>
  </languages>
  
  <question_structure>
    <question level="1">🤔 What is [TOPIC]?</question>
    <question level="2">💡 How to apply [TOPIC]?</question>
    <question level="3">🛠️ Practical examples of [TOPIC].</question>
  </question_structure>
  
  <style_rules>
    <formatting>
      <element>Use **bold** for key concepts</element>
      <element>Use *italics* for emphasis</element>
      <element>Use headings and subheadings for organization</element>
    </formatting>
    
    <code>
      <instruction>Separate each code group into distinct blocks with specified language</instruction>
      <example>```python
print("Code example")
```</example>
    </code>
    
    <conclusion>
      <references_section>
        <reference type="documentation">Official Documentation: [Link](URL)</reference>
        <reference type="article">Related Article: [Link](URL)</reference>
      </references_section>
    </conclusion>
  </style_rules>
  
  <meta_instruction>
    Specifically address the subject matter, making it clear which topic is being discussed.
    Explain the logic of each answer after presenting it, remaining faithful to the original content.
  </meta_instruction>
</template>
```

### ✨ Best Practices for Personalization
- **Be specific:** Clearly define what you want
- **Prioritize information:** Put the most important instructions first
- **Use structure:** Organize with headings, lists, and sections
- **Include examples:** Show the AI exactly what you expect
- **Test and refine:** Adjust your template based on results

### 👨‍🏫 Example: Subject Matter Expert Personalization
```
Act as an expert in [FIELD] with 15+ years of experience.
- Answer questions about [TOPIC] with depth and precision
- Use technical vocabulary appropriate for [BEGINNER/ADVANCED] level
- Structure responses with clear headings and bullet points
- Include practical examples that demonstrate concepts
- Reference authoritative sources in the field
```

### 📚 References
- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [ChatGPT Custom Instructions Guide](https://help.openai.com/en/articles/7730887-custom-instructions-for-chatgpt)
- [Gemini Advanced Documentation](https://ai.google.dev/gemini-api/docs/models/gemini)
- [Claude Documentation](https://docs.anthropic.com/claude/docs)
- [Markdown Guide](https://www.markdownguide.org/)

---

## Personalizando Assistentes de IA

### 👋 Introdução
Bem-vindo ao Guia de Personalização de Assistentes de IA! Este manual vai te ajudar a customizar assistentes populares como GPT, Copilot, Gemini e Claude para atender melhor às suas necessidades. A personalização melhora sua interação com a IA, tornando as respostas mais relevantes, estruturadas e alinhadas com suas preferências.

### 🧠 O que é Personalização de IA?
Personalização de IA é o processo de customizar como um assistente de IA responde aos seus prompts. Isso é feito através de instruções especiais que dizem à IA como formatar respostas, qual tom usar, quais idiomas priorizar e qual estrutura seguir. Pense nisso como configurar suas preferências antes de iniciar uma conversa!

### 🎯 Por que Personalizar Assistentes de IA?
- **Consistência:** Obtenha respostas estruturadas de forma semelhante a cada vez
- **Eficiência:** Receba informações no seu formato preferido
- **Relevância:** Foque em tópicos e estilos que importam para você
- **Clareza:** Estabeleça padrões claros de comunicação

### ⚙️ Como Personalizar Diferentes Assistentes de IA

#### GitHub Copilot
**Crie um arquivo de personalização:**
1. Crie um arquivo chamado `.github/copilot-instructions.md` no seu repositório
2. Adicione seu modelo de personalização (veja exemplos abaixo)

**Formato a ser usado:**
```markdown
# Instruções Personalizadas do Copilot

[Suas instruções de personalização aqui]
```

**Ativação:**
- Uma vez salvo, o Copilot usará essas instruções ao fornecer assistência neste repositório

#### ChatGPT (GPT)
**Instruções Personalizadas:**
1. Acesse as configurações do seu perfil
2. Selecione "Instruções Personalizadas"
3. Preencha as seções "O que você gostaria que o ChatGPT soubesse sobre você?" e "Como você gostaria que o ChatGPT respondesse?"
4. Adicione seu modelo de personalização

**Base por conversa:**
- Inicie qualquer conversa com seu modelo de personalização
- Exemplo: "Gostaria que você respondesse seguindo estas diretrizes: [cole o modelo]"

#### Google Gemini
**Preferências de Sessão:**
- Comece sua conversa com uma instrução clara
- Formato: "Para esta conversa, por favor siga estas diretrizes: [cole o modelo]"

**No Gemini Advanced:**
- Crie um Gem personalizado com suas preferências
- Acesse-o sempre que precisar desse estilo específico de personalização

#### Anthropic Claude
**Configuração de Sessão:**
- Inicie sua conversa estabelecendo suas preferências
- "Olá Claude, por favor siga estas instruções para nossa conversa: [cole o modelo]"

**Claude Pro:**
- Salve modelos de personalização frequentemente usados como prompts
- Acesse-os rapidamente para iniciar novas conversas

### 📝 Modelo Universal de Personalização
Aqui está um modelo universal que você pode adaptar para qualquer assistente de IA:

```
😊 *Objetivo:* Responder em tópicos claros, com empatia e profissionalismo.
🗣 Use Português BR e Inglês como idiomas preferenciais
📝 *Esqueleto da Pergunta:*
1. 🤔 O que é X?
2. 💡 Como aplicar X?
3. 🛠 Exemplos práticos de X.
🔧 *Regras de Estilo:*
- Use *negrito, *itálico e títulos.
- Separe cada grupo de código em blocos distintos.
- Termine com uma seção de *Fontes e Referências*:
- [Documentação Oficial](URL/arquivo/repositório)
- [Artigo Relacionado](URL/arquivo/repositório)
- *Sempre aborde especificamente o assunto* em sua resposta, deixando claro qual tópico você está discutindo.
🔍 *Auto-explicação:*
O Copilot deve explicar a lógica de cada resposta após apresentá-la. & Seja fiel à resposta
```

### 🔗 XML "Simples"
Para respostas mais estruturadas, você pode usar este modelo XML [Substituir apenas o texto]:

```xml
<prompt>
  <objetivo>Responder com clareza, empatia e profissionalismo</objetivo>
  <idioma>Português e Inglês</idioma>
  <estrutura>
    <secao id="conceito">O que é [TÓPICO]?</secao>
    <secao id="aplicacao">Como aplicar [TÓPICO]?</secao>
    <secao id="exemplos">Exemplos práticos de [TÓPICO]</secao>
  </estrutura>
  <estilo>
    <formatacao>Use negrito para conceitos-chave, itálico para ênfase</formatacao>
    <codigo>Separe blocos de código por linguagem</codigo>
    <referencias>Inclua fontes oficiais e documentação</referencias>
  </estilo>
  <saida>Explique o raciocínio após fornecer a resposta</saida>
</prompt>
```

### 🔄 Modelo Avançado de Prompt com XML
Para respostas mais estruturadas, você pode usar este modelo aprimorado com XML:

```xml
<template>
  <objetivo>
    Responder com clareza, empatia e profissionalismo, organizando o conteúdo em tópicos bem definidos.
  </objetivo>
  
  <idiomas>
    <idioma_principal>Português (Brasil)</idioma_principal>
    <idioma_secundario>Inglês</idioma_secundario>
  </idiomas>
  
  <estrutura_perguntas>
    <pergunta nivel="1">🤔 O que é [TÓPICO]?</pergunta>
    <pergunta nivel="2">💡 Como aplicar [TÓPICO]?</pergunta>
    <pergunta nivel="3">🛠️ Exemplos práticos de [TÓPICO].</pergunta>
  </estrutura_perguntas>
  
  <regras_estilo>
    <formatacao>
      <elemento>Usar **negrito** para conceitos-chave</elemento>
      <elemento>Usar *itálico* para ênfase</elemento>
      <elemento>Utilizar títulos e subtítulos para organização</elemento>
    </formatacao>
    
    <codigo>
      <instrucao>Separar cada grupo de código em blocos distintos com o idioma especificado</instrucao>
      <exemplo>```python
print("Exemplo de código")
```</exemplo>
    </codigo>
    
    <conclusao>
      <secao_referencias>
        <referencia tipo="documentacao">Documentação Oficial: [Link](URL)</referencia>
        <referencia tipo="artigo">Artigo Relacionado: [Link](URL)</referencia>
      </secao_referencias>
    </conclusao>
  </regras_estilo>
  
  <meta_instrucao>
    Abordar especificamente o assunto em questão, deixando claro qual tópico está sendo discutido.
    Explicar a lógica de cada resposta após apresentá-la, mantendo a fidelidade ao conteúdo original.
  </meta_instrucao>
</template>
```

### ✨ Melhores Práticas de Personalização
- **Seja específico:** Defina claramente o que você quer
- **Priorize informações:** Coloque as instruções mais importantes primeiro
- **Use estrutura:** Organize com títulos, listas e seções
- **Inclua exemplos:** Mostre à IA exatamente o que você espera
- **Teste e refine:** Ajuste seu modelo com base nos resultados

### 👨‍🏫 Exemplo: Personalização de Especialista em Assunto
```
Atue como um especialista em [ÁREA] com mais de 15 anos de experiência.
- Responda perguntas sobre [TÓPICO] com profundidade e precisão
- Use vocabulário técnico apropriado para nível [INICIANTE/AVANÇADO]
- Estruture respostas com títulos claros e marcadores
- Inclua exemplos práticos que demonstrem os conceitos
- Faça referência a fontes autoritativas na área
```

### 📚 Fontes e Referências
- [Documentação do GitHub Copilot](https://docs.github.com/en/copilot)
- [Guia de Instruções Personalizadas do ChatGPT](https://help.openai.com/en/articles/7730887-custom-instructions-for-chatgpt)
- [Documentação do Gemini Advanced](https://ai.google.dev/gemini-api/docs/models/gemini)
- [Documentação do Claude](https://docs.anthropic.com/claude/docs)
- [Guia de Markdown](https://www.markdownguide.org/)
