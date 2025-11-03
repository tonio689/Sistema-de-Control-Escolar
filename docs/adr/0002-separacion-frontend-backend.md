
# ADR-0002: Separación entre Frontend y Backend

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema requiere independencia entre la interfaz de usuario y la lógica del negocio para facilitar la escalabilidad, mantenimiento y despliegue.

## Decisión  
Se estableció una separación entre las capas **frontend y backend**. 
- El **frontend** estará compuesto por la aplicación web (React) y la aplicación móvil (Flutter). 
- El **backend** se implementará en Django, encargado del procesamiento y acceso a datos. 

## Alternativas consideradas  
- **Monolítica:** descartada por dificultar el mantenimiento y la reutilización de componentes.  
- **Microservicios:** innecesario para el alcance actual del proyecto.  

## Justificación  
Esta separación promueve el desarrollo paralelo entre equipos, facilita la integración continua y mejora la seguridad al limitar la exposición directa de la base de datos. 

## Consecuencias  
- Se requieren mecanismos de comunicación mediante API REST. 

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
