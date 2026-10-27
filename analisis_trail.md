¿Desde qué dirección IP o servicio se originó la creación de la instancia
según el JSON?

"eventTime": "2026-10-27T03:33:54Z",
"eventSource": "ec2.amazonaws.com",
"eventName": "RunInstances",
"awsRegion": "us-east-1",
"sourceIPAddress": "autoscaling.amazonaws.com",
"userAgent": "autoscaling.amazonaws.com",
"invokedBy": "autoscaling.amazonaws.com",
"userIdentity.type": "AssumedRole (AWSServiceRoleForAutoScaling)"

Respuesta: la instancia i-0085813bf8e55c18b se creó desde el servicio
AWS Auto Scaling (autoscaling.amazonaws.com), usando su rol vinculado
AWSServiceRoleForAutoScaling. No se originó desde una IP pública.

La lista de las últimas 5 acciones de su usuario IAM

1. ListAlarmMuteRules
2. DescribeAlarms
3. ListManagedNotificationEvents
4. DescribeAlarms
5. DescribeAlarms