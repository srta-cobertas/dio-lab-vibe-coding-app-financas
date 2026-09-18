# App de Organização de Finanças Pessoais I Bruna Mendes Amstalden

## 1. Resumo do Projeto

O projeto consiste em um Web App responsivo e acessível de finanças pessoais que elimina a burocracia das planilhas tradicionais ao utilizar um agente de IA conversacional e proativo capaz de entender texto, áudio e fotos de recibos, além de interagir com o usuário por meio de confirmações rápidas em um toque no painel principal. 

Voltado para iniciantes e focado em transformar a gestão financeira em um hábito sem esforço, o produto combina uma identidade visual acolhedora em tons de verde e cantos arredondados com recursos avançados de acessibilidade universal (como comandos por voz, respostas em áudio, leitores de tela e alto contraste para pessoas com baixa visão ou mobilidade reduzida), navegação adaptativa (menu lateral em desktop e barra inferior em celular) e simulação de Open Finance com dados do contexto brasileiro em conformidade com a LGPD.


## 2. Prompt Final (PRD)

```markdown

Crie um Web App de organização financeira funcional e navegável com base nas seguintes diretrizes:

### Contexto
Criar um Web App de organização de finanças pessoais, projetado com interface responsiva (mobile-first para celular e layout adaptado para desktop). O web app funciona por meio de um agente inteligente, que conversa em linguagem casual e acessível, para entender o contexto financeiro do usuário, memorizar, organizar informações e sugerir dicas práticas.

A ideia é tornar o controle financeiro mais fácil, intuitivo e acessível, livre de burocracias e alterações complexas, como planilhas e formulários.

### Problema a resolver
O brasileiro não tem o costume de controlar suas finanças devido à ausência de educação financeira na infância, forte cultura do imediatismo, informalidade do trabalho e a ilusão de que calcular os gastos "de cabeça" funciona. Sem clareza sobre o orçamento, o dinheiro se torna abstrato e o endividamento cresce.

Soluções tradicionais do mercado falham porque exigem demandas manuais exaustivas. Além disso, o excesso de burocracia e a fadiga de autenticação geram abandono rápido dessas ferramentas.

### Proposta de valor
Transformar a gestão financeira em um hábito sem esforço por meio de uma experiência conversacional fluida e recomendações automatizadas ao perfil do usuário.

### Público-alvo
Pessoas que buscam organizar suas finanças sem complicação. O foco são iniciantes que não têm o hábito de controlar os gastos, além de usuários insatisfeitos de outros aplicativos financeiros, que buscam uma experiência melhor e mais simples.

### Identidade Visual e UI/UX
- Cores: Paleta baseada em tons de verde (transmitindo saúde financeira, prosperidade e confiança) combinados com fundos claros e neutros.
- Estilo: Design amigável, acolhedor e moderno com cantos bem arredondados em cartões, botões, modais e campos de entrada.
- Acessibilidade: Interface desenvolvida com foco em pessoas com baixa visão e limitações de mobilidade (alto contraste, suporte a leitores de tela, elementos interativos com área de toque mínima e opções de personalização como tamanho de fonte, modo escuro e alto contraste).

### Princípios inegociáveis
1- Segurança e transparência: Comunicar de forma clara a conformidade com a LGPD e criptografia de dados (incluir badges e modais explicativos de segurança).
2- Acessibilidade e facilidade de uso: Priorizar recursos para pessoas com baixa visão (alto contraste e suporte a respostas em áudio) e dificuldade de mobilidade (botões amplos, comandos de voz e navegação simplificada).

### Principais funcionalidades
1- Agente de IA Proativo (tela inicial e chat):
- Feed proativo no painel principal com cartões interativos de ação rápida (ex: "Vi que caíram R$50 no Pix, foi almoço ou transporte?" com botões interativos que, ao serem clicados, começam a conversa com o agente).
- Chat conversacional multimodal com suporte visual a texto, áudio (com animação/estado visual de gravação) e upload de imagem/recibo.
- Opção de alternância no chat para o usuário escolher se a IA responde em áudio (ideal para baixa visão) ou texto.
- Liberdade para o usuário realizar ações manuais (ex: Botão flutuante para adicionar gasto manualmente).

2- Conexão Open Finance (simulado):
- Interface interativa simulando a conexão segura com bancos brasileiros (ex: Nubank, Itaú, Banco do Brasil) para importar dados sem burocracia, acompanhado de opção de registro via chat caso o usuário recuse a conexão.

3- Classificação automática de transações:
- Identificação e categorização de gastos com ícones coloridos e tags visuais no extrato.

4- Definição e acompanhamento de metas financeiras:
- Barras visuais de progresso dinâmicas para metas (ex: "Economizar R$500 até o fim do mês").

5- Dicas personalizadas do agente financeiro:
- Cartões de sugestões e conselhos práticos de economia baseados nos hábitos de consumo do usuário.

6- Relatórios e painel visual:
- Gráficos e resumos visuais e simples do saldo, gastos do mês e progresso geral.

# Entregáveis
Gerar um Web App totalmente navegável, responsivo e funcional composto por:

1- Navegação principal adaptativa:
- Layout Desktop: Menu lateral fixo (Sidebar) na esquerda com ícones e rótulos claros.
- Layout Mobile: Barra inferior fixa (Bottom Nav) para fácil alcance do polegar.
- Seções navegáveis: Início/Painel (tela inicial padrão), Chat IA, Transações (com Open Finance simulado), Metas & Dicas, e Central de Acessibilidade/Configurações.

2- Central de Acessibilidade dedicada:
- Modal ou tela de configurações contendo: slider para ajuste dinâmico do tamanho de texto, toggle para modo alto contraste, seletor de resposta por voz/áudio e seção sobre conformidade com a LGPD e segurança.

3- Estilo e design:
- Garantir o uso consistente dos tons de verde, componentes arredondados, fontes legíveis, botões grandes e visual leve.

4- Dados e contexto do Brasil:
- Pré-carregar o app com dados mockados realistas do contexto brasileiro (valores em R$, Pix, Mercado Livre, Supermercado, farmácia, salário).

5- Interatividade dinâmica:
- Ações como confirmar um card no feed proativo ou adicionar uma mensagem de gasto no chat devem atualizar dinamicamente os gráficos, o extrato e o saldo no painel principal.

```

## 3. Resultado no Lovable

Link: https://clara-controle-financeiro.lovable.app




