
# ADR-0001: Elección de la arquitectura Cliente–Servidor

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
Se requiere una arquitectura que permita separar la lógica del negocio de la interfaz de usuario, asegurando comunicación eficiente entre ambos.  

## Decisión  
Se adopta la **arquitectura Cliente–Servidor**, donde:  
- El **cliente** (navegador web o aplicación móvil) gestiona la interfaz e interacción del usuario.  
- El **servidor** central maneja la lógica de negocio y el acceso a datos.  

## Alternativas consideradas  
- **Monolítica:** descartada por su baja flexibilidad.  
- **Microservicios:** excesiva para el alcance del proyecto.  

## Consecuencias  
- Esta separación promueve el desarrollo paralelo entre equipos.
- Facilita la integración continua y mejora la seguridad al limitar la exposición directa de la base de datos. 

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
