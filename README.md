
# 🔧 Sistema Oficina V2

Sistema simples para **gerenciamento de clientes e peças de uma oficina mecânica**, desenvolvido utilizando **HTML, CSS, JavaScript e Bootstrap**, funcionando totalmente **offline no navegador**.

O objetivo do projeto é criar um **CRUD simples e funcional**, sem necessidade de backend ou banco de dados externo.

Todos os dados são armazenados utilizando **LocalStorage**.

---

# 📸 Interface do Sistema

O sistema possui duas áreas principais:

## 👥 Cadastro de Clientes

- Nome
- Email
- Telefone
- Busca de clientes
- Exclusão de registros

## 🔧 Cadastro de Peças

- Nome da peça
- Marca
- Modelo
- Número de série
- Busca de peças
- Exclusão de registros

---

# 🚀 Funcionalidades

✔ Cadastro de clientes  
✔ Cadastro de peças  
✔ Busca dinâmica em tabelas  
✔ Exclusão de registros  
✔ Interface responsiva com Bootstrap  
✔ Dark Mode 🌙  
✔ Sistema totalmente **offline**

---

# 🧠 Como funciona

O sistema utiliza o **LocalStorage do navegador** para armazenar os dados.

Estrutura de armazenamento:

```json
{
  "clientes": [],
  "pecas": []
}
```

Isso permite utilizar o sistema sem:

- banco de dados
- servidor
- conexão com internet

---

# 🖥️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura do sistema |
| CSS3 | Estilização |
| Bootstrap 5 | Layout responsivo |
| JavaScript | Lógica da aplicação |
| LocalStorage | Armazenamento de dados |

---

# 📂 Estrutura do Projeto

```
sistema-oficina/
│
└── index.html
```

Todo o sistema está concentrado em **um único arquivo HTML**, contendo:

- interface
- estilos
- scripts JavaScript

---

# ▶️ Como Executar o Projeto

### 1️⃣ Clone o repositório

```
git clone https://github.com/seuusuario/sistema-oficina.git
```

### 2️⃣ Abra o arquivo

```
index.html
```

### 3️⃣ O sistema será executado no navegador

Não é necessário:

- servidor
- banco de dados
- instalação de dependências

---

# 🧪 Exemplo de Uso

1️⃣ Acesse a aba **Clientes**  
2️⃣ Cadastre um cliente

```
Nome: João Silva
Email: joao@email.com
Telefone: 99999-9999
```

3️⃣ Acesse a aba **Peças**

```
Peça: Filtro de óleo
Marca: Bosch
Modelo: X123
Série: 2024
```

---

# 💡 Roadmap (Melhorias Futuras)

- [x] Sistema de login
- [x] Controle de estoque
- [x] Ordem de serviço
- [x] Relatórios da oficina
- [x] Exportação / Backup de dados
- [ ] Integração com banco de dados real
- [ ] Transformar em aplicativo desktop

---

# 👨‍💻 Autor

**Alessandro Arantes**

Desenvolvedor iniciante focado em:

- JavaScript
- Automação
- Sistemas simples para negócios

---

# 📜 Licença

Este projeto está sob licença **MIT**.

Uso livre para aprendizado e melhorias.
