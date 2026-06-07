# MODELO FINANCEIRO — DROPTEX

## Objetivo

Documentar como funciona o modelo financeiro da operação DROPTEX.

Este documento serve como referência para:

- Plataforma SaaS
- Site institucional
- Operação interna
- Futuras integrações

---

## Conceito Principal

A DROPTEX utiliza um sistema de créditos pré-pagos.

O cliente adiciona saldo antecipadamente.

Os serviços e produtos consumidos são debitados automaticamente desse saldo.

---

## Fluxo Financeiro

Cliente adiciona crédito

↓

Saldo disponível

↓

Utilização dos serviços

↓

Débitos registrados

↓

Atualização do saldo

↓

Consulta no extrato

---

## Créditos

Créditos representam o valor disponível para utilização.

Podem ser utilizados para:

- Produtos
- Serviços logísticos
- Embalagens
- Taxas operacionais
- Serviços futuros

---

## Saldo

O saldo representa o valor disponível para consumo.

Fórmula:

Saldo Atual = Créditos - Débitos

---

## Débitos

Débitos representam valores consumidos pelo cliente.

Exemplos:

- Compra de produtos
- Taxa de fulfillment
- Taxa de armazenagem
- Taxa operacional
- Embalagens
- Serviços adicionais

---

## Extrato

O extrato registra todas as movimentações financeiras.

Cada lançamento deve conter:

- Data
- Hora
- Tipo
- Descrição
- Valor
- Saldo após movimentação

---

## Tipos de Movimentação

### Crédito

Entrada de saldo.

Exemplos:

- PIX
- Transferência
- Depósito aprovado

---

### Débito

Saída de saldo.

Exemplos:

- Produto adquirido
- Serviço executado
- Taxa operacional

---

## Transparência

O cliente deve conseguir visualizar:

- Saldo atual
- Histórico completo
- Últimas movimentações
- Valores debitados
- Valores creditados

---

## Objetivos do Modelo

Garantir:

- Simplicidade
- Transparência
- Controle
- Previsibilidade

---

## Benefícios para o Cliente

Sem cobranças inesperadas.

Controle financeiro centralizado.

Visualização clara dos custos.

Maior organização operacional.

---

## Benefícios para a DROPTEX

Maior previsibilidade financeira.

Redução de inadimplência.

Controle operacional simplificado.

Escalabilidade.

---

## Integração com a Plataforma

A plataforma DROPTEX deverá exibir:

- Saldo disponível
- Extrato
- Histórico de créditos
- Histórico de débitos
- Informações operacionais vinculadas

---

## Regra Principal

A DROPTEX trabalha com crédito antecipado.

Toda movimentação deve ser registrada.

Todo débito deve possuir justificativa operacional.

Toda operação deve ser transparente para o cliente.