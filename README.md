# PHP & MySQL: Conexão, CRUD e Validação

Projeto prático focado em conexão com base de dados, processamento de formulários e validação de dados no servidor (*server-side*).

---

## Tecnologias

* **PHP** (Backend e validações)
* **MySQL workbench** (Base de dados)
* **HTML5** (Formulários)

---

## Prints da atividade

### MySQL Workbench com Produtos
<img width="400" height="200" alt="Captura de tela 2026-09-29 112658" src="https://github.com/user-attachments/assets/8cba1976-d075-4a9b-ac74-a5f000a5006f" />

### Formulário do Desafio
<img width="400" height="200" alt="Captura de tela 2026-09-29 112723" src="https://github.com/user-attachments/assets/ab2c8670-7270-4f52-be12-ecf90612b242" />

### MySQL Workbench com Clientes
<img width="400" height="200" alt="Captura de tela 2026-09-29 112758" src="https://github.com/user-attachments/assets/44fec8dd-fdfa-4bb5-96fd-ca52e83b4ff4" />

### Formulário de Clientes
<img width="300" height="100" alt="Captura de tela 2026-09-29 112832" src="https://github.com/user-attachments/assets/f7403c20-793e-4422-a0e9-dbbe71f4cb52" />

---
## Estrutura da Base de Dados

Cria a base de dados `exercicio` e as tabelas executando o script SQL abaixo:

```sql
CREATE DATABASE IF NOT EXISTS exercicio;
USE exercicio;

CREATE TABLE IF NOT EXISTS clientes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL
);

CREATE TABLE IF NOT EXISTS produtos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    preco DECIMAL(10, 2) NOT NULL
);
