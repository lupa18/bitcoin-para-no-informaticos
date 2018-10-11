# Pero ¿cómo funcionan?

Muy bien, en capítulos anteriores vimos qué son las criptomonedas, las críticas y la variedad de propuestas que hay. Ahora quizás de preguntes, ¿cómo puedo comenzar a utilizarlas? Primero es importante entender algunos **otros conceptos** \(utilizaremos Bitcoin como ejemplo y más adelante podrás intentar aplicar lo aprendido para otras criptomonedas\).

Repasemos cómo funciona, tomando un párrafo del libro "Bitcoin: La moneda del futuro"[^4]:

> Cuando un usuario A transfiere bitcoins a un usuario B, el usuario A renuncia a su posesión de un determinado número de bitcoins, agregándoles la llave pública de B y firmando la combinación resultante con su llave privada \(gracias al empleo de la criptografía asimétrica, la llave privada no puede ser deducida de la firma que de ella deriva\). Esta información se transmite a toda la red P2P como una nueva transacción. Entonces, el resto de los nodos de la red verifican el número de bitcoins involucrados y la autenticidad de las firmas criptográficas, antes de aceptar la transacción como válida.

Es decir, que para comenzar, es necesario crear una **billetera**, que puede ser "online", o puede estar en tu computadora, o incluso en tu celular —esto lo retomaremos en el siguiente artículo. A partir de ella, puedes generar **direcciones públicas** que servirán para establecer el punto de recibida de una transacción. Estas direcciones públicas pueden ser una o varias y depende de la criptomoneda; en el caso de bitcoin, luce algo así: 1k9B1wWZoJLcdYMg3vTrWYNfynbSCNDfs. En algunos casos, como por ejemplo cuando utilices tu celular, está la opción de codificar esa dirección como un QR:

![](/assets/Bitcoin_TEDIC.jpg)

Entonces, una dirección de este tipo, que **se genera desde tu billetera**, es que vas a recibir los bitcoins u otra moneda. La dirección que se tomó como ejemplo, pertenece a una billetera de la [ONG TEDIC](https://www.tedic.org), por lo que si alguien envía Bitcoins hacia allí, la billetera de Tedic verá aumentar su cantidad de bitcoins.

Como se puede apreciar las **direcciones públicas** de Bitcoin, no tienen información del usuario, sino que son simplemente un código. Sin embargo cabe recordar que en esta criptomoneda todas **las transacciones y sus metadatos son públicos,** lo que podría servir para identificar a los usuarios.

Veamos el ejemplo de una transacción de fines de 2016 en la que se realizó [una donación](https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e) a la red social Diaspora\*[^1]. Se puede acceder en el siguiente enlace: [https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e](https://blockchain.info/tx/dce48ad9632b213e37c7c100f340d12ce11f99f55b2dc7478cea3ece4558f32e)

Y así es como se ve la información completa de la transacción y sus metadatos:

![](/assets/transaccion_diaspora.png)En este ejemplo, se ven las **dos direcciones implicadas** en la transacción así como otra información sobre la misma: monto, comisión, fecha y hora, y otra serie de datos importantes.

También puedes hacer clic en "Ver gráfico de árbol" para explorar el camino futuro que siguieron esos bicoins que luego se fraccionaron y enviaron hacia otras personas \(hacia otras direcciones\).

Más adelante veremos que algunas monedas aplican lo que se conoce como ["privacidad por diseño"](https://karisma.org.co/que-es-la-privacidad-por-diseno-y-por-que-deberia-importarle/) y utilizan nuevas técnicas critpográficas para no exponer partes de la transacción, ni sus metadatos. Un ejemplo de esto es Zcash que utiliza [pruebas de conocimiento-cero](https://es.wikipedia.org/wiki/Prueba_de_conocimiento_cero) \(zero-knowledge\) para ocultar los metadatos y convertirse una de las formas más seguras y anónimas de transferir valor.

Volviendo al tema de las **direcciones**, decíamos que puedes generar tantas **direcciones públicas **como quieas: incluso hay quienes recomiendan generar una por cada transacción.

Una vez que tienes la billetera y las direcciones, debes lograr que alguien **transfiera bitcoins** a tu billetera, enviándole tu dirección —como por ejemplo la de TEDIC— e intercambiarlos por dinero o servicios a cambio, o simplemente pidiéndole una donación.

**No es necesario** transferir 1 bitcoin, pues como ya mencionamos, las criptomonedas son** divisibles,** por lo que se puede trabajar con fracciones, por ejemplo 0,01 btc sería una parte en cien de 1 bitcoin. En el caso de esta moneda, se puede dividir hasta 0.00000001 btc, lo que se denomina 1 Satoshi \(en honor a su creador [Satoshi Nakamoto](https://es.wikipedia.org/wiki/Satoshi_Nakamoto)\).

De nuevo, una forma de intercambiar cripto es **persona-a-persona**. Le pides a alguien que te envíe cierta cantidad y a cambio le  entregas algunos billetes de curso legal \(dólares, pesos, soles o lo que fuere\). Incluso podrías intercambiar algún servicio como la  limpieza de un dormitorio, el cuidado de su hija, un corte de césped o un corte de cabello. Entonces una vez entregado el dinero o realizado el servicio, esta persona te enviaría los bitcoins a tu billetera. Esto puede implicar riesgos, ya que podrías ser víctima de robo o estafa, tal como puede ocurrir con dólares o cualquier otro intercambio.

Una forma más impersonal es a través de las **casas de cambio** o **exchanges. ** Esto implica algunos pasos extra. Pero de forma simplificada, tu depositas allí los dólares y la casa de cambio envía los bitcoins a tu dirección, según la cotización **"de mercado"**. Muchas veces esas propias casas de cambio te ofrecen guardar tus criptos, pero es una práctica no muy recomendable, dada la cantidad de robos que han ocurrido. Así que si usas una casa de cambio, una vez que transformas los dólares en crypto, sácalos a tu computadora \(ojo, que si no tienes respaldos de tu billetera, esto puede ser muy riesgoso, ya que podrías perder tu computadora y con ella tus monedas\). Las casas de cambio también permiten colocar **órdenes de compra** de forma tal que estableces condiciones para realizar la transacción. Por ejemplo: comprar 0,1 bitcoin siempre que el precio baje a 4.000 dólares[^3]. Si esa condición se cumple, entonces se ejecuta la transferencia a tu billetera obteniendo 0,1 btc al precio de 400 dólares.

También existen otras formas como **cajeros automáticos **que funcionan en algunos países de Europa. En este caso depositas tus dólares en la máquina y esta transfiere a la dirección que le indiques.

Otros métodos con otras monedas podrían ser el **intercambio de bienes y servicios** a través de redes cooperativas como ocurre con [Faircoin](https://fair-coin.org/) y la red [Faircoop](https://fair.coop) que ya mencionamos en una entrega anterior.

También hay redes sociales como [Minds](https://www.minds.com) que están utilizando la tecnología de Blockchain y criptomoneda para pagar por el uso y promoción de tu información y comportamientos. De este modo, obtendrías los "Tokens" de Minds, simplemente por utilizar la red.

Más adelante veremos paso a paso algunas técnicas para comprar criptomonedas adaptadas a la región sur de América.

## El precio de mercado

A diferencia del dinero de curso forzoso, **la mayoría de las criptomonedas rigen su precio por el "mercado"**, es decir, por la oferta y la demanda. En los últimos meses los precios de bitcoin y similares \(Zcash, Dash, LiteCoin, BitcoinGold, \) están fluctuando más de lo deseado y hay poderosos especuladores en torno a ellas. En el futuro se espera que el sistema se haga más resiliente, los precios se estabilicen y alguna de las monedas pueda funcionar en la práctica tal como hoy se utiliza el dinero físico.

Veamos la **explicación del precio** tomada de la [web de Bitcoin en español](https://bitcoin.org/es/faq#que-determina-el-precio-del-bitcoin):

> "El precio del bitcoin se determina por la oferta y la demanda. Cuando se incrementa la demanda de bitcoin, el precio sube, y cuando cae la demanda, cae el precio. Hay un número limitado de bitcoins en circulación y los nuevos bitcoins son creados a una velocidad predecible y decreciente, esto significa que la demanda debe seguir este nivel de inflación para mantener un precio estable. Debido a que Bitcoin es todavía un mercado relativamente pequeño comparado con lo que podrá llegar a ser, no es necesaria una significativa cantidad de dinero para mover el precio del mercado arriba o abajo, es por eso que el precio del bitcoin es todavía muy volatil"

Los precios se van estableciendo en función de las miles de transacciones que van ocurriendo en las plataformas de compra y venta, o **exchanges**[^2]. Cada una tiene mecanismos de validación de usuarios, de compra y de venta, de condiciones de depósito, comisiones, etc.. Además no todas manejan las mismas monedas, recuerda que hay centenas de criptos. Como resultado de toda esta variada configuración hay gente que prefiere una u otra plataforma.

En la plataforma llamada [CryptoCompare](https://www.cryptocompare.com/) tienes un listado de varias criptomonedas, sus caraterísticas y también sus precios en diferentes casas de cambio. [Cryptowatch](https://cryptowat.ch/) es una plataforma similar, aunque más orientada al precio y a su variación.

Todo esto que mencionamos, no prohibe que vos y tu contraparte decidan un **precio diferente** al de "mercado". Después de todo ¿qué es lo que da el valor a las cosas? Digamos que el precio de mercado del zcash es 200 dólares pero encuentras a una persona cercana que te los vende a 210, puede ser un buen negocio ya que te evitas todo el trámite de enviar tus dólares a un exchange y las posibles comisiones.

## Los precios fijos o anclados

Ya menciomamos que existen otras criptomonedas que no necesariamente se rigen por un precio de "mercado" \(mercado de casas cambiarias\) sino que **establecen sus precios por otros mecanismos.**

Un ejemplo de esas es **Faircoin** que fija su precio** por asamblea**. En momentos de escribir este texto, el precio de 1 FAIR equivale a 1,2 euros \(decidido en la [asamblea del 15 de enero de 2018](https://board.net/p/r.c834302f8c713b3a7073bf9827d3d3fb)\). Esto tiene por detrás una postura política que **no cree en los precios del mercado** y que argumenta que los mismos suelen estar manipulados por actores poderososo, de tal forma que se observan grandes fluctuaciones y los pequeños siempre pierden. Según esta perspectiva, lo más importante es la confianza basada en la horizontalidad, que va en consonancia con su organización cooperativa y su apuesta por un comercio justo. El precio de FAIR está siempre visible en su web: [https://fair-coin.org/](https://fair-coin.org/) y también allí se explica cuál es la estrategia al respecto: [https://fair-coin.org/en/create-value](https://fair-coin.org/en/create-value) \(en inglés\).

Otro caso de anclaje fijo es el [Petro](https://es.wikipedia.org/wiki/Petro_%28criptomoneda%29), la criptomoneda venezolana, es la primera en ser creada y respaldada por un Estado Nacional. El valor de la misma **no es fijo**, pero tampoco se mueve según los precios de mercado de los exchanges, sino del valor del barril de petróleo: un petro equivale al precio de **1 barril de petróleo en el mercado internacional**. Este es un proyecto muy nuevo con una billetera que no tiene su código disponible al público hasta el momento. Si te interesa, puedes encontrar más información en su página web: [https://www.petromoneda.net](https://www.petromoneda.net)

## ¿Qué es la minería de criptomonedas?

La **minería** es el proceso de **validación** nuevos bloques, que se agregan al blockchain. Por lo tanto, cuanto nodos haya realizando este trabajo, mejor será la validación y más confiable y potente será la red. Esto consiste en pruebas algorítmicas que cada nodo realiza automáticamente y que varía según cada criptomoneda. Bitcoin utiliza una prueba conocida como **Prueba de Trabajo** o **ProofOfWork \(PoW\)** que requiere la utilización de gran cantidad de tiempo y poder de cómputo.

Desde tu punto de vista, esto puede significar dejar tu computadora prendida y que se recaliente, y que consumas mucha energía \(al menos en el caso de Bitcoin\). También puede ser utilizar una parte importante de tu disco duro u otro bien cada criptomoneda utilice como prueba. Entonces, **¿para qué pondrías tu equipo a minar?**

Una primer respuesta es simplemente porque crees en el sistema y quieres apoyarlo con uno o varios nodos, pero para algunas personas no es suficiente. Entonces se buscan otros incentivos, **¿qué otros incentivos hay?**

Para responder la pregunta debemos comenzar a entender cómo se generan y distribuyen algunas monedas. Pongamos como ejemplo bitcoin. Desde su **diseño** se especificó que la máxima cantidad de btc en el mercado sería de 21 millones[^5]. Esto llama existencia controlada y se realiza para evitar la inflación desproporcionada. Es decir, se comienza de 0 y se llega a este tope, pero ¿cómo puedo resolver la distribución de estas monedas?

Un mecanismo posible es que se vayan **generando paulatinamente **y a la vez sirvan para **recompensar** a quienes colaboran con poder de cómputo para la red. De ahí el nombre de **minería**: _"si pones tu máquina a resolver algoritmos y robustecer la red, serás recompensado con las nuevas monedas que se van creando a lo largo del tiempo"_.

Así en sus inicios, se generaban y distribuían unos 50 btc por cada bloque validado, luego pasó a 25 y actualmente está en 12.5 bitcoin por bloque \(se reduce a la mitad cada 4 años aproximadamente\). Al principio obtener bitcoins por minería era una tarea relativamente sencilla pero a medida que la recompensa se redujo y la complejidad del sistema aumentó se vuelve cada vez más difícil hacerlo. Además para esta moneda en particular, minar hoy en día requiere muchísimo poder de cómputo, tanto que se suelen diseñar grandes cantidades de computadoras trabajando juntas para lograrlo. A esto se le denomina **pool de minería**: si quieres ver algo impresionante, revisa este video de cripto minería en China: [https://youtu.be/K8kua5B5K3I](https://youtu.be/K8kua5B5K3I)

## Las comisiones

Pero qué ocurre ahora que es tan difícil obtener nuevos bitcoins o peor aún ¿qué ocurrirá cuando ya todos los bitcoins estén generados?

Allí es donde entran las las **comisiones **de transacción que son un pequeño monto porcentual que se cobra a quien emite una nueva transacción. Este monto es la la **recompensa** para los mineros que colaboran en validar las transacciones del blockchian. Entonce si bien la recompensa de nuevos bitcoins se reduce, la recompensa por comisiones equilibra ya que cada vez hay más y más transacciones en la red. 

Ahora, hablando de otras criptomonedas, cada una establece cómo es su existencia y sus mecanismos de generación de nuevas monedas, además de **cómo serán las comisiones**. Todo eso provoca que la minería sea diferente para cada cripto.

Como un ejemplo, al momento de escribir este artículo, al enviar **5 FAIR** \(faircoin\) la **comisión aproximada** es de 0,001808 es decir 0,036% un valor bastante interesante como comisión.



Una **conclusión** de este capítulo es la siguiente: si bien la minería podría haber sido un negocio interesante desde el punto de vista económico para quienes apoyaron al sistema inicialmente, hoy en día no está al alcance de las personas individuales ganar cripto minando \(al menos para el caso de bitcoin\). 

Ya tienes un panorama de cómo es una transacción, cómo se determinan los precios, qué es la minería y qué son las comisiones. Esperamos te sea de utilidad y quieras leer nuestro futuro artículo sobre "Cómo crear una billetera".



**Palabras clave:** transacción, dirección, metadato, billetera, comisión, minería

[^1]: En realidad la donación que realicé fue a un solo nodo de la red Diaspora\* denominado [diasp.org](https://diasp.org/)

[^2]: Aquí hay un [listado y tabla comparativa](https://www.bestbitcoinexchange.io/) que te puede ser de utilidad. Y aquí un listado de los 80 exchanges más importante por su volumen de transacciones: [https://cryptocoincharts.info/markets/info](https://cryptocoincharts.info/markets/info)

[^3]: Al momento de escribir estos artículos el precio de mercado de Bitcoin estaba en torno a 6500 dólares.

[^4]: González Otero, J. M., & Moreno de la Cova, F. \(2013\). Bitcoin: la moneda del futuro: qué es, cómo funciona y porqué cambiará el mundo. Madrid: Unión Editorial.

[^5]: Actualmente hay unos 17 millones de bitcoin en circulación y se calcula que en 2020 se habrán generado los 21 millones. Fuente: [https://www.bitcoinblockhalf.com](https://www.bitcoinblockhalf.com/)

