## Objetivo do Projeto

Uma aplicação funcional como prova de conceito para consolidar práticas DevOps modernas:

🔹 CI/CD com GitHub Actions
🔹 Docker + VPS com domínio e HTTPS (NGINX + Certbot)
🔹 Deploy automatizado com infraestrutura leve
🔹 Código versionado no GitHub
🔹 Chamadas à API da openai
🔹 Gerenciamento de chaves e segredos via GitHub Secrets

---

##  Tecnologias Utilizadas

| Camada        | Tecnologia               | Função Principal                                   |
|---------------|--------------------------|----------------------------------------------------|
| Linguagem     | Python 3.10              | Backend e lógica de negócio                        |
| Framework     | Streamlit                | Interface web interativa (frontend + backend)      |
| AI            | OpenAI API (GPT-4o)      | Geração de texto otimizado e sugestões             |
| Infraestrutura| Docker                   | Containerização da aplicação                       |
| CI/CD         | GitHub Actions           | Deploy automatizado para VPS                       |
| Web Server    | NGINX                    | Proxy reverso + HTTPS com Certbot                  |
| Hosting       | Hostinger VPS            | Ambiente Linux com IP fixo para produção           |
| Domínio       | GoDaddy (tamanduas.dev)  | Domínio próprio com subdomínio dedicado            |
| Segurança     | Let's Encrypt (Certbot)  | Certificado SSL gratuito                           |
| Qualidade     | Pylint + Codacy          | Análise estática do código                         |

---

## Arquitetura do Sistema

- **Usuário** acessa `https://resume.tamanduas.dev`
- **NGINX** redireciona o tráfego e gerencia HTTPS (SSL)
- **Streamlit App** roda no container, escutando na porta 8501
- **OpenAI API** responde as requisições de otimização de currículo

---

## Fluxo DevOps

1. Código versionado no GitHub (`main`)
2. Commits acionam o **workflow de deploy** via GitHub Actions
3. A aplicação é entregue diretamente na **VPS**
4. O NGINX já está configurado para servir o container pela web

---

## Conquistas Técnicas

- Deploy **100% automatizado**
- App acessível via domínio com HTTPS
- Compatível com **desktop e mobile**
- Interface amigável e responsiva
- Qualidade de código **acima de 9.0 no Pylint**
- Imagem Docker otimizada e publicada no DockerHub
