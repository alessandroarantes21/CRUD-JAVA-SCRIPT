# 🔧 Sistema Oficina V4

Sistema simples de gerenciamento para **oficinas mecânicas**, desenvolvido utilizando **HTML, CSS, JavaScript e Bootstrap**, funcionando totalmente **offline no navegador**.

O sistema permite controlar **clientes, peças, ordens de serviço e faturamento**, sem necessidade de servidor ou banco de dados externo.

Todos os dados são armazenados utilizando **LocalStorage do navegador**.

---

# 🚀 Funcionalidades

## 🔐 Sistema de Login

* Criar usuário
* Login com usuário e senha
* Logout do sistema
* Usuários armazenados no LocalStorage

---

## 👥 Cadastro de Clientes

Permite registrar clientes da oficina.

Campos cadastrados:

* Nome
* Email
* Telefone

Funcionalidades:

* Adicionar cliente
* Listar clientes
* Armazenamento automático

---

## 🔧 Cadastro de Peças / Controle de Estoque

Controle básico de peças utilizadas na oficina.

Campos:

* Nome da peça
* Marca
* Modelo
* Quantidade em estoque
* Preço

Funcionalidades:

* Cadastro de peças
* Controle de estoque
* Visualização das peças cadastradas

---

## 📋 Ordem de Serviço

Permite registrar serviços realizados na oficina.

Campos:

* Cliente
* Descrição do serviço
* Valor do serviço
* Data automática

Funcionalidades:

* Criar ordem de serviço
* Visualizar histórico de serviços

---

## 📊 Relatório Financeiro

Painel simples de indicadores da oficina.

Exibe:

* Total de clientes cadastrados
* Total de peças cadastradas
* Total de serviços realizados
* Faturamento total da oficina

---

## 🌙 Dark Mode

O sistema possui suporte a **modo escuro**, podendo ser ativado pelo botão na interface.

---

# 🧠 Como funciona

O sistema utiliza **LocalStorage do navegador** como armazenamento de dados.

Estrutura simplificada:

```json
{
  "usuarios": [],
  "clientes": [],
  "pecas": [],
  "ordens": []
}
```

Isso permite executar o sistema:

* sem banco de dados
* sem servidor
* sem internet

---

# 🖥️ Tecnologias Utilizadas

| Tecnologia   | Uso                    |
| ------------ | ---------------------- |
| HTML5        | Estrutura da aplicação |
| CSS3         | Estilização            |
| Bootstrap 5  | Interface e layout     |
| JavaScript   | Lógica da aplicação    |
| LocalStorage | Armazenamento de dados |

---

# 📂 Estrutura do Projeto

```
sistema-oficina/
│
├── index.html
└── README.md
```

Todo o sistema está contido em **um único arquivo HTML**, contendo:

* interface
* estilos
* scripts JavaScript

---

# ▶️ Como Executar o Projeto

1️⃣ Baixe ou clone o projeto

```
git clone https://github.com/seuusuario/sistema-oficina.git
```

2️⃣ Abra o arquivo

```
index.html
```

3️⃣ O sistema será executado no navegador.

Não é necessário instalar:

* servidor
* banco de dados
* dependências

---

# 💡 Possíveis Melhorias Futuras

* [ ] Impressão de ordem de serviço
* [ ] Geração de PDF
* [ ] Backup automático
* [ ] Gráficos financeiros
* [ ] Banco de dados real
* [ ] API backend

---

# 👨‍💻 Autor

**Alessandro Arantes**

Desenvolvedor iniciante focado em:

* JavaScript
* Automação
* Sistemas simples para negócios

---

# 📜 Licença

Este projeto está sob licença **MIT**.

Uso livre para fins educacionais e melhorias.
