# Documento Mestre do Projeto

## International Backend Engineer Journey

### Projeto

**NorthBridge Ledger Service**

### Contexto da empresa

A **NorthBridge Financial** é uma fintech fictícia localizada nos Estados Unidos.

A empresa fornece infraestrutura de pagamentos para negócios que precisam rastrear movimentações de contas, calcular saldos e manter auditoria financeira de forma confiável.

### Papel no projeto

Você atua como **Backend Software Engineer** dentro do time de **Payments Platform**.

### Missão do produto

Construir um serviço de ledger capaz de registrar movimentações financeiras com segurança, consistência e forte capacidade de auditoria.

### Princípios de engenharia

- Preferir clareza em vez de soluções excessivamente inteligentes.
- Regras de negócio devem ser explícitas.
- Valores financeiros nunca devem usar tipos de ponto flutuante.
- Consistência dos dados é mais importante do que conveniência.
- Toda decisão relevante deve ser documentada.
- Testes fazem parte da funcionalidade, não são trabalho opcional.
- Preocupações operacionais importam: logs, métricas e erros devem ser pensados de forma intencional.

### Escopo inicial

A primeira versão do serviço deverá suportar:

- Cadastro de contas
- Lançamentos de crédito e débito
- Cálculo de saldo
- Extrato de transações
- Criação idempotente de transações
- Respostas de erro padronizadas
- Testes de integração
- Documentação e registros de arquitetura

### Fora do escopo da primeira fase

- Desenvolvimento Android ou mobile
- Integração com provedor real de pagamentos
- Dados reais de clientes
- Deploy em cloud
- Kubernetes

### Estratégia de aprendizado

As ferramentas serão introduzidas gradualmente:

- Primeiro, fluxo de trabalho com GitHub
- Depois, base Java e Spring Boot
- PostgreSQL e Flyway quando persistência for necessária
- Docker quando infraestrutura local for necessária
- RabbitMQ quando processamento assíncrono for necessário
- Observabilidade quando o serviço tiver comportamento suficiente para monitorar

### Objetivo da Sprint 0

Preparar o repositório, o fluxo de trabalho e a documentação antes de implementar funcionalidades de negócio.

## English Corner

| Português | Inglês |
|---|---|
| Documento mestre | Project Bible |
| Missão do produto | Product mission |
| Princípios de engenharia | Engineering principles |
| Escopo inicial | Initial scope |
| Estratégia de aprendizado | Learning strategy |
