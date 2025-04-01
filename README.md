# LAB: Explorando Copilot & OpenAI com Azure AI Studio

Este repositório foi criado como parte de um laboratório prático com foco em Inteligência Artificial, utilizando os recursos da Microsoft (Copilot, Azure AI Foundry) e OpenAI.

---

## Estrutura do Projeto

- `inputs/` → Imagens utilizadas durante o LAB (prints do processo e arquivos enviados)
- `output/` → Resultados extraídos das ferramentas, como OCR e transcrições (e prints da resposta final)
- `readme.md` → Documentação detalhada com aprendizados e reflexões

---

## Etapas Realizadas

1. Criei o projeto `my-ai-project` no Azure AI Foundry.
2. Acessei o Playground de chat e utilizei o modelo **gpt-4-model** para responder perguntas sobre Azure AI.
3. Ativei filtros de conteúdo para garantir segurança nas interações com IA.
4. Usei o **Microsoft Copilot** para extrair texto de um arquivo `.pdf` com meu currículo.
5. Documentei os resultados gerados com prints e arquivos salvos.

---

## Prints do Processo

### 🔹 Playground com GPT-4 configurado
![Playground GPT](inputs/Captura%20de%20tela%202025-04-01%20151832.png)

### 🔹 Resposta à pergunta "How can I use Azure AI Services in a software development project?"
![Resposta GPT](inputs/Captura%20de%20tela%202025-04-01%20151921.png)

### 🔹 Envio de PDF para extração com Copilot
![Envio PDF](inputs/Captura%20de%20tela%202025-04-01%20152739.png)

### 🔹 Resultado da extração de texto com Copilot (parte 1)
![Texto extraído 1](output/Captura%20de%20tela%202025-04-01%20152749.png)

### 🔹 Resultado da extração de texto com Copilot (parte 2)
![Texto extraído 2](output/Captura%20de%20tela%202025-04-01%20152802.png)

---

## Arquivos gerados em `output/`

### Texto extraído do PDF com Copilot
Arquivo: [`output/ocr_output.txt`](output/ocr_output.txt)

> O Copilot conseguiu extrair o conteúdo do meu currículo, identificando informações como:
> - Dados pessoais
> - Competências técnicas (Git, HTML, CSS, Java, Python, Docker, React, MySQL, JS)
> - Experiência profissional
> - Cursos realizados

---

## Insights e Aprendizados

- A IA pode ser usada para automatizar tarefas repetitivas e transformar arquivos (como PDFs e imagens) em dados estruturados.
- O Copilot permite interagir com conteúdo em diversos formatos e responder de forma contextual.
- O Playground do Azure AI Studio é uma ferramenta poderosa para testar interações com modelos OpenAI.
- Os filtros de conteúdo são essenciais para garantir segurança em ambientes produtivos.

---

## Finalização

Este repositório representa um portfólio prático das tecnologias de IA que explorei com Copilot e OpenAI.  
Foi uma oportunidade para entender na prática como IA generativa pode apoiar tarefas profissionais e técnicas.

