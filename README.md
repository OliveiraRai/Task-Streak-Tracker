<div align="center">
  <h1>🔥 Task Streak Tracker</h1>
  <p><i>Um gerenciador de hábitos focado em consistência e persistência.</i></p>
</div>

<hr>

<h2>📌 Sobre o Projeto</h2>
<p>
  O <b>Task Streak Tracker</b> é uma aplicação Full Stack desenvolvida para ajudar usuários a monitorarem seus hábitos diários. 
  O sistema permite criar tarefas e acompanhar "streaks" (sequências) de dias consecutivos, incentivando a manutenção de rotinas saudáveis.
</p>

<h2>🚀 Tecnologias Utilizadas</h2>

<table>
  <tr>
    <th>Backend</th>
    <td>Python, Django, Django REST Framework</td>
  </tr>
  <tr>
    <th>Banco de Dados</th>
    <td>PostgreSQL</td>
  </tr>
  <tr>
    <th>Frontend</th>
    <td>React.js (Vite), CSS3</td>
  </tr>
  <tr>
    <th>Segurança</th>
    <td>CORS Headers, Autenticação de Usuário</td>
  </tr>
</table>

<h2>⚙️ Funcionalidades do Backend</h2>
<ul>
  <li><b>API RESTful:</b> Endpoints estruturados para operações de CRUD.</li>
  <li><b>Filtro de Dono (Privacy):</b> Cada usuário autenticado visualiza apenas as suas próprias tarefas.</li>
  <li><b>User-Aware Logic:</b> O sistema identifica automaticamente o autor da tarefa através do token de autenticação, sem necessidade de seleção manual.</li>
  <li><b>Serialização Avançada:</b> Respostas JSON otimizadas incluindo dados aninhados do perfil do usuário.</li>
</ul>

<h2>🛠️ Como rodar o projeto (Backend)</h2>

<pre>
<code>
# Clone o repositório
git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git

# Entre na pasta do backend
cd backend

# Crie e ative o ambiente virtual
python -m venv .venv
source .venv/bin/activate  # No Linux/Mac

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações do banco de dados
python manage.py migrate

# Inicie o servidor
python manage.py runserver
</code>
</pre>

<h2>📝 Próximos Passos</h2>
<ul>
  <li>[ ] Integração completa com o Frontend (React).</li>
  <li>[ ] Implementação de sistema de login via JWT.</li>
  <li>[ ] Dashboard visual com gráficos de progresso.</li>
</ul>

<hr>

<p align="center">
  Desenvolvido por <strong>Rai</strong> — Conecte-se comigo no <a href="https://linkedin.com">LinkedIn</a>!
</p>
