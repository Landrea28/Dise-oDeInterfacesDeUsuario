> **Rama:** `Taller4`  
> **Asignatura:** Diseño de Interfaces de Usuario  
> **Fecha:** Marzo 2026
> **Rama Main:** https://github.com/Landrea28/Dise-oDeInterfacesDeUsuario/tree/main 

# Taller 4 - Diseño de Interfaces de Usuario

Este directorio corresponde al desarrollo del Taller 4 dentro del repositorio de la materia Diseño de Interfaces de Usuario.

La idea de este repositorio es mantener cada taller organizado por ramas para que el contenido quede separado, fácil de revisar y más claro para cualquier persona que entre desde GitHub. Si estás viendo la rama `Taller4`, este README describe exactamente qué contiene esta parte del proyecto.

## Organización del repositorio

El repositorio está ordenado por ramas.

- Cada rama representa un taller o avance específico.
- Esta rama, `Taller4`, contiene únicamente los archivos relacionados con el Taller 4.
- Cada rama puede tener su propio README para explicar su objetivo, estructura y forma de uso.

Con esta organización, una persona externa puede identificar rápidamente qué trabajo pertenece a cada entrega sin mezclar archivos de otros talleres.

## Objetivo de esta rama

En esta rama se presenta una interfaz web sencilla en HTML orientada a un ejercicio académico de maquetación y navegación básica entre vistas.

El taller incluye:

- Una vista principal con encabezado, menú lateral y contenido central.
- Un formulario de registro de usuarios.
- Una vista de reporte con datos tabulares.
- Una página inicial cargada dentro de un `iframe`.

## Estructura de archivos

- `index(taller4).html`: archivo principal del taller. Desde aquí se carga la interfaz general.
- `frontPrincipal.html`: contenido inicial que aparece en el área central.
- `registroUsuario.html`: formulario para registrar información de usuario.
- `reporte.html`: tabla de reporte con información de ejemplo.

## Flujo de navegación

El funcionamiento general del taller es el siguiente:

1. Se abre `index(taller4).html`.
2. La página muestra un encabezado superior, un menú lateral y una zona principal de contenido.
3. En la zona central se carga por defecto `frontPrincipal.html`.
4. Desde el menú lateral se puede cambiar el contenido del `iframe` para mostrar:
   - `registroUsuario.html`
   - `reporte.html`

## Tecnologías utilizadas

- HTML5
- CSS interno
- Navegación básica con `iframe`

## Cómo visualizar este taller

1. Clona el repositorio desde GitHub.
2. Cambia a la rama `Taller4`.
3. Abre el archivo `index(taller4).html` en tu navegador.

Si se desea, también puede abrirse con una extensión como Live Server en Visual Studio Code para una visualización más cómoda.

## Nota sobre la organización general

Este README busca que cualquier persona que revise el repositorio entienda dos cosas de inmediato:

- Qué representa esta rama dentro del repositorio.
- Qué hace este taller y cómo está compuesto.

La intención es mantener un repositorio más ordenado, donde cada rama documente su contenido de forma independiente.> **Rama:** `MelodiaSteam`  
> **Asignatura:** Diseño de Interfaces de Usuario  
> **Fecha:** Febrero 2026
> **Rama Main:** https://github.com/Landrea28/Dise-oDeInterfacesDeUsuario/tree/main 

## Proyecto: Melodia Stream - Plataforma de Streaming Especializada

Este proyecto consiste en el diseño y desarrollo de una interfaz web moderna para una plataforma de streaming de música enfocada en tres géneros específicos: **Alternativa, Jazz y Rock**. El objetivo principal es aplicar conceptos de usabilidad, accesibilidad (WCAG AA) y diseño responsivo bajo una estética retro-vintage.

### Información del Estudiante
- **Materia:** Diseño de Interfaces de Usuario
- **Laboratorio:** #3
- **Ciclo:** 2026

### Características del Proyecto
- **Temática:** Curaduría musical curada de nicho con vibras de Jazz, Rock y Hippie/Indie.
- **Paleta de Colores:** Basada en tonos cálidos y oscuros (Amarillo Oro, Naranja Terracota y Crema Vintage) para evocar la estética de vinilos y clubes nocturnos.
- **Secciones Implementadas:**
    - **index.html:** Portal principal con exploración de géneros y artistas recomendados.
    - **quienes-somos.html:** Narrativa de marca sobre la curaduría humana y la pasión por el sonido sin pérdida.
    - **productos-servicios.html:** Planes de suscripción y servicios exclusivos como el "Vinyl Club".
    - **login.html:** Interfaz de acceso de usuario con diseño minimalista.
- **Tecnologías:** HTML5 semántico y CSS3 puro (Flexbox, Grid, Variables, Media Queries).

### Criterios de Diseño (UX/UI)
1. **Accesibilidad:** Cumplimiento de contrastes de color WCAG AA y navegación optimizada para teclado (`focus-visible`).
2. **Responsividad:** Diseño adaptativo para dispositivos móviles, tablets y escritorio con un header horizontal optimizado.
3. **Consistencia Visual:** Uso de variables CSS para mantener una identidad de marca coherente en todas las páginas.
4. **Interactividad:** Feedback visual en botones y tarjetas de géneros para mejorar la experiencia de usuario.

---
*Este repositorio es parte de las entregas académicas para la asignatura de Diseño de Interfaces de Usuario.*