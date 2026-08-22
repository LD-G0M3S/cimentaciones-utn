# cimentaciones-utn

Herramientas interactivas de cálculo para la cátedra de Cimentaciones - UTN FRGP
(Universidad Tecnológica Nacional, Facultad Regional General Pacheco).

Aplicaciones web pensadas para hacer visible conceptos que en el pizarrón quedan en una
fórmula: se modifican los datos y las verificaciones se recalculan en tiempo real, con los
diagramas asociados.

## Estado del proyecto

Versión beta - acceso restringido.
Las herramientas están en revisión y su uso requiere un código de acceso.

## Herramientas disponibles

### Fundación con carga excéntrica

Zapata sometida a carga normal y momento, resuelta en paralelo por las tres verificaciones
que conviven sobre la misma pieza:

* **Suelo en servicio (ASD, práctica argentina):** cargas sin mayorar, presión bruta,
  excentricidad y control de despegue, tensión máxima contra tensión admisible.
* **Suelo en estados últimos (formato AASHTO LRFD):** cargas mayoradas, demanda uniforme
  sobre el área efectiva de Meyerhof, resistencia afectada por un factor φ_b.
* **Hormigón en estados últimos (CIRSOC 201-2005):** cargas mayoradas, presión neta de
  diseño para dimensionar armadura, corte y punzonado.

Una pestaña de comparación contrasta las dos primeras sobre la misma zapata: utilizaciones,
B mínimo requerido por cada rama y el factor de seguridad global implícito. Ahí se ve si
las dos filosofías conducen o no a la misma fundación, y bajo qué condiciones se cruzan.

El objetivo didáctico es doble: que la presión mayorada del hormigón es un artificio de
cálculo y no una presión que el suelo llegue a experimentar; y que la diferencia entre
criterios no es de equilibrio sino de formato de seguridad, coeficiente global en un caso,
factores parciales en el otro.

Base normativa: CIRSOC 101-2005, CIRSOC 201-2005, EN 1997-1 (Eurocódigo 7) y AASHTO LRFD
Bridge Design Specifications.

## Cómo obtener acceso

El acceso está abierto a estudiantes de Ingeniería Civil, docentes y profesionales que
quieran probar las herramientas y aportar correcciones.

1. Completá el formulario de solicitud: https://forms.cloud.microsoft/r/btB8pZr6sC?origin=lprLink
2. Al enviarlo recibís el enlace y el código de acceso.

También podés escribirme por LinkedIn: www.linkedin.com/in/leandro-daniel-gomes-58989272

## Reporte de errores

Toda la etapa beta existe para eso. Dentro de cada herramienta hay un botón **Reportar un
error**. Se agradecen especialmente los reportes sobre resultados que no cierren, hipótesis
de cálculo que no queden claras y textos que se presten a confusión.

## Condiciones de uso

* Uso académico. Estas herramientas no reemplazan el criterio ni la responsabilidad
  profesional de quien firma un proyecto.
* Al tratarse de versiones en revisión, los resultados deben verificarse antes de aplicarlos
  a un caso real.
* El acceso es personal y no está autorizada la redistribución.
* Todos los derechos reservados. El repositorio es público a los fines de la publicación
  web, lo que no implica licencia de uso, copia o modificación del código.

## Autor

**Ing. Leandro Daniel Gomes**
Profesor de Cimentaciones - UTN FRGP
Ingeniero civil, especializado en estructuras y fundaciones

© 2025-2026
