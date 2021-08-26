# Desafío postulación MercadoLibre

Buscador desarrollado como desafío para ingresar a MercadoLibre.

# Tecnologías utilizadas

El proyecto contiene un servidor montado en nodejs utilizando expressjs como framwork del lado del servidor, y, React en el lado del cliente.
Requerimientos

Generar 3 vistas correspondientes a un buscador, una lista de resultados de la búsqueda, y el detalle de un producto. Las vistas deben ser navegables de manera independiente, y cuentan con sus propias URL:

    Buscador: “/”
    Lista de resultados: “/items?search=”
    Detalle del producto: “/items/:id”

También, construir los siguientes endpoints para ser utilizados desde las vistas:

    /api/items?q=:query
    /api/items/:id

# Instalación y Compilación

Para levantar un entorno local, hace falta tener instalado nodejs y npmjs.

Clonar el repositorio, y dentro de la carpeta raíz, instalar las dependencias del archivo package.json:

    $ sudo npm install

Iniciar el servidor:

    $ npm start

