
# ADR-0005: Selección de Flutter para la Aplicación Móvil

**Fecha:** 03/11/2025  
**Estado:** Propuesto  

## Contexto  
El sistema requiere una aplicación móvil multiplataforma con alto rendimiento y consistencia visual en Android e iOS.

## Decisión  
Se adoptó Flutter como framework de desarrollo móvil. 

## Alternativas consideradas  
- **React Native:** descartado por menor rendimiento gráfico. 
- **Kotlin/Swift:** descartados por no ser multiplataforma.  

## Justificación  
Flutter permite compilar en código nativo, ofrece una interfaz moderna y mantiene una única base de código para ambas plataformas, reduciendo tiempo y costos de desarrollo. 

## Consecuencias
- Facilita la integración con las APIs REST del backend.
- Permite mantener consistencia en el diseño visual con la versión web. 

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
