# Desafio Clientes 

## Api Rest que retorna informações de clientes 

## Ações: 
Busca de clientes por Id:
 <code> GET /clients/1 </code>

Busca paginada de clientes:
<code> GET /clients?page=0&size=6&sort=name </code>

Inserção de novo cliente: 
<code> POST /clients
 {
  "name": "Luis Suarez",
  "cpf": "12345678901",
  "income": 30000.0,
  "birthDate": "1994-07-20",
  "children": 2
 }</code>

Inserção de novo cliente:
<code> PUT /clients/1
{
"name": "Luis Suarez",
"cpf": "12345678901",
"income": 30000.0,
"birthDate": "1994-07-20",
"children": 2
}</code>

Deleção de cliente 
<code> DELETE /clients/1 </code>

## Checklist - Testes Realizados
#### 1 - [X] Busca por id retorna cliente existente
#### 2 - [X] Busca por id retorna 404 para cliente inexistente
#### 3 - [X] Busca paginada retorna listagem paginada corretamente
#### 4 - [ ] Inserção de cliente insere cliente com dados válidos
#### 5 - [ ] Inserção de cliente retorna 422 e mensagens customizadas com dados inválidos
#### 6 - [ ] Atualização de cliente com dados válidos 
#### 7 - [ ] Atualização de cliente retorna 404 para cliente inexistente
#### 8 - [ ] Atualização de cliente retorna 422 e mensagens customizadas com dados inválidos
#### 9 - [ ] Deleção de cliente existente
#### 10 -[ ] Deleção de cliente retorna 404 para cliente inexistente

