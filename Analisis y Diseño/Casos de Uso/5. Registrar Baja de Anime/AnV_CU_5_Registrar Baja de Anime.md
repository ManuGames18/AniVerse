# Caso de Uso: Registrar Baja Anime

## Información General
- **ID:** 5  
- **Nombre del caso de uso:** Registrar Baja Anime  
- **Actor principal:** Usuario  
- **Actor secundario:** —  
- **Tipo de caso de uso:**  Concreto
- **Objetivo:** Registrar la baja de un anime con todos sus contenidos  
- **Precondición:** El Anime debe existir  

---

## Curso Normal
1. El CU comienza cuando el Usuario selecciona la opción **“Eliminar”**.  
2. El Sistema pregunta si se desea eliminar o cancelar.  
3. El Usuario selecciona la opción **“Eliminar”**.  
4. El Sistema busca todos los contenidos relacionados con el anime, y hay.  
5. El Sistema llama al CU 6. Registrar Baja de Contenido.  
6. El Sistema informa que se eliminó correctamente el anime con sus contenidos.  
7. **Fin del CU.**

---

## Cursos Alternativos
- **A1 (Paso 3):**
  - El Usuario selecciona la opción **“Cancelar”**
  - Fin del CU.  
- **A2 (Paso 4):**
  - El Sistema busca todos los contenidos relacionados con el anime, y no hay.  
  - El Sistema informa de un error debido a que el anime no tiene contenidos.  
  - **Fin del CU.**

---

## Postcondiciones
- **Éxito:** Se registró la baja del anime con sus contenidos exitosamente.  
- **Fracaso:** El anime no existe anteriormente o no tiene contenidos.  

---

## Cancelación
- El CU se cancela cuando el Usuario selecciona la opción **“Cancelar”**.  
## Observaciones
- El CU se puede cancelar en cualquier momento.  

---

## Requerimientos No Funcionales
- Debe tener modo oscuro y modo claro.  
- Se debe respetar la paleta de colores del logo.  