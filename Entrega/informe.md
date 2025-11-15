# Informe Técnico del Taller
---
## Nombre del Taller

Taller 2 - BPMN

---
## Intergantes del equipo

- Julián David Alvarado Gantiva
- Julián Camilo Durán Valencia
- Sebastián Piñeros Castellanos
---

## Descripción general del trabajo

En el taller presente se realiza la implementación de la metodología BPMN para el caso de aplicación con respecto al cliente asociado al grupo. En el diagrama que se encuentra en este mismo repositorio se define el proceso que se llevara a cabo con la solución propuesta por el grupo. Este archivo se encuentra bajo el nombre ModeloCasoReal.jpeg bajo el directorio "entrega".

---
## Proceso de desarrollo

Para la realización del trabajo se decidió modelar el proceso de envío de extracto al cliente utilizando la herramienta draw.io, dado que permite construir diagramas BPMN de manera colaborativa y sencilla. En primer lugar, se identificaron las actividades principales del flujo, comenzando por el evento de inicio y la tarea de identificación del cliente. Posteriormente, se definieron las dos posibles ramas de decisión (clientes de Zipa tractores y de Chía Motomart) y se asignaron las tareas correspondientes a cada caso.

Inicialmente se modeló la secuencia básica: identificación del cliente, envío de correo, revisión del extracto y confirmación final. Luego, en una fase de ajuste, se incorporó el nodo de aprobación del proceso para unificar ambas ramas antes de llegar a la confirmación del cliente, con el fin de reflejar un control de calidad centralizado. Finalmente, se añadieron los eventos de inicio y fin, asegurando que el diagrama representara un ciclo completo y claro.

De esta forma, las decisiones principales giraron en torno a qué actividades incluir, cómo representar la bifurcación de clientes y dónde centralizar la aprobación, logrando un modelo coherente y entendible.

---
##  Análisis del modelo propuesto

Para la realización del trabajo se utilizó la herramienta draw.io, por su facilidad para modelar procesos en notación BPMN. En primer lugar, se definieron las tareas esenciales del flujo: identificación del cliente, envío del extracto, revisión, aprobación y confirmación final. Inicialmente se construyó una secuencia simple y posteriormente se incorporó la bifurcación por tipo de cliente (Zipa Tractores y Chía Motomart), así como la tarea de aprobación del proceso que centraliza la validación antes de la confirmación al cliente. Finalmente, se añadieron los eventos de inicio y fin, cerrando el ciclo completo.

Análisis del modelo:

- Estructura del modelo: El diagrama se organiza de manera lineal con una bifurcación condicional que distingue a los clientes según su procedencia. Ambos caminos confluyen en una etapa de aprobación centralizada antes de la confirmación al cliente. Esto asegura claridad en la secuencia de actividades y evita duplicidad en la validación.

- Representación de las necesidades del cliente: El modelo responde a la necesidad de garantizar que cada cliente reciba su extracto de manera correcta y validada. La bifurcación permite atender casos específicos de clientes distintos, mientras que la aprobación asegura calidad y consistencia en la información enviada.

- Supuestos tomados: Se asumió que el flujo para ambos tipos de cliente es equivalente, diferenciándose únicamente en el responsable del envío inicial. También se consideró que el área encargada de la revisión sigue un procedimiento estandarizado, y que la aprobación centralizada representa una etapa obligatoria para garantizar confiabilidad antes de la comunicación final.

---
## Diagrama final entregado

![alt text](image.png)

---
## Tabla de actores, entidades o componentes

| Nombre del elemento | Tipo      | Descripción                                               | Responsable         |
|----------------------|-----------|-----------------------------------------------------------|---------------------|
| Cliente              | Actor     | Persona o empresa que solicita el extracto                | Cliente             |
| Jefe encargado Zipa  | Actor     | Responsable de recibir y gestionar solicitudes en Zipa    | Área Zipa Tractores |
| Jefe encargado Chía  | Actor     | Responsable de recibir y gestionar solicitudes en Chía    | Área Chía Motomart  |
| Área de revisión     | Entidad   | Encargada de verificar la validez y consistencia del extracto | Equipo interno      |
| Aprobación proceso   | Componente| Etapa donde se valida y autoriza el envío final           | Responsable interno |

---
## Investigación complementaria

Tema investigado: Buenas prácticas en el modelado de procesos con BPMN.

Resumen:

El modelado de procesos mediante BPMN (Business Process Model and Notation) se ha convertido en un estándar para documentar y optimizar flujos de negocio. Una de las buenas prácticas más destacadas es mantener la simplicidad en los diagramas, evitando un exceso de elementos que dificulten su lectura (Visual Paradigm, s.f.). Además, es recomendable definir claramente los eventos de inicio y fin, ya que esto facilita que cualquier miembro de la organización comprenda cuándo empieza y concluye un proceso.

Otra práctica clave consiste en utilizar adecuadamente compuertas de decisión, de manera que las bifurcaciones representen de forma precisa las diferentes rutas posibles sin ambigüedades. Finalmente, se recomienda centralizar las validaciones y aprobaciones para evitar redundancias y asegurar la calidad de los procesos (Business Process Experts, s.f.).

Estas recomendaciones se relacionan directamente con el taller realizado, ya que al modelar el envío de extractos al cliente se aplicaron estas prácticas: se identificaron eventos de inicio y fin, se incorporó una bifurcación según el tipo de cliente, y se añadió una etapa de aprobación unificada para garantizar claridad y consistencia.

---

## Referencias

Visual Paradigm. (s.f.). *BPMN essentials: A comprehensive guide to business process modeling and notation*. Recuperado el 15 de agosto de 2025 de https://blog.visual-paradigm.com/bpmn-essentials-a-comprehensive-guide-to-business-process-modeling-and-notation/

Business Process Experts. (s.f.). *Best practices for creating effective BPMN diagrams*. Recuperado el 15 de agosto de 2025 de https://businessprocessxperts.com/best-practices-for-creating-effective-bpmn-diagrams/