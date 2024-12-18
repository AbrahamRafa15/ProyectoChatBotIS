# ProyectoChatBotIS
Proyecto de Ingeniería de Software Otoño 2024. Chatbot para guiar a una persona que acaba de entrar al ITAM


## 3. Arquitectura y Justificación

![Imagen arquitectura](Ingeniería de Software (2).png)

La arquitectura basada en eventos organiza el flujo del chatbot a partir de la generación y manejo de **eventos** que representan las acciones del usuario. En este caso, el chatbot reacciona a eventos específicos, como **mostrar opciones, desplegar el mapa, proporcionar URLs o mostrar información de horarios**, entre otros.
Cada interacción del usuario desencadena un evento que es detectado y procesado de manera independiente. Por ejemplo, al seleccionar “Ver el mapa”, se genera un evento que activa un componente encargado de recuperar y enviar el enlace correspondiente. Este modelo permite que el sistema sea **asíncrono** y **desacoplado**, es decir, las acciones pueden ejecutarse sin depender directamente unas de otras, facilitando la incorporación de nuevas funcionalidades sin modificar el flujo central.
El uso de eventos garantiza una mayor **eficiencia** y **escalabilidad** del chatbot, ya que permite manejar múltiples solicitudes simultáneamente. Además, al estar diseñado en módulos independientes que reaccionan a eventos específicos, el sistema se vuelve más fácil de mantener y expandir en el futuro.
