# 💸 Meu Agente Financeiro com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o **Copilot Web** e o **Lovable**. A proposta é criar um aplicativo de organização financeira pessoal baseado em conversas em linguagem natural: o usuário fala com o agente financeiro "como se fosse no WhatsApp" e o app organiza receitas, despesas, metas e insights automaticamente.

---

## 🔄 Como o Projeto Foi Feito

1. **Criei um PRD** (Product Requirements Document) descrevendo o produto, o problema, o público, as funcionalidades, as telas e a estratégia de validação.
2. **Refinei o PRD no Copilot Web**, deixando tudo claro, objetivo e bem estruturado.
3. **Usei o PRD como prompt no Lovable**, que gerou o app completo com onboarding, dashboard, chat e relatórios.

---

## 📝 PRD Refinado no Copilot Web

Este foi o PRD que escrevi e refinei para servir de base ao Lovable:

````markdown
# PRD - Meu Agente Financeiro

## Visão do Produto

Criar um aplicativo de finanças pessoais baseado em conversação que permita aos usuários registrar despesas, receitas e metas financeiras utilizando linguagem natural.

O objetivo é tornar o controle financeiro simples, acessível e menos burocrático do que aplicativos tradicionais.

## Problema

Muitas pessoas abandonam aplicativos de controle financeiro porque:

- Exigem preenchimento manual excessivo.
- Possuem interfaces complexas.
- Não fornecem orientações personalizadas.
- Tornam o gerenciamento financeiro uma atividade cansativa.

Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade para economizar.

## Público-Alvo

### Usuário Principal

Pessoas entre 18 e 45 anos que:

- Desejam melhorar sua organização financeira.
- Nunca utilizaram aplicativos financeiros regularmente.
- Consideram planilhas complicadas.
- Procuram uma solução simples e intuitiva.

### Usuário Secundário

- Universitários.
- Jovens profissionais.
- Pessoas iniciando sua jornada de educação financeira.

## Proposta de Valor

Controle suas finanças conversando.

O usuário não precisa preencher formulários complexos. Basta informar suas movimentações financeiras como faria em uma conversa comum.

Exemplos:

- "Gastei R$ 50 no supermercado."
- "Recebi R$ 3.000 de salário."
- "Quero economizar R$ 2.000 para viajar."

## Objetivo do MVP

Validar se uma interface conversacional aumenta a frequência de registros financeiros quando comparada a métodos tradicionais baseados em formulários.

## Funcionalidades do MVP

### Registro Financeiro por Chat

Permitir que o usuário registre:

- Despesas
- Receitas
- Transferências simples

Exemplos:

- Gastei R$ 120 com gasolina.
- Paguei R$ 45 no almoço.
- Recebi R$ 2.500 de salário.

### Classificação Automática

O sistema deve identificar automaticamente:

- Valor
- Tipo da transação
- Categoria
- Data

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Outros

### Metas Financeiras

Permitir:

- Criar metas
- Editar metas
- Acompanhar progresso

Exemplo:

"Quero guardar R$ 5.000 até dezembro."

### Agente Financeiro

Assistente baseado em IA responsável por:

- Analisar gastos
- Identificar padrões
- Gerar recomendações de economia
- Incentivar hábitos financeiros saudáveis

Exemplos:

- Você gastou 20% mais com delivery este mês.
- Sua maior categoria de gastos é transporte.
- Mantendo seu ritmo atual, você atingirá sua meta em cinco meses.

### Relatórios Simples

Exibir:

- Total gasto no mês
- Total recebido no mês
- Saldo atual
- Gastos por categoria
- Evolução mensal

## Principais Telas

### 1. Onboarding

Objetivos:

- Explicar o funcionamento do aplicativo
- Coletar informações iniciais do usuário

Campos:

- Nome
- Objetivo financeiro principal
- Faixa de renda (opcional)

### 2. Dashboard

Exibir:

- Saldo atual
- Gastos do mês
- Receitas do mês
- Metas ativas
- Resumo financeiro

### 3. Chat Financeiro

Funcionalidades:

- Registrar despesas
- Registrar receitas
- Consultar saldo
- Conversar com o Agente Financeiro

### 4. Metas Financeiras

Permitir:

- Criar metas
- Editar metas
- Visualizar progresso

### 5. Relatórios

Exibir:

- Gastos por categoria
- Evolução dos gastos
- Tendências mensais
- Insights gerados pela IA

## Fluxo Principal do Usuário

1. Usuário cria uma conta.
2. Define um objetivo financeiro inicial.
3. Registra gastos e receitas através do chat.
4. O sistema classifica automaticamente as transações.
5. O dashboard é atualizado.
6. O Agente Financeiro gera recomendações personalizadas.
7. O usuário acompanha metas e evolução financeira.

## Requisitos Não Funcionais

### Usabilidade

- Interface simples para iniciantes.
- Curva de aprendizado mínima.
- Linguagem amigável e educativa.

### Performance

- Resposta do chat em até 3 segundos.

### Segurança

- Dados financeiros protegidos.
- Conformidade com LGPD.

### Responsividade

- Funcionar perfeitamente em dispositivos móveis e desktop.

## Critérios de Sucesso

### Produto

- 70% dos usuários registram pelo menos uma transação na primeira sessão.
- 50% dos usuários retornam após 7 dias.
- 80% das transações são categorizadas corretamente.

### Experiência

- Registro de uma despesa em menos de 10 segundos.
- Avaliação média superior a 4 de 5.

## Estratégia de Validação

### Hipótese Principal

Usuários preferem registrar despesas através de conversa em vez de formulários tradicionais.

### Teste Inicial

Disponibilizar o MVP para um grupo de 20 a 50 usuários.

### O que Validar

- Frequência de uso.
- Facilidade de registro.
- Utilidade das recomendações.
- Interesse em continuar utilizando o produto.

### Critério de Validação

O MVP será considerado validado se:

- A maioria dos registros ocorrer via chat.
- Pelo menos 50% dos usuários retornarem após 7 dias.
- Os usuários relatarem que a experiência é mais simples do que aplicativos financeiros tradicionais.

## Fora do Escopo do MVP

Não implementar nesta primeira versão:

- Integração bancária automática.
- Open Finance.
- Importação de extratos.
- Investimentos.
- Cartão de crédito avançado.
- Compartilhamento familiar.
- Multiusuários.

Essas funcionalidades poderão ser avaliadas em versões futuras após a validação do MVP.
````

---

## 💬 Prompt Usado no Lovable

O PRD acima foi colado inteiro no Lovable com o seguinte prompt:

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

### 🧩 Do PRD para o App

Cada parte do PRD virou uma parte do app gerado pelo Lovable:

| Seção do PRD | O que o Lovable gerou |
|---|---|
| Onboarding (nome, objetivo, renda) | Fluxo de 4 etapas com barra de progresso |
| Dashboard | Saldo atual, receitas, gastos e balanço líquido |
| Chat Financeiro | Conversa com o Agente Financeiro e sugestões de mensagens |
| Relatórios | Gráficos por categoria e receitas vs despesas, com filtros de período |
| Metas Financeiras | Área de metas no menu lateral |
| Proposta de valor ("controle suas finanças conversando") | Tom de conversa de WhatsApp em todo o app |

---

## 🎯 Resultado Final

Acesse o protótipo funcional no Lovable:  
**[SEU-LINK-AQUI.lovable.app](https://SEU-LINK-AQUI.lovable.app/)**

<img width="1581" alt="Dashboard do Meu Agente Financeiro" src="./images/05-dashboard.png" />

---

## 🔍 Telas e Funcionalidades do App

### 1. Boas-vindas
- Apresenta o agente financeiro: *"Olá! Sou seu agente financeiro"*
- Mostra os três pilares do app: **Chat natural**, **Insights IA** e **Metas**
- Botão **Começar** e opção **Pular e carregar dados de demonstração**

<img width="776" alt="Tela de boas-vindas" src="./images/01-boas-vindas.png" />

### 2. Vamos nos conhecer
- Campos: **nome**, **renda mensal aproximada (R$)** e **saldo atual em conta (R$)**
- Botões **Voltar** e **Continuar**

<img width="752" alt="Tela de perfil do usuário" src="./images/02-perfil.png" />

### 3. Qual seu objetivo principal?
- O usuário escolhe um objetivo para personalizar os insights:
  - **Sair das dívidas**: organizar e quitar débitos
  - **Guardar dinheiro**: criar reserva de emergência
  - **Investir**: fazer o dinheiro crescer

<img width="732" alt="Tela de objetivo principal" src="./images/03-objetivo.png" />

### 4. Tudo pronto!
- Mensagem personalizada com o nome do usuário
- Sugere frases para experimentar no chat:
  - *"Gastei R$ 35 no Uber"*
  - *"Recebi R$ 1.200 de freela"*
  - *"Quanto gastei este mês?"*
- Botão **Ir para o Dashboard**

<img width="725" alt="Tela de finalização do onboarding" src="./images/04-tudo-pronto.png" />

### 5. Dashboard: "Seu dinheiro hoje"
- **Saldo atual**, com gráfico da evolução nos últimos dias
- **Receitas do mês**, **Gastos do mês** e **Balanço líquido**
- Card do **Assistente IA** incentivando o primeiro registro
- Botão de atalho **Registrar no chat**
- Menu lateral: Dashboard, Chat, Metas e Relatórios

<img width="1581" alt="Dashboard" src="./images/05-dashboard.png" />

### 6. Chat com o Agente Financeiro
- Agente com status **online** e mensagem de boas-vindas
- Registro de gastos e receitas em linguagem natural
- Atalhos prontos: *"Gastei R$ 35 no Uber"*, *"Recebi R$ 1.200 de freela"*, *"Comprei pão R$ 12"* e *"Quanto gastei este mês?"*
- Campo **Digite sua mensagem...** com botão de envio

<img width="1578" alt="Chat com o Agente Financeiro" src="./images/06-chat.png" />

### 7. Relatórios
- Filtros de período: **Este mês**, **3 meses** e **Ano**
- Cards de **Receitas**, **Despesas** e **Líquido**
- Gráficos de **Despesas por categoria** e **Receitas vs Despesas**
- Exibe "Sem dados no período" enquanto não há transações

<img width="1596" alt="Tela de Relatórios" src="./images/07-relatorios.png" />

### 8. Metas Financeiras
- Área dedicada no menu lateral para criar e acompanhar objetivos, como *"Quero guardar R$ 5.000 até dezembro"*

### 9. Experiência e Design
- Tema escuro moderno, com destaque em verde
- Linguagem simples, amigável e educativa
- Navegação lateral clara
- Interface responsiva para celular e desktop

---

## 🛠️ Ferramentas Utilizadas

- **Copilot Web**: refinamento do PRD
- **Lovable**: geração do app a partir do PRD
- **DIO**: desafio de projeto de Vibe Coding

---

## 🧠 Reflexão

### O que funcionou bem?  
Ter um PRD bem refinado no Copilot Web fez muita diferença: o Lovable entendeu o produto, as telas e o tom de conversa, e gerou um app completo logo na primeira interação.

### O que não funcionou como o esperado?  
No protótipo, os gráficos e os relatórios ficam vazios até que existam transações registradas, e o app roda em modo demo.

### O que aprendi sobre conversar com IAs?  
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você der, melhor é a interação.
