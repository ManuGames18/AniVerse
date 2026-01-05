# AniVerse

## Objetivo
Facilitar la visualización y el registro de animes de las páginas “AnimeFLV”, “AnimeJL”, “Anime-ninja” y “Crunchiroll”. Permitiendo listar y calificar los animes vistos, facilitando las estadísticas de los gustos del usuario.

## Estructura del Repositorio

```
ANIVERSE
|
├── Posibles Logos
├── Analisis y Diseño
|   ├── Casos de Uso
|   |   ├── 1. Registrar Anime
|   |   ├── 2. Registrar Contenido
|   |   └── 5. Registrar Baja de Anime
|   |
|   ├── Historias de Usuario
|   └── Imagenes
|
└── Desarrollo
    ├── Frontend
    └── Backend
```

## Ramas

- **main:** Rama principal, con toda la documentación, y el codigo fuente en una version estable, revisada y probada.

- **dev:** Rama secundaria en la cual se encontrara el codigo fuente en desarrollo y testeo, una vez lograda una version estable se mergea a la main. A partir de esta partiran futuras ramas para desarrollar aspectos especificos del codigo.

## Linea Base

### Criterio de Creación

Se establecerá la Linea de Base del proyecto con cada version estable, funcional y revisada del codigo, y que cuente con la documentacion pertinente.

### Identificación

Las lineas base se identificaran con la siguiente etiqueta: LB-AnV-\<NroVersion>

### Historial de Cambios

| Línea Base    | Fecha      | Descripción          |
|---------------|------------|----------------------|
| **LB-AnV-0.0**| 00/00/0000 |  "Descripcion de ej" |

## Items de Configuración

### Glosario

|   Siglas  |   Significado         |
|-----------|-----------------------|
| AnV       | AniVerse              |
| Temp      | Template              |
| CU        | Caso de Uso           |
| HU        | Historia de Usuario   |
| LB        | Linea Base            |
| Prob      | Probable              |

### Reglas de Nombrado y Ubicaciones

| Item                  | Regla de Nombrado                 | Ubicación                                                     |
|-----------------------|-----------------------------------|---------------------------------------------------------------|
| Analisis              | AnV_Analisis.md                   | ANIVERSE/Analisis y Diseño                                    |
| Casos de Uso          | AnV_CU_\<NroCU>_\<NombreCU>.md    | ANIVERSE/Analisis y Diseño/Casos de Uso/\<NroCU>. \<NombreCU> |
| Template CU           | AnV_Temp_CU.md                    | ANIVERSE/Analisis y Diseño/Casos de Uso                       |
| Historias de Usuario  | AnV_HU_\<NombreHU>.md             | ANIVERSE/Analisis y Diseño/Historias de Usuario               |
| Logos Probables       | AnV_Prob_Logo_\<NroLogo>.\<ext>   | ANIVERSE/Posibles Logos