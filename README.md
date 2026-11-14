# 💸 App de Organização de Finanças Pessoais com Vibe Coding - O Agente 008

Link de acesso: https://money-mate-mischief.lovable.app/

- Meu **prompt final** (PRD) refinado no Gemini:

'''markdown

Crie um aplicativo web de finanças pessoais com base no seguinte PRD (Product Requirements Document) e com layout 100% responsivo para celular:

# PRD: Agente 008 – Finanças Pessoais Sem Complicação

## 1. Visão Geral do Produto
Criar um aplicativo web responsivo (foco mobile-first) de organização financeira pessoal baseado em conversação natural. O objetivo é eliminar formulários manuais e planilhas complexas, permitindo que iniciantes sem educação financeira controlem seus gastos conversando com uma IA bem-humorada.

## 2. Público-Alvo e Problema
- **Público:** Jovens adultos e iniciantes brasileiros que nunca controlaram suas finanças e têm aversão a termos técnicos (como "amortização", "passivos" ou gráficos complexos).
- **Problema:** O abandono precoce de apps financeiros devido ao tédio do preenchimento manual e à linguagem intimidadora.

## 3. Identidade, Tom de Voz e Design (UI/UX)
- **Persona da IA:** "Agente 008" (007+1), um espião financeiro atrapalhado, carismático e parceiro.
- **Tom de Voz:** Leve, acessível, empático e bem-humorado, inspirado nas notificações do iFood e na gamificação do Duolingo. Sem julgamentos pesados, mas com alertas criativos (ex: *"Missão comprometida: esse delivery de terça-feira custou 15% da sua meta da semana. Vamos compensar no café em casa amanhã?"*).
- **Estilo Visual:** Limpo, moderno, amigável e minimalista. Fundo claro (off-white/cinza bem suave), cartões com bordas arredondadas, tipografia legível e uso estratégico de cores (Verde menta para metas atingidas/economia, Laranja/Coral para alertas leves, Azul vibrante para ações principais).

## 4. Escopo do MVP e Telas Principais

### Tela 1: Onboarding Express (Boas-vindas)
- Sem cadastros longos. O Agente 008 se apresenta em 2 balões de conversa, pergunta o nome do usuário e qual é o seu maior objetivo financeiro atual (ex: *"Sair do sufoco"*, *"Juntar para uma viagem"*, *"Controlar o iFood"*).

### Tela 2: Central de Comando (Chat Principal - Tela Inicial)
- Interface estilo WhatsApp/chat moderno, limpa e direta.
- **Input rápido:** Campo de texto na parte inferior com sugestões de atalhos rápidos acima do teclado (ex: *"Gastei R$..."*, *"Recebi R$..."*, *"Como estou hoje?"*).
- **Feedback imediato:** Quando o usuário digita *"Almocei por 32 reais no pix"*, o Agente 008 responde confirmando o registro, mostra um mini-card visual com a categoria atribuída automaticamente ( Alimentação - R$ 32,00) e faz um comentário divertido.

### Tela 3: Raio-X Financeiro (Relatórios Simples)
- Nada de gráficos de velas ou tabelas gigantes.
- **Card de Saldo da Missão:** Quanto entrou vs. quanto saiu no mês, em números grandes e claros.
- **Top 3 Vilões do Mês:** Lista visual simples mostrando apenas as 3 categorias onde o usuário mais gastou, com barras de progresso coloridas e porcentagens fáceis de entender.
- **Pílula de Sabedoria do 008:** Um card no topo com uma dica prática e personalizada baseada nos gastos recentes.

### Tela 4: Missões (Metas Financeiras)
- Lista de metas criadas pelo usuário (ex: *"Reserva de Paz"* ou *"Show no fim do ano"*).
- Cada meta tem uma barra de progresso visual, o valor atual, o valor alvo e um botão rápido de *"Aportar agora"* que simula a transferência e gera uma comemoração visual (confetes ou selo de missão cumprida).

## 5. Requisitos Funcionais e Dados (Para Protótipo)
- Criar dados fictícios (mock data) realistas pré-carregados para que o usuário já veja o dashboard e o chat funcionando ao abrir o app pela primeira vez.
- Simular a inteligência do chat categorizando palavras-chave comuns (ex: "uber", "lanche", "mercado", "aluguel", "salário") e respondendo com variações de humor do Agente 008.
- Navegação inferior (Bottom Bar) fixa com 3 ícones: **Chat (Agente 008)**, **Resumo (Raio-X)** e **Missões (Metas)**.

Importante: Otimize a utilização de créditos para que o resultado seja completo e satisfatório.

'''


- Prints ou pequenos vídeos das interações com a IA:
<img width="1567" height="761" alt="Print primeira resposta Gemini" src="https://github.com/user-attachments/assets/18ab4f23-7e42-41da-b5a5-2829c2a07845" />
<img width="1587" height="744" alt="Print segunda resposta Gemini" src="https://github.com/user-attachments/assets/602cc3df-eaaa-4124-b307-251885725ad7" />
<img width="1598" height="771" alt="Print primeiro pedido Lovable" src="https://github.com/user-attachments/assets/28260d18-6b8b-4f9f-a714-dfc0dcfeca1b" />
<img width="452" height="759" alt="image" src="https://github.com/user-attachments/assets/7ab3a6a2-61dd-4493-bdce-8219e8613f4d" />


### Um resumo do que o seu **App de Finanças Pessoais** faz;
O Agente 008 foi concebido para pessoas que acham planilhas e aplicativos financeiros tradicionais chatos, burocráticos ou punitivos.

### O que o aplicativo é capaz de fazer hoje
- Registro conversacional de gastos e receitas (Chat 008):

- Em vez de preencher formulários com dezenas de campos, você digita em linguagem natural (ex.: "Paguei 45 no uber", "Almocei 32 no pix", "Recebi 250 de freela").
O agente extrai o valor, identifica se é entrada ou saída, categoriza automaticamente (Transporte, Alimentação, Delivery, Moradia, Renda, etc.) e gera um cartão de confirmação.
O 008 devolve uma resposta imediata com personalidade bem-humorada de agente secreto.
Raio-X Financeiro (Resumo visual direto ao ponto):

- Saldo consolidado do mês (quanto entrou vs. quanto saiu).
Destaque para os 3 maiores "vilões" de gastos (as categorias que mais consumiram o orçamento com barras de porcentagem).
Pílula de sabedoria dinâmica gerada com base no seu padrão de gastos atual.
Histórico cronológico das transações registradas.
Missões Gamificadas (Metas financeiras):

- Acompanhamento visual de metas (ex.: "Reserva de Paz", "Show no fim do ano", "Viagem").
Botão de aporte rápido ("Aportar R$ 50 agora") para incentivar o hábito de guardar pequenas quantias com um toque.
Animações de celebração ao atingir o objetivo e formulário rápido para criar novas missões.
Apresentação e persistência local:

- Onboarding rápido que pergunta o nome e o objetivo financeiro para calibrar o diálogo.
Dados salvos localmente no navegador, permitindo testar tudo imediatamente.


### Breve reflexão sobre o processo:
- O que funcionou bem? A utilização de uma segunda IA para planejar o prompt inicial do Lovable, refinando o pedido inicial e otimizando o uso de créditos.
- O que não funcionou como o esperado? O uso de créditos do Lovable, mesmo que feito o planejamento prévio do prompt. Para o processo de criação, aparentemente os créditos terminam muito rápido e algumas alterações críticas não puderam ser feitas tempestivamente.
- O que aprendeu sobre conversar com IAs? O processo de conversa foi bem natural e intuitivo, trazendo respostas especializadas sobre assuntos específicos, mostrando-se um recurso com potenciais ilimitados.


