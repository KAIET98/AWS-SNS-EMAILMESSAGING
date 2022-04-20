# AWS-SNS-EMAILMESSAGING
El objetivo es que se puedan mandar emails, o notificaciones por medio de una suscripción de SNS


# 1. Creación de un topic en SNS

1. Le damos a create topic

2. Seleccionamos Standard puesto que tiene la funcionabilidad de mandar SMSs e Emails. 
3. En nombre ponemos algo identificativo: 

```
SNS_EMAIL_TOPIC
```
y en el display name también lo repetimos:

```
SNS_EMAIL_TOPIC
```

Ahora mismo el todo lo demás lo dejamos tal cual está. Y creamos el Topic

3. Creamos la subscipción al Topic, mediante Create Subscription

- En protocol seleccionamos la opción de "Email"
- En endpoint ponemos nuestro correo en mi caso: kaiglebar98@gmail.com
- Creamos la subscripción


4. Accedemos al correo que hemos puesto

Si todo lo hemos hecho bien hasta ahora, tendremos un correo con la suscripción a AWS SNS.

5. Le damos a "Confirm suscription


6. Si volvemos a SNS al topic que hemos creado, debajo, en el identificador, solo tendremos un correo electrónico de destino 
y su status pondrea "Confirmado".

7. Enviamos nuestro primer mensaje. 

- Clicamos en "Publish Message"
- En el body ponemos: 


```
Hola mundo
```
- Le damos a "Publish"

8. Si chequeamo nuestro correo , deberiamos de tener un correo con dicho mensaje.

:)

