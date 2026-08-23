# cimentaciones-utn

Herramientas interactivas de cálculo para la cátedra de Cimentaciones - UTN FRGP
(Universidad Tecnológica Nacional, Facultad Regional General Pacheco).
Aplicaciones web pensadas para hacer visible conceptos que en el pizarrón quedan en una
fórmula: se modifican los datos y las verificaciones se recalculan en tiempo real, con los
diagramas asociados.

## Estado del proyecto

Versión beta - acceso restringido.
La v8 está en desarrollo activo y se publica por etapas: los módulos de envolvente,
dimensionamiento y resumen están implementados de forma parcial. Su uso requiere un código
de acceso.

## Herramientas disponibles

### Fundación con carga excéntrica (`index.html`)

Zapata aislada bajo carga normal, momento y fuerza horizontal, resuelta en los **dos planos
normativos** que conviven sobre la misma pieza:

* **Plano de asiento, en servicio (art. 15.2.2):** cargas sin mayorar, presión bruta
  incluyendo peso propio y tapada, excentricidad, control de despegue y tensión máxima
  contra σadm.
* **Plano estructural, en estados últimos (art. 9.2.1 y 15.2.1):** combinaciones (9-1) a
  (9-6), presión neta de diseño y envolvente de solicitaciones para dimensionar.

Las acciones se ingresan por tipo (D, L, W) en el plano elegido y se trasladan al plano de
asiento con una regla única, M_base = M + H·z. Incluye predimensionado de B y L con criterio
de forma y restricción de excentricidad, vista en planta con núcleo central, diagrama de
presiones brutas de servicio y superposición de las presiones últimas.

El objetivo didáctico es mostrar que cada plano usa cargas distintas y presiones distintas,
y que mezclarlos es el error más frecuente: la presión mayorada del hormigón es un artificio
de cálculo y no una presión que el suelo llegue a experimentar.

Alcance: no se implementan las combinaciones sísmicas (9-5) y (9-7), la fracción de momento 
transferida por corte excéntrico γ_v, ni el reemplazo de 1,6·W por 1,3·W del art. 9.2.1 a).

Base normativa: CIRSOC 101-2005 y CIRSOC 201-2005.
En estudio para versiones futuras: la comparación con formatos de factores parciales
(EN 1997-1, AASHTO LRFD).

## Cómo obtener acceso

El acceso está abierto a estudiantes de Ingeniería Civil, docentes y profesionales que
quieran probar las herramientas y aportar correcciones.

Escribirme por LinkedIn: [www.linkedin.com/in/leandro-daniel-gomes-58989272](https://www.linkedin.com/in/leandro-daniel-gomes-58989272)

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
