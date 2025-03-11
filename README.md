# Screenmatch

## 📌 Descrição
Screenmatch é um projeto Java utilizando Spring Boot para consumir dados da API OMDB e converter os resultados em um modelo de dados estruturado. 

## 🛠️ Tecnologias
- Java 17
- Spring Boot
- API OMDB

## 🚀 Como executar o projeto
### 📦 Pré-requisitos
Certifique-se de ter instalado em sua máquina:
- Java 17+
- Maven

### ▶️ Rodando o projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/screenmatch.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd screenmatch
   ```
3. Execute o projeto com:
   ```bash
   mvn spring-boot:run
   ```

## 📂 Estrutura do Projeto
```
 screenmatch/
 ├── src/main/java/br/com/alura/screenmatch
 │   ├── model/              # Modelos de dados
 │   ├── service/            # Classes de serviço
 │   ├── ScreenmatchApplication.java  # Classe principal
 ├── pom.xml                 # Configuração do Maven
```

## 🔗 API Utilizada
O projeto consome dados da API OMDB. Exemplo de requisição:
```
https://www.omdbapi.com/?t=gilmore+girls&apikey=6585022c
```

## ✨ Funcionalidades
- Consumo de API externa (OMDB)
- Conversão de JSON para objetos Java
