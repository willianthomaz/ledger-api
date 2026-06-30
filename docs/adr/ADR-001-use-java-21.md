# ADR-001: Usar Java 21

## Status

Aceita

## Contexto

O **Ledger Service** deve representar um serviço backend com aparência de produção dentro de um ambiente de fintech.

O projeto precisa usar uma versão moderna do Java, mas sem se afastar das exigências comuns de vagas backend enterprise.

## Decisão

Vamos usar **Java 21** como versão principal da linguagem no projeto.

## Justificativa

Java 21 é uma versão LTS (*Long-Term Support*) e está alinhada com aplicações backend modernas.

Essa escolha permite demonstrar conhecimento atual em Java, mantendo o projeto relevante para ambientes enterprise que valorizam estabilidade, manutenção e compatibilidade com Spring Boot 3.

## Consequências

### Positivas

- Alinha o projeto com vagas backend Java modernas.
- Suporta versões atuais do Spring Boot.
- Demonstra conhecimento além de versões antigas como Java 8.
- Permite discutir recursos modernos da linguagem em entrevistas.

### Negativas

- Algumas empresas ainda utilizam Java 8, 11 ou 17.
- Será importante explicar em entrevistas que a escolha foi feita por ser uma versão LTS moderna.
- O desenvolvedor precisa ficar atento à compatibilidade de bibliotecas.

## English Corner

| Português | Inglês |
|---|---|
| Decisão arquitetural | Architectural decision |
| Status | Status |
| Contexto | Context |
| Justificativa | Rationale |
| Consequência | Consequence |
