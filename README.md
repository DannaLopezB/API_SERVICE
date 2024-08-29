# Wit.ai API Example
Este repositorio contiene un ejemplo de una API que utiliza Wit.ai para el procesamiento de lenguaje natural. La API se probó y configuró utilizando Postman.

## Requisitos Previos
- Cuenta en Wit.ai.
- Postman instalado para probar la API.

## Configuración
1. **Crear una Cuenta en Wit.ai**:
  Visita Wit.ai y regístrate utilizando tu cuenta de Facebook o CorreoElectronico.![2](https://github.com/user-attachments/assets/6cc58434-75f0-4831-8748-102630bc72b0)
  Una vez registrado, crea una nueva aplicación y dale un nombre relevante a tu proyecto. ![3](https://github.com/user-attachments/assets/ed13ec52-3b75-44d5-8e75-c56572a17025)

3. **Obtener el Token de Wit.ai**:
   - Ve a la configuración de tu aplicación en Wit.ai y copia el **Server Access Token**. Este token es necesario para autenticar las solicitudes. ![7](https://github.com/user-attachments/assets/1b834ed9-8cf0-4434-a4c3-2e3a9f1fb349)

4. **Configurar la API en Postman**:
   **Crear una Nueva Colección** en Postman para que se vea organizado.
   **Crear una Nueva Solicitud GEST** nos pregutamos porque GEST bunoe porque usa principalmente para consultas simples a la API de Wit.ai.
     - **URL**: `https://api.wit.ai/message`
     - **Headers**:
       - `Authorization: Bearer YOUR_WIT_AI_TOKEN`![5](https://github.com/user-attachments/assets/a52f8876-00d3-43ad-b426-26c888f203e4)

     - **Params**:
       - `q`: El texto que deseas analizar. ![6](https://github.com/user-attachments/assets/a843b659-fd64-4131-83fe-b8054f53ac8c)

     - **Enviar Solicitud**: Haz clic en "Send" para enviar la solicitud y recibir una respuesta con los datos procesados por Wit.ai. ![8](https://github.com/user-attachments/assets/2baa17c4-3695-4a87-a58f-9fcf961a4b11)

¡Danna Lopez Bravo!
