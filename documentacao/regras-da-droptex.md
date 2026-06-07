# REGRAS DA DROPTEX

## Objetivo

Este documento define as regras obrigatórias para qualquer alteração realizada no projeto DROPTEX.

Aplica-se a:

* ChatGPT
* Codex
* Claude
* Cursor
* Lovable
* Desenvolvedores
* Colaboradores

---

# REGRA PRINCIPAL

Antes de qualquer alteração:

Analisar completamente a estrutura existente.

Compreender o funcionamento atual.

Identificar dependências.

Avaliar impactos.

Somente após essa análise realizar modificações.

---

# NÃO FAZER

## Sistema

Não recriar o sistema.

Não alterar arquitetura sem necessidade.

Não substituir funcionalidades operacionais.

Não criar funcionalidades duplicadas.

Não modificar fluxos estáveis sem justificativa técnica.

---

## Banco de Dados

Não apagar tabelas.

Não apagar registros.

Não alterar estrutura crítica sem análise prévia.

Não modificar permissões sem validação.

Não alterar RLS sem necessidade comprovada.

---

## Interface

Não alterar identidade visual da DROPTEX.

Não modificar cores principais sem aprovação.

Não substituir componentes funcionais apenas por preferência estética.

Não realizar redesign completo sem planejamento.

---

## WordPress

Não trocar tema sem análise.

Não remover plugins sem auditoria.

Não remover páginas publicadas sem validação.

Não apagar CSS personalizado sem backup.

---

# DEVE FAZER

## Antes de Alterar

Analisar:

* Estrutura do projeto
* Componentes
* Rotas
* Banco de dados
* Integrações
* CSS
* Plugins
* Páginas

---

## Prioridades

1. Reaproveitar estrutura existente.
2. Corrigir apenas o necessário.
3. Implementar de forma incremental.
4. Preservar compatibilidade.
5. Preservar dados existentes.

---

## Documentação

Toda alteração relevante deve ser registrada.

Atualizar quando necessário:

* changelog.md
* auditorias
* documentação técnica
* documentação de negócio

---

## Git

Toda alteração deve seguir:

git add .

git commit -m "Descrição da alteração"

git push

---

# IDENTIDADE DA MARCA

Toda alteração deve preservar:

Marca:
DROPTEX

Slogan:
A logística que escala o seu negócio.

Posicionamento:

O cliente vende.
A DROPTEX opera.

Objetivos:

* Autoridade
* Confiança
* Clareza
* Profissionalismo

Evitar:

* Aparência amadora
* Excesso de efeitos
* Poluição visual
* Informações confusas

---

# PLATAFORMA DROPTEX

A plataforma deve manter como prioridade:

* Segurança
* Transparência
* Controle financeiro
* Facilidade de uso

Não comprometer:

* Login
* Extrato
* Saldo
* Créditos
* Débitos
* Auditoria

---

# WORDPRESS

Antes de alterar:

Verificar:

* Tema Neve
* Elementor
* Plugins ativos
* CSS personalizado
* Estrutura da página

Preservar:

* SEO
* Responsividade
* Conversão
* Performance

---

# REGRA FINAL

A DROPTEX deve evoluir por melhorias graduais.

Nunca por reconstruções desnecessárias.

Princípio permanente:

Analisar.
Documentar.
Validar.
Implementar.
Testar.
Registrar.
