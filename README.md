# Simple Blog Django

Um projeto simples em **Django** onde o usuário pode se cadastrar, realizar login e fazer postagens após autenticado.  

---

## 🚀 Preparação do Ambiente

### 1. Verifique se o Python está instalado
No terminal (PowerShell, CMD ou Bash), execute:

```bash
python --version
```

ou, em alguns sistemas:

```bash
python3 --version
```

Se não aparecer a versão, baixe e instale o Python:  
👉 [Download do Python](https://www.python.org/downloads/)

---

### 2. Verifique se o **pip** está instalado
```bash
pip --version
```

Se não aparecer, instale o pip (no Windows ele geralmente vem junto com o Python).  
No Linux/Mac você pode instalar com:

```bash
sudo apt install python3-pip
```

---

### 3. Crie e ative um ambiente virtual (venv)
No diretório do projeto, rode:

```bash
# Criar ambiente virtual
python -m venv venv
```

Ativar o ambiente virtual:

- **Windows (PowerShell):**
```bash
venv\Scripts\Activate
```

- **Linux/Mac:**
```bash
source venv/bin/activate
```

Você verá o prefixo `(venv)` no terminal quando estiver ativo.

---

### 4. Instale as dependências
Instale todas as dependências listadas no arquivo `requirements.txt`:

```bash
python -m pip install -r requirements.txt
```
---

### 5. Rodando o projeto
Após instalar, inicie o servidor Django:

```bash
python manage.py runserver
```

Abra no navegador:  
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📂 Estrutura do Projeto
```
simple-blog-django/
│
├─ myproject/
│  ├─ assets/
│  ├─ media/
│  ├─ myproject/
│  ├─ static/    
│  ├─ templates/  
│  ├─ users/      # applications
│  ├─ posts/      # applications 
│
├─ venv/
├─ .gitignore
├─ README.md
└─ requirements.txt

```

---
## 📦 requirements.txt
```txt
asgiref==3.9.1
Django==5.2.5
pillow==11.3.0
sqlparse==0.5.3
tzdata==2025.2
```
---

## 🛠️ Tecnologias
- Python 3.x  
- Django  
- SQLite (banco padrão do Django)  
---

## ✨ Funcionalidades
- Cadastro e login de usuários  
- Postagens autenticadas  
- Visualização de posts no feed  

---

## 📄 Licença
Este projeto é de uso livre para estudos e melhorias.  

## 😃 Autor
Feito por Dante Alves 