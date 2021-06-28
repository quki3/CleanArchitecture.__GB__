# CleanArchitecture.__GB__
proyecto
```bash
API[
    /api=>'es la carpeta de presentacion con la que los usuarios interactuan'---------->[
                                                                                        /controller=>'aca ban los controller'
                                                                                        /middlewares=>'es una logica que va antes que la peticion llegue al controlador'
                                                                                        /routes=>'aca van las configuraciones de las rutas'------------------------------->[
                                                                                                                                                                            #container.js=>'es para uso de las dependencias'
    config =>'aca van todas las configuraciones que son comunes a todas las capas'=>'como tenemos diferentes ambientes de configuracion cada uno requiere su configuracion'--->[
                                                                                                                                                                               #development.js
                                                                                                                                                                               #production.js
                                                                                                                                                                               #qa.js
                                                                                                                                                                               #index.js=>'aca vamos a hacer un expor de los archivos para que determine en que ambiente estamos y dependiendo de eso nos retorne dicha configuracion'
    dal=> 'la responzable de los accesos a los datos'
    domain => 'aca se acientan nuestras entidades'
    services => 'aca se crean nuestros servicios'
    index.js => 'el punto de acceso de nuestro programa'
    
```

