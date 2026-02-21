# 🔥 Task Streak Tracker

Uma aplicação **Full Stack** para gerenciamento de tarefas e hábitos, focada em produtividade e consistência. O sistema permite que múltiplos usuários gerenciem suas próprias tarefas de forma isolada.

## 🚀 Funcionalidades Atuais

* **Sistema de Usuários:** Cadastro de novas contas e login seguro via Token.
* **Isolamento de Dados:** Cada usuário visualiza e gerencia apenas as suas próprias tarefas.
* **Gestão de Tasks:** Criar, listar e excluir tarefas.
* **Contador de Streaks:** Acompanhamento dinâmico da sequência de conclusão.
* **Dashboard:** Visualização de estatísticas (total de tarefas e maior streak).

## 🛠️ Tecnologias Utilizadas

### Frontend
* **React** (com TypeScript)
* **Vite** (Build tool)
* **Axios** (Consumo de API)

### Backend
* **Python 3**
* **Django** & **Django REST Framework**
* **SQLite** (Banco de dados)
* **Token Authentication** (Segurança)

---

## 📦 Como Rodar o Projeto

### 1. Backend (Django)
```bash
# Entre na pasta do backend
cd backend

# Execute as migrações
python manage.py migrate

# Inicie o servidor
python manage.py runserver
```
### 2. Frontend (React)
```bash
# Entre na pasta do frontend
cd frontend

# Instale as dependências
npm install

# Inicie o servidor
npm run dev
```

### 3. Endpoints Principais da API

<table>
  <tr>
    <td>**Método**</td>
    <td>**Endpoint**</td>
    <td>**Descrição**</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/register/</td>
    <td>Cria um novo usuário</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api-token-auth/</td>
    <td>Login e geração de Token</td>
  </tr>
  <tr>
    <td>GET</td>
    <td>/api/tasks/</td>
    <td>CLista as tarefas do usuário logado</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/api/tasks/</td>
    <td>Cria uma nova tarefa</td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>/api/tasks/{id}</td>
    <td>Remove uma tarefa</td>
  </tr>
</table>

🛠️ Próximos Passos (Roadmap)

    [ ] Implementar lógica de expiração automática de streaks.

    [ ] Adicionar Categorias (Tags) para as tarefas.

    [ ] Interface Responsiva (Mobile First).

Desenvolvido com ☕ e Python



