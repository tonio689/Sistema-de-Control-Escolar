
# ADR-0006: Selección de Clean Architecture para la Aplicación Móvil

**Fecha:** 20/11/2025  
**Estado:** Propuesto  

## Contexto  
La aplicación móvil necesita una estructura que permita organizar el código de forma clara, facilitar el mantenimiento y hacer más sencilla la incorporación de nuevas funciones a futuro.

## Decisión  
Se decidió utilizar el patrón Clean Architecture para la aplicación móvil, ya que organiza el proyecto en capas de entidades, casos de uso, interfaces y frameworks, para mantener un sistema desacoplado y fácil de mantener

## Alternativas consideradas  
- **MVP (Model–View–Presenter):** ofrece buena separación entre la vista y la lógica, pero puede requerir más código y volverse complejo a medida que crece la aplicación.
- **MVVM (Model–View–ViewModel):** facilita la sincronización entre la interfaz y los datos, pero puede volverse difícil de manejar si la lógica del ViewModel aumenta demasiado.
- **VIPER (View–Interactor–Presenter–Entity–Router):** Todavía no es común en los desarrolladores y requiere un cierto nivel de conocimiento y experiencia para usarlo.

## Consecuencias
- Se obtendrá una estructura clara y organizada, que separa bien la lógica interna de la interfaz de usuario.
- Será más fácil mantener, probar y ampliar la aplicación con nuevas funcionalidades.
- Puede requerir más tiempo inicial de organización, pero facilitará el desarrollo en etapas posteriores.

## Autor  
Antonio Cartuche

## Revisión  
Ing. Lissette López
