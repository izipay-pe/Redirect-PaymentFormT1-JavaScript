# Crear un formulario en REDIRECCIÓN

Seguir los siguientes pasos para poder ejecutar este ejemplo:


1. Descargar el manual desde [Manual Izipay - implementación en REDIRECCIÓN](https://secure.micuentaweb.pe/doc/es-PE/form-payment/quick-start-guide/sitemap.html).


2. ## Ingreso al BO Vendedor

Ingresar al siguiente link: [Back Office Vendedor](https://secure.micuentaweb.pe/vads-merchant/), ingresar con tus credenciales, seguir la siguiente ruta:

*`Configuración -> Tienda -> Claves`.

Copiar el "Identificador de la tienda" y reemplazarlo en el valor del `id = campo7` segun el paso `3. Realizar los siguientes cambios`.
Copiar la clave de TEST O PRODUCCION segun sea el caso y reemplazarlo en el valor del `id = key` segun el paso `3. Realizar los siguientes cambios`.


3. ## Realizar los siguientes cambios:

Cambiar las credenciales en:

### `scr -> index.html`

*En el input con el `id = campo7`, reemplazar el valor de `value = xxxxxxxx` por el "Identificador de la tienda" extraido desde el BO vendedor.

*En el input con el `id = key`, reemplazar el valor de `value = xxxxxxxx` por la "clave TEST O PRODUCCION" de la tienda extraida desde el BO vendedor.

