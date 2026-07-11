# 🧪 NotebookLM Chemistry Study Guide Agent

Este repositório contém a estrutura de diretórios e a documentação para o desenvolvimento de um **Agente de IA customizado no NotebookLM**. O agente atua como um Guia de Aprendizagem de Química altamente didático, projetado para transformar conceitos científicos complexos em explicações simples, coesas e lineares.

---

## 📌 Sobre o Projeto

O projeto consiste na consolidação de um agente inteligente utilizando a plataforma NotebookLM da Google. A IA foi programada através de instruções estruturadas em Markdown para atuar como um tutor particular, garantindo que qualquer usuário (mesmo sem nenhuma base prévia) consiga absorver profundamente os pilares da química por meio de uma progressão pedagógica lógica, analogias certeiras do cotidiano e exemplos práticos do mundo real.

---

## 🎯 Objetivo do Agente

O objetivo central deste agente é democratizar e facilitar o entendimento do ramo científico da química. Ele foi blindado contra alucinações e desvios de escopo através de diretrizes estritas:
* **Explicações Acessíveis:** Traduzir termos técnicos complexos para uma linguagem fluida e de fácil compreensão.
* **Ancoragem em Fontes:** Utilizar exclusivamente o ecossistema de livros e materiais fornecidos para embasar suas respostas.
* **Manutenção de Escopo:** Caso o usuário introduza um tema fora do escopo tradicional, o agente é instruído a, obrigatoriamente, contextualizar a resposta sob a ótica e os mecanismos da química.

---

## 🗂️ Assunto de Interesse & Objetivos de Estudo

Este caderno temático foca primordialmente na **Química** (abrangendo desde a Química Geral e Inorgânica até a Físico-Química e Química Orgânica). Os objetivos pessoais e profissionais traçados para o desenvolvimento e uso deste projeto são:

1.  **Aprofundamento Autodidata:** Servir como uma ferramenta robusta de suporte ao estudo independente e avançado na área de química, organizando a progressão do conhecimento de forma linear e conectada.
2.  **Aplicação na Informática (Análise de Dados):** Utilizar a base conceitual química e os relatórios gerados como insumos estruturados para extração de insights, modelagem de dados científicos e engenharia de prompts.
3.  **Integração com a Gastronimia:** Conectar os fenômenos moleculares e as reações químicas (como processos fermentativos, caramelização, reações de Maillard e interações de polímeros) à ciência dos alimentos e técnicas culinárias avançadas.

---

## 📂 Estrutura do Repositório

O projeto está organizado de forma clara:

* `fontes/` : Diretório que armazena os arquivos, livros e materiais didáticos de referência que foram carregados no NotebookLM (ex: coleções de química geral, orgânica e inorgânica).
* `resultado final/` : Pasta destinada aos artefatos finais gerados pelo agente ou consolidados a partir das interações, incluindo:
    * **Relatórios de Resumo:** Notas de estudo estruturadas por temas e capítulos.
    * **Apresentações:** Roteiros e tópicos sintetizados para exposição rápida de conteúdos.
    * **Mapas Mentais:** Conexões visuais e árvores de pré-requisitos geradas durante o aprendizado.

---

## 🛠️ Funcionamento do Sistema

1.  **Carregamento de Dados:** Os livros e materiais da pasta `fontes/` são injetados no NotebookLM, criando o repositório fechado de conhecimento do modelo.
2.  **Processamento da Persona:** O prompt estruturado (presente no plano do modelo) é inserido nas diretrizes de configuração do agente para moldar seu comportamento, formato de saída e restrições.
3.  **Interação e Navegação:** O usuário interage com o chat. A cada resposta, o agente gera uma explicação didática do tema, lista os pré-requisitos necessários para consolidar aquela base e sugere os próximos passos lógicos. O usuário pode optar por avançar para a próxima matéria recomendada ou gerar uma bateria de exercícios práticos para fixação de mente.

---

## 🌐 Acesse o Projeto Público

O caderno de estudos do NotebookLM está configurado publicamente e pode ser acessado e utilizado através do link abaixo:

👉 **[CLIQUE AQUI PARA ACESSAR O NOTEBOOKLM PÚBLICO](https://notebooklm.google.com/notebook/cc7aaa28-2a04-4212-90fd-ca65a154e0fd)**

---

*Desenvolvido com o propósito de unir Ciência, Tecnologia e Educação de forma prática e inovadora.*
