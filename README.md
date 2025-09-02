# ⚙️ Lista de Tarefas – API Backend

Este repositório implementa a **API REST** responsável por centralizar as regras de negócio e o gerenciamento de dados do sistema de **Lista de Tarefas**.  
Ela funciona como o "coração" da aplicação full-stack, sendo consumida por dois clientes distintos:  

- 🌐 **Interface Web** desenvolvida em Angular  
- 💻 **Aplicação Desktop** criada em JavaFX  

---

## 🏗️ Estrutura da Solução

A aplicação foi organizada em três módulos independentes, que se comunicam por meio de endpoints REST. Essa separação permite maior flexibilidade e manutenibilidade.

1. **Backend (este projeto)**  
   - Desenvolvido em **Java + Spring Boot**  
   - Implementa operações **CRUD** (Criar, Ler, Atualizar, Excluir)  
   - Utiliza **H2 Database** em memória para simplificar o desenvolvimento  

2. **Frontend Web**  
   - Construído com **Angular**  
   - 🔗 [lista-tarefas-web](https://github.com/iguibarbosa/listadetarefas-WEB)

---

## 🚀 Tecnologias

- Java 21  
- Spring Boot 3  
- Spring Data JPA  
- Maven  
- H2 Database  

---

## ▶️ Executando o projeto

### Pré-requisitos
- Ter instalado o **JDK 21**

### Passos
```bash
# Clone este repositório
git clone https://github.com/RafaelSilvaGomes/lista-tarefas-api.git

# Abra o projeto em sua IDE (IntelliJ, VS Code, Eclipse, etc.)

# Execute a classe principal
ListaTarefasApiApplication.java
