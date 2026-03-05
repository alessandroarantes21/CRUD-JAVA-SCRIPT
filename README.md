# 🚛 Sistema Oficina V5

Sistema simples de gestão para oficinas mecânicas desenvolvido em
**HTML, JavaScript e LocalStorage**.

Este projeto demonstra a criação de um **CRUD completo em uma única
página (Single Page Application)**, permitindo o gerenciamento de
clientes, peças, ordens de serviço e relatórios.

------------------------------------------------------------------------

# 📦 Funcionalidades

## 🔐 Autenticação

-   Login de usuário
-   Cadastro de novos usuários
-   Sessão simples utilizando LocalStorage

------------------------------------------------------------------------

## 📊 Dashboard

Painel inicial com indicadores do sistema:

-   Total de clientes
-   Total de peças
-   Total de serviços realizados
-   Faturamento total

Inclui também **gráfico de faturamento** usando Chart.js.

------------------------------------------------------------------------

## 👤 Cadastro de Clientes

Gerenciamento completo de clientes da oficina.

Funções: - Cadastrar cliente - Editar cliente - Excluir cliente - Buscar
cliente em tempo real

Campos: - Nome - Email - Telefone

------------------------------------------------------------------------

## 🔧 Cadastro de Peças

Controle básico de estoque da oficina.

Funções: - Cadastrar peça - Editar peça - Excluir peça

Campos: - Nome da peça - Marca - Modelo - Quantidade em estoque - Preço

------------------------------------------------------------------------

## 🧾 Ordem de Serviço

Registro de serviços realizados na oficina.

Campos: - Cliente - Descrição do serviço - Valor do serviço - Data
automática

Funções: - Criar ordem de serviço - Visualizar lista de serviços -
Imprimir ordem de serviço

------------------------------------------------------------------------

## 📈 Relatório Financeiro

Tela com resumo geral do sistema:

-   Total de clientes
-   Total de peças
-   Total de serviços
-   Faturamento geral

------------------------------------------------------------------------

## 📊 Gráfico de Faturamento

Implementado com **Chart.js**, exibindo o faturamento total diretamente
no dashboard.

------------------------------------------------------------------------

## 💾 Backup e Restauração

O sistema permite:

### Exportar Backup

Baixa um arquivo:

backup_oficina.json

Contendo: - clientes - peças - ordens de serviço

### Restaurar Backup

Importa novamente os dados do sistema através do arquivo JSON.

------------------------------------------------------------------------

# 🧱 Estrutura do Projeto

sistema-oficina/

index.html\
README.md

Todo o sistema está concentrado no arquivo:

index.html

Que contém: - HTML (interface) - CSS (estilo) - JavaScript (lógica do
sistema)

------------------------------------------------------------------------

# 💻 Tecnologias Utilizadas

-   HTML5
-   CSS3
-   JavaScript
-   Bootstrap 5
-   Chart.js
-   LocalStorage

------------------------------------------------------------------------

# 🚀 Como Executar o Projeto

## 1. Baixar o projeto

Faça download do projeto ou clone o repositório.

## 2. Abrir no VS Code

Abra a pasta do projeto:

File → Open Folder

## 3. Executar

Abra o arquivo:

index.html

Ou utilize a extensão **Live Server** no VS Code.

------------------------------------------------------------------------

# 🧠 Conceitos Utilizados

Este projeto demonstra vários conceitos importantes:

-   CRUD com JavaScript
-   Manipulação do DOM
-   Armazenamento com LocalStorage
-   Single Page Application (SPA)
-   Dashboard com gráficos
-   Exportação de dados JSON

------------------------------------------------------------------------

# 🔮 Melhorias Futuras

Possíveis evoluções do sistema:

-   Cadastro de caminhões
-   Controle automático de estoque
-   Geração de PDF da ordem de serviço
-   Gráfico de faturamento mensal
-   Sistema multiusuário
-   Banco de dados MySQL
-   Backend com Node.js

------------------------------------------------------------------------

# 📜 Licença

Projeto livre para estudo e aprendizado.

------------------------------------------------------------------------

# 👨‍💻 Autor

Projeto criado como estudo para desenvolvimento de um **mini ERP de
oficina mecânica**.
