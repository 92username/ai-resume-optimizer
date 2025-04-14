[![Deploy to VPS](https://github.com/92username/ai-resume-optimizer/actions/workflows/deploy.yml/badge.svg)](https://github.com/92username/ai-resume-optimizer/actions/workflows/deploy.yml) [![Pylint](https://github.com/92username/ai-resume-optimizer/actions/workflows/pylint.yml/badge.svg)](https://github.com/92username/ai-resume-optimizer/actions/workflows/pylint.yml) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/5af46814f5704138a7066c1d23abf174)](https://app.codacy.com/gh/92username/ai-resume-optimizer/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

[![Python](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/github/license/92username/ai-resume-optimizer)](LICENSE)

![GitHub commit activity](https://img.shields.io/github/commit-activity/m/92username/ai-resume-optimizer)
![Last Commit](https://img.shields.io/github/last-commit/92username/ai-resume-optimizer)

![Docker stats](https://img.shields.io/badge/Docker%20/%20stats-blue?logo=docker)
![Docker Image Size (latest)](https://img.shields.io/docker/image-size/user92/ai-resume-optimizer/latest)
![Docker Pulls](https://img.shields.io/docker/pulls/user92/ai-resume-optimizer)
![Docker Image Version](https://img.shields.io/docker/v/user92/ai-resume-optimizer?sort=semver)

 ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![ChatGPT](https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
# AI Resume Optimizer

**Otimize seu currículo com inteligência artificial de forma eficaz.**

Este projeto oferece uma ferramenta de análise de currículo que aplica boas práticas de otimização com base em palavras-chave relevantes para sistemas de triagem automática, como ATS (Applicant Tracking Systems). A proposta é ajudar candidatos a posicionarem melhor seus currículos.

---

## ✨ Funcionalidades

- Análise textual do currículo do usuário
- Sugestão de palavras-chave relacionadas à área de atuação
- Reescrita de trechos do currículo com linguagem mais profissional
- Interface simples via Streamlit

---

## 🌐 Acesse diretamente clicando na badge abaixo:
[![Hostinger](https://img.shields.io/badge/Hostinger-673DE6?style=for-the-badge&logo=hostinger&logoColor=white)](https://resume.tamanduas.dev/)

Ou acessando https://resume.tamanduas.dev/


## 🚀 Como Executar Localmente

```bash
# Clone o repositório
$ git clone https://github.com/92username/ai-resume-optimizer.git
$ cd ai-resume-optimizer

# Instale as dependências
$ pip install -r requirements.txt

# Crie um arquivo .env com sua chave da API OpenAI
OPENAI_API_KEY=sua-chave-aqui

# Rode o app
$ streamlit run form.py
```

---

## 🐳 Executar via Docker

```bash
# Build da imagem
$ docker build -t ai-resume-optimizer .

# Executar o container
$ docker run -d -p 8501:8501 --env-file .env ai-resume-optimizer
```

---

## 🧠 Exemplo de Uso
- O usuário insere seu currículo em texto.
- A IA sugere melhorias na estrutura, clareza e vocabulário profissional.
- Também sugere palavras-chave que alinham o currículo com descrições de vagas na área escolhida.

---

## 📌 Objetivo

- **Auxiliar candidatos** a apresentar seus perfis de forma mais estratégica.
- **Promover boas práticas** de escrita de currículo.

---

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
