
# ADR-0004: Selección de Flutter para el desarrollo del frontend Móvil

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema requiere una aplicación móvil con alto rendimiento, tiempos de respuesta rápidos y una interfaz visual consistente en Android e iOS, evitando desarrollar dos aplicaciones nativas independientes.

## Decisión  
Se adoptó Flutter como framework para el desarrollo del frontend móvil. 

## Alternativas consideradas  
- **React Native:** descartado por menor rendimiento gráfico. 
- **Kotlin/Swift:** descartados por no ser multiplataforma, lo que duplicaría esfuerzos de desarrollo y mantenimiento para Android e iOS.

## Consecuencias
- Permite desarrollar una sola base de código para Android e iOS, asegurando capacidades multiplataforma y reduciendo significativamente el tiempo y el esfuerzo de desarrollo.
- Facilita la integración con las APIs REST del backend.
- Permite mantener consistencia en el diseño visual con la versión web. 

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
