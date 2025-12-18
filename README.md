# 🚀 FastAPI Auth System (Nome do Projeto)

Sistema de autenticação profissional desenvolvido durante a graduação em Ciência da Computação, focado em **Clean Architecture** e segurança.

## 🛠️ Tecnologias e Conceitos
- **Linguagem:** Python 3.12+
- **Framework:** FastAPI
- **Persistência:** SQLAlchemy (ORM) e SQLite
- **Segurança:** Hashing de senhas com Bcrypt (Passlib)
- **Arquitetura:** Separação em camadas (Models, Schemas, Database, Main)

## 📌 Diferenciais Técnicos
- **Injeção de Dependência:** Gestão eficiente de sessões de banco de dados.
- **Desacoplamento:** Estrutura pronta para migração para **AWS (RDS/PostgreSQL)**.
- **Validação:** Uso rigoroso de Pydantic para integridade de dados.

## 🚀 Como rodar o projeto
1. Clone o repositório
2. `pip install -r requirements.txt`
3. `uvicorn main:app --reload`
