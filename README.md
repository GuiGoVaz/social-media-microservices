# Social Media Microservices

Uma plataforma de rede social construída com **arquitetura de microsserviços**, utilizando Node.js, Express, MongoDB e Redis. O projeto foi desenvolvido com foco em escalabilidade, separação de responsabilidades e boas práticas de API.

## 📦 Microsserviços

- **API Gateway** – Ponto de entrada único para todas as requisições, com roteamento, rate limiting, autenticação via JWT e logging centralizado.
- **Identity Service** – Gerencia autenticação e autorização de usuários, com cadastro, login e validação de tokens JWT.
- **Post Service** – Responsável pela criação, leitura, atualização e exclusão de publicações.
- **Media Service** – (Em desenvolvimento) Para upload e gerenciamento de arquivos de mídia.

## 🛠️ Tecnologias utilizadas

- **Node.js** com **Express** – servidores HTTP leves e rápidos
- **MongoDB** com **Mongoose** – banco de dados NoSQL para persistência
- **Redis** com **ioredis** – cache e gerenciamento de sessões/rate limiting
- **JWT** (`jsonwebtoken`) – autenticação stateless
- **Helmet**, **CORS** e **express-rate-limit** – segurança e proteção básica
- **Winston** – logging estruturado

