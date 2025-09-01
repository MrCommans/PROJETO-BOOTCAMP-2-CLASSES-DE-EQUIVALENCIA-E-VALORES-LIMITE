# Design de Testes para o Formulário de Carteira de Motorista - Sprint 2 TripleTen

## Visão Geral

Este projeto foi desenvolvido como parte do **Sprint 2 do Bootcamp de Análise de QA da TripleTen**. O objetivo foi projetar testes para o formulário "Adicionar carteira de motorista" do aplicativo **Urban Routes**, especificamente para o recurso de compartilhamento de carros. A tarefa envolveu a criação de **classes de equivalência**, **valores-limite** e **casos de teste** para garantir a validação correta dos campos do formulário, com foco no campo "Nome".

## Objetivos do Projeto

- **Definir classes de equivalência e valores-limite**: Analisar os requisitos do formulário "Adicionar carteira de motorista" para os campos "Nome", "Sobrenome" e "Data de nascimento", identificando classes de equivalência e valores-limite, incluindo cenários positivos e negativos.
- **Escrever casos de teste**: Desenvolver casos de teste detalhados para o campo "Nome", baseados nos valores de teste escolhidos, para verificar o comportamento do formulário em diferentes condições.
- **Documentar no modelo fornecido**: Preencher as abas "Classes de equivalência" e "Casos de teste" no modelo do Google Sheets, garantindo clareza e organização na documentação.

## Metodologia

1. **Análise dos Requisitos**:
   - Li a seção "Adicionar carteira de motorista" dos requisitos do Urban Routes para entender as regras de validação dos campos "Nome", "Sobrenome" e "Data de nascimento".
   - Identifiquei os critérios de aceitação, como formatos aceitáveis, limites de caracteres e restrições (ex.: apenas letras para o campo "Nome").

2. **Definição de Classes de Equivalência e Valores-Limite**:
   - Para cada campo ("Nome", "Sobrenome" e "Data de nascimento"), defini classes de equivalência para cenários positivos (ex.: entradas válidas) e negativos (ex.: entradas inválidas, como números ou caracteres especiais no campo "Nome").
   - Determinei valores-limite para cenários aplicáveis, como comprimento mínimo e máximo de caracteres ou datas válidas/inválidas.
   - Registrei as classes e valores de teste na aba "Classes de equivalência" do modelo do Google Sheets.

3. **Escrita de Casos de Teste**:
   - Com base nos valores de teste escolhidos para o campo "Nome", escrevi casos de teste detalhados na aba "Casos de teste" do modelo.
   - Cada caso de teste incluiu:
     - **ID**: Identificador único.
     - **Nome do Caso de Teste**: Descrição do cenário testado.
     - **Pré-condição**: Estado inicial (ex.: formulário aberto).
     - **Descrição da Etapa**: Ações a serem executadas (ex.: inserir um nome válido).
     - **Resultado Esperado**: Comportamento esperado do sistema (ex.: aceitação ou rejeição do input).
   - Considerei cenários positivos (ex.: nome válido com letras) e negativos (ex.: nome com números ou vazio).

4. **Documentação**:
   - Preenchi o modelo do Google Sheets, nomeando-o como "[Seu Nome], [Sobrenome], [Grupo] — 2º sprint".
   - Assegurei que a documentação fosse clara, organizada e seguisse as instruções fornecidas.

## Ferramentas Utilizadas

- **Google Sheets**: Para documentar classes de equivalência e casos de teste no modelo fornecido.
- **Urban Routes**: Aplicativo referência para análise dos requisitos do formulário.

## Estrutura do Repositório

- `Design de Testes - Urban Routes.xlsx