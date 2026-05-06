# Plantilla de manuscrito/reporte (Quarto)

Plantilla mínima para generar manuscritos y reportes de clase usando Quarto. Incluye estructura recomendada, metadatos y ejemplos para exportar a HTML, PDF y Word.

## Requisitos
- Editor de código. Se sugiere VSCode.
- Extensión Quarto.
- Quarto instalado: https://quarto.org.
- (Opcional) Ejecutar en terminal `quarto install tinytex` para render en formatos pdf y docx.
- (Opcional) R, Python o otro motor soportado (según los snippets del proyecto)
- (Opcional) Dependencias (paquetes) opcionales según los ejemplos incluidos

## Instalación
1. Clonar el repositorio.
2. Abrir la carpeta del proyecto en tu IDE preferido.
3. Ejecutar el comando `quarto preview` o `quarto render`.

## Uso rápido
- Vista previa interactiva:
    - quarto preview .
- Renderizar a formato final:
    - quarto render 

## Personalización
- Editar el bloque YAML en los archivos .qmd para cambiar título, autor, fecha, etc.

## Estructura sugerida para el proyecto
- manuscript.qmd — documento principal
- data/ — datos en formato .csv o .xslx
- figures/ — figuras y recursos
- scripts/ — scripts de Python o R para generar tablas o figuras.
- sections/ — capítulos o secciones parciales
- tables/ — tablas en formatos .md o TeX.
- references.bib — bibliografía

## Contribución
Ajustes simples y mejoras en secciones, estilos y ejemplos son bienvenidos. Abrir issues o pull requests con cambios claros y pruebas de renderizado.

## Licencia
Vease archivo de licencia.
