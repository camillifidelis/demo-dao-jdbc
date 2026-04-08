<div align="center">
  <h1 align="center">
    <code>─── DEMO-DAO-JDBC ───</code>
  </h1>
  <p>Projeto Java para demonstração do padrão DAO (Data Access Object) <br> utilizando JDBC puro para integração com banco de dados MySQL.</p>
</div>

## 🛠 Tecnologias
- **Java** (JDK 17+)
- **JDBC** 
- **MySQL** 
- **MySQL Connector/J** 
- **Git/GitHub**

## ⚙️ Funcionalidades
- Padrão **DAO** para isolamento da camada de acesso a dados
- Implementação de operações CRUD (FindById, FindAll, Insert, Update, Delete)
- Gerenciamento manual de conexões com `DB.java`
- Tratamento de exceções personalizadas (`DbException`, `DbIntegrityException`)
- Mapeamento manual de ResultSet para objetos Java

## 🟣 Como executar (local)

### 1) Pré-requisitos
- Java JDK 17 instalado.
- Servidor MySQL rodando.
- Banco de dados criado.

### 2) Clonar o repositório
No terminal:

```bash
git clone [https://github.com/camillifidelis/demo-dao-jdbc.git](https://github.com/camillifidelis/demo-dao-jdbc.git)
cd demo-dao-jdbc
```
### 3) Configurar a conexão

Crie ou edite o arquivo db.properties na raiz do projeto com as suas credenciais locais:
```bash
user=seu_usuario
password=sua_senha
dburl=jdbc:mysql://localhost:3306/coursejdbc
useSSL=false
```

### 4) Executar o projeto
Como este é um projeto Java puro, você pode executá-lo diretamente pela sua IDE através da classe principal:
`application/Program.java`

### 🎓 Créditos
Este projeto faz parte do curso Java Completo do professor Nelio Alves. O foco principal é entender como o Java se comunica com bancos de dados relacionais em baixo nível, sem o uso de frameworks de persistência como o Hibernate, permitindo total controle sobre as queries SQL.

---
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/camillifidelis/cami-projeto-mongo/main/assets/logo-dark.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/camillifidelis/cami-projeto-mongo/main/assets/logo-light.svg">
    <img alt="CamiDev Logo" src="https://raw.githubusercontent.com/camillifidelis/cami-projeto-mongo/main/assets/logo-dark.svg" width="300">
  </picture>
</div>
