# $\color{#516DA6}{\text{PHP e MySQL: Conexão e Validação}}$

Projeto prático focado em conexão com base de dados, processamento de formulários e validação de dados no servidor (*server-side*).

---

## $\color{#516DA6}{\text{Tecnologias}}$

* **PHP** (Backend e validações)
* **MySQL workbench** (Base de dados)
* **HTML5** (Formulários)

---

## $\color{#516DA6}{\text{Prints da atividade}}$

### $\color{#516DA6}{\text{MySQL Workbench com Produtos}}$
<img width="400" height="200" alt="Captura de tela 2026-09-29 112658" src="https://github.com/user-attachments/assets/8cba1976-d075-4a9b-ac74-a5f000a5006f" />

### $\color{#516DA6}{\text{Formulário do Desafio}}$
<img width="400" height="200" alt="Captura de tela 2026-09-29 112723" src="https://github.com/user-attachments/assets/ab2c8670-7270-4f52-be12-ecf90612b242" />

### $\color{#516DA6}{\text{MySQL Workbench com Clientes}}$
<img width="400" height="200" alt="Captura de tela 2026-09-29 112758" src="https://github.com/user-attachments/assets/44fec8dd-fdfa-4bb5-96fd-ca52e83b4ff4" />

### $\color{#516DA6}{\text{Formulário de Clientes}}$
<img width="300" height="100" alt="Captura de tela 2026-09-29 112832" src="https://github.com/user-attachments/assets/f7403c20-793e-4422-a0e9-dbbe71f4cb52" />

---
## $\color{#516DA6}{\text{Estrutura da Base de Dados}}$

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
```

<img width="498" height="361" alt="oke-yamada-ryo" src="https://github.com/user-attachments/assets/5fd621ad-4147-4eb1-85a0-933bf0692810" />


