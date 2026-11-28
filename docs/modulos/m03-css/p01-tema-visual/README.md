# Práctica 1 — Tema visual de ConSentidos

**Sitio de la Clínica Veterinaria ConSentidos**
Desarrollo de Software V · Módulo III: Páginas web y CSS · Unidad 1
Prof. José Peralta B. · Universidad Tecnológica de Panamá, Centro Regional de Veraguas

---

## Qué contiene este paquete

| Archivo | Qué es |
| --- | --- |
| `assets/css/tema.css` | Tu hoja de tema, con sus secciones comentadas. La completas tú. |
| `assets/fonts/Bitter-VF.woff2` | Fuente variable Bitter para los títulos. |
| `assets/fonts/OFL-Bitter.txt` | Licencia de la fuente (SIL Open Font License). |
| `assets/vendor/fontawesome/` | Font Awesome 7 Free: solo la hoja y la fuente de los iconos sólidos, y su licencia. |
| `README.md` | Este archivo. Sustituye al de la Práctica 5 del Módulo II. |

## Qué vas a hacer

Vas a cambiar el aspecto de todo el sitio **sin tocar `consentidos.css`** y
casi sin tocar el HTML: una sola hoja nueva, `tema.css`, cargada después de la
del sitio.

1. Una **paleta** propia, con contraste AA, en modo claro y oscuro.
2. Una **tipografía** para los títulos, alojada en el sitio.
3. Los **estados de los enlaces** y del menú.
4. **Iconos** de Font Awesome en el menú y en los datos de contacto.
5. Comprobar en las herramientas de desarrollo **por qué gana** tu hoja.

## Dónde va

```
docs/modulos/m03-css/p01-tema-visual/
```

Cuando termines:

```
p01-tema-visual/
├── README.md              ← este archivo
├── index.html             ← copiado: enlace a tema.css y CSP ajustada
├── servicios.html         ← ídem
├── componentes.html       ← ídem
├── tarifas.html           ← ídem
├── cita.html              ← ídem
├── revision.html          ← ídem
├── paginas/
│   └── test.html          ← ídem (rutas con ../)
└── assets/
    ├── css/
    │   ├── consentidos.css   ← sin cambios
    │   └── tema.css          ← nuevo, de este paquete
    ├── fonts/                ← nuevo, de este paquete
    └── vendor/
        └── fontawesome/      ← nuevo, de este paquete
```

## Cómo empezar

1. Copia **toda** la carpeta `docs/modulos/m02-html/p05-revision/` y pégala
   como `docs/modulos/m03-css/p01-tema-visual/`.
2. Sustituye su `README.md` por el de este paquete y copia la carpeta
   `assets/` del paquete encima de la que ya tienes (solo añade archivos).
3. Abre con **Live Server** y sigue la guía.

## Dos avisos antes de empezar

> **Ten la consola abierta** (**F12** o **Ctrl+Shift+I**). La CSP de tus
> páginas bloquea las fuentes alojadas en el sitio hasta que añadas `'self'` a
> `font-src`; la consola te dirá exactamente qué bloqueó.
>
> **Live Server sigue apareciendo en la consola**, como en la Práctica 5: su
> script de recarga lo bloquea tu política. Ese aviso es esperado.

## Antes de entregar

1. Revisa las **siete** páginas publicadas, en modo claro y en modo oscuro,
   con la consola abierta: ningún recurso del sitio bloqueado.
2. Registra la ficha de la práctica en `docs/modulos/index.html`.
3. Confirma y sube:

   ```bash
   git add docs/modulos/m03-css/p01-tema-visual docs/modulos/index.html
   git commit -m "M03 Práctica 1: tema visual con tema.css"
   git push
   ```

4. Sube a Moodle el PDF de evidencia, con el nombre exacto
   `4GS121-NN_Apellido-Nombre_M03_Pra01.pdf`.

## Recuerda

- `consentidos.css` no se modifica: si una regla tuya no gana, la respuesta
  está en la cascada, no en `!important`.
- Tu identificación sigue **en la cabecera** de todas las páginas.
