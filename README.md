# HighCapital-Desafio-Tecnico

## Projeto de Chatbot com Integração à Inteligência Artificial

Este documento contém as diretrizes e requisitos para o desenvolvimento de uma aplicação web que permite interação com um chatbot personalizado, utilizando inteligência artificial por meio da API do ChatGPT. O projeto deve ser desenvolvido com C# no back-end e ReactJS no front-end.

⸻

🎯 Objetivo do Projeto

Criar uma aplicação onde o usuário pode:
	•	Criar um chatbot personalizado, definindo seu contexto e estilo de resposta.
	•	Interagir com esse chatbot por meio de uma interface web simples.
	•	Visualizar o histórico da conversa com o chatbot.

⸻

🛠️ Requisitos Técnicos

🔙 Backend
	•	Linguagem: C#
	•	Framework: .NET 6 ou superior
	•	API de LLM: OpenAI (ChatGPT - via gpt-3.5-turbo ou gpt-4)
	•	Persistência: Entity Framework Core (banco de dados à sua escolha)

🔜 Frontend
	•	Framework: ReactJS
	•	Ferramentas: Vite ou Create React App

⸻

📦 Funcionalidades

🤖 Criação de Chatbot
	•	O usuário pode criar um chatbot informando:
	•	Nome do bot
	•	Descrição ou contexto inicial (ex: “Você é um assistente de vendas educado”)
	•	Esse contexto será utilizado em todas as interações com o bot.

💬 Interação com o Chatbot
	•	O usuário pode enviar mensagens para o bot via interface web.
	•	A resposta é gerada em tempo real utilizando a API da OpenAI.
	•	O histórico da conversa é exibido em uma interface de chat.
	•	As mensagens (perguntas e respostas) devem ser armazenadas no banco de dados.

⸻

🗃️ Armazenamento de Dados

A estrutura do banco de dados deve conter:
	•	Lista de bots criados com seus contextos
	•	Histórico de mensagens (mensagem do usuário e resposta do bot, associadas a um bot)

⸻

🎨 Interface de Usuário

A aplicação deve conter:
	•	Tela para criar e visualizar bots existentes.
	•	Tela de chat com o bot:
	•	Campo de mensagem e botão de envio
	•	Exibição do histórico completo da conversa

⸻

📌 Orientações Gerais
	•	Priorize código limpo, organizado e fácil de manter.
	•	Use boas práticas de arquitetura e separação de responsabilidades.
	•	Documente as principais partes da aplicação.
	•	Utilize componentes reutilizáveis no front-end.

⸻

📤 Entrega do Projeto

O projeto deve ser entregue em um repositório Git contendo:
	•	Código fonte do back-end e front-end
	•	Arquivos de configuração (ex: appsettings.json, .env, package.json)
	•	Arquivo README.md com:
	•	Visão geral do projeto
	•	Instruções de instalação e execução
	•	Tecnologias utilizadas

⸻

✅ Avaliação

A avaliação será baseada em:
	•	Funcionalidade: As funcionalidades descritas devem estar funcionando corretamente.
	•	Qualidade do Código: Clareza, organização e boas práticas.
	•	Documentação: README completo e código comentado onde necessário.
	•	Interface: Facilidade de uso e experiência de interação com o bot.

⸻

🌟 Diferenciais
	•	Implementação de testes unitários no back-end
	•	Interface com UX aprimorada (scroll automático, loading states)
	•	Utilização eficiente da API da OpenAI (contexto, temperatura, etc.)
