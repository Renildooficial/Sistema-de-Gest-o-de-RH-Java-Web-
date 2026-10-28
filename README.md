 <div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=005C84&height=200&section=header&text=👥%20SIGRH&fontSize=48&fontColor=ffffff&fontAlignY=35" width="100%" alt="SIGRH - Sistema Integrado de Gestão de Recursos Humanos" />

  <h2>Sistema Integrado de Gestão de Recursos Humanos</h2>

  <p align="center">
    <b>Sistema web desenvolvido em Java para a gestão integrada, moderna e eficiente dos recursos humanos de uma organização.</b>
  </p>

  <p align="center">
    <a href="#-sobre-o-projeto">Sobre</a> •
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-tecnologias-utilizadas">Tecnologias</a> •
    <a href="#-estrutura-do-projeto">Estrutura</a> •
    <a href="#-como-executar">Como Executar</a> •
    <a href="#-autores">Autor</a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17+" />
    <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Jakarta%20EE-1B6AC6?style=for-the-badge&logo=eclipseide&logoColor=white" alt="Jakarta EE" />
    <img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Apache Tomcat" />
    <img src="https://img.shields.io/badge/Arquitetura-MVC-8A2BE2?style=for-the-badge" alt="MVC" />
  </p>

</div>

---

## 📌 Sobre o Projeto

O **SIGRH — Sistema Integrado de Gestão de Recursos Humanos** é uma aplicação web desenvolvida em **Java**, utilizando tecnologias como **Jakarta EE, JSP, Servlets, MySQL e Apache Tomcat**, seguindo uma organização baseada no padrão arquitetural **MVC (Model-View-Controller)**.

O sistema foi concebido para centralizar e facilitar os principais processos relacionados à gestão de recursos humanos, permitindo organizar informações dos funcionários, acompanhar férias, gerir a folha de pagamento, administrar formações e controlar diferentes processos administrativos.

A plataforma procura melhorar a organização dos dados, facilitar o acesso à informação e apoiar as atividades dos departamentos de Recursos Humanos, Gestão e Finanças.

### 🎯 Objetivos

- Centralizar as informações dos funcionários numa única plataforma.
- Automatizar os processos administrativos de Recursos Humanos.
- Facilitar a gestão de férias e ausências.
- Organizar informações relacionadas com salários e pagamentos.
- Melhorar o acompanhamento das formações dos funcionários.
- Controlar o acesso às funcionalidades de acordo com o perfil do utilizador.
- Melhorar a organização, a integridade e a consulta dos dados.

---

## ✨ Funcionalidades

### 👥 Gestão de Funcionários e Acesso

- 👤 **Gestão de Funcionários**
  - Registo e consulta de funcionários.
  - Atualização dos dados pessoais e profissionais.
  - Organização das informações dos colaboradores.
  - Consulta de informações e histórico profissional.

- 🔐 **Autenticação e Controlo de Acesso**
  - Sistema de autenticação por utilizador.
  - Gestão de sessões.
  - Controlo de permissões por perfil.
  - Restrição de acesso às áreas protegidas.

- 🏢 **Gestão Administrativa**
  - Organização de processos administrativos.
  - Gestão de informações profissionais.
  - Acompanhamento de atos e registos administrativos.

### 🏖️ Gestão de Férias e Ausências

- 📅 **Gestão de Férias**
  - Registo e consulta de pedidos de férias.
  - Validação dos períodos solicitados.
  - Controlo das datas de início e fim.
  - Aprovação ou rejeição dos pedidos pelos responsáveis.
  - Acompanhamento dos dias de férias disponíveis.
  - Consideração dos dias de férias transitados de anos anteriores, conforme as regras do sistema.

- ⏱️ **Controlo de Datas**
  - Validação das datas introduzidas nos formulários.
  - Verificação da coerência entre datas de início e fim.
  - Prevenção de períodos inválidos.
  - Aplicação das regras de negócio aos pedidos de férias.

### 💰 Gestão Financeira e Salarial

- 💵 **Gestão Salarial**
  - Organização de informações salariais.
  - Consulta de registos relacionados com salários.
  - Apoio ao controlo administrativo da remuneração dos funcionários.

- 📊 **Gestão Financeira**
  - Consulta de informações para apoio à gestão.
  - Organização dos dados financeiros disponíveis.
  - Apoio aos processos administrativos relacionados com pagamentos.

### 🎓 Gestão de Formações

- 📚 **Formação dos Funcionários**
  - Registo de informações sobre formações.
  - Organização dos dados de capacitação profissional.
  - Consulta do histórico de formação, conforme as funcionalidades implementadas.

### 📈 Relatórios e Consultas

- Consulta de informações dos funcionários.
- Acompanhamento dos registos de férias.
- Consulta de informações salariais.
- Apoio à análise administrativa.
- Disponibilização de dados para acompanhamento da gestão dos recursos humanos.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função |
|---|---|
| ☕ **Java 17+** | Linguagem principal do sistema |
| 🌐 **Jakarta EE 10** | Plataforma para desenvolvimento de aplicações web empresariais |
| 📄 **JSP** | Construção de páginas web dinâmicas |
| ⚙️ **Servlets** | Processamento de requisições e controlo da aplicação |
| 🏗️ **MVC** | Organização da lógica, dos dados e da interface |
| 🗄️ **MySQL 8+** | Sistema de gestão da base de dados |
| 🔌 **JDBC** | Comunicação entre Java e MySQL |
| 🐱 **Apache Tomcat** | Servidor web e de execução da aplicação |
| 🎨 **HTML5** | Estrutura das páginas |
| 🎨 **CSS3** | Estilização da interface |
| ⚡ **JavaScript** | Interatividade no frontend |
| 🅱️ **Bootstrap** | Construção de interfaces responsivas |
| 🔐 **Sessões e filtros** | Apoio à autenticação e ao controlo de acesso |

---

## 📁 Estrutura do Projeto

A estrutura abaixo representa uma organização de referência para o projeto. Os nomes concretos dos diretórios e ficheiros podem variar de acordo com a versão existente no repositório.

<details>
<summary>👉 <b>Clique aqui para expandir a árvore de diretórios</b></summary>

```text
SIGRH/
│
├── src/
│   └── main/
│       │
│       ├── java/
│       │   └── com/
│       │       └── sigrh/
│       │           │
│       │           ├── config/
│       │           │   └── # Configurações da aplicação
│       │           │
│       │           ├── controller/
│       │           │   └── # Servlets e controlo das requisições
│       │           │
│       │           ├── dao/
│       │           │   └── # Acesso e operações na base de dados
│       │           │
│       │           ├── filter/
│       │           │   └── # Filtros de autenticação e autorização
│       │           │
│       │           ├── model/
│       │           │   └── # Entidades e modelos de dados
│       │           │
│       │           └── util/
│       │               └── # Classes e métodos utilitários
│       │
│       └── webapp/
│           │
│           ├── WEB-INF/
│           │   └── # Configurações internas da aplicação
│           │
│           ├── css/
│           │   └── # Folhas de estilo
│           │
│           ├── js/
│           │   └── # Scripts JavaScript
│           │
│           ├── uploads/
│           │   └── # Ficheiros enviados, se aplicável
│           │
│           └── *.jsp
│               # Páginas da aplicação
│
├── database/
│   └── # Scripts SQL, se existentes
│
├── db.properties
│   # Configurações da ligação à base de dados
│
├── pom.xml
│   # Dependências e configurações do Maven
│
└── README.md
    # Documentação do projeto
```

</details>

---

## ⚙️ Como Executar

### 📋 Pré-requisitos

Antes de executar o sistema, certifique-se de que tem instalado:

- ☕ **Java JDK 17 ou superior**
- 🐱 **Apache Tomcat compatível com Jakarta EE 10**
- 🗄️ **MySQL Server 8 ou superior**
- 📦 **Apache Maven**
- 💻 **Eclipse IDE for Enterprise Java and Web Developers**, IntelliJ IDEA ou IDE compatível
- 🌐 Um navegador web atualizado

> **Nota:** O projeto utiliza Jakarta EE 10. Confirme a versão do Tomcat e as dependências configuradas no `pom.xml` antes de executar a aplicação.

### 🚀 1. Clonar o Repositório

Abra o terminal e execute:

```bash
git clone https://github.com/Renildooficial/SIGRH.git
```

Entre na pasta do projeto:

```bash
cd SIGRH
```

> Se o repositório tiver outro nome ou endereço, substitua o URL pelo endereço correto do projeto.

### 📥 2. Importar o Projeto na IDE

No Eclipse, siga os passos:

```text
File
   ↓
Import
   ↓
Maven
   ↓
Existing Maven Projects
```

Selecione a pasta do projeto e clique em **Finish**.

Aguarde o Maven descarregar e configurar as dependências.

### 🗄️ 3. Criar a Base de Dados

Abra o MySQL Workbench, phpMyAdmin ou outro cliente MySQL.

Utilize o script SQL disponibilizado no projeto, caso exista.

A base de dados utilizada pelo sistema é:

```text
sigrh
```

Se o projeto possuir um ficheiro SQL com outro nome, verifique o conteúdo antes de o importar para evitar conflitos com bases de dados existentes.

### 🔐 4. Configurar a Ligação com o MySQL

Localize o ficheiro `db.properties` e configure os parâmetros de ligação de acordo com o ambiente local.

Exemplo ilustrativo:

```properties
db.url=jdbc:mysql://localhost:3306/sigrh
db.user=root
db.password=sua_senha
```

> ⚠️ Os nomes das propriedades devem corresponder aos que são utilizados pela classe de conexão do projeto. Não publique palavras-passe reais no repositório.

### 🐱 5. Configurar o Apache Tomcat

Na IDE, abra a vista **Servers** e adicione uma instalação do Apache Tomcat compatível com as dependências do sistema.

Associe o projeto ao servidor e confirme que a configuração de execução está correta.

### ▶️ 6. Executar o Sistema

No Eclipse, clique com o botão direito sobre o projeto e selecione:

```text
Run As
   ↓
Run on Server
```

Selecione o servidor configurado e aguarde o arranque da aplicação.

Em alternativa, se o projeto estiver configurado para gerar um ficheiro WAR, poderá construí-lo através do Maven:

```bash
mvn clean package
```

O ficheiro gerado poderá ser implantado no servidor, de acordo com a configuração do projeto.

### 🌐 7. Aceder à Aplicação

Depois de o servidor iniciar, abra o navegador e aceda ao endereço correspondente à configuração local.

Exemplo:

```text
http://localhost:8080/SIGRH/
```

> 💡 O endereço, a porta e o caminho inicial dependem da configuração do Tomcat e do nome do contexto da aplicação.

---

## 🏗️ Arquitetura do Sistema

O SIGRH organiza as responsabilidades da aplicação segundo o padrão **MVC (Model-View-Controller)**, complementado pelo acesso à base de dados através de classes DAO, quando aplicável.

```text
                 ┌──────────────────────┐
                 │      Utilizador      │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │         View         │
                 │     JSP / HTML       │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │      Controller      │
                 │       Servlets       │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │        Model         │
                 │   Entidades / Regras │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │         DAO          │
                 │         JDBC         │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │        MySQL         │
                 │      Database        │
                 └──────────────────────┘
```

### 🔄 Fluxo básico

```text
Utilizador
    ↓
Página JSP
    ↓
Servlet
    ↓
Regras de negócio
    ↓
DAO / JDBC
    ↓
Base de dados MySQL
    ↓
DAO
    ↓
Servlet
    ↓
Página JSP
    ↓
Utilizador
```

---

## 🔒 Segurança

A segurança é um componente importante na gestão dos recursos humanos, uma vez que o sistema pode tratar dados pessoais, profissionais e salariais.

Entre os mecanismos considerados na aplicação estão:

- 🔐 Autenticação de utilizadores.
- 👤 Gestão de sessões.
- 🛡️ Filtros para controlo de acesso.
- 🔑 Permissões associadas aos perfis dos utilizadores.
- 🚫 Restrição de acesso às funcionalidades autorizadas.
- 🗄️ Acesso estruturado à base de dados.
- 🔒 Proteção das credenciais de ligação.

Os mecanismos efetivamente disponíveis dependem da implementação e da configuração da versão do sistema.

---

## 👤 Perfis de Utilizador

O sistema está orientado para a gestão de diferentes responsabilidades organizacionais, de acordo com os perfis configurados na aplicação.

| Perfil | Responsabilidade |
|---|---|
| 👨‍💼 **Administrador** | Gestão geral e configuração do sistema |
| 👥 **Recursos Humanos** | Gestão dos funcionários e processos de RH |
| 🏢 **Gestão** | Acompanhamento e aprovação de processos administrativos |
| 💰 **Finanças** | Consulta e gestão das informações financeiras autorizadas |
| 👤 **Funcionário** | Consulta das informações e utilização das funcionalidades disponibilizadas ao seu perfil |

As permissões específicas devem corresponder às regras de autorização implementadas no código.

---

## 📌 Possíveis Melhorias Futuras

Entre as possíveis evoluções do SIGRH encontram-se:

- 📱 Desenvolvimento de uma aplicação móvel Android.
- 🔔 Implementação de notificações automáticas.
- 📧 Envio de notificações por e-mail.
- 📊 Dashboard com gráficos e indicadores de gestão.
- 📄 Exportação de relatórios para PDF.
- 📥 Exportação de dados para Excel.
- 🔐 Reforço da recuperação de palavras-passe.
- ☁️ Implantação em ambiente cloud.
- 📅 Aperfeiçoamento da validação de datas e períodos administrativos.
- 🏖️ Melhoria do controlo de férias acumuladas e transitadas.
- 📈 Produção de estatísticas sobre funcionários, férias, formações e salários.
- 🧾 Auditoria das operações realizadas pelos utilizadores.

---

## 👨‍💻 Autor

### Renildo Cândido

**Estudante de Informática | Java & Web Developer**

- **GitHub:** [Renildooficial](https://github.com/Renildooficial)
- **LinkedIn:** [Renildo Cândido](https://www.linkedin.com/in/renildo-candido-2b8829413/)

---

## 📄 Licença

Este projeto foi desenvolvido para fins **académicos e educacionais**.

A utilização, distribuição ou modificação do código deve respeitar a licença aplicável ao repositório.

---

<div align="center">

### 👥 SIGRH

**Sistema Integrado de Gestão de Recursos Humanos**

Desenvolvido com Java, Jakarta EE, MySQL e tecnologias web.

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=005C84&height=120&section=footer" width="100%" alt="SIGRH Footer" />

</div>
