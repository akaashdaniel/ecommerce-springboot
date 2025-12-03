# Minimal E-commerce Spring Boot App

This is a minimal, educational **E-commerce Web App** built with Spring Boot, Thymeleaf and H2 database.
It includes:
- Product listing
- Simple cart (session-based)
- Place order (stored in H2)

## Run locally
Requirements: Java 11+, Maven

```bash
mvn spring-boot:run
```

Visit http://localhost:8080

## To push to GitHub
```bash
git init
git add .
git commit -m "Initial commit - minimal ecommerce"
# create repo on GitHub and push
git remote add origin <your-git-url>
git branch -M main
git push -u origin main
```
