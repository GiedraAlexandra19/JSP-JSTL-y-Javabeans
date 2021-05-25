# JSP-JSTL-y-Javabeans
Practica 4: JSP, JSTL y Javabeans

apinoh@unsa.edu.pe -> Angie Alexandra Pino Huarsaya

Objetivo: Usar la biblioteca JSTL en páginas JSP
Pre-requisitos: Eclipse, Tomcat, Java, 

a. Desacargar la biblioteca JSTL (https://tomcat.apache.org/taglibs/standard/) 

b. Actualizar el proyecto:
    Subir las bibliotecas jstl*.jar en WEB-INF/lib
    
    Importar las bibliotecas jstl*.jar en el proyecto: properties -> build path -> libraries -> add external jars
    
c. Actualizar el servlet:
    • Traer el código JAVA de la JSP al Servlet

    • Crear Java Bean (atributos que representan los datos que serán impresos en el JSP)

    • Enviar el Java Bean al JSP

d. Actualizar JSP
    • Usar la biblioteca JSTL para imprimir el Java Bean enviado por el Sevlet
  importar en JSP: <%@ taglib uri="http://java.sun.com/jsp/jstl/core&quot; prefix="c" %>
  
e. Ejecutar el Proyecto
