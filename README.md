# 🏥 Doctor-Patient Suggestion API

A Spring Boot 3 based REST API that allows doctors to register, patients to be added with symptoms, and suggests appropriate doctors based on patient symptoms and location.

---

## 📌 Project Features

- ✅ Add Doctor with name, city, email, phone, and speciality
- ✅ Add Patient with name, city, email, phone, and symptom
- ✅ Suggest doctors based on patient's symptom and city
- ✅ Edge case handling for unsupported cities or unavailable doctors
- ✅ Input validations on all fields
- ✅ Swagger UI for API documentation
- ✅ In-memory H2 database

---

## ⚙️ Tech Stack

- **Spring Boot 3**
- **Spring Data JPA (Hibernate)**
- **H2 In-Memory Database**
- **Spring Validation**
- **Springdoc OpenAPI (Swagger)**
- **Postman**

---

## 🚀 How to Run the Project

### 🛠️ Requirements

- Java 17+
- Maven
- IntelliJ or VS Code (recommended)

### ▶️ Run Steps

```bash
# 1. Clone the repository
git clone https://github.com/your-username/doctor-patient-suggestion.git
cd doctor-patient-suggestion

# 2. Run using Maven
./mvnw spring-boot:run