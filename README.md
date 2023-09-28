# Learn_NodeJS
- Author: @ansanchezx for Sofgrox
- Last update date: 01/10/23
- Last update by: @ansanchezx

INSTALACION Y CONFIGURACION


PASO #1:

Lo primero es instalar NVM para el controlador de versiones de Node y NPM.

ingresar en la página/repositorio oficial de NVM:
https://github.com/coreybutler/nvm-windows

Para instalar en Windows se debe buscar la siguiente opción:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/2be9201a-d82f-48ef-91a4-76e170d55357)

Asegurar que la versión a descargar tenga el texto “Latest” en color verde al lado del número de la versión:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/af5fd1c3-1c2c-4a30-9692-ff0d8a1807c3)

Luego dirigirse hacia la parte inferior y en el caso de Windows seleccionar la opción .exe

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/7d67b099-21b7-432d-83b1-2605b397b1e5)

Proceder a instalar el ejecutable descargado con los siguientes pasos:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/8d7fd5bb-b666-45b8-a6f5-69e94a6fd598)

Seleccionar aceptar los terminos:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/2065e80e-b3db-45b9-91ed-e5a1f1ecd72f)

Se recomienda no cambiar la ruta de instalación para su óptimo funcionamiento, dar siguiente sin cambiar la ruta:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/b681cb00-a7e1-4411-ac34-4e391cec39bc)

Esta ruta tampoco se recomienda cambiar, solo dar clik en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/ec9e7003-c4c1-43fe-9106-a8be80a5bde7)

En esta ventana de confirmación dar clic en instalar:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/828eec11-d44e-4020-8de3-d72ec938b557)

Iniciara el proceso de instalación solo debemos esperar a que termine:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/af98a252-04d6-4006-8d6a-e6a186231129)

Dar clic en finalizar:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/bbe32744-1931-4da0-95d2-fa62c1ffe2ce)


PASO #2:

El siguiente paso es confirmar que nvm quedó instalado, realizar los siguientes pasos.

Abrir consola como administrador:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/6aae9060-967a-4b28-9dea-336f1e8e9937)

Escribir el siguiente comando y ejecutarlo con la tecla ENTER:

nvm v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/a27ec1c6-9161-4d1c-bf9e-971ee6cfa426)

Esto muestra la versión instalada en el equipo, indicando asi que la instalación fue correcta.

PASO #3:

Ingresar a la página oficial de NodeJS y asegurarnos cual es la versión LTS:
https://nodejs.org/en

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/c04329ec-ae27-49df-9b65-0f847648d673)

NOTA: NO descargar e instalar desde la página, esto arruinaria el proceso de manejo de varias versiones en NodeJS

Abrir una consola de comandos como administrador y ejecutar el siguiente comando:

nvm install 18.18.0

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/092e845e-ea35-44d6-939b-298cbf1239d0)

Esto deja instalado el NodeJS en su version reciente LTS y nos instala el npm

para verificar la instalación en la termina usamos el siguiente comando:

nvm list

Esto nos muestra la lista de versiones de NodeJs instaladas hasta el momento solo hay una.

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/fb7a9711-58e0-49d3-9461-1819e611d041)

Ahora se ejecuta el siguiente comando

node -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/39135b12-d727-4e8d-aa08-cabd25714a06)

El mensaje debe ser que no se reconoce node, esto debido a que aun no se ha selecionado dicha versión, para seleccionarla usar el siguiente comando:

nvm use 18.18.0

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/3f947a02-09b3-42a3-a839-9703b9339a7d)

Indica que ya se esta usando esta versión en el equipo

Ejecutar de nuevo el comando:

node -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/5801aaff-a9e9-4fa4-922c-32f987ce33b3)

Ahora si os dice la versión actual que usa el equipo, podemos ejecutar el comando:

npm -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/1186eda9-0cb9-4d69-9e0f-5d2b6541b359)

Esto nos muestra la versión instalada, con esto confirmamos que se instalo correctamente NPM el cual se instala en conjunto con NodeJS.

PASO #4

No siempre npm queda en la versión reciente, para verificar esto se ingresa a la página/repositorio oficial de npm el cual indica su versión actual:
https://github.com/npm/cli/releases

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/b8099057-3cf9-4f42-99fe-6d0ea76a58c8)

Aqui podemos ver que la versión actual de npm no es la que esta instalada en el equipo, para actualizar la versión de NPM se deben realizar los siguientes pasos.

En la consola del sistema abierta como administrador, ejecutar el siguiente comando y presionar ENTER:

NOTA: en el comando que vera a continuación se deben reemplaxar las X.X.X por la version indicada en la página/repositorio de npm
ejemplo npm install -g npm@X.X.X

Para ejecutarlo en consola con la versión actual de npm hasta el momento de creación de esta guía seria:

npm install -g npm@10.1.0

Luego ejecutar el siguiente comando y presionar ENTER:

npm -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/23dbaf57-fca9-421b-9f2f-ecb2bb1f7299)

Esto deja el npm instalado en su ultima versión.

PASO #5

Abrir consola del sistema como administrador:

Para instalar otra versión de NodeJs se debe buscar una versión valida, para ello se revisa la siguiente página:
https://nodejs.org/es/download/releases

Para este ejemplo se instalara una version 16 de NodeJS

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/e90d06e3-bdfa-4217-85d5-5c5555e10739)

nvm install 16.20.2

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/cdc4d1f9-41c7-40cb-96bd-e568e67608ef)

para usar esta versión se utiliza el comando:

nvm list

Con este comando sale la lista indicando las versiónes instaladas hasta el momento y cual es la actual

nvm use 16.20.2

dejamos de usar cualquier otra versión para usar la indicada en el comando

nvm list

nos muestra de nuevo la lista esta vez indicando la versión actual que se esta utilizando

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/63ad38f3-97b1-4918-af56-198c6c65c613)

Si ejecutamos el comando:

node -v

nos indica la versión de node que el sistema tiene actualment

npm -v

nos indica la versión npm que el sistema tiene actualmente


![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/74245e7c-7200-4d73-b0a4-59823aa4d346)

NOTA: para versiones anteriores a la mas reciente LTS no se debe actualizar el npm, esto solo se hace cuando se instala la ultima version actual de node LTS para versiones antiguas no se le actualiza el npm

En caso tal que entremos a un proyecto que usen una version que no este en la lista:

podemos instalar esa version que nos pase el proyecto o que veamos en el archivo package.json

usando el comando:

nvm use 14.16.1

esto es una version valida de Node que no esta en la lista de la pagina de versiones de node:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/2535f5b3-f286-4e28-9a60-8128e7cbfe2d)

Para saber cual es la version actual usada por nvm sin necesidad de usar el nvm list:

nvm current

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/9e0afbfa-4df2-4159-a1eb-a34a84677e73)

















