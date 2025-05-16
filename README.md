# FirstSpringApp
This is a basic Spring Boot project created as part of Task 1 from the programming exercises.

##  Short description
The purpose of this application is to:
- Create a new Spring Boot project
- Write the first simple Spring controller.
- Run the project and handle a basic localhost request.
- Use the `@ResponseBody` annotation to return text to the browser.

## What I used in project 
- Java
- Spring Boot (latest  version which I used )
- Spring Web
- Maven
- INTJ

## THE STRUCTURE HOW IT WORKS 
creating files on MAIN 
then in directory resources for images and html files.
- `HelloController.java` - processing for web requestsand 
when we use localhost:8080/greeting?name=Vistula -> he is giving to me the HTML file as greeting.html for the name Vistula
AT THE SAME TIME WE USE DEPENDENCY the library, for conecting our project 
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>

## HOW TO RUN  
1. mvn spring-boot:run or use your IDE to run the application.
2. LINK http://localhost:8080/ for the main page.
3. LINK http://localhost:8080/greeting?name=Gulzira greeting page 
## SCREENSHOT + RESULT 
![vistulariver](https://github.com/user-attachments/assets/ba361655-f97b-4800-bd7b-901182b354c1)
