# Mi primera aplicación de Android Studio - Dice Roller 

## Utilizar Strings con diferentes idiomas

Voy a crear otro string en diferente idioma que practicamente lo escrito antes se mostrara
en el nuevo idioma que cree.

1. En la carpeta de Strings creamos un nuevo Values resourse file.
2. Le ponemos el mismo nombre de strings.
3. Elegimos locale y el idioma que queremos, que en mi caso puse el ingles.

[Commit](https://github.com/Britza/andfun-kotlin-dice-roller/commit/8c45ea14d39bcf33abb04c4e3eb6efe4151910a8)  

## Añadimos las imagenes

1. Buscamos las imagenes y las descargamos en formato png.
2. Cambiamos el _TextView_ por un _ImageView_ .
3. Añadimos las imagenes y cambiamos la función del **MainActivity**.

[Commit](https://github.com/Britza/andfun-kotlin-dice-roller/commit/431d9513d1c5f77e7adb766410c4df15e20d26fb)  


## Cambiamos la función random

Buscamos otra manera para la función random y la cambiamos.

` val randomInt = (0 until 6).random() `

[Commit](https://github.com/Britza/andfun-kotlin-dice-roller/commit/86e854520d23e622474f1df878e4d431440ec79a)  

## Añadimos el icono al boton

1. Implementamos en el **build.gradle** el material que utilizaremos para la huella.
2. Añadimos un nuevo drawable con el dibujo de la huella.
3. Y por ultimo añadimos al boton el icono de la huella.

[Commit](https://github.com/Britza/andfun-kotlin-dice-roller/commit/c515cf4fc56afb4c19565093f724e92de3798920)  
