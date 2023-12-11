# Projeto: Catálogo de Veículos

## Objetivo
Desenvolver um sistema de catálogo de veículos a venda, com funcionalidades de listagem, criação, edição e exclusão de registros. O projeto será dividido em um frontend usando React, um backend usando FastAPI (ou Flask) e um banco de dados MongoDB.

## Instalação
Certifique-se de ter o Node.js, Python, e MongoDB instalados em sua máquina.

### Backend (FastAPI)
1. Clone o repositório.
2. Navegue até a pasta `backend`.
3. Instale as dependências usando o comando: `pip install -r requirements.txt`.
4. Execute o servidor com: `uvicorn main:app --reload`.

### Frontend (React)
1. Navegue até a pasta `frontend`.
2. Instale as dependências usando o comando: `npm install`.
3. Inicie o aplicativo com: `npm start`.

## Requisitos

### Frontend
1. **Homepage Pública**
   - Exibir a vitrine de veículos.

2. **Ordenação de Veículos**
   - Os veículos devem ser ordenados em ordem de valor.

3. **Autenticação Administrativa**
   - Implementar login administrativo com token JWT.
   - Acesso restrito às operações administrativas.

4. **Token JWT**
   - Todas as requisições privadas devem incluir um token JWT válido.

5. **Operações CRUD**
   - Listagem, criação, edição e deleção de registros de veículos.

6. **Atributos Obrigatórios**
   - ID, nome, marca, modelo, foto.

### Backend
1. **API REST**
   - O backend deve ser uma API REST usando FastAPI ou Flask.

2. **Persistência de Dados**
   - Os dados devem ser persistidos em um banco de dados MongoDB.

3. **Token JWT**
   - Gerar e validar tokens JWT para autenticação.

## Checklist de Milestones

### Frontend
- **Dia 1: Configuração Inicial**
  - Configurar o projeto React.
  - Criar a estrutura da homepage.

- **Dia 2: Autenticação e Rotas**
  - Implementar autenticação e rotas privadas.

- **Dia 3: Listagem de Veículos**
  - Buscar e exibir veículos ordenados por valor.

- **Dia 4: Formulário de Cadastro**
  - Criar formulário para cadastrar veículos.

- **Dia 5: Edição e Exclusão**
  - Implementar edição e exclusão de veículos.

- **Dia 6: Estilização**
  - Estilizar a aplicação.

- **Dia 7: Testes e Finalização**
  - Realizar testes e finalizar a aplicação.

### Backend
- **Dia 1: Configuração Inicial**
  - Configurar o projeto FastAPI/Flask.
  - Conectar-se ao MongoDB.

- **Dia 2: Autenticação e Tokens JWT**
  - Implementar autenticação e geração de tokens.

- **Dia 3: Modelos de Dados**
  - Criar modelos para os veículos.

- **Dia 4: Rotas da API**
  - Implementar rotas para CRUD de veículos.

- **Dia 5: Validações e Middleware**
  - Adicionar validações e middleware para proteger rotas.

- **Dia 6: Testes e Documentação**
  - Realizar testes e documentar o código.

- **Dia 7: Deploy na AWS**
  - Fazer o deploy do backend na AWS.

## Tecnologias Utilizadas
- Frontend: React (com TypeScript, se possível).
- Backend: FastAPI (ou Flask), MongoDB.
- Autenticação: JWT.
- Deploy: AWS (backend), Vercel (frontend).
