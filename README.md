# laboratoriogit
# Bootcamp JS 2 - Laboratorio Git
## Creamos desde la consola con md una carpeta y nos posicionamos en ella con cd, iniciamos el repositorio con git init
***
![1](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/4e848495-fba7-4e4f-84c4-34f54597e66a)

## Creamos un repositorio publico en github
***
![2](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/7a6f946d-c79f-4425-a471-0b455bef8d33)

## Realizamos la conexion con git remote add origin "direccion protocolo ssh que nos ha generado github"
***
![3](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/f902a326-dd3a-48a4-8c38-b594b355e503)

## Creamos un archivo en este caso index.js que pasaremos a staging con git add . y luego realizamos el commit acompañandolo de un mensaje, observamos que se haya insertado y realizamos un git -u push origin master ya que se trata del primer push de esta rama
***
![4](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/f6028772-6919-4e1e-8ca1-52e53e9be100)

## Observamos los cambios en github
***
![5](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/98924002-73cd-4637-8a4d-e216a91d2788)

## Lo siguiente es crear una rama nueva con git branch development (nombre sugerido) y nos posicionamos en esa rama con git checkout development donde cambiaremos el mensaje del index.js y repetimos los pasos para llevar los cambios a github (git add ./git commit -m/git push -u origin development ya que es la primera vez que hacemos push en esta rama)
***
![6](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/7d97067d-aa15-4131-a061-a477a3ba2874)

## Observamos que nuestro github ahora tiene 2 ramas ademas de los commits realizados
***
![8](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/9c5fbf3d-ca17-4b59-b593-8a596de2ff2b)

## Nos posicionamos en nuestro caso en la rama master con git checkout master y realizamos desde esta un git merge development, introducimos un git log para comprobar que la rama development se ha introducido en la rama master y realizamos un ultimo cambio en nuestro index.js para comitearlo y hacer push
***
![123](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/a38973a8-a409-4a03-a0ba-c091e9ed6903)

## Nos vamos a github y comprobamos que todos nuestros commit y cambios se han realizado
![10](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/c631813d-bacf-4f74-8037-51dd6f80cbdd)
![11](https://github.com/AlexisCO93/laboratoriogit/assets/135819858/8a75f21b-4abe-4583-9a11-7a1f5e1d6fbe)
