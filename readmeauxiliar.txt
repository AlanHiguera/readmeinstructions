class Config {
  static const String appName = "Handmade Geeks";
  static const String apiURL = '192.168.1.91';
  static const obtenerProductoMainAPI = "api/producto/obtenerproductomain";
  static const productoAPI = "api/producto";
  static const tiendaAPI = "api/tienda";
  static const loginAPI = "api/login/";
  static const obtenertokenAPI = "api/api-token-auth/";
  static const productoadminAPI = "api/productoadmin/";
  static const usuarioAPI = "api/usuario/";
  static const administradorAPI = "api/administrador";
  static const productodeseadoAPI = "api/productodeseado";
  static const tipocategoriaAPI = "api/tipocategoria";
  static const carritoAPI = "api/carrito";
  static const seguimientotiendaAPI = "api/seguimientotienda";
}

"api/tienda"; Entrega los atributos de todas las tiendas una por una.
"api/seguimientotienda"; Este Entrega la id del seguidor y el id de la tienda que sigue.
"api/tienda/ObtenerProducto/ Recibe un producto y retorna la tienda a la que pertenece(toda la tienda no solo id)
"api/producto"; Entrega todos los productos de la base de datos que sean visibles
"api/producto/obtenerproductomain"; obtiene un producto del main sin todos los atributos, solo precio, nombre, e imagen ('Nomprod', 'Precio', 'FotoProd')
"api/productoadmin/"; obtiene todos los productos que no sean visibles en la base de datos
"api/productoadmin/obtenerproductomain"; obtiene todos los productos que no sean visibles en la base de datos con atributos ('Nomprod', 'Precio', 'FotoProd')
