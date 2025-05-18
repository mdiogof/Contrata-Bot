# Contrata-Bot
# 🤖 Contrata Bot

O **Contrata Bot** é um sistema inteligente desenvolvido para ajudar estudantes do ensino superior a encontrarem oportunidades de emprego ou estágio compatíveis com sua formação, localização e período acadêmico. Utiliza os agentes de IA do **Google Gemini**, combinando busca em tempo real com filtragem por relevância.

## 🧠 Sobre o Projeto

Este projeto demonstra o uso prático de **IA generativa**, com foco na automação da busca por vagas de forma personalizada. A aplicação se divide em três etapas principais:

1. **Busca Inteligente:** Um agente realiza pesquisas por vagas com base no curso, local e cargo informado.
2. **Refinamento de Resultados:** Um segundo agente filtra as vagas mais adequadas ao período do estudante.
3. **Interface Visual:** As vagas selecionadas são exibidas como botões interativos com links diretos.

---

## 🚀 Tecnologias Utilizadas

- [Google Gemini (via Google ADK)](https://cloud.google.com/vertex-ai/docs/generative-ai/overview)
- [Python](https://www.python.org/)
- [Google Colab](https://colab.research.google.com/)
- [Google Search Tool (API do ADK)](https://github.com/google/generative-ai-docs/tree/main/gemini-api-examples)

---

## 🔑 Configurando sua chave da API do Gemini

Para executar este notebook, você precisa configurar sua chave da API do Gemini:

1. No Google Colab, vá até o menu:
   - Executar → Gerenciar chaves de API (secrets)
   - Ou Runtime → Manage Secrets
2. Adicione uma nova chave:
   - Nome: sua_chave_aqui
   - Valor: sua_chave_da_api_do_gemini
3. Depois de salvar, ative a chave clicando no botão ao lado do campo no painel de Secrets.

Pronto! Agora o Contrata Bot poderá acessar a API com segurança.

---

## 🧪 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/contrata-bot.git
2. Abra o notebook no Google Colab.
3. Insira sua Google API Key no userdata do Colab:
   import os  
   from google.colab import userdata  
   os.environ["GOOGLE_API_KEY"] = userdata.get('sua_chave_aqui')
   - Essa parte já está no código, basta alterar o campo 'sua_chave_aqui' com o nome dela.
5. Execute o notebook e responda às perguntas interativas.

---

## 💼 Exemplo de Uso

- Curso: Engenharia de Computação
- Período: 1º semestre
- Local: Sorocaba - SP
- Cargo: Estagiário

🔗 O bot exibirá as vagas mais relevantes com links clicáveis para cada uma.

---

## ✍️ Autor

Desenvolvido por Diogo Melo Ferraz.
