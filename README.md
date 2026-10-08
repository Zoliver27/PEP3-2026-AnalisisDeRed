# Sistema de Análisis Estadístico de Uso de Red Universitaria

Repositorio académico del proyecto de Probabilidad y Estadística (PEP3-2026).

## Descripción
La propuesta plantea un sistema para analizar estadísticamente registros históricos de uso de la red universitaria. Entre los objetivos propuestos están identificar patrones temporales, resumir datos con estadística descriptiva y calcular probabilidades a partir de datos disponibles y autorizados.

## Objetivo y alcance propuestos
- Importar y limpiar datos de entrada, previstos en formatos CSV o Excel.
- Calcular frecuencias absolutas y relativas, media, mediana, moda, rango, varianza y desviación estándar.
- Explorar patrones temporales y probabilidades empíricas o condicionales.
- Presentar resultados mediante tablas y gráficos.

Son funcionalidades previstas en la propuesta, no una afirmación de que ya estén implementadas. El alcance definitivo debe confirmarse con el equipo y el docente.

## Tecnologías
La propuesta contempla C#/.NET. La tecnología de interfaz y la arquitectura definitiva todavía deben confirmarse. No hay instrucciones de instalación o ejecución hasta que exista una versión ejecutable.

## Estado del proyecto
**Estado registrado: planificación y organización inicial del repositorio.** Actualizar esta sección cuando el equipo verifique avances reales.

## Estructura del repositorio
```text
docs/
  propuesta/       Informes y propuesta
  requisitos/      Requisitos acordados
  arquitectura/    Diagramas y diseño técnico
  planificacion/   Gantt e hitos
  presentaciones/  Presentaciones
  equipo/          Integrantes y responsabilidades
  manuales/        Manuales
  decisiones/      Decisiones documentadas
src/
  Presentacion/    Interfaz (pendiente de definir e implementar)
  Logica/          Reglas y cálculos (pendiente de implementar)
  Datos/           Importación y validación (pendiente de implementar)
tests/             Pruebas cuando existan
data/
  samples/         Solo datos sintéticos o anonimizados
  schemas/         Especificación de archivos de entrada
resources/         Recursos compartibles
.github/           Plantillas de Issues y Pull Requests
```

Las carpetas reservadas pueden contener README de orientación; eso no significa que exista código implementado.

## Documentación
- [Propuesta e informes](docs/propuesta/README.md)
- [Requisitos](docs/requisitos/README.md)
- [Arquitectura](docs/arquitectura/README.md)
- [Planificación y Gantt](docs/planificacion/README.md)
- [Presentaciones](docs/presentaciones/README.md)
- [Equipo](docs/equipo/README.md)
- [Manuales](docs/manuales/README.md)
- [Decisiones del proyecto](docs/decisiones/README.md)

Los documentos originales deben añadirse a su carpeta después de comprobar su versión y contenido.

## Equipo
- **Oliver Matías Zunagua Arce:** Líder, FrontEnd
- **Alison Bejarano Fuertes:** Programación
- **Camila Isabella Andia Sánchez:** Programación, BugFixer

Las responsabilidades se transcriben de los archivos de integrantes existentes.

## Colaboración
1. Crear o comentar un Issue para describir una tarea, error, duda o bloqueo.
2. Crear una rama de trabajo para los cambios.
3. Abrir un Pull Request hacia `main`, describiendo cambios y pruebas realizadas.
4. Revisar los cambios antes de integrarlos y actualizar el Issue o tablero.

Se incluyen plantillas iniciales de Issues y Pull Requests en `.github/`. El tablero de GitHub Projects debe configurarse desde GitHub.

## Privacidad y uso de datos
Trabajar únicamente con registros cuyo uso haya sido autorizado y aplicar anonimización antes de compartirlos. No subir información personal, registros reales sensibles, contraseñas, tokens ni cadenas de conexión. Para pruebas, utilizar datos sintéticos o debidamente anonimizados.
