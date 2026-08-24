\# 🏗️ Arquitectura del Proyecto



\## Diagrama de Arquitectura



```mermaid

flowchart TD

&#x20;   U\[👤 Usuario] --> F\[🖥️ Frontend Next.js]

&#x20;   F --> A\[⚙️ API FastAPI]

&#x20;   A --> D\[(🗄️ Base de Datos)]

```



\## ¿Por qué esta arquitectura se adapta mejor a metodologías Ágiles que a Cascada?



1\. \*\*Separación por capas:\*\* El frontend, la API y la base de datos son independientes. Se puede evolucionar una capa sin reescribir todo. Ejemplo: cambiar el diseño web sin tocar la lógica de la API.



2\. \*\*Entregas incrementales:\*\* Se construye y prueba una funcionalidad completa en cada ciclo (ej.: primero productos, luego usuarios, luego ventas), demostrando valor cada vez.



3\. \*\*Adaptación rápida:\*\* Si cambian los requisitos, se ajusta la API y la interfaz en el siguiente Sprint sin afectar todo el sistema. En Cascada habría que reescribir la planificación completa.



4\. \*\*Pruebas continuas:\*\* Al tener componentes separados, se puede probar cada uno por separado a medida que se construye, no esperar al final.



5\. \*\*Menor riesgo:\*\* Si una funcionalidad se cancela o cambia, el resto del sistema sigue funcionando. No se pierde todo el trabajo realizado.



\## En resumen



Esta arquitectura permite cambiar fácilmente, entregar valor rápido y recibir retroalimentación temprana — exactamente lo que promueve el enfoque Ágil.



