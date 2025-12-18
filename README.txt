# API de Autenticação — Projeto Backend

API em Python com FastAPI que permite cadastro de usuários com senhas criptografadas (bcrypt) e armazenamento em banco SQLite. Possui validação de e-mail, documentação automática via `/docs` e estrutura pronta para integração com frontend ou evolução para login e JWT.

## Tecnologias
- Python 3
- FastAPI
- SQLAlchemy
- SQLite
- Passlib (bcrypt)

## Como executar
```powershell
py -m pip install "fastapi" "uvicorn" "sqlalchemy" "passlib[bcrypt]" "pydantic[email]"
py -m uvicorn main:app --reload
