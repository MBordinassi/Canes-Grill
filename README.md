# Canes-Grill

<p align="center">
  <img src="https://github.com/MBordinassi/Canes-Grill/blob/main/public/images/Canes-Logo.png" alt="Logo do Canes-Grill" width="200"/>
</p>

## 🍔 Descrição do Projeto

O **Canes-Grill** é uma plataforma completa para a gestão de um restaurante. O projeto é dividido em duas partes principais: um **backend** robusto em **Django** para gerenciar o banco de dados e a lógica de negócio, e um **frontend** dinâmico em **React** para a interface do usuário. Ele permite aos clientes navegar pelo cardápio e fazer pedidos, enquanto administradores podem gerenciar o menu com facilidade.

---

## ✨ Funcionalidades

- **Backend em Django:**
  - **Roteamento de URLs:** Gerencia o mapeamento entre URLs e views.
  - **Banco de Dados (SQLite):** Configuração e controle do banco de dados.
  - **Gestão de requisições:** Lida com as requisições e respostas HTTP.
  - **Autenticação:** Possível sistema de login e permissões.
  - **Painel de Administração:** CRUD (Create, Read, Update, Delete) de produtos.
- **Frontend em React:**
  - **Menu Dinâmico:** Visualização do cardápio completo, com opções de categorias.
  - **Carrinho de Compras:** Adicione e remova itens, veja o total e "finalize" o pedido.

---

## 💻 Tecnologias Utilizadas

### Backend

- **Python**
- **Django:** Framework web para o backend.
- **SQLite:** Banco de dados padrão do Django.

### Frontend

- **React:** Biblioteca JavaScript para construir a interface do usuário.
- **Context API:** Gerenciamento de estado.
- **React Router DOM:** Gerenciamento das rotas.
- **Styled Components:** Estilização baseada em componentes.

---

## ⚙️ Como Rodar o Projeto

Siga os passos abaixo para ter uma cópia do projeto em sua máquina local.

### Pré-requisitos

-   **Python 3.x**
-   **pip** (gerenciador de pacotes do Python)
-   **Node.js** e **npm**

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/MBordinassi/Canes-Grill.git](https://github.com/MBordinassi/Canes-Grill.git)
    ```
2.  **Entre na pasta do projeto:**
    ```bash
    cd Canes-Grill
    ```
3.  **Configuração do Backend (Django):**
    -   Crie e ative um ambiente virtual (recomendado):
        ```bash
        python -m venv venv
        source venv/bin/activate  # No Windows: venv\Scripts\activate
        ```
    -   Instale as dependências do Python:
        ```bash
        pip install -r requirements.txt
        ```
    -   Execute as migrações para criar o banco de dados:
        ```bash
        python manage.py migrate
        ```
    -   Crie um superusuário para o painel de administração:
        ```bash
        python manage.py createsuperuser
        ```
    -   Inicie o servidor do Django:
        ```bash
        python manage.py runserver
        ```

4.  **Configuração do Frontend (React):**
    -   Entre na pasta do frontend:
        ```bash
        cd frontend_react
        ```
    -   Instale as dependências:
        ```bash
        npm install
        ```
    -   Inicie o servidor de desenvolvimento:
        ```bash
        npm start
        ```
    O projeto será aberto no seu navegador em `http://localhost:3000`.

---

## 📄 Licença

Este projeto está licenciado sob a Licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

---

## 📬 Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- **Desenvolvedor:** [Matheus Bordinassi](https://github.com/MBordinassi)
