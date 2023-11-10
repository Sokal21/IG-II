**Pattern:** AdministradorDeBanco

**base on:** Fábrica Abstracta

**becasue:**

Queremos permitir al sistema para administrar bancos seguir incorporando nuevas sucursales de diferentes entidades bancarias

Queremos permitirles a las demas partes del sistema que trabajen con nuestraas representaciones de los diferentes componentes de sofware y no se filtren detalles de implementación de las diferentes entidades bancarias

**where:**

FabricaAbstracta **is** FrabricaBancoAbstracta

FabricaContreta **is** FabricaHSBC

FabricaContreta **is** FabricaICBC

ProductoAbstracto **is** CajaAhorroUSDAbstracta

ProductoAbstracto **is** CajaAhorroARSAbstracta

ProductoAbstracto **is** CuentaCorrienteARSAbstracta

ProductoAbstracto **is** CuentaCorrienteUSDAbstracta

...

Producto **is** CajaAhorroUSD_ICBC

Producto **is** CajaAhorroUSD_HSBC

...
