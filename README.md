# retotelematica-3

Tercer reto topicos de telematica

Para esta reto usaremos Bookstore le cual fue proporcionado por el profesor de la materia se encuentre en este git

Instrucciones

Para este proyecto se necesitara EC2, para este reto su uso aws academy en su defecto.

Crearemos tres maquinas virtuales (frontend, backend y nuestra maquina para el certificado) ubunto a las cuales les asignaremos una ip elastica, a estas maquinas les instalaremos Docker y MongoDB

Ahora bien necesitaremos adquirir un dominio para el cual usaremos Freenom, es importante configurar adecuadamente nuestro dominio y haber asignado la ip elastica como se indico anteriormente para asignar dicha a nuestro dominio, la ip que usuaremos para el dominio sera la del fronend

Como se habia indicado debemos certificar nuestro sitio, con la herramienta de NGINX podremos realizarlo, primero la instalaremos en nuestra maquina de certificado y de esto hecho se correra el siguiente comando en la misma maquina

sudo certbot --nginx certonly -d dominio -d www.*dominio*

Con las instrucciones hechas tendremos nuestro lindo sitio

https://libroschikitos.tk/
