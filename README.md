[![CircleCI](https://circleci.com/gh/IsaakKrut/springmvc-deliveryapp.svg?style=svg)](https://circleci.com/gh/IsaakKrut/deliveryapp)


Spring MVC application, that mimics the behavior of an online shopping service or food delivery app. It stores User and
Shopping Cart objects as session attributes which are available to different views throughout the application.

It uses MySQL database and Hibernate JPA specification to map objects to their corresponding repositories.

Service layer implements custom interfaces, which are being injected into controllers thus adhering to
SOLID programming principles.

Thymeleaf template engine is used to render views to the user. Bootstrap framework helps with styling of these views.

Used JUnit5 to test services and controllers.

Used Annotation-based and Java-based configurations as well as constructor-based dependency injection 
throughout application.

Used CircleCI continuous integration tool and Project Lombok.

Used JavaMailSender interface to send confirmation emails to the users.

Refactored https://github.com/IsaakKrut/FoodDeliveryApp from Spring REST->React.js into Spring MVC application