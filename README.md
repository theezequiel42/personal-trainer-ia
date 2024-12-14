# 🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal

<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

---

## 📋 Índice

- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto busca criar um **Assistente de Personal Trainer Automatizado** usando práticas avançadas de engenharia de prompts. O assistente é capaz de gerar treinos personalizados para usuários com base nos seguintes fatores:

- **Biotipo corporal**.
- **Dias disponíveis para treinar**.
- **Tipo de exercícios preferidos**.

O objetivo é fornecer uma experiência prática e customizada para o usuário, alinhando seus objetivos e limitações com um planejamento eficiente de treinos.

---

## 💪 Biotipos Corporais

Os biotipos corporais são fundamentais para a personalização de treinos. Confira as características principais de cada biotipo e identifique o que mais se aproxima do seu perfil:

| **Imagem**                                                    | **Biotipo**   | **Descrição**                                                                 |
|---------------------------------------------------------------|---------------|-------------------------------------------------------------------------------|
| <img src=".github/assets/ectomorph.jpg" width="50%">          | **Ectomorfo** | Corpo magro, dificuldade em ganhar peso e massa muscular.                    |
| <img src=".github/assets/mesomorph.jpg" width="50%">          | **Mesomorfo** | Corpo naturalmente musculoso, facilidade para ganhar massa muscular.         |
| <img src=".github/assets/endomorph.jpg" width="50%">          | **Endomorfo** | Corpo com tendência ao acúmulo de gordura, dificuldade para perder peso.     |

> 💡 **Dica:** Escolha o biotipo que mais representa suas características atuais para treinos mais eficazes.

---

## 📅 Dias Disponíveis para Treino

Determine quantos dias por semana você pode se dedicar ao treino. Isso ajudará o assistente a sugerir o melhor plano:

| **Dias por Semana** | **Tipo de Treino Sugerido**   | **Descrição**                                                               |
|---------------------|-----------------------------|-----------------------------------------------------------------------------|
| 1 dia              | **Full Body**               | Treino completo para todo o corpo.                                          |
| 3 dias             | **ABC**                     | Divisão de treino com foco em grupos musculares específicos.                |
| 5 dias             | **ABCDE**                   | Divisão avançada para treinar diferentes grupos musculares em cada sessão.  |

> 🗓️ **Nota:** Um maior número de dias proporciona uma especialização mais detalhada nos treinos.

---

## 🏋️ Tipos de Exercícios

Selecione o estilo de treino que mais combina com seus objetivos e preferências pessoais:

| **Tipo de Treino** | **Descrição**                                                                                     | **Exemplo de Exercício**                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Funcional**      | Foco na funcionalidade e movimentos naturais do corpo.                                           | Prancha, agachamentos livres.                                                         |
| **Maquinário**     | Uso de máquinas para isolar músculos específicos.                                                | Leg press, puxador dorsal.                                                            |
| **Peso Livre**     | Trabalha múltiplos grupos musculares simultaneamente.                                            | Agachamento com barra, supino com halteres.                                           |
| **Cardio**         | Exercícios que melhoram o sistema cardiovascular e queimam gordura.                              | Corrida, bicicleta ergométrica.                                                       |
| **HIIT**           | Treinos curtos e intensos com intervalos de recuperação, ideais para quem busca emagrecimento rápido. | Burpees, sprints intervalados.                                                        |

---

## 🛠️ Regras de Negócio

1. **Identifique seu biotipo corporal** para adaptar o treino às suas necessidades fisiológicas.
2. **Determine a quantidade de dias** que você pode treinar para estruturar o cronograma.
3. **Escolha o estilo de treino** preferido para personalizar os exercícios.
4. Use o prompt do assistente para gerar seu plano de treino e começar a evolução!

---

## 📖 Material de Apoio

- [Fundamentos de Engenharia de Prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas Práticas de Treinamento Físico](https://www.academias.org/treinamentos)

---

## 🎯 Prompt de Resposta Proposto

