# CleanArchitecture.__GB__
proyecto
```bash
API[
    /api=>'es la carpeta de presentacion con la que los usuarios interactuan'---------->[
                                                                                        /controller=>@index.js=>'aca ban los controller'
                                                                                        /middlewares=>'es una logica que va antes que la peticion llegue al controlador'
                                                                                        /routes=>[
                                                                                                   @index.js=>'aca van las configuraciones de las rutas'
                                                                                                   @user.routers.js'configuracion de las rutas del usuario'
                                                                                         @container.js=>'es para uso de las dependencias'
                                                                                         @sever.js=>'serparar el servidor de la aplicacion'
                                                                                         @startup.js=>'aca van a estar las configuaciones de nuestro proyecto como tal'
    config =>'aca van todas las configuraciones que son comunes a todas las capas'=>'como tenemos diferentes ambientes de configuracion cada uno requiere su configuracion'--->[
                                                                                                                                                                               @development.js
                                                                                                                                                                               @production.js
                                                                                                                                                                               @qa.js
                                                                                                                                                                               @index.js=>'aca vamos a hacer un expor de los archivos para que determine en que ambiente estamos y dependiendo de eso nos retorne dicha configuracion'
    dal=> 'la responzable de los accesos a los datos'
    domain => 'aca se acientan nuestras entidades'
    services => 'aca se crean nuestros servicios'
    index.js => 'el punto de acceso de nuestro programa'
    
```

