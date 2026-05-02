# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

O que eu fiz para ter a minha versão:

Criei o  **repositório no GitHub** (fazendo o **fork** do original).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  

# 💡 PROJETO: App de Finanças Pessoais Conversacional

## 🎯 Objetivo
Criar um aplicativo de controle financeiro simples, baseado em chat, onde o usuário registra gastos em linguagem natural e recebe insights automáticos.

---

## 🧠 Problema
Apps financeiros atuais falham porque:
- Exigem entrada manual excessiva
- São complexos para iniciantes
- Não oferecem orientação personalizada

---

## 👤 Público-Alvo
- Iniciantes em finanças pessoais
- Pessoas que evitam planilhas
- Usuários que preferem simplicidade

---

## 🚀 Proposta de Valor
“Controle financeiro tão simples quanto conversar.”

---

## 🔑 FUNCIONALIDADES PRINCIPAIS (MVP)

1. Registro de gastos via linguagem natural  
Ex: “Gastei 30 reais com Uber”

2. Classificação automática  
Sistema interpreta:
- valor
- categoria
- data

3. Metas financeiras  
Ex: “Quero guardar 500 reais”

4. Agente Financeiro (IA)
- Dá dicas simples
- Sugere economia
- Gera alertas

5. Relatórios simples
- Resumo semanal/mensal
- Insights automáticos

---

## 🤖 AGENTE FINANCEIRO (COMPORTAMENTO)

### Personalidade
- Simples
- Educativo
- Motivador
- Não julgador

### Tom de voz
- Conversa natural (estilo WhatsApp)
- Frases curtas
- Direto ao ponto

### Exemplos
- “Você gastou bastante com comida essa semana. Quer tentar reduzir?”
- “Se economizar 10 reais por dia, você atinge sua meta.”

---

## 📱 FLUXO DO APP (BASEADO EM CHAT)

### 1. Onboarding
- Pergunta objetivo financeiro
- Ex: “Quer economizar ou só organizar?”

---

### 2. Tela Principal (Chat)
- Input de texto
- Histórico de conversa
- Sugestões rápidas

---

### 3. Interpretação de Mensagem
Usuário: “Gastei 50 no mercado”

Sistema:
- Detecta valor, categoria
- Retorna confirmação:
  “Registrar 50 reais em alimentação?”

---

### 4. Metas
- Criar meta
- Acompanhar progresso

---

### 5. Relatórios
- Resumo automático:
  “Você gastou 1200 este mês. 40% foi alimentação.”

---

## ⚙️ REGRAS IMPORTANTES

- Priorizar simplicidade (evitar telas complexas)
- Tudo deve poder ser feito via chat
- Sempre confirmar ações importantes
- Usar linguagem natural em toda UI

---

## 🧪 VALIDAÇÃO DO MVP

### Hipóteses
- Chat é mais fácil que formulário
- Simplicidade aumenta uso contínuo

### Métricas
- Retenção (7 dias)
- Nº de registros por usuário
- Criação de metas
- Engajamento com dicas

### Teste inicial
- 20 a 50 usuários
- Feedback direto
- Iteração rápida

---

# ⚡ PROMPTS OTIMIZADOS PARA LOVABLE

## 🔹 Prompt 1 (PRINCIPAL — USE PRIMEIRO)
Crie o app completo com base neste PRD.
Gere:
- Estrutura de telas
- Componentes principais
- Fluxo de navegação
- Experiência de chat detalhada

Priorize simplicidade e UX conversacional.

---

## 🔹 Prompt 2 (AGENTE)
Defina o comportamento completo do agente financeiro.
Inclua:
- Personalidade
- Tom de voz
- 10 exemplos de diálogo real

---

## 🔹 Prompt 3 (UX)
Otimize a experiência do usuário.
Sugira:
- Melhorias no fluxo
- Redução de fricção
- Microinterações

---

## 🔹 Prompt 4 (MVP RESUMIDO)
Resuma o MVP em:
- 5 funcionalidades essenciais
- Stack recomendada
- Forma mais rápida de validar

---

## 🔹 Prompt 5 (VALIDAÇÃO)
Crie um plano prático de validação com:
- Testes reais
- Métricas claras
- Critérios de sucesso

- Prints ou pequenos vídeos das interações com a IA;
<img width="675" height="527" alt="image" src="https://github.com/user-attachments/assets/1e066c29-42aa-4951-860c-b2a11237d211" />
<img width="688" height="546" alt="image" src="https://github.com/user-attachments/assets/9b0bb97c-37aa-4b53-9106-a549fed1ba2b" />
<img width="672" height="546" alt="image" src="https://github.com/user-attachments/assets/f7bda9c4-478e-4d1a-a778-95a17f8c315e" />
<img width="686" height="569" alt="image" src="https://github.com/user-attachments/assets/35d3556b-8346-4c1a-bcdb-7a9434472a2e" />
Melhorias no comportamento do agente, que não esta rodando uma ia Real - sua parser PT-BR Local.
A IA entrará como um plus na versao paga !

- Um resumo do que o seu **App de Finanças Pessoais** faz;
  O app já está implementado como MVP frontend (sem IA real — usa parser PT-BR local). Vou definir o comportamento do agente como documento de referência (markdown em /mnt/documents/) e também salvá-lo na memória do projeto para guiar futuras iterações de copy e tom no código. Resumo do que ficou definido:
Personalidade: Fin — amigo organizado (coach calmo + companheiro leve + assistente preciso), nunca julga, nunca dá palpite de investimento.
Tom de voz: PT-BR informal-respeitoso, 1–3 frases, valores em R$ 0,00, máx 1–2 emojis funcionais, sem caixa alta.
10 diálogos canônicos cobrindo: registro simples, valor com data, mensagem ambígua, categoria incerta, criar meta, relatório, insight proativo, erro, usuário ansioso, e pedido fora do escopo.
Mapa de respostas por intenção alinhado ao parser que já existe em src/lib/parser.ts.

- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    🧠 O que mudou (e por que isso é melhor)
    Aqui vai o ponto importante — direto:
    Transformei o PRD em prompt executável (Lovable entende melhor assim)
    Reduzi ambiguidade → respostas mais assertivas
    Estruturei ordem ideal das 5 interações
    Foquei em:
    UX conversacional (core do produto)
    rapidez de MVP (seu objetivo real)
    clareza para IA (menos “interpretação”, mais “execução”)
   ⚡ Dica estratégica (isso vai te economizar MUITO tempo)
   Na prática, use assim:
   -  Cole TODO o PRD + Prompt 1
   -  Depois vá refinando com os outros prompts
   Se  fizer isso certo, você consegue:
   -  Protótipo funcional em 1–2 interações
   -  Ajustes nas outras 3
   O que não funcionou como o esperado?
    Como em todas as vezes que faço um desafio gosto de caminhar por caminhos ainda não trilhados, usei o chatgpt ao inves do copilot, vou fazer o copilot depois para fazer um comparativo, pois o chatgpt que uso é o gratuito, que estaria assim mais          acessivel  a pessoas mais leigas.
   -  Consegui rodar o prompt #1 que me deu um app finalizado , e rodei o prompt #2 que me deu um tom mais personalizado, ao rodar o prompt #3 os creditos acabaram.
   O que aprendeu sobre conversar com IAs?
   -  Que o que eu consigo depende de ser claro, colocar contexto, muitas vezes tenho de ser breve, principalmente quando uso de forma gratuita, tem algumas limitaçoes, as vezes tenho de fazer mais iteraçoes para ter sucesso.

> [!TIP]
> Publiquei o meu repositório e compartilhei o link na plataforma da DIO! Minha entrega é a prova de que agora domino o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

Vibe Coding permitiu que pessoas de "produto" iniciem nesta aventura de codificar e fazer MVP de forma mais simples e prática.

## Proposta Indecente da IA
Se quiser, posso dar o próximo passo mais avançado:
👉 converter isso direto em arquitetura + stack + banco + APIs (pronto pro n8n e SaaS)

Versão antiga do readme :

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
