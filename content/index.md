# 🤖 Bem-vindo ao Guia Completo do Projeto ChatBot - GTHC

Seja bem-vindo ao **chatbot**, seu guia completo para entender e explorar todas as funcionalidades do nosso projeto de chatbot inteligente!  

---

## 🔹 Sobre o Projeto

O **chatbot - GTHC** é uma aplicação projetada para **interagir de forma natural com usuários**, automatizando respostas, oferecendo suporte e criando experiências eficientes e inteligentes.  
Nosso objetivo é entregar **um chatbot versátil e fácil de usar**, para os alunos da UFABC com conteúdos sobre a Universidade, buscando dinamizar o acesso a informação e conteúdos diversos

---

Dentro do **chatbot**, a estrutura está organizada em **4 subitens principais**: as pastas `app`, `src`, `shared` e uma série de **9 arquivos de instrução**.  

O chatbot funciona como um **sistema integrado entre frontend, backend e motor RAG**:

1. O usuário envia uma mensagem pelo frontend (`index.html` + `script.js`).  
2. A mensagem é recebida pelo backend em **Flask**.  
3. O backend utiliza funções do `src/` para **consultar o índice vetorial dos documentos** e gerar respostas com base no conteúdo disponível.  
4. O motor RAG combina **recuperação de informações relevantes** com **geração de texto pelo modelo de linguagem**, garantindo respostas precisas e contextualizadas.  
5. A resposta é enviada de volta ao frontend e exibida ao usuário.

> Toda a infraestrutura de dados, incluindo carregamento de documentos, criação de índices e consultas, está centralizada na pasta `src`. A pasta `shared` define os **modelos de dados** usados na comunicação. O script de execução garante que as dependências estejam instaladas e que o servidor Flask rode de forma organizada e prática.
