# 🔄 n8n Workflows

Repositório com automações construídas em [n8n](https://n8n.io/) como parte do meu aprendizado e portfólio em automação de processos, inteligência artificial e ciência de dados.

---

## 📁 Projetos

| Projeto | Descrição | Tecnologias |
|--------|-----------|-------------|
| [curriculo-triagem](./curriculo-triagem/) | Triagem automatizada de currículos com análise qualitativa e verificação de match para vagas | Groq, Google Sheets, PDF Extract |

---

## 🛠️ Tecnologias utilizadas

- **[n8n](https://n8n.io/)** — plataforma de automação de workflows
- **[Groq](https://groq.com/)** — inferência de LLMs (modelos: `llama-3.3-70b-versatile`, `llama-3.1-8b-instant`)
- **Google Sheets** — armazenamento de resultados
- **JavaScript** — transformações e manipulação de dados nos nós Code

---

## 📥 Como importar um workflow

1. Abra o seu n8n
2. Acesse o menu principal → **Workflows** → **Add Workflow**
3. Clique nos três pontos (`...`) no canto superior direito → **Import from file**
4. Selecione o arquivo `workflow.json` do projeto desejado

> ⚠️ Após importar, configure as credenciais necessárias (Groq API Key, Google Sheets, etc.) antes de executar.

---

> Este repositório está em constante evolução conforme novos projetos forem desenvolvidos.

