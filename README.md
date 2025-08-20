# 📚 LiterAlura Challenge

Aplicación de consola desarrollada en **Java 17 + Spring Boot + PostgreSQL**, que permite consultar libros y autores desde la API pública [Gutendex](https://gutendex.com/) y almacenarlos en una base de datos.  

Este proyecto forma parte del **Challenge Back-End de Alura + Oracle Next Education**.

---

## ✨ Funcionalidades

- 🔎 **Buscar libro por título** en la API Gutendex y guardarlo en la base de datos.  
- 📖 **Listar todos los libros** registrados en la base de datos.  
- 🧑‍🎓 **Listar todos los autores** registrados.  
- ⏳ **Listar autores vivos en un año específico**.  
- 🌍 **Listar libros por idioma** (ejemplo: EN, ES, PT, FR).  
- ⚠️ Manejo de errores:
  - Evitar insertar el mismo libro dos veces.
  - Notificar si un libro no existe en la API.

---

## 🛠️ Tecnologías utilizadas

- **Java 17**
- **Spring Boot 3.2.3**
- **Maven 4**
- **PostgreSQL 16**
- **Spring Data JPA**
- **Jackson (JSON Parser)**

---

## ⚙️ Requisitos previos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- [Java JDK 17+](https://www.oracle.com/java/technologies/downloads/)
- [Maven 4+](https://maven.apache.org/download.cgi)
- [PostgreSQL 16+](https://www.postgresql.org/download/)
- IDE recomendado: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) o Eclipse.

---

## 🚀 Instalación y ejecución

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/literalura-challenge.git
   cd literalura-challenge
