
# ADR-0003: Selección de Django como framework Backend

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema necesita un framework robusto para gestionar la lógica de negocio, ofrecer seguridad y conectarse eficientemente con bases de datos relacionales.

## Decisión  
Se seleccionó Django como framework backend principal.

## Alternativas consideradas  
- Flask: ligero, pero requiere mayor configuración y mantenimiento.  
- Laravel: opción potente, pero no se ajusta al entorno Python utilizado en el proyecto. 

## Justificación  
Django ofrece un ORM integrado, autenticación incorporada, alta seguridad contra ataques web y una estructura escalable, lo que permite acelerar el desarrollo manteniendo buenas prácticas arquitectónicas.  

## Consecuencias  
- Se facilitará la integración con PostgreSQL.  
- Servirá como base para decisiones futuras sobre tecnologías y despliegue.  

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
