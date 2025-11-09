
# ADR-0005: Selección de PostgreSQL como gestor de base de datos

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema requiere una base de datos relacional que soporte transacciones seguras, consultas complejas y escalabilidad a mediano plazo.

## Decisión  
Se seleccionó PostgreSQL como sistema de gestión de base de datos 

## Alternativas consideradas  
- **MySQL:** menor cumplimiento del estándar SQL en comparación con PostgreSQL.
- **SQLite**: no adecuada para entornos multiusuario o de alta concurrencia.

## Consecuencias  
- PostgreSQL es una base de datos libre, robusta, con soporte avanzado para integridad referencial, manejo de JSON y compatibilidad nativa con Django.
- Se garantizará la persistencia y consistencia de los datos. 
- Facilita la futura escalabilidad del sistema.

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
