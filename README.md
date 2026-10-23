# 🛒 Prompt: Automação de Compras Mensais de Casa (N8N)

Este repositório contém o prompt e a estrutura de regras para criar um fluxo de automação no **N8N** focado no controle e registro mensal de compras de supermercado para uma família (2 adultos e 1 criança).

---

## 🎯 Objetivo

O prompt orienta a criação de um workflow que conecta **Google Forms**, **Google Sheets** e **Gmail** para:
- Receber solicitações de compras a partir do dia 8 de cada mês.
- Filtrar e ignorar registros com e-mails inválidos.
- Salvar automaticamente os itens categorizados na planilha de controle.
- Enviar um e-mail de confirmação com o resumo dos itens registrados.

---

## 📝 O Prompt

```text
Atue como um especialista em N8N.

Crie uma automação para registrar itens de compras de casa mensalmente. Onde posso inserir e deletar os itens que são ou não necessários todos os meses. Itens como de limpeza, alimentos perecíveis e não perecíveis, carnes, embutidos, ovos e manteigas. O essencial para uma família com três pessoas, sendo 2 adultos e uma criança. As compras serão realizadas a partir do dia 8 de cada mês.

Público:
Família

Ferramentas envolvidas:
Google Forms, Google Sheets e Gmail.

Fluxo:
Receber uma lista, salvar os dados na planilha e enviar um e-mail de confirmação.

Regras:
Ignorar registros sem e-mail válido.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
