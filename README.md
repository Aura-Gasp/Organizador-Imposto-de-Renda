# Organizador de Declaração de Imposto de Renda

## 📌 Sobre o Projeto

Ferramenta desenvolvida em Excel para organizar as informações necessárias na hora de declarar o Imposto de Renda. A planilha centraliza dados do titular, informes de rendimento bancário e lançamentos de notas/holerites ao longo do ano, com navegação facilitada entre as telas e validações que reduzem erro de preenchimento.

Projeto desenvolvido como desafio prático do curso **Excel Avançado com IA e Claude** (Santander Open Academy / DIO), com orientação do especialista Felipe Aguiar (Tech Educator, DIO).

## 🎯 Objetivos

- Criar uma ferramenta de organização de dados fiscais em Excel
- Aplicar validação de dados e formatação personalizada para facilitar o preenchimento
- Construir uma navegação clara entre diferentes telas da planilha
- Documentar o processo técnico e compartilhar via GitHub

## 🗂️ Estrutura da Planilha

### 1. TÍTULAR
Formulário com os dados pessoais do declarante (nome, CPF, data de nascimento, título de eleitor, endereço, contato), com máscaras de formatação aplicadas a CPF, CEP, telefone e celular, e campos de confirmação (Sim/Não) controlados por lista suspensa.

### 2. INFORMES
Registro dos informes de rendimento de até 3 contas bancárias, com:
- Seleção do banco por lista suspensa (puxada de uma base com mais de 50 instituições)
- Campo de valor atual por conta
- Total geral somado automaticamente
- Campo de anexo, indicando o nome do arquivo do informe correspondente

### 3. NOTAS
Lançamento de rendimentos ao longo do ano (data, categoria e valor), com um **Resumo Anual** que soma automaticamente o total recebido em cada mês (via `SOMASES`) e um gráfico mostrando a evolução mensal dos rendimentos — atualizado sozinho conforme novos lançamentos são adicionados.

### Menu de Navegação
Um ícone personalizado (Leão) presente nas três telas funciona como atalho, levando diretamente para a aba correspondente ao ser clicado.

## ⚙️ Recursos Técnicos Utilizados

- **Validação de dados (listas suspensas)**: seleção de banco, respostas Sim/Não
- **Formatação personalizada**: máscaras para CPF, CEP, telefone e celular
- **Fórmulas**: `SUM` para totalização dos informes, `SOMASES` para o resumo mensal de rendimentos
- **Hyperlinks em imagens**: menu de navegação entre abas usando ícones clicáveis
- **Gráfico dinâmico**: evolução dos rendimentos mês a mês

## 🚀 Como Usar

1. Baixe o arquivo `Organizador_de_Declaração_de_Imposto_de_Renda.xlsx`
2. Preencha a aba **TÍTULAR** com seus dados pessoais
3. Registre os informes de rendimento bancário na aba **INFORMES**
4. Lance seus rendimentos mensais na aba **NOTAS** conforme o ano avança
5. Use o ícone do Leão para navegar entre as telas

## 👤 Autora

Aura Gaspar Ribeiro
