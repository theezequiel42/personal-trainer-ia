# 🏋️‍♂️ Projeto Assistente de Personal Trainer - Gerador de Treino Ideal

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

## 📋 Índice

- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [✨ Funcionalidades Adicionais](#-funcionalidades-adicionais)
- [🛠️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa aprimorar a experiência de personal trainers e seus alunos, proporcionando um assistente automatizado para criar planos de treino personalizados. Através de uma interface intuitiva e regras de negócios claras, o sistema considera características individuais, como biotipo corporal, dias disponíveis para treino e preferências de exercícios.

---

## 💪 Biotipos Corporais

Os biotipos corporais são a base para ajustar o plano de treino às necessidades do usuário. Abaixo estão os três principais biotipos, com descrições claras e sugestões:

| **Imagem**                                | **Biotipo**  | **Descrição**                                                                                                                                  | **Sugestão de Treino**                                      |
|------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| <img src=".github/assets/ectomorph.jpg"> | **Ectomorfo** | Corpo magro, difícil ganhar massa muscular e peso.                                                                                            | Foque em treinos de força com menos repetições e mais carga. |
| <img src=".github/assets/mesomorph.jpg"> | **Mesomorfo** | Corpo musculoso, facilidade em ganhar massa muscular e perder gordura.                                                                        | Utilize treinos balanceados para manter e definir o físico. |
| <img src=".github/assets/endmorph.jpg">  | **Endomorfo** | Corpo com maior propensão a acumular gordura, dificultando a perda de peso.                                                                   | Priorize treinos HIIT e exercícios aeróbicos para queima de gordura. |

---

## 📅 Dias Disponíveis para Treino

O sistema adapta o plano com base no número de dias disponíveis para treinar, otimizando o tempo do usuário.

| **Imagem**                                | **Dias por Semana** | **Treino Sugerido**                                     |
|------------------------------------------|---------------------|--------------------------------------------------------|
| <img src=".github/assets/calendar.png">  | **1 dia**           | Treino Full Body                                       |
| <img src=".github/assets/calendar.png">  | **3 dias**          | Divisão ABC (ex.: Peito/Costas/Pernas)                |
| <img src=".github/assets/calendar.png">  | **5 dias ou mais**  | Divisão ABCDE com foco em grupos musculares específicos |

---

## 🏋️ Tipos de Exercícios

O assistente permite ao usuário escolher entre diferentes categorias de exercícios, com exemplos práticos:

| **Imagem**                                 | **Tipo de Exercício** | **Descrição**                                                                                     |
|-------------------------------------------|-----------------------|---------------------------------------------------------------------------------------------------|
| <img src=".github/assets/dumbells.png">   | **Funcional**          | Movimentos naturais para melhorar a funcionalidade do corpo.                                      |
| <img src=".github/assets/4760665.png">    | **Maquinário**         | Isolamento de grupos musculares com maior segurança.                                              |
| <img src=".github/assets/barr.png">       | **Peso Livre**         | Uso de halteres e barras para trabalhar vários grupos musculares simultaneamente.                 |
| <img src=".github/assets/cardio.png">     | **Cardio**             | Atividades aeróbicas como corrida e ciclismo para melhorar a resistência cardiovascular.          |
| <img src=".github/assets/hiit.png">       | **HIIT**               | Treinos intervalados de alta intensidade, ideais para quem busca otimizar a queima de gordura.    |

---

## ✨ Funcionalidades Adicionais

1. **Registro de Progressos**: Uma funcionalidade onde alunos podem registrar pesos levantados, repetições realizadas e melhorias ao longo do tempo.
2. **Receitas e Dicas Nutricionais**: Sugestões de cardápios ajustados ao biotipo e metas do usuário.
3. **Plano de Descanso**: Indicações sobre a importância e o cronograma de recuperação muscular.
4. **Relatórios Automatizados**: Painéis de controle para personal trainers acompanharem a evolução de múltiplos alunos.

---

## 🛠️ Regras de Negócio

1. **Identificação do Biotipo**: Fundamental para ajustar o volume e intensidade do treino.
2. **Dias Disponíveis**: Treinos são adaptados para aproveitar o tempo ao máximo.
3. **Escolha de Exercícios**: O sistema prioriza a preferência do aluno, oferecendo variedade e flexibilidade.
4. **Monitoramento**: Inclui feedback contínuo com ajustes semanais baseados no progresso.

---

## 📖 Material de Apoio

- [Fundamentos de Engenharia de Prompts](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Planejamento de Treinos](https://www.treinomaster.com)
- [Nutrição e Performance Física](https://www.nutri.org)

---

## 🎯 Prompt de Resposta Proposto

**"Com base nas informações abaixo, crie um plano de treino personalizado:**

- **Biotipo Corporal**: [Informe aqui: Ectomorfo, Mesomorfo ou Endomorfo]
- **Dias Disponíveis para Treino**: [Informe o número de dias disponíveis por semana]
- **Tipo de Exercícios Preferido**: [Funcional, Maquinário, Peso Livre, Cardio, HIIT]

**Inclua recomendações sobre aquecimento, descanso e técnicas de execução para maximizar resultados e prevenir lesões."**

---
