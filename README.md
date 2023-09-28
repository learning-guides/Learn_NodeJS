# Learn_NodeJS

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

Ingresar a la página oficial de NodeJS y descargar la versión LTS:
https://nodejs.org/en

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/c04329ec-ae27-49df-9b65-0f847648d673)

Ejecutar el instalador descargado:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/fe85e9d0-14ed-4d7e-b494-da43f59fd366)

Click en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/9f2d22e1-ab3c-476f-9e28-68aff3123763)


Aceptar los terminos dando click a la casilla de verificación y dar clic en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/707590d1-eff6-46f7-a0fd-afc974e6765d)

Se recomienda no cambiar la ruta de instalación, solo dar clic en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/7c39d76f-2db9-4137-aca1-208df5ed39b9)

Dar click en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/e57c9e41-3792-4de8-bc04-d35761e44700)

Dejar la casilla de verificación en blanco y dar clic en siguiente:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/5c749116-7e2a-4f2c-a887-f84cb348a739)

Clic en installar:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/06c35469-304b-423d-92af-4ae908e5e60a)

Esperar que termine el proceso de instalación:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/a6559f5d-5495-477d-9ed7-dfab442c9291)

Clic en finalizar:

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/2ade01b9-ac77-4c3b-8a28-b15ae709cf93)

PASO #4

Abrir consola del sistema como administrador y ejecutar el siguiente comando presionando ENTER:

node -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/ef762d27-3c80-487d-9191-1e0819012ee2)

Esto nos muestra la versión instalada, con esto confirmamos que se instalo correctamente NodeJS

Ejecutar el siguiente comando y presionar ENTER:

npm -v

![image](https://github.com/learning-guides/Learn_NodeJS/assets/141972615/32c0db97-bbe9-436a-a740-7338148cb38b)

Esto nos muestra la versión instalada, con esto confirmamos que se instalo correctamente NPM el cual se instala en conjunto con NodeJS.

PASO #5

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















