# Employee Management System APIs

Este repositório contém duas APIs para um sistema de gerenciamento de funcionários. Uma API é usada para consultar os dados dos funcionários e a outra é responsável pelo acesso ao banco de dados.

## API de Consulta de Dados de ProjectConsult (Leitura)

- **Endpoint:** `GET /api/employee/{id}`
- **Descrição:**
  - Esta API permite a consulta de informações específicas de um funcionário com base em seu ID.
  - Retorna os dados do funcionário em formato JSON.
  
## API de Acesso ao Banco de Dados ProjectServer (Escrita)

- **Endpoint:** `POST /api/employee`
- **Descrição:**
  - Esta API é utilizada para adicionar, atualizar ou excluir registros de funcionários no banco de dados.
  - Os dados do funcionário são enviados no corpo da solicitação em formato JSON.
  - Suporta ações como adicionar um novo funcionário, atualizar informações de um funcionário existente e excluir um funcionário.

## Exemplo de Solicitação JSON para Adicionar um Novo Funcionário:

```json
{
  "name": "Maria Pereira",
  "dateOfBirth": 17/08/1980 10:10:25,
  "admissionDate": 21/10/2009 11:10:25,
  "resignationDate": 10/08/2012 16:10:25
}

