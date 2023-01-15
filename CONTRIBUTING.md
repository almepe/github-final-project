#Contributing
Cuando contribuya con un cambio importante a este repositorio, primero discuta el cambio que desea realizar a través de un problema o a través de Slack en el canal #racial-justice-legit-info en el espacio de trabajo de Call for Code Slack. Los problemas menores se pueden abordar simplemente mediante el envío de una solicitud de extracción.

Todas las solicitudes de extracción requerirán que se asegure de que el cambio esté certificado a través del Certificado de origen del desarrollador (DCO). El DCO es una forma ligera para que los contribuyentes certifiquen que escribieron o tienen derecho a enviar el código que están contribuyendo al proyecto.

Tenga en cuenta que tenemos un Código de conducta, sígalo en todas sus interacciones con el proyecto y su comunidad.

Estándares de codificación
Este proyecto se adhiere a las Pautas de estilo de codificación de Python de PEP 8, las convenciones de nomenclatura de Django y otros estándares. Ver ESTILO.md para más detalles.

Lenguajes de programación
Los scripts están escritos para HTML5. El código de Javascript está escrito en el nivel MAS ACTUAL.

Gestión de dependencias
Instale o desinstale todas las dependencias usando estos comandos mientras está en el shell de pipenv:

(cfc) $ pipenv install <programa>"
(cfc) $ pipenv lock -r > requisitos.txt"
El pipfile, pipfile.lock y requirements.txt serán parte de la solicitud de confirmación/extracción de git que se revisará.
