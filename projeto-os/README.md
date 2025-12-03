# Projeto Integrador – Etapas 1 e 2

## Informações Gerais
- Curso: Análise e Desenvolvimento de Sistemas  
- Aluno: Tiago Back  
- Data: Dezembro de 2025  

---

## Etapa 1 – Definição do Projeto

### Problema Identificado
Muitas pequenas assistências técnicas ainda utilizam papel, cadernos ou planilhas simples para controlar suas ordens de serviço. Isso causa desorganização, perda de informações e dificuldade no acompanhamento dos serviços.

### Solução Proposta
Desenvolver um **Sistema Web Simples** que permita o registro e acompanhamento básico dos atendimentos realizados por uma assistência técnica.

### Funcionalidades do Sistema
- Tela de login para o administrador
- Cadastro de clientes
- Criação de ordens de serviço
- Atualização do status da ordem de serviço
- Consulta das ordens cadastradas

### Fora do Escopo
- Aplicativo mobile
- Relatórios avançados
- Controle financeiro
- Cadastro de técnicos

### Seleção da Plataforma
- Plataforma: Web  
- Justificativa: Permite acesso via navegador, sem instalação, e uso em diferentes dispositivos.

### Tecnologias
- **Front-end:** HTML5, CSS3, JavaScript  
- **Back-end:** PHP  
- **Banco de Dados:** PostgreSQL  
- **Ferramentas de Desenvolvimento:** Visual Studio Code, GitHub, BrModelo, Draw.io

### Diagramas Iniciais
**Ator:** Administrador  

**Casos de Uso:**  
- Realizar login  
- Cadastrar cliente  
- Criar ordem de serviço  
- Atualizar status da ordem  
- Consultar ordens de serviço  

**Diagrama de Sequência – Criação de Ordem de Serviço:**  
1. Administrador realiza login  
2. Sistema valida dados  
3. Administrador seleciona “Nova Ordem de Serviço”  
4. Sistema solicita dados  
5. Administrador informa dados  
6. Sistema grava informações no banco  
7. Sistema confirma cadastro da ordem  

**MER – Modelo Entidade Relacionamento (Conceitual):**  
- USUÁRIO: id_usuario, nome, email, senha  
- CLIENTE: id_cliente, nome, telefone  
- ORDEM_SERVIÇO: id_os, data, defeito, status, id_cliente  

**Relacionamentos:**  
- Um cliente pode possuir várias ordens de serviço  
- Uma ordem de serviço pertence a apenas um cliente

### Cronograma Inicial
| Dia | Atividade |
|-----|-----------|
| 1   | Planejamento e criação dos diagramas |
| 2   | Criação do banco de dados |
| 3   | Desenvolvimento da tela de login |
| 4   | Cadastro de clientes |
| 5   | Cadastro de ordens |
| 6   | Consulta e atualização de status |
| 7   | Testes finais e entrega |

---

## Etapa 2 – Desenvolvimento Inicial

### Banco de Dados
- Scripts DDL (criação de tabelas) e DML (inserção de dados) executados no PostgreSQL.  
- Arquivos salvos em `database/ddl.sql` e `database/dml.sql`.

### Wireframes
- Telas principais desenvolvidas no Figma:
  - Login  
  - Cadastro  
  - Listagem de dados  
  - Detalhes/Edição  
- Arquivos salvos em `wireframes/`  

### APIs / Backend

- Próxima etapa: Funcionalidades complementaresTarefa
 

---

## Estrutura do R

