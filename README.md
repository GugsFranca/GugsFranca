<h1 align="center"> 
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExY3h1cHFraWY1eXZ6dDd2b2E4OGVvOWx5N3B4NWV2eXh3YjB0d3J3diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPEqDGUULpEU0aQ/giphy.gif" width="50px"> 
  Olá, sou Gustavo de França
</h1>

<h3 align="center">
  Backend Developer focado em construir sistemas escaláveis com Java & Spring Boot ☕
</h3>

---

### 🚀 Meu Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

---

### 💡 O Que Faço Bem

- Desenho **APIs RESTful** eficientes com Spring Boot
- Crio **microsserviços** resilientes e desacoplados
- **Containerizo** aplicações para deploy consistente
- Otimizo performance com **Hibernate** e queries SQL
- Automatizo fluxos com **GitHub Actions** e Docker

---

### 📊 Coding Activity

<div align="center">
  
![Estatísticas](https://github-readme-stats.vercel.app/api?username=GugsFranca&show_icons=true&theme=blueberry&hide=stars,prs)

![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=GugsFranca&layout=compact&theme=blueberry)

</div>

---

### 🐳 Meu Dockerfile Favorito

```dockerfile
FROM eclipse-temurin:17-jdk-alpine as build
WORKDIR /app
COPY mvnw .
COPY .mvn .mvn
COPY pom.xml .
RUN ./mvnw dependency:go-offline
COPY src src
RUN ./mvnw package -DskipTests

FROM eclipse-temurin:17-jre-alpine
COPY --from=build /app/target/*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]
````
### 📬 Vamos Conversar?
<p align="center"> <a href="https://www.linkedin.com/in/gustavo-fonseca-384a91206/"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"> </a> 
  <a href="mailto:gustavoffonsec4@gmail.com"> <img src="https://img.shields.io/badge/Email-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white"> </a> 
</p>
<p align="center"> <i>"Primeiro resolva o problema, depois escreva o código" - John Johnson</i> 🛠️ </p>
