# FastAPI Todo API 🚀

Este é um projeto de uma API RESTful para gerenciar tarefas (to-do list) usando **FastAPI**.

## Funcionalidades
- Criar uma nova tarefa
- Listar todas as tarefas
- Buscar uma tarefa pelo ID
- Atualizar uma tarefa existente
- Excluir uma tarefa

## Tecnologias Utilizadas
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

## Como Rodar o Projeto

### Pré-requisitos
- Python 3.7+
- Virtualenv

### Passos para rodar
```bash
# Clonar o repositório
git clone https://github.com/RodrigoMaciel00/fastapi_todo_app.git
cd fastapi_todo_app

# Criar ambiente virtual
python -m venv venv
source venv/bin/activate

# Instalar dependências
pip install -r requirements.txt

# Rodar o servidor
uvicorn main:app --reload
