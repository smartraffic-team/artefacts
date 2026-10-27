# Documentação e Artefatos

Este repositório contém a documentação em LaTeX, os artefatos de projeto e os diagramas do **SmarTraffic**, um sistema de controle de tráfego inteligente utilizando câmeras e visão computacional para otimização de semáforos.

## Estrutura do Repositório

* `artefatos.tex` — Arquivo principal em LaTeX contendo todos os artefatos e a documentação.
* `referencias.bib` — Arquivo de bibliografia para as citações (ABNT).
* `imgs/` — Diretório contendo todas as imagens, logos e diagramas utilizados no documento.
* `README.md` — Este arquivo.

## Artefatos Documentados
O documento LaTeX contempla os seguintes artefatos de engenharia de software:
- **Business Model Canvas:** Modelo de negócio e estratégia.
- **SWOT:** Análise estratégica (Forças, Fraquezas, Oportunidades e Ameaças).
- **UX/UI:** Design de interface, paleta de cores e wireframes.
- **Website:** Estrutura e especificações técnicas do site do projeto.
- **Diagramas UML:** Modelagem visual (Casos de Uso e Classes).
- **DevOps:** Pipeline CI/CD, infraestrutura de rede e arquitetura de deploy.

## Tecnologias Utilizadas no Projeto
A stack tecnológica mapeada nos artefatos inclui:
- **Visão Computacional:** Python, OpenCV, YOLOv8n.
- **Hardware/Controle:** Arduino, C++.
- **Plataforma Web:** React, TypeScript, Nest.js, Prisma, MySQL.
- **Hospedagem:** Vercel.

## Como compilar o documento (LaTeX)

Para gerar o PDF localmente, você precisará de uma distribuição TeX instalada (TeX Live, MiKTeX ou MacTeX) e do `latexmk`.

1. Clone o repositório:
   ```bash
   git clone https://github.com/smartraffic-team/artefacts.git
   cd artefacts

2. Limpe arquivos auxiliares antigos (opcional):
   ```bash
   latexmk -C
   ```
   
3. Compile o PDF:
   ```bash
   latexmk -pdf artefatos.tex
   ```
O arquivo `artefatos.pdf` será gerado na raiz do projeto.
