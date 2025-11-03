
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

## Justificación  
La arquitectura Cliente–Servidor ofrece simplicidad, escalabilidad básica y compatibilidad con el modelo C4 utilizado en el diseño.  

## Consecuencias  
- Se crearán contenedores separados para cliente y servidor en los diagramas C4.  
- Servirá como base para decisiones futuras sobre tecnologías y despliegue.  

## Autor  
José Antonio Cartuche Robalino

## Revisión  
Ing. Lissette López
