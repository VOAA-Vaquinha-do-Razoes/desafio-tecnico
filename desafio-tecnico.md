# Processo Seletivo VOAA - Desenvolvedor(a) JavaScript Full Stack

## Capturando Doações

Você deverá criar uma aplicação web para receber doações e um admin para ajudar beneficiários a visualizar e gerenciar todas as doações recebidas.

### Requisitos Obrigatórios (MVP)

- Fluxo de checkout para pagamento de doações
  - Passo 1: Captura dos dados do doador, contendo os campos nome*, email*, CPF\*, e telefone (com DDD)
  - Passo 2: Captura do valor da doação e opção para doar anonimamente
  - Passo 3: Página de Pagamento, com opção de escolha da forma de pagamento
  - Passo 4: Página de confirmação do pagamento
- Admin
  - Página contendo todas as doações recebidas
  - Botão para estornar uma doação
  - Campos para filtrar relatórios por data inicial e final
  - Botão para exportar relatórios (CSV ou XLS)

### Requisitos Opcionais

- Autenticação de usuário (doador e admin)
- Doação recorrente

## User Stories

### Doador

- Eu, como doador, preciso informar meu nome, email, CPF, e telefone
- Eu, como doador, gostaria de escolher o valor da doação
- Eu, como doador, gostaria de fazer uma doação anônima
- Eu, como doador, gostaria de escolher uma forma de pagamento (cartão de crédito, PIX, etc)
- Eu, como doador, preciso visualizar todas as minhas doações
-

### Beneficiário

- Eu, como beneficiário, preciso visualizar as doações recebidas
- Eu, como beneficiário, preciso estornar uma doação
- Eu, como beneficiário, preciso visualizar um relatório de doações recebidas num único mês
- Eu, como beneficiário, preciso exportar um relatório de doações extornadas num único mês
