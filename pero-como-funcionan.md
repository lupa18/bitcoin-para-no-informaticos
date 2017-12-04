# Pero ¿cómo funcionan?

¿Cómo puedo comenzar a utilizar el sistema? Primero entendamos los **conceptos** usando como ejemplo la criptomoneda Bitcoin, y luego podrás intentar aplicar lo aprendido en caso que quieras usar otras.

Repasemos como funciona, citando un texto del libro "Bitcoin: La moneda del futuro":

> Cuando un usuario A transfiere bitcoins a un usuario B, el usuario A renuncia a su posesión de un determinado número de bitcoins, agregándoles la llave pública de B y firmando la combinación resultante con su llave privada. \(Gracias al empleo de la criptografía asimétrica, la llave privada no puede ser deducida de la firma que de ella deriva\). Esta información se transmite a toda la red P2P como una nueva transacción. Entonces, el resto de los nodos de la red verifican el número de bitcoins involucrados y la autenticidad de las firmas criptográficas, antes de aceptar la transacción como válida.

Es decir, que para comenzar, es necesario crear una **billetera**, que puede ser online, o puede estar en tu computadora, o incluso en tu celular -- esto lo retomaremos en el siguiente artículo. A partir de ella, se generarán una o varias **direcciones públicas** como la siguiente: 1k9B1wWZoJLcdYMg3vTrWYNfynbSCNDfs.

A partir de ella, se envía o se reciben los bitcoins. Esa dirección que se tomó como ejemplo, se generó en una billetera de la [ONG TEDIC](https://www.tedic.org) por lo que si alguien envía Bitcoins hacia allí, colaborará en el desarrollo y sostenimiento de la organización.

Como se puede apreciar las **direcciones públicas** de Bitcoin, no tienen información del usuario, sin embargo las **transacciones que también son públicas** almacenan otros **metadatos** que podrían servir para identificar a los usuarios. Es que todas las transacciones son accesibles a través de las plataformas de exploración del **blockchain**.

Veamos el ejemplo de una transacción que realicé sobre fines de 2016 como [una donación](https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e) a la red social Diaspora\*[^1]. Se puede acceder en el siguiente enlace: [https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e](https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e)

Y así es como se ve la información completa de la transacción y sus metadatos:

![](/assets/Selección_081.png)En este ejemplo, se ven las **dos direcciones implicadas** en la transacción así como otra información sobre la misma: monto, comisión, fecha y hora, etc..

Más adelante veremos que algunas monedas aplican lo que se conoce como ["privacidad por diseño"](https://karisma.org.co/que-es-la-privacidad-por-diseno-y-por-que-deberia-importarle/) y utilizan nuevas técnicas critpográficas para no exponer la información sobre la transacción y por tanto tampoco los metadatos. Un ejemplo de esto es Zcash que utiliza [pruebas de conocimiento-cero](https://es.wikipedia.org/wiki/Prueba_de_conocimiento_cero) \(zero-knowledge\) para ocultar los metadatos y convertirse una de las formas más seguras y anónimas de transferir dinero.

Volviendo al tema de las **direcciones**, decíamos que puedes generar tantas direcciones como quieas: incluso hay quienes recomiendan generar una por cada transacción. Por el momento piensa que una billetera es una dirección para simplificar.

Una vez que tienes la billetera y las direcciones, debes lograr que alguien **transfiera bitcoins** a tu billetera, enviándole tu dirección -- como por ejemplo la de TEDIC -- y entregándole dinero o servicios a cambio, o simplemente pidiéndole una donación.

No es necesario transferir 1 bitcoin, pues como ya mencionamos, las criptomonedas son** divisibles,** por lo que se puede trabajar con fracciones, por ejemplo 0,01 btc sería una parte en cien de 1 bitcoin. En el caso de esta moneda, se puede dividir hasta 0.00000001 btc, lo que se denomina 1 Satoshi \(en honor a su creador [Satoshi Nakamoto](https://es.wikipedia.org/wiki/Satoshi_Nakamoto)\).

Por ejemplo, podrías lograr tener bitcoins, pidiéndole a amigo que transfiera algunos bitcoins, por los que tu le entregarías algunos billetes de curso legal \(dólares, pesos, soles o lo que fuere\). Incluso podrías intercambiar algún servicio como la  limpieza de un dormitorio, el cuidado de su hija, un corte de césped o un corte de cabello. Entonces una vez entregado el dinero o realizado el servicio, esta persona te enviaría los bitcoins a tu billetera.

Otra forma es a través de las casas de cambio: se colocan allí los dólares u otra moneda, y la casa de cambio envía los bitcoins a tu dirección, según la cotización **"de mercado"**. Además existen otras formas como máquinas automáticas que funcionan por el momento en algunos países de Europa.

También podrías crear una **orden de compra** condicional en una casa de cambio, por ejemplo, comprar 0,1 bitcoin siempre que el precio baje a 9.000 dólares[^3]. De forma que si el precio baja de 9.600 a 9.000 se ejecuta la transferencia a tu billetera y habrás gastado 9000 dólares \(más las comisiones\).

Más adelante veremos varias técnicas para comprar criptomonedas en detalle.

## El precio de mercado

Como no existe autoridad monetaria central, el precio de las criptomonedas, se asigna por oferta y demanda. Es cierto que los precios están fluctuando más de lo deseado y seguramente existen quienes las utilizan de forma especulativa, pero esperemos que en un futuro los precios se estabilicen y aumente la confianza en el sistema.

Veamos la explicación tomada de la [web de Bitcoin en español](https://bitcoin.org/es/faq#que-determina-el-precio-del-bitcoin):

> "El precio del bitcoin se determina por la oferta y la demanda. Cuando se incrementa la demanda de bitcoin, el precio sube, y cuando cae la demanda, cae el precio. Hay un número limitado de bitcoins en circulación y los nuevos bitcoins son creados a una velocidad predecible y decreciente, esto significa que la demanda debe seguir este nivel de inflación para mantener un precio estable. Debido a que Bitcoin es todavía un mercado relativamente pequeño comparado con lo que podrá llegar a ser, no es necesaria una significativa cantidad de dinero para mover el precio del mercado arriba o abajo, es por eso que el precio del bitcoin es todavía muy volatil"

Son muchas las plataformas de compra y venta de criptomonedas y es apartir de esas plataformas que se van colocando órdenes de compra y venta que van haciendo variar los precios. En el ejemplo de que alguna persona conocida te venda critpomonedas, pueden acordar también un precio diferente al de mercado, nada lo imprediría ¿no?

Sobre las pltaformas de intercambio, alguna de las que se pueden listar son [Coinbase](https://www.coinbase.com/), [Poloniex](https://poloniex.com/), [Cex.io](https://cex.io/), [Coinmama](https://www.coinmama.com), [LocalBitcoins](https://localbitcoins.com/), [Kraken](https://www.kraken.com/), [Bitfinex](https://www.bitfinex.com/), [SatohiTango](https://satoshitango.com),  [Bisq](https://bisq.network/), etc.[^2], y cada una tiene mecanismos, precios y condiciones: no todas tienen los mismos precios o comisiones, no todas manejan todas las monedas, no todas permiten colocar fondos de la misma forma, etc.. En otro apartado veremos cómo realizar transacciones con criptomonedas de forma práctica.

## ¿Comisiones?

Ya se nombró algunas veces el concepto de comisión. Efectivamente, para sostener la red, debe haber un incentivo.

FIXME: continuar

¿Qué es la minería de criptomonedas?

FIXME: continuar

## Herramientas

Aquí presentamos algunas herramientas que te pueden resultar de gran utilidad.

* [https://bitinfocharts.com](https://bitinfocharts.com) - Una comparativa de diferentes aspectos de las criptomonedas: precio, capitalización de mercado, cantidad de transacciones, tamaño del blockhain, etc.. 

---

**Palabras clave:** transacción, dirección, metadato, billetera, comisión

[^1]: En realidad la donación que realicé fue a un solo nodo de la red Diaspora\* denominado [diasp.org](https://diasp.org/)

[^2]: Aquí hay un [listado y tabla comparativa](https://www.bestbitcoinexchange.io/) que te puede ser de utilidad. 

[^3]: Al momento de escribir estos artículos el precio de mercado de Bitcoin había superado los 10 mil dólares por unidad.

