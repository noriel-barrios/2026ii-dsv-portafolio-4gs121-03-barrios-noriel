# Laboratorio 2 — Préstamo a domicilio

**Biblioteca Universitaria**
Desarrollo de Software V · Módulo II: Páginas web y HTML
Prof. José Peralta B. · Universidad Tecnológica de Panamá, Centro Regional de Veraguas

---

## Qué contiene este paquete

| Archivo | Qué es |
| --- | --- |
| `assets/css/biblioteca-base.css` | Hoja **mínima**, solo para que las páginas se lean bien mientras escribes. No la amplíes: el diseño del sitio lo harás en el Laboratorio 3. |
| `assets/img/logo-biblioteca.svg` | Logotipo de la biblioteca. |
| `README.md` | Este archivo. |

## Qué vas a construir

Tres páginas sobre el servicio de **préstamo a domicilio**. Es el mismo sitio
que continuará en los Laboratorios 3 (CSS) y 4 (JavaScript), así que cuida
los nombres de archivos, los `id` y los `name`: se reutilizarán.

| Ejercicio | Página | Qué practica |
| --- | --- | --- |
| E01 | `index.html` | Estructura semántica, contenido textual, cita con su fuente y enlace externo protegido. |
| E02 | `catalogo.html` | Dos tablas: el catálogo con encabezados de dos niveles y los préstamos del usuario con pie. |
| E03 | `prestamo.html` | El formulario de solicitud, con validación nativa y el ejemplar e.1 deshabilitado. |

Al terminar, las tres páginas llevan la política de seguridad de contenidos y
validan sin errores.

## Las reglas del servicio

- Se prestan a domicilio los libros de la **Colección General**.
- El ejemplar **e.1** de cada título se reserva para consulta en sala; se
  prestan del **e.2 en adelante**.
- Los préstamos se cargan a la cuenta del usuario, que puede **renovarlos
  hasta tres veces** si no tiene adeudos ni multas.

Fuente: *Reglamento de Servicios Bibliotecarios del Sistema de Bibliotecas*,
Universidad Tecnológica de Panamá.

## Se trabaja en equipo

Equipos de **tres** integrantes (cuatro como máximo, solo si sobra alguien en
el grupo). El equipo trabaja en un repositorio compartido y, al terminar, cada
integrante copia el sitio en su propio portafolio.

| Dónde | Qué va |
| --- | --- |
| `2026ii-dsv-lab02-4gs121-eqEE` | El repositorio del equipo, donde se trabaja con ramas y pull requests. `EE` es el número del equipo. |
| `docs/modulos/m02-html/lab02-biblioteca/` | La copia final en el portafolio de **cada** integrante. |

La cabecera de las tres páginas lleva los datos de **todos** los integrantes.

## Dónde va

En el repositorio del equipo, los archivos van en `docs/`. En tu portafolio,
la copia final queda así:

```
lab02-biblioteca/
├── README.md
├── index.html             ← E01
├── catalogo.html          ← E02
├── prestamo.html          ← E03
└── assets/
    ├── css/biblioteca-base.css
    └── img/logo-biblioteca.svg
```

## Cómo empezar

1. Un integrante crea el repositorio del equipo, público, añade a los demás
   como colaboradores y sube el contenido de este paquete dentro de `docs/`.
2. Cada integrante clona el repositorio del equipo y trabaja su parte en una
   rama propia; la integra con un pull request que revisa otro integrante.
3. Abre con **Live Server** y sigue la guía, ejercicio por ejercicio.

## Antes de entregar

1. Valida las **tres** páginas en <https://validator.w3.org>.
2. Recorre las tres solo con el teclado y abre la consola (**F12** o
   **Ctrl+Shift+I**): ningún recurso del sitio debe quedar bloqueado.
3. Cada integrante copia la versión final en
   `docs/modulos/m02-html/lab02-biblioteca/` de su portafolio y registra la
   ficha del laboratorio en `docs/modulos/index.html`, con el enlace a su copia
   y el enlace al repositorio del equipo.
4. Confirma y sube, desde tu portafolio:

   ```bash
   git add docs/modulos/m02-html/lab02-biblioteca docs/modulos/index.html
   git commit -m "Laboratorio 2: sitio de préstamo a domicilio"
   git push
   ```

5. Cada integrante sube a Moodle la evidencia del equipo, con **su** nombre de
   archivo (`4GS121-NN_Apellido-Nombre_M02_Lab02.pdf`) y **sus** conclusiones.

## Recuerda

- Los datos del equipo van **en la cabecera** de las tres páginas: número de
  equipo y, de cada integrante, nombre completo y código. Nunca la cédula.
- El catálogo, los préstamos y los datos de contacto son ficticios.
