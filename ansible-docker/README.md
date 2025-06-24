<!--Commands -->

<!-- crear ssh -->
<!-- ssh-keygen -t rsa -b 2048 -f control/ssh/id_rsa -q -N "" -->

<!-- copiar clave publica al contexto del target -->
<!-- cp control/ssh/id_rsa.pub target/id_rsa.pub -->

<!-- ¿Qué hacen exactamente los pasos?
Ansible desde el contenedor control se conecta al contenedor target por SSH.

Usa un archivo playbook.yml para decirle qué hacer: instalar Apache2.

Apache se instala, se inicia y se configura para que arranque automáticamente cada vez que se encienda el sistema.

Apache corre dentro del contenedor target. -->
