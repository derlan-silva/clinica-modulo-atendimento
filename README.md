\# 🏥 Sistema de Clínica Médica - Módulo de Atendimento



\## 👥 Integrantes do Grupo

\* \*\*Lucas Silveira\*\* - (Responsável pelo Módulo de Atendimento)

\* \*\*João Gabriel\*\* - (Responsável pelo Módulo de Agendamento)

\* \*\*Geovani\*\* - (Responsável pelo Módulo Administrativo)



\---



\## 📌 Sobre o Subprojeto

Este módulo é responsável por toda a inteligência e gerenciamento do \*\*Atendimento Médico\*\* da clínica (prontuários, anamnese, registro de sintomas e receitas médicas), funcionando de maneira independente.



\### 🛠️ Tecnologias Utilizadas

\* \*\*Java 17\*\* (Linguagem principal)

\* \*\*Spring Boot 3.5.x\*\* (Framework do projeto)

\* \*\*Maven\*\* (Gerenciador de dependências)

\* \*\*PostgreSQL\*\* (Banco de dados relacional)

\* \*\*YAML (`application.yml`)\*\* (Formato de configuração)



\---



\## ⚙️ Configuração do Banco de Dados



Para que o módulo funcione localmente, as configurações do PostgreSQL devem ser inseridas no arquivo `src/main/resources/application.yml`:



```yaml

spring:

&#x20; datasource:

&#x20;   url: jdbc:postgresql://localhost:5432/clinica\_db

&#x20;   username: seu\_usuario

&#x20;   password: sua\_senha

&#x20; jpa:

&#x20;   hibernate:

&#x20;     ddl-auto: update

&#x20;   show-sql: true

