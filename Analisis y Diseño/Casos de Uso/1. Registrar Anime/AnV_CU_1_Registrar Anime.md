# Caso de Uso: Registrar Anime

## Información General
- **ID:** 1  
- **Nombre del caso de uso:** Registrar Anime  
- **Actor principal:** Usuario  
- **Actor secundario:** —  
- **Tipo de caso de uso:** Concreto
- **Objetivo:** Registrar un nuevo anime con todos sus contenidos  
- **Precondición:** No aplica  

---

## Curso Normal
1. El CU comienza cuando el Usuario selecciona la opción **“Crear”**.  
2. El Sistema busca los tipos, estados y calificaciones de animes posibles.  
3. El Sistema solicita que se ingrese el título, tipo, estado y calificación del anime.  
4. El Usuario ingresa el título, tipo, estado y calificación.  
5. El Sistema pregunta si se desea agregar contenidos.  
6. El Usuario selecciona la opción **“Añadir Contenido”**.  
7. El Sistema llama al CU 2. Registrar Contenido.  
8. El Sistema pregunta si se desea fusionar contenidos.  
9. El Usuario no selecciona nada.  
10. El Sistema pregunta si se desea **“Cancelar”** o **“Grabar”**.  
11. El Usuario selecciona la opción **“Grabar”**.  
12. El Sistema valida que se hayan ingresado los campos solicitados (Título, Tipo), y están.  
13. El Sistema valida que se haya ingresado algún contenido, y así es.  
14. El Sistema valida si ya existe el nombre del anime previamente, y no existe.  
15. El Sistema registra el nuevo anime.  
16. El Sistema registra los contenidos del anime.  
17. El Sistema informa que el anime se registró correctamente.  
18. **Fin del CU.**

---

## Cursos Alternativos
- **A1 (Paso 3):** 
   - El Sistema recibe los datos y muestra título, tipo, estado, calificación y contenidos.
   - El Sistema pregunta si se desea agregar contenidos.  
- **A2 (Paso 9):** 
  - El Usuario selecciona la opcion **“Fusionar Contenidos”**.  
  - El Sistema solicita seleccionar dos contenidos para fucionar.  
  - El Usuario selecciona dos contenidos.  
  - El Sistema pregunta si se desea fusionar.  
  - El Usuario selecciona la opcion **“Fusionar”**.  
  - El Sistema agrega todas las direcciones y géneros del segundo contenido al primero.  
  - El Sistema borra el segundo contenido.  
  - El Sistema informa que se fusionaron correctamente los contenidos.  
- **A3 (Paso 11):** 
  - El Usuario selecciona la opción **“Cancelar”**
  - Fin del CU.
- **A4 (Paso 12):**
  - El Sistema valida que se hayan ingresado los campos solicitados (Nombre, Tipo), y no están.
  - El Sistema solicita nuevamente que se ingresen los datos.
- **A5 (Paso 13):**
  - El Sistema valida y no se ingresó ningún contenido.
  - El Sistema solicita que se ingrese al menos un contenido.
- **A6 (Paso 14):** 
  - El Sistema valida si ya existe el nombre del anime previamente, y existe.
  - El Sistema informa que dicho anime ya existe.  

---

## Postcondiciones
- **Éxito:** Se registró el anime con sus contenidos exitosamente.  
- **Fracaso:** El anime ya existe anteriormente.  

---

## Cancelación
- El CU se cancela cuando el Usuario selecciona la opción **“Cancelar”**.  

## Observaciones 
- El CU se puede cancelar en cualquier momento.
- Se pueden agregar tantos contenidos como se deseen.  

---

## Requerimientos No Funcionales
- Por cada anime se debe registrar:  
  - Título  
  - Tipo de Anime  
  - Si está en Emisión  
  - Estado  
  - Calificación  
- **Tipos de Animes disponibles:** Serie, Película, OVA  
- **Estados disponibles:** Por Ver, Viendo, Visto, Volver a Ver  
- Debe tener modo oscuro y modo claro.  
- Se debe respetar la paleta de colores del logo.  