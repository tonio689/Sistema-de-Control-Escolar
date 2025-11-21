
# ADR-0002: Selección de Django como framework Backend

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema necesita un framework robusto para gestionar la lógica de negocio, ofrecer seguridad y conectarse eficientemente con bases de datos relacionales.

## Decisión  
Se seleccionó Django como framework backend principal.

## Alternativas consideradas  
- Flask: ligero, pero requiere mayor configuración y mantenimiento.  
- Laravel: es un framework sólido, pero está basado en PHP, lo que no se ajusta al entorno del proyecto, que utiliza Python.
 
## Consecuencias 
- Django ofrece un ORM integrado, autenticación incorporada, alta seguridad contra ataques web y una estructura escalable.
- Facilita la integración continua y mejora la seguridad al limitar la exposición directa de la base de datos. 
- Se facilitará la integración con PostgreSQL.  
- Servirá como base para decisiones futuras sobre tecnologías y despliegue.  

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
