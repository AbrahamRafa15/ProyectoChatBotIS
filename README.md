# ProyectoChatBotIS
Proyecto de Ingeniería de Software Otoño 2024. Chatbot para guiar a una persona que acaba de entrar al ITAM

2. Plan de Calidad
Objetivo del Plan de Calidad
El Plan de Calidad tiene como objetivo asegurar que el chatbot cumple con los requerimientos funcionales, no funcionales y las expectativas del usuario final, brindando una experiencia eficiente, intuitiva y precisa.

Estándares de Calidad
Se definirán estándares con base en ISO/IEC 25010 para la calidad del software:
Funcionalidad: El chatbot debe ofrecer respuestas precisas y alineadas a las preguntas planteadas.
Eficiencia: Respuesta rápida (menos de 3 segundos en promedio).
Usabilidad: Interfaz amigable, con navegación intuitiva.
Confiabilidad: El chatbot debe tener una disponibilidad del 99%.
Mantenibilidad: Código modular y documentación detallada.
Portabilidad: Compatible con múltiples dispositivos y navegadores.

Criterios de Aceptación
El proyecto será considerado exitoso si cumple con los siguientes criterios:
Respuestas adecuadas y funcionales:
Al menos 90% de las interacciones cumplen con los flujos diseñados.
Respuestas en menos de 3 segundos.
Accesibilidad y navegación fluida:
Las opciones y botones deben funcionar en todas las plataformas compatibles.
Estabilidad del sistema:
El chatbot no debe presentar errores críticos en las pruebas funcionales.
Documentación técnica completa:
Entrega del ReadMe con instrucciones claras.




Tipo de prueba
Descripción
Herramienta a usar
Pruebas unitarias
Evaluar componentes individuales del chatbot.
Jest, Mocha
Pruebas de integración
Validar interacciones entre botones y respuestas.
Postman, Insomnia
Pruebas funcionales
Revisar que los botones y respuestas funcionen correctamente.
Manual / Selenium
Pruebas de rendimiento
Medir tiempos de respuesta y uso de recursos.
JMeter
Pruebas de usabilidad
Validar la experiencia del usuario con evaluadores externos.
Feedback en clase
Pruebas de regresión
Asegurar que nuevas funcionalidades no rompan el sistema.
Git + Test Automáticos


5. Resultados Esperados
Chatbot funcional y entregado en la fecha establecida.
Disponibilidad: 99% durante las pruebas finales.
Respuestas precisas y alineadas al objetivo del ITAM.
Documentación clara y completa para replicar el proyecto.


6. Documentación para Replicar el Proyecto
1. Requisitos Previos
Para replicar y ejecutar el proyecto se necesita:
Sistema Operativo: Windows, macOS o Linux.
Herramientas:
Gestor de versiones: Git.
Entorno de desarrollo: Node.js v18+ y un editor de texto (recomendado: Visual Studio Code).
Accesos: Configuraciones y claves API necesarias para servicios externos.

2. Clonación del Proyecto
Obtener el enlace del repositorio.
Clonar el repositorio localmente:
Ubicarse en el directorio deseado y ejecutar el comando para clonar.
Confirmar que la estructura de archivos se haya descargado correctamente.

3. Configuración del Proyecto
Revisar los archivos de configuración y ajustes iniciales.
Definir variables de entorno:
Crear un archivo .env con parámetros críticos (puertos, claves, etc.).
Instalar las dependencias necesarias siguiendo los lineamientos proporcionados.

4. Ejecución del Proyecto
Iniciar el servidor local del chatbot.
Validar que las funcionalidades respondan correctamente en el navegador.
Confirmar la navegación entre menús y respuestas esperadas.

5. Verificación de Funcionalidades
Realizar pruebas básicas:
Navegación: Funcionalidad de los botones principales.
Respuestas: Validación de mensajes y redirecciones correctas.
Retorno: Flujo adecuado hacia el menú principal.

6. Validación Final
El proyecto se considerará replicado exitosamente cuando:
El servidor funcione sin errores.
Las respuestas y navegación del chatbot sean correctas.
El entorno esté configurado y documentado adecuadamente.

7. Observaciones
Para evitar errores, se recomienda mantener actualizados los archivos de configuración y revisar periódicamente la documentación.





