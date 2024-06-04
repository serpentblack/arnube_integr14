# APIs en python integrada con lambda, CloudFormation y otras tecnologías de AWS

Durante esta semana de práctica técnica, crearás una solución integral que combine AWS Lambda, AWS Serverless Application Model (SAM), bases de datos gestionadas, AWS SQS para la gestión de mensajes, EventBridge para tareas programadas y AWS Systems Manager Parameter Store. Las funciones Lambda se implementarán utilizando el lenguaje de programación Python y se integrará la plataforma de servicios de correo electrónico en la nube Sendgrid para el envío de  correos electrónicos.

Lambda permite ejecutar código sin necesidad de gestionar servidores, escalando automáticamente según la demanda, mientras que las bases de datos gestionadas ofrecen un rendimiento confiable y escalabilidad automática. AWS SAM facilita la definición y despliegue de aplicaciones sin servidor, reduciendo el tiempo de desarrollo y mantenimiento. SQS gestiona mensajes entre componentes, EventBridge maneja tareas programadas y la orquestación de eventos, y Parameter Store proporciona almacenamiento seguro para parámetros de configuración. Este conjunto tecnológico permite a los desarrolladores centrarse en la lógica de negocio y optimizar el rendimiento de las aplicaciones.

## Pre requisitos

* **SAM CLI** https://docs.amazonaws.cn/en_us/serverless-applicationmodel/latest/developerguide/install-sam-cli.html
* **AWS CLI** https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
* **Docker** https://docs.docker.com/engine/install/

## ¿Qué haremos durante esta semana?

* Crear funciones lambda en aws usando python y Cloudformation
* Crear base de datos MySQL y Postgres en AWS
* Ver logs de las funciones lambda (CloudWatch)
* Crear proyecto en ECR para ejecutar proyecto local sin la necesidad de desplegar en aws
* Integracion de base de datos en las funciones Lambda
* Creación de SQS y agregarlo a CloudFormation
* Envió de mensajes usando Sendgrid
* Creación de Cron en AWS usando EventBrige y añadirlo en CloudFormation





