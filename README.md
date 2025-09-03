# 📊 Spring Boot Report Application

This is my **first mini project** in Spring Boot.  
The project implements a **Report Search Application** with functionalities like **searching citizen plans, generating reports in Excel & PDF format, and sending reports via email**.

---

## 🚀 Tech Stack

- **Java** (Spring Boot)
- **Spring Web**
- **Spring Data JPA**
- **MySQL**
- **Spring Mail**
- **Lombok**
- **DevTools**
- **JSP / JSTL**
- **Tomcat Embed Jasper**
- **Excel & PDF generation libraries**

---

## 📂 Project Structure

src/main/java/com/excelr
│
├── controller
│ └── ReportController.java
│
├── entity
│ └── CitizenPlan.java
│
├── repository
│ └── CitizenPlanRepository.java
│
├── request
│ └── SearchRequest.java
│
├── runner
│ └── DataLoader.java
│
├── service
│ ├── ReportService.java
│ └── ReportServiceImpl.java
│
├── util
│ ├── PdfGenerator.java
│ ├── ExcelGenerator.java
│ └── EmailUtil.java
│
└── Starter.java



---

## ⚙️ Required Files

### 1. `pom.xml` dependencies
- spring-boot-starter-web  
- spring-boot-starter-data-jpa  
- mysql-connector-java  
- lombok  
- spring-boot-devtools  
- spring-boot-starter-mail  
- tomcat-embed-jasper  
- jstl, jstl-api  
- Apache POI (Excel)  
- iText (PDF)  

### 2. `application.properties`
- Database Configuration  
- Email Configuration  
- File Paths  

### 3. Views
- `index.jsp` (response file)  

---

## ✨ Features

- ✅ Search Citizen Plans  
- ✅ Export Reports in **Excel** and **PDF**  
- ✅ Send Reports via **Email**  
- ✅ Auto-load sample data using **DataLoader**  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spring-boot-report-application.git
   cd spring-boot-report-application



2. Configure application.properties with:

    MySQL Database details

    Spring Mail settings

3. Build & Run:
   
```bash
    mvn spring-boot:run


4. Open in browser:

http://localhost:8080/



📧 Email Config Example (application.properties)
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=your-email@gmail.com
spring.mail.password=your-app-password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true

📝 Author

Khwaja Hussain Shaikh
First Spring Boot Mini Project – Spring Boot Report Application


