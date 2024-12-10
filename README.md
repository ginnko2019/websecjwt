# websecjwt

## Arquitectura

![Screenshot 2024-12-10 at 7 46 52 AM](https://github.com/user-attachments/assets/6d8b906a-20ad-4315-b6ef-d6189f738dc9)

Dentro de la arquitectura se pueden evidenciar diferentes servicios a continuación explicaré cada uno:

### AWS Amplify
Se utilizó como un servicios en AWS para poder cargar el front-end sin necesidad de servidor. Todo lo que se requiere ya se encuentra preconfigurado.

### Amazon Cognito
Se empleó como servicio de autenticación que permite que los recursos del front se encuentren protegidos.

### API Gateway 

El JavaScript que se ejecuta en el navegador envía peticiones a través de un backend creado a través de funciones lamda y apiu gateway para crear un recurso rest que utilizará el front. 

## Ejemplo de funcionamiento AWS

![Screenshot 2024-12-10 at 7 54 01 AM](https://github.com/user-attachments/assets/57653502-cc07-485c-8584-e8addc5ac10d)

### Registro
![Screenshot 2024-12-10 at 7 55 35 AM](https://github.com/user-attachments/assets/c83030ed-3a99-4d9c-bf82-598d9b2e11d3)


### Verificación

![Screenshot 2024-12-10 at 7 57 10 AM](https://github.com/user-attachments/assets/de3f3f92-3fd5-4b65-b2f8-5c7e23c759e3)

![Screenshot 2024-12-10 at 7 57 51 AM](https://github.com/user-attachments/assets/5f85d440-fbce-4be6-bcfe-82de894684de)


### Autenticación
![Screenshot 2024-12-10 at 7 58 25 AM](https://github.com/user-attachments/assets/6385cc30-303e-4ce3-a849-80c158466106)
