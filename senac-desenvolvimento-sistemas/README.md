# Calculadora Nutricional Desktop

Aplicação desktop em **Java** (interface construída no NetBeans) desenvolvida para a Atividade Avaliativa 2 da UC9 (Desenvolvimento de Sistemas — Senac RS).

## Sobre o projeto

O sistema foi encomendado, no enunciado da atividade, para um sindicato de nutricionistas que precisa distribuir aos seus associados uma ferramenta rápida para cálculos comuns da rotina clínica. A aplicação reúne três calculadoras em uma tela inicial de navegação:

- **IMC** — calcula o Índice de Massa Corporal (Peso / Altura²) e classifica o resultado em Magreza, Normal, Sobrepeso, Obesidade ou Obesidade grave.
- **Gasto Calórico** — calcula o gasto calórico basal (fórmula diferente para homem e mulher) e, a partir dele, o gasto calórico total conforme o nível de atividade física selecionado (sedentário a extremamente ativo).
- **Recomendações** — a partir do total calórico informado, recomenda a quantidade em gramas de carboidratos, proteínas e gorduras a serem ingeridas.

## O que a aplicação faz, na prática

1. Abre em uma tela inicial com botões de navegação para cada calculadora.
2. Cada tela coleta os dados do usuário, valida o preenchimento e trata entradas inválidas sem travar o programa.
3. Exibe o resultado do cálculo e, no caso do IMC, uma interpretação textual da faixa correspondente.

## Tecnologias

- Java
- Swing (formulários e componentes visuais via IDE do NetBeans)
- Tratamento de exceções e validação de formulário

## Status

✅ Concluído — entregue como Atividade Avaliativa 2 da UC9.

---

*Projeto acadêmico desenvolvido no curso técnico de Desenvolvimento de Sistemas (Senac RS).*