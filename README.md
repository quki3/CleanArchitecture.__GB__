# CleanArchitecture.__GB__
proyecto
```bash
API[
    /api=>'es la carpeta de presentacion con la que los usuarios interactuan'---------->[
                                                                                        /controller=>'aca ban los controller'
                                                                                        /middlewares=>'es una logica que va antes que la peticion llegue al controlador'
                                                                                        /routes=>'aca van las configuraciones de las rutas'------------------------------->#container.js=>'es para uso de las dependencias
    config =>'aca van todas las configuraciones que son comunes a todas las capas'
    dal=> 'la responzable de los accesos a los datos'
    domain => 'aca se acientan nuestras entidades'
    services => 'aca se crean nuestros servicios'
    index.js => 'el punto de acceso de nuestro programa'
    
```

