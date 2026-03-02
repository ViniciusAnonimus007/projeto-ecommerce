#  Tech Store - E-commerce

Um e-commerce funcional focado em performance e segurança, desenvolvido com uma arquitetura separada (Multi-repo)

---

## 🎯 Objetivo
Criar uma plataforma de e-commerce completa utilizando tecnologias modernas, aplicando conceitos de Clean Architecture, segurança (JWT) e escalabilidade. Este projeto faz parte de um plano de desenvolvimento de carreira.

## 🏗️ Arquitetura do Sistema
O projeto é dividido em dois repositórios independentes para simular um ambiente profissional:

1.  **Frontend (Repositório Atual):** Desenvolvido em **Next.js e React**, focado em SEO e interface responsiva.
2.  **Backend (API):** Servidor em **Node.js/Express**, responsável pela lógica de negócio e segurança.
3.  **Banco de Dados:** **PostgreSQL** para persistência de dados relacionais.

---

## 📋 Roadmap de Tarefas

### Interface e Estrutura (Frontend)
- [ ] Estrutura inicial das pastas do projeto.
- [ ] Configuração de bibliotecas (React, Next.js, Tailwind, Typescript).
- [ ] Landing page e Listagem de produtos (Mock data).
- [ ] Página de Checkout com avisos sobre doações.

### O Coração do Backend (API & DB)
- [ ] Definição do Schema do banco de dados PostgreSQL.
- [ ] Criação da API REST própria com Node.js.
- [ ] Implementação de Autenticação (Login e Cadastro) com JWT.
- [ ] Conexão entre Frontend e API.

### Refinamento e Deploy
- [ ] Páginas de administração (Gestão de estoque).
- [ ] Validações de segurança e tratamento de erros.
- [ ] Deploy do Frontend (Vercel) e Backend (Render/Railway).

---

## 🛠️ Tecnologias e Linguagens 
- **Linguagem:** TypeScript
- **Frontend:** Next.js, React, Tailwind CSS, Lucide Icons
- **Backend:** Node.js, Express
- **Banco de Dados:** PostgreSQL

---

## 🕵️‍♂️ Versionamento 

Utilizo o padrão **Conventional Commits** para manter o histórico organizado:

| Tipo | Descrição |
| :--- | :--- |
| `feat:` | Nova funcionalidade |
| `fix:` | Correção de bug |
| `docs:` | Mudanças na documentação |
| `style:` | Ajustes de estilo/CSS |
| `refactor:` | Mudança no código que não altera lógica |

---

## 📜 Histórico de Versões

### v0.0.1 - Documentação Inicial
- [x] Criação do `README.md` com objetivos, arquitetura e roadmap.
