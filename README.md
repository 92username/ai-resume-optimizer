# AI Resume Optimizer

**Otimize seu currículo com inteligência artificial, de forma ética e eficaz.**

Este projeto oferece uma ferramenta de análise de currículo que aplica boas práticas de otimização com base em palavras-chave relevantes para sistemas de triagem automática, como ATS (Applicant Tracking Systems). A proposta é ajudar candidatos a posicionarem melhor seus currículos.

---

## ✨ Funcionalidades

- Análise textual do currículo do usuário
- Sugestão de palavras-chave relacionadas à área de atuação
- Reescrita de trechos do currículo com linguagem mais profissional
- Interface simples via Streamlit

---

## 📦 Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [OpenAI API (GPT-4o)](https://platform.openai.com/)
- [Docker](https://www.docker.com/) (para deploy em container)

---

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

## 📁 Estrutura
```
ai-resume-optimizer/
├── Dockerfile
├── README.md
├── form.py         
├── requirements.txt
└── .env  
```

---

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
