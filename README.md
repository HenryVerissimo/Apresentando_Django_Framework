# Apresentação sobre o Django
### Workshop dia 01/08/2025

Apresentando o Framework Django a F5Softwares.

**Instalar o UV:**  
Linux: `curl -LsSf https://astral.sh/uv/install.sh | sh`  
Windows: `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`

**Instalar as dependências**:  
Comando: `uv sync` ou `uv pip install -r requirements.txt`


**Rodar o servidor da aplicação:**  
Linux: `uv run python3 manage.py runserver`  
Windows: `uv run python manage.py runserver`