# PRD — Sistema de Gestão para Móveis Planejados (SaaS)

## 1) Visão do Produto
Criar um sistema SaaS completo para empresas de móveis planejados, permitindo gestão ponta a ponta do negócio: captação e gestão de clientes, orçamentos personalizados, controle de estoque e serviços, planejamento de produção, gestão de equipe, agendamento de visitas, e acompanhamento financeiro. O sistema deve ser vendido por assinatura e integrado à conta do Stripe para cobrança recorrente.

## 2) Objetivos
- Centralizar operações em um único sistema.
- Reduzir retrabalho em orçamentos e planejamento de produção.
- Garantir previsibilidade financeira com assinaturas.
- Aumentar produtividade e controle (estoque, equipe, agenda, financeiro).

## 3) Público-Alvo
- Marcenarias e empresas de móveis planejados de pequeno a médio porte.
- Gestores operacionais, administradores e equipes comerciais.

## 4) Problemas a Resolver
- Orçamentos manuais e demorados.
- Falta de visibilidade de estoque e consumo de materiais.
- Dificuldade em planejar e acompanhar produção.
- Agenda descentralizada (visitas, medições e instalações).
- Financeiro sem controle consolidado.

## 5) Métricas de Sucesso
- Redução de tempo médio para gerar orçamento.
- Aumento de taxa de conversão de orçamentos em vendas.
- Diminuição de atraso em produção e instalação.
- Crescimento do MRR (Receita Recorrente Mensal).

## 6) Escopo do Produto
### 6.1 Módulos Principais (MVP)
1) **CRM e Clientes**
   - Cadastro de clientes (dados, preferências, histórico).
   - Funil de vendas (lead → orçamento → fechamento).

2) **Orçamentos Personalizados**
   - Templates de orçamento (com logotipo, condições e prazos).
   - Cadastro de ambientes, itens e materiais.
   - Cálculo automático (margem, impostos, descontos).
   - Geração de PDF e envio por e-mail/WhatsApp.

3) **Controle de Estoque e Materiais**
   - Cadastro de materiais e fornecedores.
   - Entradas/saídas e alertas de mínimo.
   - Reserva de material por projeto.

4) **Planejamento de Produção**
   - Cronograma por projeto.
   - Etapas de produção (corte, montagem, acabamento, instalação).
   - Status e apontamentos de tarefas.

5) **Gestão de Equipe**
   - Cadastro de colaboradores e funções.
   - Distribuição de tarefas e acompanhamento.

6) **Agendamento de Visitas**
   - Calendário integrado (visitas, medições, instalações).
   - Notificações e lembretes.

7) **Dashboard Financeiro**
   - Receita prevista vs realizada.
   - Custos por projeto.
   - Indicadores de margem e fluxo de caixa.

8) **Assinaturas e Cobrança (Stripe)**
   - Planos mensais/anuais.
   - Cobrança recorrente automática.
   - Gestão de inadimplência e cancelamentos.

### 6.2 Funcionalidades Futuras (Pós-MVP)
- **Gestão de contratos com assinatura digital**.
- **Integração com fornecedores e pedidos automáticos**.
- **Controle de estoque com código de barras/QR Code**.
- **App mobile para equipe externa**.
- **Analytics avançado com BI**.

## 7) Requisitos Funcionais
- RF01: Usuário deve criar e gerenciar clientes.
- RF02: Usuário deve gerar orçamentos personalizados com cálculo automático.
- RF03: Sistema deve permitir cadastro e controle de materiais em estoque.
- RF04: Sistema deve permitir planejar produção com etapas e status.
- RF05: Sistema deve permitir agendar visitas com notificações.
- RF06: Usuário deve visualizar indicadores financeiros em dashboard.
- RF07: Sistema deve integrar com Stripe para cobrança recorrente.
- RF08: Usuário deve gerenciar permissões de equipe.

## 8) Requisitos Não Funcionais
- RNF01: Interface web responsiva.
- RNF02: Disponibilidade mínima de 99%.
- RNF03: Dados criptografados em repouso e em trânsito.
- RNF04: LGPD e políticas de privacidade.

## 9) Jornadas do Usuário (exemplo)
1. **Novo cliente** → cadastro → orçamento → aprovação → produção → instalação → faturamento.
2. **Gestor** → vê dashboard financeiro → identifica margem baixa → ajusta template de preços.

## 10) Monetização
- Modelo SaaS com planos:
  - **Básico**: CRM + Orçamentos.
  - **Profissional**: Básico + Estoque + Produção.
  - **Enterprise**: Tudo + API + suporte dedicado.

## 11) Integração Stripe
- Cadastro de planos e preços.
- Checkout para assinatura.
- Webhooks para atualização de status (ativo, inadimplente, cancelado).
- Gestão de upgrades/downgrades.

## 12) Riscos e Considerações
- Adoção inicial pode ser baixa sem onboarding.
- Complexidade no cálculo de custos de materiais.

## 13) Próximos Passos
- Validar com 3–5 empresas de móveis planejados.
- Priorizar MVP e prototipar fluxos principais.
- Definir stack tecnológica e cronograma.
