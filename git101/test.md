De acuerdo a las últimas estadísticas, tenemos un aproximado de 700 a 1000 afiliaciones de usuarios por mes, durante los últimos 5 meses.

Asumiendo que se mantenga esta tendencia, podemos esperar un máximo de 1300 usuarios por mes. Esto es, hasta 1300 notificaciones de nueva afiliación de forma mensual. El cálculo de precios de todos los servicios de SMS depende bastante del volumen de notificaciones, pero se asumirá que se mantendrá en el rango de 1000-5000 SMS mensuales, para estos cálculos.


Servicio: Amazon SNS
Precio: $0.0126 USD (~$0.25 MXN) [x1300 ~330.05 MXN] (posibles costos ocultos. pendiente a revisar)
Documentación: SDK. Tienen un SDK genérico para PHP, se necesita hacer trabajo para adaptarlo a Laravel pero está bien hecho, inlcuyen un [ejemplo sencillo de implementación](https://github.com/awsdocs/aws-doc-sdk-examples/blob/master/php/example_code/sns/SubscribeTextSMS.php). El problema de Amazon SNS es la extensa documentación que tiene muchos específicos y vuelve complicada la evaluación.


Servicio: Twilio
Precio: $0.0490 USD (~$0.99 MXN) [x 1300 = ~1270.0 MXN]
Documentación: Excelente. Nota: Twilio incluye un [SDK para laravel](https://www.twilio.com/blog/create-sms-portal-laravel-php-twilio) que va a acortar el tiempo de implementación, incluyen buenas sugerencias y prácticas.

Servicio: Vonage
Precio: $0.0481 USD ($~0.97MXN) [x 1300 = ~1261.00 MXN]
Documentación: Es la integración por default de Laravel, las clases son sencillas de integrar y configurar.

Servicio: WauSMS
Precio: $0.34240 MXN [x 1300 $445 MXN]
Documentación: Un PDF, con codigos de ejemplo PHP.

Servicio: Altiria
Precio: 0.45 MXN [x 1300 = 585.00 MXN]
Documentación: Es un PDF con las especificaciones del API.

Servicio: SMS Masivos
Precio: 0.77 MXN [x 1300 = 1000 MXN]
Documentación: OpenAPI. Se requiere crear una clase de conexión a el servicio, esto nos hace más sencillo cambiar de proveedor en el futuro, pero lleva tiempo de desarrollo.
> Esta es la librería de "ejemplo" que proporcionan, es una [implementación](https://bitbucket.org/smsmasivos/php-v2/src/master/classes/sms.php) pura y dura de cURL en PHP.

Servicio: SmartSMS
Precio: $0.49 MXN
Documentación: Ninguna, o al menos no es pública.
