# Informe de exposiciones: herramientas de modelado y generación de código

> Registro académico de las exposiciones realizadas sobre herramientas CASE, modelado UML y generación automática de código.

| Información | Detalle |
|---|---|
| **Estudiante** | Erick Jhair Mera Arias |
| **Curso** | 4.º Software «A» |
| **Asignatura** | Ingeniería de Requisitos |
| **Fecha** | 20 de julio de 2026 |

## Contenido

1. [Resumen general](#resumen-general)
2. [Grupo H — Enterprise Architect](#grupo-h--enterprise-architect)
3. [Grupo A — StarUML](#grupo-a--staruml)
4. [Grupo G — Umple Online](#grupo-g--umple-online)
5. [Grupo E — Eclipse Papyrus y Acceleo](#grupo-e--eclipse-papyrus-y-acceleo)
6. [Grupo B — BOUML](#grupo-b--bouml)
7. [Grupo D — Modelio](#grupo-d--modelio)
8. [Grupo C — Visual Paradigm](#grupo-c--visual-paradigm)
9. [Grupo F — Software Ideas Modeler](#grupo-f--software-ideas-modeler)
10. [Conclusión general](#conclusión-general)

## Resumen general

| Grupo | Integrantes | Herramienta | Trazabilidad presentada |
|:---:|---|---|:---:|
| **H** | Huilcapi, Tigasi y Vaca | Enterprise Architect | No |
| **A** | Escudero, Mera, Mesías y Díaz | StarUML | Grupo del autor |
| **G** | Alvia, Arboleda y Calle | Umple Online | No |
| **E** | Gamarra Araujo y Pérez Ruiz | Eclipse Papyrus + Acceleo | No |
| **B** | Marcillo, Robinson, Kamila y Herrera | BOUML | No |
| **D** | Rizzo, Crespo y Amagua | Modelio | No |
| **C** | Castro, Mora, Vera y Villafuerte | Visual Paradigm | No |
| **F** | Alcívar, Barrionuevo y Quintero | Software Ideas Modeler | Parcial, con observaciones |

---

## Grupo H — Enterprise Architect

**Integrantes:** Denisses Huilcapi, Paul Tigasi y David Vaca  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### ¿Qué es Enterprise Architect? — Huilcapi

Enterprise Architect es una herramienta de modelado visual y diseño de software desarrollada por Sparx Systems. Permite crear diagramas UML 2.5, representar procesos de negocio mediante BPMN 2.0 e implementar marcos de arquitectura empresarial como TOGAF y Zachman.

#### Ciclo de modelado integral — Huilcapi

La herramienta trabaja con estándares como UML 2.5, BPMN 2.0 y otros lenguajes de arquitectura y modelado. UML facilita la elaboración de diagramas estructurales y de comportamiento, entre ellos los diagramas de clases, secuencia y casos de uso.

#### Funcionamiento — Vaca

Enterprise Architect cubre un ciclo de modelado que comprende negocio, requisitos, análisis, diseño, implementación, pruebas y mantenimiento. Los artefactos se almacenan en un repositorio central, lo que permite relacionarlos y dar seguimiento a los cambios.

#### Diagramas presentados — Vaca

- Diagrama de casos de uso.
- Diagrama de clases.
- Diagrama de estados.

#### Funciones principales — Vaca

- Gestión de requisitos y matriz de trazabilidad.
- Vinculación entre requisitos y diseño.
- Seguimiento de cambios.
- Generación automática de documentación.
- Exportación de reportes a Word o HTML.
- Ingeniería inversa de código.

#### Ventajas — Tigasi

La herramienta integra requisitos, análisis y diseño en una misma plataforma. Además, ofrece un rendimiento adecuado para proyectos grandes y equipos multidisciplinarios.

#### Limitaciones — Tigasi

Presenta una curva de aprendizaje elevada debido a la cantidad de funciones disponibles. Requiere licencia comercial e instalación local y ofrece menos posibilidades de colaboración en tiempo real que algunas plataformas basadas en la nube.

#### Respaldo académico y profesional — Tigasi

Su respaldo se relaciona con el uso de estándares del Object Management Group (OMG), entre ellos UML 2.5, BPMN 2.0, SysML y ArchiMate.

### Demostración práctica

- Exploración de la interfaz principal.
- Creación de un diagrama de clases con atributos, métodos y operaciones.
- Incorporación de asociaciones, composiciones y agregaciones.
- Uso de la caja de herramientas y definición de cardinalidades.
- Generación de código a partir de un modelo UML.

---

## Grupo A — StarUML

**Integrantes:** Escudero, Mera, Mesías y Díaz.  
**Observación:** corresponde al grupo del autor del informe.

---

## Grupo G — Umple Online

**Integrantes:** Alvia, Arboleda y Calle.  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### ¿Qué es Umple y POM? — Alvia

Umple fue presentada como una herramienta intuitiva para crear modelos y generar código. Permite mantener sincronizados el código y el diagrama, de modo que los cambios realizados en uno puedan reflejarse en el otro. Asimismo, admite varios lenguajes de programación.

#### Sincronización vertical — Alvia

Durante la exposición se mostró el entorno web y los distintos diagramas disponibles. También se indicó que el proyecto de la camaronera empleaba C# y que el soporte de este lenguaje todavía se encontraba en fase beta.

#### Características clave — Arboleda

- Modelado estático.
- Máquinas de estados.
- Trazabilidad.

#### Ciclo de desarrollo — Calle

Se explicó el proceso de funcionamiento de la herramienta y se destacó que su interfaz resulta sencilla e intuitiva para el modelado.

#### Facilidad de uso — Calle

Umple fue presentada como una herramienta de código abierto con distintas opciones para apoyar el modelado. Sin embargo, durante la exposición se señaló que varias funciones complementarias son de pago.

### Demostración práctica

- Generación de código Java a partir de un diagrama de clases.
- Modificación de una parte del código desde la interfaz visual.

---

## Grupo E — Eclipse Papyrus y Acceleo

**Integrantes:** Gamarra Araujo y Pérez Ruiz.  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### ¿Qué son Eclipse Papyrus y Acceleo? — Gamarra

Eclipse Papyrus fue presentado como un entorno de modelado que puede complementarse con Acceleo para generar código. La explicación abordó el desarrollo dirigido por modelos y el proceso que parte del diseño, continúa con el modelo y las reglas de transformación y finaliza con la producción de código.

#### MDE, MDA y MDD — Gamarra

Se explicaron los enfoques de Ingeniería Dirigida por Modelos (MDE), Arquitectura Dirigida por Modelos (MDA) y Desarrollo Dirigido por Modelos (MDD), destacando sus distintos niveles de abstracción y su aplicación en el desarrollo de software.

#### Niveles de abstracción — Pérez

- **CIM:** representa procesos y requisitos sin describir detalles tecnológicos.
- **PIM:** expresa el diseño del sistema sin depender de una plataforma específica.
- **PSM:** adapta el modelo a una tecnología o plataforma concreta.

#### Beneficios del MDD — Gamarra y Pérez

El MDD permite automatizar parte del desarrollo y mantener relaciones entre modelos y artefactos. Además, las plantillas de transformación ayudan a organizar el proceso, detectar inconsistencias y mejorar la calidad del software generado.

#### Eclipse Papyrus — Gamarra

Papyrus es una herramienta UML basada en Eclipse. Permite editar diagramas, utiliza estándares del OMG, es de código abierto y puede ampliarse mediante complementos.

#### Acceleo — Pérez

Acceleo se integra en el entorno Eclipse para transformar modelos en código mediante plantillas de generación.

#### Integración de las herramientas — Pérez

Ambas herramientas son de código abierto y trabajan con estándares del OMG. La exposición señaló que su integración facilita la generación de código a partir de modelos, aunque no permite realizar el proceso inverso de la misma manera.

### Demostración práctica

- Creación de un modelo UML.
- Generación de código Java desde un diagrama de clases.
- Revisión de atributos y métodos generados.
- Modificación del código y demostración de ingeniería inversa.

---

## Grupo B — BOUML

**Integrantes:** Marcillo, Robinson, Kamila y Herrera.  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### Ingeniería Dirigida por Modelos — Marcillo

La presentación abordó MDE como metodología de desarrollo de software organizada en tres niveles: CIM, PIM y PSM. El caso de estudio aplicado en BOUML correspondió a un sistema de gestión de citas para una veterinaria.

#### MDD y funcionamiento — Robinson

Se explicó que BOUML permite generar código a partir de modelos UML y recuperar modelos desde código existente. También se presentó una breve historia de la herramienta y se revisaron diagramas estructurales, de comportamiento y de interacción.

#### Ventajas — Kamila

- Rapidez de funcionamiento.
- Bajo consumo de recursos.
- Facilidad de uso.

#### Lenguaje Unificado de Modelado — Robinson

UML permite representar la estructura y el comportamiento de un sistema antes de programarlo. Sus diagramas ayudan a comprender las funcionalidades identificadas durante el análisis de requisitos.

#### Comparación con otras herramientas — Kamila

BOUML fue destacada por su eficiencia y velocidad. Además, admite ingeniería directa para transformar modelos UML en código fuente.

#### Ingeniería inversa — Herrera

La ingeniería inversa permite transformar código en modelos, recuperar proyectos antiguos y documentar sistemas que carecen de representaciones UML actualizadas.

### Demostración práctica

- Exploración de la interfaz principal.
- Carga de un diagrama con clases, atributos, cardinalidades y relaciones.
- Generación de código desde el modelo.
- Incorporación de un nuevo atributo a una clase.
- Intento de sincronización del cambio con el código, limitado por incompatibilidad con la versión de C++ utilizada.

---

## Grupo D — Modelio

**Integrantes:** Rizzo, Crespo y Amagua.  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### ¿Qué es Modelio? — Rizzo

Modelio es una herramienta de modelado compatible con estándares como UML, BPMN y ArchiMate. Dispone de mecanismos para verificar la consistencia, organizar jerárquicamente los proyectos y ampliar sus funciones mediante módulos.

#### Historia y evolución — Rizzo

La herramienta tuvo como antecedente a Objecteering, desarrollado desde 1991. Posteriormente incorporó soporte para MDA y UML y, en 2011, fue presentada como una herramienta de código abierto. También ofrece funciones de modelado e ingeniería inversa.

#### Características principales — Rizzo

- Modelado UML completo.
- Verificación de consistencia mediante auditorías.
- Compatibilidad con UML 2, BPMN 2 y ArchiMate.
- Organización jerárquica de proyectos.
- Arquitectura modular y extensible.
- Disponibilidad para distintos sistemas operativos.

#### Interfaz y diagramas disponibles — Crespo

La interfaz está formada por el explorador del modelo, el área de trabajo, la paleta de herramientas y la vista de propiedades. Permite elaborar diagramas estructurales, de comportamiento, actividad, estados, procesos de negocio, diccionarios de datos y arquitectura.

#### Estereotipos y elementos de modelado — Crespo

La herramienta admite estereotipos para identificar la función de los elementos del modelo. Durante la exposición se mostraron estereotipos de dominio e identidad, además de la configuración necesaria para generar código Java.

#### Ventajas — Amagua

Modelio dispone de un núcleo de código abierto, soporte para UML, BPMN y ArchiMate, arquitectura modular, compatibilidad con distintos sistemas operativos y una comunidad activa.

#### Limitaciones — Amagua

Presenta una curva de aprendizaje pronunciada y algunas funciones avanzadas requieren módulos de pago. Parte de su documentación se encuentra en inglés y francés. Además, el código agregado manualmente puede perderse durante una nueva generación si no se aplica un control adecuado.

#### Beneficios y limitaciones del MDD — Amagua

El MDD permite generar código desde diagramas UML, reducir tiempos de desarrollo, disminuir errores y facilitar la documentación, el mantenimiento y la reutilización. Sin embargo, exige conocimientos de UML, ajustes manuales y un control apropiado de los cambios.

#### Conclusión — Amagua

Modelio fue presentada como una herramienta madura, extensible y adecuada para aprender modelado de software. Su capacidad para generar código Java y trabajar con diferentes estándares favorece su uso en proyectos académicos.

### Demostración práctica

- **Rizzo:** mostró la interfaz, los módulos, la organización jerárquica y un diagrama de clases para un sistema de gestión de una camaronera.
- **Crespo:** configuró la generación de código, seleccionó el directorio de salida y verificó las clases, atributos y operaciones creadas.
- **Amagua:** presentó un diagrama de estados asociado al requisito 5 de la planificación de la siembra y explicó el flujo entre sus estados.

---

## Grupo C — Visual Paradigm

**Integrantes:** Castro, Mora, Vera y Villafuerte.  
**Observación:** no presentó trazabilidad.

### Contenido expuesto

#### MDE, MDA y MDD — Castro

MDE convierte los modelos en fuentes principales para producir otros artefactos. MDA organiza el modelado en los niveles CIM, PIM y PSM, mientras que MDD aplica estos principios directamente al desarrollo del software.

#### Perfiles y estereotipos UML — Castro

Los perfiles UML adaptan el lenguaje de modelado a las necesidades de un proyecto. Durante la exposición se utilizaron los estereotipos `entity`, `service` y `repository` para identificar la responsabilidad de cada clase.

#### Configuración del generador de código — Mora

La generación se configuró con Java como lenguaje objetivo, codificación UTF-8 y compatibilidad con JDK 8. También se definieron el mapeo de asociaciones múltiples, la carpeta de salida y la política de regeneración.

#### Generación y estructura del proyecto — Vera

La generación automática produce la estructura básica de las clases, pero no implementa toda la lógica de negocio. Por ello, las reglas de negocio, la persistencia, el manejo de errores y las pruebas unitarias deben desarrollarse manualmente.

#### Justificación de la herramienta — Villafuerte

Visual Paradigm fue seleccionada porque transforma diagramas en código mediante Instant Generator. Los proyectos se almacenan en archivos `.vpp`; además, la herramienta admite estereotipos UML y permite representar clases y relaciones.

### Demostración práctica

- **Castro:** explicó los estereotipos y el proceso de validación aplicado a la clase `Palma`.
- **Mora:** configuró Instant Generator, seleccionó los elementos del modelo, estableció Java y UTF-8 y definió el directorio de destino.
- **Vera:** explicó las restricciones para generar código C# y la disponibilidad de la generación en Java.
- **Villafuerte:** mostró la interfaz y el diagrama de clases del proyecto Sigma.

---

## Grupo F — Software Ideas Modeler

**Integrantes:** Alcívar, Barrionuevo y Quintero.  
**Observación:** presentó parcialmente la trazabilidad y los requisitos, pero se identificaron aspectos por mejorar.

### Contenido expuesto

#### ¿Qué es Software Ideas Modeler? — Alcívar

La herramienta fue presentada como una alternativa versátil para elaborar modelos UML durante el desarrollo de sistemas.

#### Funcionalidades — Barrionuevo

- Motor de generación de código.
- Soporte para estereotipos y perfiles UML.
- Validación de modelos.
- Uso de bloques protegidos.
- Interfaz intuitiva.

#### Generación del modelo — Barrionuevo

Se explicó que la herramienta permite generar archivos a partir de los modelos elaborados.

#### Ventajas — Quintero

- Automatización y reducción del tiempo requerido para generar artefactos.
- Interfaz disponible en español.
- Indicadores para revisar el estado del diagrama durante el modelado.

#### Limitaciones — Quintero

- Algunas estructuras de código generadas requieren ajustes.
- Determinada información puede resultar extensa y compleja de interpretar.

#### Caso de estudio — Quintero

El caso seleccionado correspondió a un sistema de gestión para una camaronera.

### Demostración práctica

- Creación de requisitos con atributos como identificador y prioridad.
- Registro de estanques y siembras.
- Configuración de una alerta de crecimiento bajo.
- Elaboración de casos de uso para la gestión de estanques y siembras.
- Aplicación de ingeniería inversa para crear diagramas desde código.

---

## Conclusión general

Las exposiciones permitieron comparar herramientas con capacidades diferentes para modelado UML, administración de requisitos, trazabilidad, generación de código e ingeniería inversa. Enterprise Architect destacó por la integración de múltiples etapas del ciclo de desarrollo; Umple, Eclipse Papyrus con Acceleo, BOUML, Modelio, Visual Paradigm y Software Ideas Modeler mostraron alternativas para transformar modelos en artefactos de software. No obstante, la mayoría de los grupos no presentó una trazabilidad completa, aspecto que debe fortalecerse para evidenciar la relación entre requisitos, modelos y código generado.

## Fuente del informe

Mera Arias, E. J. (2026). *Informe de exposiciones: herramientas de modelado y generación de código* [Documento académico no publicado].
