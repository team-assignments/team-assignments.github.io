---
title: Technology Inventory
subtitle: "Inventory of Technology used on front end and back end."
menu: Technology
order: 60
---



# Technology Stacks

## Back end

* Ubuntu Linux OS
* Apache HTTP server configured as reverse proxy
* JRE 8
* Apache Tomcat Java application server
* Web service application, incorporating:
    * Data model
        * Embedded Apache Derby database
        * Hibernate ORM
        * Custom entity classes
        * Spring Data JPA
        * Custom data repository interfaces
    * Service controllers
        * Spring MVC
        * Custom controller classes
    * View composition & serialization
        * Jackson JSON
    * Authentication
        * Spring Security
        * Google Sign In (external service; see
          https://developers.google.com/identity)
        * Custom authentication verifier method for audience (client ID)

## Front end

* Android OS
* Data model
    * SQLite
    * Room ORM
    * Custom entity and other model classes
    * Data access object (DAO) interfaces
  
* Remote service interfaces
    * Retrofit
    * ReactiveX
    * Gson
    
* Viewmodel components
    * Android Lifecycle framework (ViewModel & LiveData)
    * Custom viewmodel classes
  
* View
    * Custom RecyclerView.Adapter and RecyclerView.Holder classes
    * Custom layouts
  
* Controller
    * Custom activity and fragment classes
  
* Authentication
    * Google Sign In (external service; see https://developers.google.com/identity)
    * Custom sign in service class
  
* Formatting and UI
    * Custom images
      

## Copyrights

[copyrights](/copyrights.md)