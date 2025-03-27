# 📖 Diário Interativo

Este é um projeto de um **Diário Interativo**, desenvolvido utilizando **Django** no backend e **Tailwind CSS** para estilização no frontend. A aplicação permite o cadastro de pessoas, escrita de entradas de diário e gerenciamento de registros por data.

## 🚀 Tecnologias Utilizadas
- **Python** (Django para o backend)
- **Django Ninja** (para criação de APIs REST)
- **HTML, CSS e Tailwind CSS** (para o frontend)
- **Banco de Dados** (MySQL, PostgreSQL ou SQLite)

## 🎯 Funcionalidades
- 📌 Cadastro de pessoas
  ![projeto_diario3](https://github.com/user-attachments/assets/def02b2b-c7b9-4046-ba0a-7978cc1d1613)

- 📝 Criação e edição de registros no diário
 ![projeto_diario4](https://github.com/user-attachments/assets/a9f39b15-7552-4223-9b31-5d3721db8551)

- 📅 Visualização de entradas por data
  ![projeto_diario5](https://github.com/user-attachments/assets/deb3d1bc-b263-434f-9ed3-a72d49d6d0ed)

- 🗑️ Exclusão de registros
 ![projeto_diario6](https://github.com/user-attachments/assets/09a14dc3-9a91-43d3-bf39-8c9fadfff7ba)

- 🔍 Interface dinâmica e responsiva
  ![projeto_diario](https://github.com/user-attachments/assets/2c11c5ec-428f-4188-9182-7cc88e9d6e04)
 ![projeto_diario2](https://github.com/user-attachments/assets/47521c91-47a4-4d4a-9716-227a13bdcec8)



## 📌 Pré-requisitos
Antes de iniciar, certifique-se de ter instalado:
- **Python 3.8+**
- **Banco de Dados** (MySQL, PostgreSQL ou SQLite)

## 📥 Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
3. Instale as dependências do projeto:
   ```bash
   pip install -r requirements.txt
   ```

## ⚙️ Configuração do Banco de Dados
1. Configure as credenciais do banco de dados no arquivo **settings.py** ou utilize um arquivo **.env**.
2. Aplique as migrações:
   ```bash
   python manage.py migrate
   ```

## ▶️ Como Executar
Para iniciar o servidor, execute:
```bash
python manage.py runserver
```
O backend estará disponível em `http://127.0.0.1:8000/`.

## 📌 Estrutura do Projeto
- **`views.py`**: Contém a lógica das páginas e funções do sistema
- **`templates/`**: Diretório com os arquivos HTML
- **`static/`**: Diretório com arquivos de estilo e scripts

## 📜 Licença
Este projeto está sob a licença **MIT**.

---
💡 *Contribuições são bem-vindas!*
