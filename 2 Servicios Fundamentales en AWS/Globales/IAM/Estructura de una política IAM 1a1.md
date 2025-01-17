
El documento o JSON consta de:

1. Versión: la versión del lenguaje de la política
2. Id: Identificador para la política
3. Statement: Una o mas declaraciones de la politica

```json
{
  "Version": "2012-10-17",
  "Id": "S3-Account-Permissions",
  "Statement": [
    {
      "Sid": "1",
      "Effect": "Allow",
      "Principal": {
        "AWS": ["arn:aws:iam::123456789012:root"]
      },
      "Action": [
        "s3:GetObject",
        "s3:PutObject"
      ],
      "Resource": ["arn:aws:s3:::mybucket/*"]
    }
  ]
}
```

Ahora desglosemos el campo **Statement**
- SID: Identificador para la declaración
- Effect: Esto define si va a ser una declaración que permite o deniega
- Principal: Es la cuenta, el usuario o al rol que se aplica esta política
- Action: Lista de acciones que se permiten o deniegan, depende del Effect
- Resource: Una lista de recursos a la que se le aplican las acciones 
- Condition: Es opcional, pero es un condición para que se aplique esta política 