# Portafolio técnico — Héctor Alejandro Nene

Sitio estático de portafolio con una dirección visual **técnico-editorial**. Está preparado para publicarse en GitHub Pages sin instalar dependencias ni ejecutar un proceso de compilación.

## Estructura

```text
portfolio-hector/
├── index.html
├── 404.html
├── assets/
│   ├── favicon.svg
│   ├── script.js
│   └── styles.css
├── docs/
│   └── README_TEMPLATE.md
└── proyectos/
    ├── automatizacion-procesos.html
    ├── caja-clara.html
    ├── cauce.html
    └── diseno-mecanico.html
```

## Verlo localmente

Se puede abrir `index.html` directamente. Para probarlo como sitio web, desde esta carpeta ejecuta:

```bash
python3 -m http.server 8000
```

Después abre `http://localhost:8000`.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube el contenido de esta carpeta.
2. En el repositorio, entra a **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda y espera a que GitHub muestre la URL publicada.

Los enlaces son relativos, por lo que el sitio funciona tanto en `usuario.github.io` como dentro de `usuario.github.io/nombre-del-repositorio/`.

## Antes de publicar

- Confirmar nombres, cargos, fechas y descripción de las empresas con el CV final.
- Sustituir o ampliar los textos de proyecto con evidencia real.
- Añadir imágenes optimizadas en WebP o AVIF, con texto alternativo descriptivo.
- Agregar vínculos a GitHub o demos sólo cuando los repositorios estén presentables.
- Incorporar el CV final cuando exista una versión aprobada; no se dejó un enlace provisional.
- Verificar que cualquier dato profesional respete acuerdos de confidencialidad.
- Probar el sitio en teléfono y computadora.

## Cómo documentar cada proyecto

La carpeta `docs` incluye una plantilla reutilizable para los README de los repositorios. La regla principal es separar con claridad:

- problema y usuario;
- contribución personal;
- decisiones y restricciones;
- resultado o estado real;
- instalación y uso;
- siguientes pasos.

## Edición rápida

- Colores y tipografía: variables al inicio de `assets/styles.css`.
- Textos de portada: `index.html`.
- Contenido de casos: archivos dentro de `proyectos/`.
- Correo: buscar `alejandronener98@gmail.com` en los HTML.

No se utilizan bibliotecas externas, rastreadores ni formularios que almacenen datos.
