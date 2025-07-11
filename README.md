# GestorPro

**Sistema Web de Controle de Produção e Estoque**  
Projeto final do curso CC50 (CS50 em Português)

---

## 🧰 Tecnologias utilizadas

- Python 3
- Flask
- SQLite
- HTML5 + Jinja2 (para templates dinâmicos)

---

## ⚙️ Funcionalidades

- Login com autenticação
- Cadastro e listagem de produtos
- Cadastro de funcionários
- Registro de produção por funcionário
- Controle de estoque via produção
- Relatórios:
  - Produção por funcionário
  - Produção por produto

---

## ▶️ Como executar o projeto

### 1. Clone este repositório

```bash
git clone https://github.com/SEU_USUARIO/gestorpro.git
cd gestorpro
```

### 2. Instale as dependências

```bash
pip install flask
```

### 3. Execute o servidor

```bash
python app.py
```

### 4. Acesse o sistema

Abra o navegador em:  
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🔐 Login padrão

- **Usuário:** admin  
- **Senha:** 123

---

## 📂 Estrutura

```
gestorpro/
├── app.py
├── database.db
└── templates/
    ├── login.html
    ├── dashboard.html
    ├── produtos.html
    ├── funcionarios.html
    ├── producao.html
    └── relatorios.html
```

---

## ✍️ Autor

Desenvolvido como projeto final do curso CC50.
