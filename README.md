# 💸 App de Organização de Finanças Pessoais com Vibe Coding - Everton A Santos

### 1 PRD foi refinado no chatGPT 

````
# PRD – Aplicativo de Finanças Pessoais Conversacional

## 1. Contexto e Visão
O aplicativo propõe um modelo de organização financeira baseado em conversas em linguagem natural, eliminando a complexidade de planilhas e formulários. A experiência é centrada em um Assistente Financeiro que registra gastos, organiza informações e orienta o usuário de forma simples e direta.

## 2. Problema a Ser Resolvido
Usuários desistem de controlar suas finanças porque os apps disponíveis:
- exigem muita entrada manual
- apresentam interfaces difíceis
- não se adaptam à forma como as pessoas realmente falam
- oferecem pouco suporte personalizado

A solução proposta usa conversa e automação para reduzir fricção e aumentar o engajamento.

## 3. Público-Alvo
- Pessoas iniciantes em controle financeiro.
- Usuários que desejam simplicidade e rapidez.
- Pessoas que desistem de apps tradicionais por exigirem muito esforço.
- Interessados em orientação prática e contextual.

## 4. Objetivos do Produto
1. Criar o app de finanças pessoais mais fácil de usar, baseado em chat.
2. Ajudar o usuário a registrar gastos diariamente sem esforço.
3. Oferecer visão clara de situação financeira, metas e compromissos futuros.

### KPIs principais
- Retenção D7 e D30
- Número de registros por dia por usuário
- Percentual de transações classificadas automaticamente
- Número de metas criadas e cumpridas
- Engajamento com o assistente financeiro

## 5. Funcionalidades-Chave do MVP

### 5.1. Registro de gastos via chat
O usuário registra gastos escrevendo mensagens como:
- "Gastei 35 no Uber."
- "Paguei mercado 120."

A IA extrai valor, data, categoria e registra automaticamente.

### 5.2. Classificação automática de transações
- Modelo inicial baseado em regras e palavras-chave.
- Correções feitas pelo usuário refinam o comportamento.
- Sistema aprende as preferências do usuário.

### 5.3. Metas financeiras
Exemplos:
- "Quero gastar menos de 300 em delivery este mês."
- "Meta de guardar 200 por mês."

O aplicativo acompanha, envia alertas e mostra progresso.

### 5.4. Agente Financeiro (Dicas e Insights)
O assistente fornece orientações contextualizadas sobre:
- gastos acima da média
- padrões de consumo
- oportunidades de economia
- alertas relativos a metas

Tom: claro, educativo e acessível.

### 5.5. Cartão de Crédito e Controle de Parcelamentos

#### 5.5.1. Registro conversacional de parcelamentos
Exemplos:
- "Comprei um celular de 2400 em 10x no cartão."
- "Farmácia em 6 vezes de 80."
- "Uber em 3x no Visa."

A IA identifica:
- valor total da compra
- número de parcelas
- valor da parcela
- categoria
- cartão utilizado
- mês da primeira parcela

Perguntas complementares são feitas apenas quando necessário.

#### 5.5.2. Controle de compromissos futuros
O sistema armazena:
- parcelas pagas e restantes
- total ainda comprometido
- impacto mensal nas faturas
- histórico de pagamentos

#### 5.5.3. Visão de Parcelamentos Ativos
Lista contendo:
- item
- valor mensal
- parcelas restantes
- total pendente
- categoria

#### 5.5.4. Projeção de Faturas Futuras
O app exibe os próximos três meses com:
- total projetado
- parcela de cada compromisso
- gastos avulsos já registrados
- assinaturas e gastos recorrentes identificados

#### 5.5.5. Insights financeiros sobre cartão e compromissos
Exemplos:
- "Sua fatura do próximo mês já está em determinado valor."
- "Você tem um total comprometido em parcelamentos futuros."
- "Seu parcelamento da loja X termina em março."

## 6. Fluxo do Usuário (MVP)
1. Onboarding rápido com perguntas simples.
2. Tela principal em formato de chat.
3. Registro de gastos e parcelamentos via linguagem natural.
4. Visualização de relatórios simples.
5. Projeção de faturas futuras.
6. Acompanhamento de metas.

## 7. Arquitetura do MVP

### Back-end
- Motor leve de NLP para interpretar mensagens.
- Sistema de classificação baseado em regras.
- Banco de dados para transações, metas e parcelamentos.
- Módulo de projeção financeira.

### Front-end
- Interface conversacional.
- Dashboard minimalista.
- Telas auxiliares para parcelamentos, metas e relatórios.

## 8. Principais Telas do MVP
- Onboarding
- Chat principal
- Relatórios mensais
- Parcelamentos ativos
- Projeção de faturas futuras
- Detalhe do parcelamento
- Metas financeiras
- Configurações gerais

## 9. Plano de Validação Inicial

### Fase 1 – Usabilidade
- Testar clareza do registro por chat.
- Avaliar interpretação da IA.
- Verificar compreensão das telas de projeção e parcelamentos.

### Fase 2 – Beta fechado
- Acompanhar uso por duas semanas.
- Métricas avaliadas:
  - número de registros
  - precisão da interpretação
  - uso das telas de compromissos futuros
  - repetição de uso do chat

### Fase 3 – Ajustes
- Refinar NLP
- Melhorar categorização automática
- Ajustar relatórios e projeções

## 10. Roadmap Futuro (Pós-MVP)
- Conexão com bancos por Open Finance
- Importação automática de faturas
- Identificação automática de parcelamentos via OCR
- Regras personalizadas por usuário
- Modo compartilhado ou familiar
- Registro por voz

## 11. Tom de Comunicação
- Amigável
- Claro
- Sem jargão técnico
- Educativo e motivador

## 12. Resumo para o Lovable
Criar um MVP navegável com:
- Chat principal
- Registro de gastos e parcelamentos via linguagem natural
- Classificação automática
- Metas básicas
- Relatórios mensais simples
- Visualização de parcelamentos ativos
- Projeção de faturas futuras
- Insights financeiros
- Interface minimalista e acessível
````


### 2 Interação com o Lovable
> Crie um app utilizando este PRD: {PRD}
> O salário se refere a um valor de crédito, e não de débito, o valor precisa entrar com saldo positivo e sensibilizar o saldo total positivamente
> os valores precisam sensibilizar a soma de Receitas (positivos) gastos (negativos) e saldo disponível

### 3 Resulado final no Lovable
https://chatty-cents-28.lovable.app/
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6db30ff9-6b80-4a98-8118-4bc0cb9c9cde" />


### 4. Resumo do que o seu **App de Finanças Pessoais** faz;  
# Resumo do Protótipo do Aplicativo

## Visão Geral
O site representa o protótipo inicial do aplicativo de finanças pessoais conversacional, criado no Lovable. Ele materializa a proposta central do PRD: permitir que o usuário gerencie suas finanças por meio de uma interface simples, com foco em interações via chat.

## Principais Elementos Observados
- Estrutura minimalista e funcional, adequada a um MVP.
- Tela principal orientada à conversa, refletindo o núcleo da experiência definida no PRD.
- Base ideal para evolução dos módulos de gastos, metas, parcelamentos e projeção de faturas.

## Aderência ao PRD
- Alinhado com o objetivo de reduzir fricção no registro de gastos através de linguagem natural.
- Facilita a validação rápida da experiência conversacional.
- Permite expandir para funcionalidades-chave: classificação automática, acompanhamento de metas e controle de parcelamentos de cartão.

## Pontos de Validação
- Fluidez da experiência no chat.
- Clareza do fluxo inicial (onboarding).
- Preparação do modelo para incorporar regras de parcelamento e projeção futura.
- Compreensão do usuário ao navegar pelas informações básicas do app.


## 5 Minha reflexão

  - O que funcionou bem?  
Funcionou muito bem o refinamento do PRD e foi bem interessante as interações para aperfeiçoamento do app. No lovable foi incrível ver o app sendo construído em minutos, pena que o crédito acabou, o designing ficou muito bom 

  - O que não funcionou como o esperado?
    Alguns calculos de soma e subtração não parecem estar correto, mas foi interessante para funcionar como protótipo

  - O que aprendeu sobre conversar com IAs?
    É como uma equipe de desenvolvimento ao meu dispor, no enanto é necessário um bom contexto e boa clareza do que se pretende fazer e principalmente qual o problema de negócio



