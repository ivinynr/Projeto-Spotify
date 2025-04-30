# 🎧 Projeto Aplicação com REACT que simula Spotify

Este projeto é uma aplicação web full-stack que simula uma plataforma de streaming musical, semelhante ao Spotify. A interface de usuário foi desenvolvida com **React**, enquanto o back-end utiliza **Node.js** para oferecer as APIs necessárias.

---

## ✅ Pré-requisitos

Para rodar este projeto localmente, você precisa ter os seguintes softwares instalados:

- [Node.js](https://nodejs.org/) (recomendado: versão 18 ou superior)
- [NPM](https://www.npmjs.com/) (gerenciador de pacotes que já vem com o Node.js)
- [Docker](https://www.docker.com/) e Docker Compose

> 🔹 **Node.js** é um ambiente de execução JavaScript server-side.  
> 🔹 **NPM** (Node Package Manager) é usado para instalar bibliotecas e dependências do projeto.  
> 🔹 **Docker** permite criar ambientes isolados para rodar aplicações em containers, facilitando a configuração e execução do projeto.

---

## 📁 Estrutura de Pastas

📦 projeto-spotify-simulador 
	├── back-end # Contém a API construída com Node.js 
	│ └── api/ 
	│ └── server.js 
	├── front-end # Aplicação React 
	│ ├── public/ 
	│ ├── src/ 
	│ └── ... 
	├── docker-compose.yml 
	└── README.md


---


## 📦 Execução e Suporte

### 🚀 Como Rodar a Aplicação

1. Inicie os containers com Docker Compose:
```bash
   docker-compose up -d
   ```
   

2. Inicie a API (back-end):
```bash
   cd ./back-end
   node ./api/server.js
```
   A aplicação back-end estará rodando em: http://localhost:3000

3. Inicie a aplicação React (front-end):
```bash
   cd ./front-end
   npm install
   npm run dev
```
   O frontend estará em: http://localhost:5173 ou a porta que o Vite indicar.

   OBS: Os 3 comandos em terminais diferentes.

---

### 📬 Suporte e Contato

Fique à vontade para:

- Abrir issues com dúvidas, sugestões ou problemas
- Enviar pull requests com melhorias
- Usar o projeto como base para outros experimentos






