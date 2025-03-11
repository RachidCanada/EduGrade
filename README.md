# EduGrade 🎓
EduGrade est une application **Spring Boot** permettant de gérer les étudiants et leurs notes avec **MySQL**.

## 🚀 Technologies utilisées
- **Java 17** (Spring Boot 3.1)
- **Maven** (Gestion des dépendances)
- **Spring Boot** (Web, JPA, MySQL)
- **MySQL** (Base de données)
- **Postman** (Tests API REST)

## 📂 Installation et exécution

### 1️⃣ Cloner le projet

git clone https://github.com/RachidCanada/EduGrade.git cd EduGrade


### 2️⃣ Configurer la base de données
Modifie le fichier **`src/main/resources/application.properties`** avec tes identifiants MySQL :

spring.datasource.url=jdbc:mysql://localhost:3306/edugrade spring.datasource.username=root spring.datasource.password=yourpassword


### 3️⃣ Installer les dépendances Maven

mvn clean install

### 4️⃣ Lancer l’application Spring Boot
