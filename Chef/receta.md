Crear receta para instalar Debian Jessie en portátiles de la Oficina Software Libre.

# ¿Qué es Chef?

* Es un framework de automatización de infraestructura de sistemas, esto permite desplegar aplicaciones y sistemas a cualquier ambiente físico, virtual o en la nube fácilmente con un enfoque en la preparación de instalación y configuración previa del ambiente. Como su nombre lo indica, la herramienta pretende seguir un conjunto de pasos o recetas con el propósito de presentar un producto final ya listo para trabajar y/o probar.

### Existen 2 tipos de versiones:

* Chef Server está enfocado a ser el servidor central que, en comunicación con los equipos de trabajo, permite suministrar a los diferentes ambientes o nodos con las diversas configuraciones que sean necesarias, las cuales se mantienen alojadas en el servidor. Además ofrece varias ventajas particulares del trabajo de varios nodos como balanceo de carga, escalabilidad, búsquedas rápidas por tipo (Ej. todos los ambientes Ubuntu Precise, o todos los ambientes con 4GB de RAM), y mucho más.

* Por el contrario, Chef Solo es la versión de código abierto y reside localmente en el nodo, esto quiere decir que toda la información y recetas necesarias para configurar el nodo deben estar presentes en su disco duro. 

Información recogida de [codehero.co](http://codehero.co/como-instalar-y-configurar-chef/).
