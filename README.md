JSP_JSTL_Javabeans

Rushell Vanessa Zavalaga Orozco, rzavalaga@unsa.edu.pe.

Objetivo: Usar la biblioteca JSTL en páginas JSP
Pre-requisitos: Eclipse, Tomcat, Java, 
JSTL (http://www.jtech.ua.es/j2ee/restringido/cw/sesion08-apuntes.html)

En base al proyecto de la Práctica 3 - JSP y Servlet (https://www.ecodeup.com/primeros-pasos-java-web-jsp-servlets/):

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

Entregable: Repositorio Github conteniendo el proyecto actualizado
