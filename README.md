<div align="center">

# 👥 SIGRH

## Sistema Integrado de Gestão de Recursos Humanos

<p>
  Sistema web moderno para gestão integrada de funcionários, férias, folha de pagamento, formações, notificações e processos administrativos.
</p>

<p>
  Desenvolvido com tecnologias Java para oferecer uma solução robusta, segura e escalável para a gestão de Recursos Humanos.
</p>

<br>

[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)](https://adoptium.net/)
[![Jakarta EE](https://img.shields.io/badge/Jakarta%20EE-10-007396?style=for-the-badge\&logo=jakartaee\&logoColor=white)](https://jakarta.ee/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)](https://www.mysql.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge\&logo=bootstrap\&logoColor=white)](https://getbootstrap.com/)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](LICENSE)

<br>



</div>

---

# 📌 Índice

* [📖 Sobre o Projeto](#-sobre-o-projeto)
* [🚀 Funcionalidades](#-funcionalidades)
* [🛠️ Tecnologias](#️-tecnologias-utilizadas)
* [📁 Estrutura do Projeto](#-estrutura-do-projeto)
* [⚙️ Pré-requisitos](#️-pré-requisitos)
* [🚀 Instalação](#-instalação-e-configuração)
* [👤 Perfis de Utilizador](#-perfis-de-utilizador)
* [📦 Módulos](#-módulos-do-sistema)
* [📡 API](#-api-endpoints)
* [📸 Screenshots](#-screenshots)
* [🤝 Contribuição](#-contribuição)
* [📄 Licença](#-licença)
* [📞 Contacto](#-contacto)

---

# 📖 Sobre o Projeto

O **SIGRH — Sistema Integrado de Gestão de Recursos Humanos** é uma aplicação web desenvolvida para centralizar e automatizar os principais processos de gestão de pessoas dentro de uma organização.

O sistema foi projetado para oferecer uma experiência moderna, intuitiva, responsiva e segura, permitindo que diferentes perfis de utilizadores tenham acesso às funcionalidades de acordo com as suas permissões.

### 🎯 Principais objetivos

* 👥 Centralizar a gestão de funcionários
* 🏖️ Automatizar processos de férias
* 💰 Gerir a folha de pagamento
* 📚 Controlar formações e qualificações
* 📊 Gerar relatórios administrativos e financeiros
* 🔔 Enviar notificações aos utilizadores
* 🔐 Garantir segurança e controlo de acessos
* 📋 Registar ações através de auditoria

---

# 🚀 Funcionalidades

## 👥 Gestão de Funcionários

* Cadastro de funcionários
* Edição e atualização de dados
* Gestão de dados pessoais
* Upload de fotografia do funcionário
* Gestão de agregados familiares
* Formação académica e profissional
* Histórico de cargos e nomeações
* Pesquisa e filtros avançados
* Controlo de estado do funcionário

---

## 🏖️ Gestão de Férias

* Solicitação de férias pelo funcionário
* Aprovação ou rejeição de solicitações
* Gestão do plano anual de férias
* Calendário visual
* Controlo do saldo de férias
* Check-in e Check-out
* Cancelamento de solicitações
* Acompanhamento do histórico de férias

---

## 💰 Folha de Pagamento

* Processamento mensal da folha
* Gestão de salários
* Cálculo de impostos e descontos
* Gestão de subsídios
* Histórico de pagamentos
* Estados da folha de pagamento

```text
PENDENTE
   ↓
PROCESSADO
   ↓
PAGO
```

* Relatórios financeiros
* Consulta de detalhes da folha

---

## 📚 Gestão de Formações

* Registo de formações
* Histórico académico e profissional
* Gestão de qualificações
* Associação de formações aos funcionários
* Consulta e filtros

---

## 🔔 Sistema de Notificações

* Notificações em tempo real
* Contador de notificações não lidas
* Marcação individual como lida
* Marcação de todas como lidas
* Diferentes tipos de notificações

```text
ℹ️ INFO
✅ SUCESSO
⚠️ AVISO
❌ ERRO
```

Exemplos de eventos:

* Login realizado
* Solicitação de férias
* Aprovação ou rejeição
* Processamento da folha
* Nova formação
* Atualizações importantes

---

## 📊 Dashboard

O sistema possui dashboards personalizados de acordo com o perfil do utilizador.

### Funcionalidades

* 📈 Estatísticas em tempo real
* 👥 Total de funcionários
* 🏖️ Funcionários em férias
* 📋 Solicitações pendentes
* 💰 Informações financeiras
* 📊 Gráficos interativos
* 🔔 Últimas atividades

---

## 📈 Relatórios

O SIGRH permite gerar relatórios relacionados com:

* Funcionários por setor
* Estado dos funcionários
* Férias
* Formações
* Nomeações
* Informações financeiras
* Folha de pagamento

### Exportação

* 📄 PDF
* 📊 Excel

---

## 🔐 Segurança

A segurança é uma das principais características do sistema.

### Recursos implementados

* 🔑 Autenticação de utilizadores
* 🔒 Senhas protegidas com BCrypt
* 📧 Recuperação de senha por e-mail
* 👤 Controlo de acesso por perfil
* 🛡️ Gestão de sessão
* 📝 Auditoria das ações
* 🚫 Restrição de páginas não autorizadas

---

# 🛠️ Tecnologias Utilizadas

## ⚙️ Backend

| Tecnologia         | Versão | Descrição                     |
| ------------------ | ------ | ----------------------------- |
| ☕ Java             | 17+    | Linguagem principal           |
| 🌐 Jakarta EE      | 10     | Plataforma empresarial        |
| 🔗 Jakarta Servlet | 6.0    | Desenvolvimento de Servlets   |
| 📄 JSP             | 3.1    | Interface dinâmica            |
| 🗄️ JDBC           | —      | Comunicação com base de dados |
| 🐬 MySQL Connector | 8.0+   | Driver MySQL                  |
| 🔐 BCrypt          | 0.4    | Hash de senhas                |
| 📦 GSON            | 2.10+  | Manipulação de JSON           |
| 📝 Log4j           | 2.20+  | Sistema de logs               |

---

## 🎨 Frontend

| Tecnologia      | Descrição             |
| --------------- | --------------------- |
| 🌐 HTML5        | Estrutura das páginas |
| 🎨 CSS3         | Estilização           |
| ⚡ JavaScript    | Interatividade        |
| 🅱️ Bootstrap 5 | Framework CSS         |
| 🎯 Font Awesome | Ícones                |
| 📊 Chart.js     | Gráficos              |
| 🔤 Google Fonts | Tipografia            |

---

## 🗄️ Base de Dados

* **MySQL 8.0+**
* Modelo relacional
* Integridade referencial
* Chaves estrangeiras
* Índices otimizados
* Estrutura organizada para escalabilidade

---

# 📁 Estrutura do Projeto

```text
sigrh/
│
├── src/
│   └── main/
│
│       ├── java/
│       │   └── com/sigrh/
│       │
│       │       ├── controller/
│       │       │   └── Servlets e Controllers
│       │
│       │       ├── model/
│       │       │   └── Entidades do sistema
│       │
│       │       ├── dao/
│       │       │   └── Acesso à base de dados
│       │
│       │       ├── service/
│       │       │   └── Regras de negócio
│       │
│       │       ├── filter/
│       │       │   └── Filtros e autenticação
│       │
│       │       ├── exception/
│       │       │   └── Exceções personalizadas
│       │
│       │       └── util/
│       │           └── Classes utilitárias
│       │
│       ├── resources/
│       │   ├── db.properties
│       │   └── database/
│       │       └── schema.sql
│       │
│       └── webapp/
│
│           ├── WEB-INF/
│           │   └── views/
│           │
│           │       ├── admin/
│           │       ├── rh/
│           │       ├── gestor/
│           │       ├── financeiro/
│           │       ├── funcionario/
│           │       ├── auth/
│           │       └── layout/
│           │
│           ├── css/
│           ├── js/
│           └── uploads/
│
├── pom.xml
│
└── README.md
```

---

# ⚙️ Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

| Software         | Versão |
| ---------------- | ------ |
| ☕ Java JDK       | 17+    |
| 🐱 Apache Tomcat | 10+    |
| 🐬 MySQL         | 8.0+   |
| 📦 Maven         | 3.8+   |
| 🌳 Git           | 2.0+   |

### Links úteis

* [Java / Adoptium](https://adoptium.net/)
* [Apache Tomcat](https://tomcat.apache.org/)
* [MySQL](https://www.mysql.com/)
* [Apache Maven](https://maven.apache.org/)
* [Git](https://git-scm.com/)

---

# 🚀 Instalação e Configuração

## 1️⃣ Clonar o Repositório

```bash
git clone https://github.com/Renildooficial/sigrh.git
```

Entre na pasta do projeto:

```bash
cd sigrh
```

---

## 2️⃣ Configurar a Base de Dados

Crie a base de dados:

```sql
CREATE DATABASE sigrh
CHARACTER SET utf8mb4
COLLATE utf8mb4_unicode_ci;
```

Depois importe o ficheiro:

```bash
mysql -u root -p sigrh < src/main/resources/database/schema.sql
```

---

## 3️⃣ Configurar a Ligação à Base de Dados

Configure o ficheiro:

```text
src/main/resources/db.properties
```

Exemplo:

```properties
db.url=jdbc:mysql://localhost:3306/sigrh?useSSL=false&serverTimezone=Africa/Maputo
db.username=root
db.password=sua_senha
```

> ⚠️ Nunca publique palavras-passe reais no GitHub.

---

## 4️⃣ Compilar o Projeto

```bash
mvn clean package
```

---

## 5️⃣ Fazer Deploy no Tomcat

Copie o ficheiro `.war` gerado:

```text
target/sigrh.war
```

Para a pasta:

```text
tomcat/webapps/
```

---

## 6️⃣ Iniciar o Tomcat

### Windows

```bash
startup.bat
```

### Linux / macOS

```bash
./startup.sh
```

---

## 7️⃣ Aceder ao Sistema

Abra o navegador:

```text
http://localhost:8080/sigrh
```

---

# 👤 Perfis de Utilizador

## 🔴 ADMIN

Administrador do sistema.

### Permissões

* Acesso total
* Gestão de utilizadores
* Configurações
* Auditoria
* Relatórios
* Gestão de todos os módulos

---

## 🟢 RH

Recursos Humanos.

### Permissões

* Gestão de funcionários
* Gestão de formações
* Gestão de nomeações
* Gestão de férias
* Plano anual de férias
* Relatórios de RH

---

## 🟡 GESTOR

Gestor ou responsável por funcionários.

### Permissões

* Visualização de funcionários
* Aprovação de solicitações
* Gestão do plano de férias
* Relatórios gerenciais

---

## 🟣 FINANCEIRO

Responsável pela área financeira.

### Permissões

* Dashboard financeiro
* Processamento da folha
* Gestão de salários
* Gestão de pagamentos
* Relatórios financeiros

---

## 🔵 FUNCIONÁRIO

Funcionário da organização.

### Permissões

* Visualizar os próprios dados
* Solicitar férias
* Consultar saldo de férias
* Consultar formações
* Consultar nomeações
* Alterar palavra-passe

---

# 📦 Módulos do Sistema

## 🔐 Autenticação

```text
/auth
```

Principais funcionalidades:

* Login
* Logout
* Recuperação de senha
* Recuperação através de código
* Controlo de sessão

---

## 📊 Dashboard

```text
/dashboard
```

Funcionalidades:

* Estatísticas
* Gráficos
* Informações em tempo real
* Dashboard personalizado por perfil

---

## 👥 Funcionários

```text
/funcionarios
```

Funcionalidades:

```text
GET     /                 → Listar funcionários
GET     /novo             → Novo funcionário
POST    /                 → Guardar funcionário
GET     /editar/{id}      → Editar funcionário
POST    /excluir          → Excluir funcionário
POST    /alterar-status   → Alterar estado
```

---

## 🏖️ Férias

```text
/ferias
```

Funcionalidades:

```text
GET     /              → Listar solicitações
GET     /pendentes     → Solicitações pendentes
POST    /solicitar     → Nova solicitação
POST    /aprovar       → Aprovar férias
POST    /rejeitar      → Rejeitar férias
POST    /checkout      → Iniciar férias
POST    /checkin       → Finalizar férias
POST    /cancelar      → Cancelar solicitação
```

---

## 💰 Financeiro

```text
/financeiro
```

Funcionalidades:

```text
GET     /dashboard
GET     /folha-pagamento
POST    /processar-folha
GET     /folha-detalhes/{id}
POST    /folha-pagar
POST    /folha-cancelar
```

---

## 📚 Formações

```text
/formacoes
```

Funcionalidades:

```text
GET     /
POST    /
POST    /excluir
```

---

## 🔔 Notificações

```text
/notificacoes
```

Funcionalidades:

```text
GET     /
GET     /api
POST    /marcar-lida
POST    /marcar-todas
```

---

# 📡 API Endpoints

## 🔔 Notificações

### Endpoint

```http
GET /notificacoes/api
```

### Resposta

```json
[
  {
    "id": 1,
    "titulo": "Novo Login",
    "mensagem": "Login realizado com sucesso",
    "tipo": "INFO",
    "icone": "fa-info-circle",
    "lida": false,
    "dataCriacao": "2026-09-07 16:47:10"
  }
]
```

---

## 🔢 Contagem de Notificações

```http
GET /notificacoes/contar
```

### Resposta

```json
{
  "success": true,
  "count": 3
}
```

---

## 🏖️ Saldo de Férias

```http
GET /ferias/saldo?idFuncionario=1
```

### Resposta

```json
{
  "success": true,
  "saldo": 15
}
```

---

# 📸 Screenshots

> 🚧 **Em breve serão adicionadas imagens reais do sistema.**

## 📊 Dashboard

<img src="https://via.placeholder.com/900x450/2563EB/FFFFFF?text=Dashboard+SIGRH" alt="Dashboard SIGRH" width="100%"/>

## 👥 Gestão de Funcionários

<img src="https://via.placeholder.com/900x450/16A34A/FFFFFF?text=Gest%C3%A3o+de+Funcion%C3%A1rios" alt="Gestão de Funcionários" width="100%"/>

## 🏖️ Gestão de Férias

<img src="https://via.placeholder.com/900x450/F59E0B/FFFFFF?text=Gest%C3%A3o+de+F%C3%A9rias" alt="Gestão de Férias" width="100%"/>

## 💰 Folha de Pagamento

<img src="https://via.placeholder.com/900x450/DC2626/FFFFFF?text=Folha+de+Pagamento" alt="Folha de Pagamento" width="100%"/>

---

# 🗺️ Roadmap

* [x] Sistema de autenticação
* [x] Gestão de funcionários
* [x] Gestão de férias
* [x] Gestão de formações
* [x] Sistema de notificações
* [x] Dashboard
* [x] Controlo de permissões
* [x] Auditoria
* [ ] Exportação avançada para PDF
* [ ] Exportação avançada para Excel
* [ ] Melhorias no módulo financeiro
* [ ] Notificações por e-mail
* [ ] Melhorias na responsividade
* [ ] API REST completa

---

# 🤝 Contribuição

Contribuições são bem-vindas! 🚀

Para contribuir:

### 1. Faça um Fork

Crie uma cópia do projeto na sua conta.

### 2. Crie uma Branch

```bash
git checkout -b feature/nova-feature
```

### 3. Faça as Alterações

Implemente a nova funcionalidade.

### 4. Faça o Commit

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

### 5. Envie para o GitHub

```bash
git push origin feature/nova-feature
```

### 6. Abra um Pull Request

Envie as suas alterações para análise.

---

# 📄 Licença

Este projeto está sob a licença **MIT**.

Consulte o ficheiro:

```text
LICENSE
```

Para mais informações.

---

# 👨‍💻 Desenvolvedor

<div align="center">

## Renildo Cândido

💻 **Estudante de Licenciatura em Informática**
🚀 **Java & Web Developer**
🇲🇿 **Moçambique**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-RenildoOficial-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Renildooficial)

</div>

---

# 🙏 Agradecimentos

Agradecimentos às tecnologias e ferramentas que tornam este projeto possível:

* [Java](https://www.java.com/)
* [Jakarta EE](https://jakarta.ee/)
* [Bootstrap](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [Chart.js](https://www.chartjs.org/)
* [MySQL](https://www.mysql.com/)
* [Apache Tomcat](https://tomcat.apache.org/)
* [Maven](https://maven.apache.org/)

---

<div align="center">

### ⭐ Se este projeto foi útil, considere deixar uma estrela!

<br>

**SIGRH — Sistema Integrado de Gestão de Recursos Humanos**

Feito com ❤️ e ☕ por **Renildo Cândido**

© 2026

</div>
