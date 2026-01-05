# Caso de Uso: Registrar Contenido

## Información General
- **ID:** 2  
- **Nombre del caso de uso:** Registrar Contenido  
- **Actor principal:** Usuario  
- **Actor secundario:** —  
- **Tipo de caso de uso:** Concreto
- **Objetivo:** Obtener los datos de un nuevo contenido correspondiente a un anime con todos sus datos.  
- **Precondición:** Debe haberse registrado el anime previamente.  

---

## Curso Normal
1. El CU comienza cuando el Usuario selecciona la opción **“Añadir Contenido”**.  
2. El Sistema busca los Tipos de Contenido, los Géneros y los sitios webs disponibles.  
3. El Sistema solicita que se ingrese el título del contenido y la URL de imagen.  
4. El Usuario ingresa el título del contenido y la URL de imagen.  
5. El Sistema solicita que se seleccione el tipo de contenido, si está en español y si está en emisión.  
6. El Usuario selecciona el tipo de contenido, si está en español y si está en emisión.  
7. El Sistema pregunta si se desean modificar los géneros del contenido.  
8. El Usuario selecciona la opción **“Modificar Géneros”**.  
9. El Sistema solicita seleccionar los géneros correspondientes al contenido.  
10. El Usuario selecciona los géneros.  
11. El Sistema muestra los géneros seleccionados.  
12. El Sistema pregunta si se desea añadir una URL.  
13. El Usuario selecciona la opción **“Añadir URL”**.  
14. El Sistema solicita seleccionar el sitio web e ingresar la URL.  
15. El Usuario selecciona el sitio web e ingresa la URL.  
16. El Sistema pregunta si desea cancelar.  
17. El Usuario no selecciona nada.  
18. El Sistema valida que se haya ingresado: Título, Tipo, al menos un género, URL de imagen, y al menos una URL de un sitio web, y así es.  
19. El Sistema envía los datos del nuevo contenido al CU 1. Registrar Anime.  
20. **Fin del CU.**

---

## Cursos Alternativos
- **A1 (Paso 3):**}
   - El Sistema recibe los datos (título, tipo, géneros, si está en español, si está en emisión, URL de imagen y URLs con sus sitios webs).
   - El Sistema muestra (título, tipo, géneros, si está en español, si está en emisión, URL de imagen y URLs con sus sitios webs).
   - El Sistema pregunta si se desean modificar los géneros del contenido
- **A2 (Paso 17):**
   - El Usuario selecciona la opción **“Cancelar”**
   - Fin del CU.  
- **A3 (Paso 18):**
   - El Sistema valida que se haya ingresado el título, tipo, al menos un género, url de imagen y al menos una url de un sitio web, y no es asi.
   - El Sistema solicita se ingresen estos datos nuevamente.

---

## Postcondiciones
- **Éxito:** Se obtuvieron los datos del contenido correspondiente al anime exitosamente.
- **Fracaso:** El contenido ya existe anteriormente.  

---

## Cancelación
- El CU se cancela cuando el Usuario selecciona la opción **“Cancelar”**.  

## Observaciones
- El CU se puede cancelar en cualquier momento.
- Se pueden agregar tantas URLs de sitios web como se deseen.  

---

## Requerimientos No Funcionales
- Por cada contenido se debe registrar:  
  - Anime relacionado  
  - Título  
  - Tipo de Contenido  
  - Géneros relacionados  
  - Si está disponible en español  
  - Si está en emisión  
  - URL de imagen  
  - URL de los sitios web  
- **Tipos de Contenidos disponibles:** Anime, Película, OVA, Donghua  
- Debe tener modo oscuro y modo claro.  
- Se debe respetar la paleta de colores del logo.  