# Bitcon, ethereum, faircoin ¿cuántas criptomonedas hay?

En las dos entregas anteriores, hablamos de forma general de las criptomonedas \[FIXME:enlace\], y vimos alguna de las críticas al sistema\[FIXME:enlace\]. Esta vez veremos algunos ejemplos que nos parecen más relevantes.

Comencemos respondiendo la pregunta del título, ¿cuántes criptomonedas hay? Hay **cientos de criptomonedas diferentes**: bitcoin fue solo la primera[^3].

En este artículo, nos centraremos en alguna de ellas porque son las más famosas o simplemente nos parece que resultan de mayor interés, es una elección totalmente arbitraria.

Las que describimos abajo, tienen las características que desarrrollamos en el capítulo anterior \[FIXME:enlace\]: son **software libre**, funcionan como una **red distribuída** \(p2p\), generan una **cantidad finita** de unidades monetarias y se basan en un registro o libro contable llamado **blockchain**.

La primera y la más famosa hasta el momento es [Bitcoin](https://bitcoin.org/es/), y veremos otras que tienen diferentes propuestas tecnológicas o políticas: cada una con diferente grado de éxito o adpoción hasta el momento.

Entonces veamos nuestro listado **no exahustivo y totalmente arbitrario** de criptomonedas:

## La primera: Bitcoin

Bitcoin fue la primer criptomoneda de éxito mundial y la más adoptada **hasta el momento**, veamos una explicación del sitio web de  [Bitcoin en Español: ](https://bitcoin.org/es/faq)

> "Bitcoin es la primera implementación de un concepto conocido como "moneda criptográfica", la cual fue descrita por primera vez en 1998 por Wei Dai en la lista de correo electónico "cypherpunks", donde propuso la idea de un nuevo tipo de dinero que utilizara la criptografía para controlar su creación y las transacciones, en lugar de que lo hiciera una autoridad centralizada. La primera especificación del protocolo Bitcoin y la prueba del concepto la publicó Satoshi Nakamoto en el 2009 en una lista de correo electrónico. Satoshi abandonó el proyecto a finales de 2010 sin revelar mucho sobre su persona. Desde entonces, la comunidad ha crecido de forma exponencial y cuenta con [numerosos desarrolladores](https://bitcoin.org/es/desarrollo) que trabajan en el protocolo Bitcoin".

Como ya se mencionó las criptomonedas deben ser un **"bien" escaso**, por eso existe un número limitado de bitcoins, que se ha fijado de forma arbitraria en **21 millones de unidades**. Lo mismo aplica para la amplia mayoría de las criptomonedas.

En el libro _"Bitcoin, la moneda del futuro"_ se resumen estas características de la siguiente forma:

> "A diferencia del dinero de curso forzoso, Bitcoin no puede ser controlado por ninguna autoridad debido a su naturaleza descentralizada. La expansión de la base monetaria está predeterminada por el software de Bitcoin y es conocida por todos, de modo que no es posible afectar el poder adquisitivo de los usuarios manipulando la cantidad de bitcoins en circulación".

Veremos más adelante de que estas afirmaciones sobre la "gobernanza" del sistema, como por ejemplo "no es controlado" y "conocida por todos" se ha expresado recientemente en algunos cambios y bifurcaciones, conocidos como **"hardforks"** con diversas implicaciones políticas y económicas. Lo retomaremos en futuras entregas.

Por último, cabe mencionar algunos elementos que se adelantaron en la sección de "críticas", que esta criptomoneda debería mejorar:

1. La cuestión de la** privacidad,** ya que los metadatos de la transacción son públicos: fecha, hora, monto y otros. También existen métodos de asociar dirección IP con usuarios, en caso que no se use en conjunto con Tor[^5]
2. El **tamaño del blockchain**: para correr un "nodo completo" de Bitcoin es necesario descargar el blockchain completo que al momento de escribir este texto pesa 160 GB[^1]
3. El **consumo** de recursos informáticos y energéticos que no suele ser amigable con el ambiente. La forma como valida las transacciones se denomina Proof-of-Work e implica un gran poder de cómputo. 

El software de Bitcoin está disponible para GNU/Linux, Android, Windows y Mac,  con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT) y veremos cómo instalarlo en siguientes artículos.

Te recomendamos que leas **todas** las [preguntas frecuentes de Bitcoin en español](https://bitcoin.org/es/faq): no tienen desperdicios.

## Litecoin, un intento de superar a Bitcoin

Está inspirada en Bitcoin y es técnicamente muy similar, con **3 diferencias principales**: **i\)** realiza el **procesamiento de bloques** de forma más rápida, **ii\)** el total de **unidades** en la red será 4 veces mayor que Bitcoin y **iii\)** usa la función **"scrypt"** en su mecanismo de Proof-of-Work \(PoW\) que hace el minado más sencillo.

Un tema interesante a tener en cuenta, que se desprende de esas 3 diferencias planteadas y que impacta en la [instalación de "nodo completo"](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/crear-un-nodo-completo-de-bitcoin.html) por parte de los usuarios, es el** tamaño del blockhain**. Sin embargo hasta el momento, su adopción y su valorización **no se han popularizado**: tiene unas 8 veces menos transacciones diarias que Bitcoin o Ethereum.

En el artículo ["What is the Difference Between Litecoin and Bitcoin?"](https://www.coindesk.com/information/comparing-litecoin-bitcoin/) ofrecen una tabla comparativa entre ambas monedas, así como las diferencias en los algoritmos de minado y otros detalles técnicos.

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT).

Puedes seguir investigando en la [Web Oficial de Litecoin.](https://litecoin.org/)

## Faircoin, una forma "justa" de intercambio de valor

En su web oficial, se plantea como una **alternativa a las criptomonedas**, que funciona a través de la cooperación en vez de la competencia y que utiliza una prueba llamada Prueba-de-Cooperación \(Proof-of-Cooperation\)[^2].

Su versión 2 fue lanzada en diciembre de 2016 y desde entonces existen unas **53 millones** de _fair. _ A diferencia de las otras, la existencia de monedas _fair_ no varía por la creación de nuevos bloques.

Para compensar el esfuerzo de correr un **Nodo Colaborativo y Validado** \(CVN\) se utiliza una pequeña comisión por cada transacción que se efectiviza en la creación de un bloque. El consumo de un CVN es tan bajo que puede correr en una RaspberryPi[^6].

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT](https://es.wikipedia.org/wiki/Licencia_MIT).

Te recomendamos [esta comparativa entre bitcoin y faircoin](https://criptomonedasfavoritas.tumblr.com/post/165550463544/comparativa-bitcoin-faircoin) y además puedes profundizar en [su página web](https://fair-coin.org).

## La privacidad por diseño: Zcash y Monero

Hay otras 2 monedas que se disputan **mejorar la privacidad** del sistema: sus creadores han aplicado el principio de** "privacidad por diseño".** Buscan "superar" bitcoin con diversas técnicas de anonimización y ocultamiento de metadatos, pues identifican que dirección de origen, destino y montos **pueden poner en riesgo** la identidad de los usuarios.

La primera que aparece, en 2014, es _Monero_ en 2014 y no es una "derivada de bitcoin" sino que utiliza un protocolo diferente llamado [CryptoNote](https://en.wikipedia.org/wiki/CryptoNote), además de un algoritmo de minado llamado _CryptoNight._ A su vez tiene 3 componentes tecnológicos que permiten **mantener las transacciones confidenciales**:_ ring signatures,_ _ring confidential transactions_ \(RingCT\) y _stealth address_. Como resultado la información acerca de quién envía, quien recibe y los montos de cada transacción queda oculta, es decir, todas las transacciones de la red son privadas "por mandato" y no hay forma de hacer una transacción transparente.

En cuanto a las existencias, en mayo de 2024, se llegará a un total de **18,4 millones **de monedas y luego tendrá una inflación de 1% anual que irá reduciéndose paulatínamente[^4].

Puedes seguir profundizando sobre monero en su [página web](https://getmonero.org/) que también tiene una sección de [preguntas frecuentes](https://getmonero.org/get-started/faq/).

La segunda moneda que nos interesa aquí es _Zcash_ que surge en 2016 y de la misma forma, aplica el principio de "privacidad por diseño". En este caso, surge como una mejora de bitcoin, utilizando parte de su protocolo. Utiliza el algoritmo Equihash y técnicas criptográficas de conocimiento cero[^7] para mantener los detalles de las transacciones en secreto: las transacciones que ocultan los metadatos se llaman [transacciones blindadas](https://z.cash/es/blog/zcash-private-transactions.html). En el blog de Zcash puedes leer una explicación en español de cómo funcionan: 

Puedes seguir investigando en la [Web de Zcash](https://z.cash/).

## Chia, un abordaje para proteger al ambiente

[Web de Chia](https://chia.network)

ProofOfSpace

Artículo: [https://techcrunch.com/2017/11/08/chia-network-cryptocurrency/](https://techcrunch.com/2017/11/08/chia-network-cryptocurrency/)

## Ethereum, más allá de las monedas

asdf

En el artículo ["Pero, ¿cómo funcionan?"](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/pero-como-funcionan.html) presentamos una sección "Herramientas" donde encontrarás varias formas de comparar todas estas criptomonedas

[^1]: "Nodo completo" significa tener funcionando en tu propia computadora la versión oficial del software de bitcoin y la billetera bajo tu completo control. No es necesario que esto sea así para tener tus bitcoin, pero es la forma más soberana de tenerlo. Lo seguiremos desarrollando en futuros artículos. Puedes ver el [tamaño del blockchain aquí](https://blockchain.info/es/charts/blocks-size) en "tiempo real".

[^2]: Esto será retomado en el artículo ["Las diferentes pruebas".](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/pow-vs-pos.html)

[^3]: Aquí podrás acceder a un listado de más de mil criptomonedas: [https://coinmarketcap.com/all/views/all/](https://coinmarketcap.com/all/views/all/)

[^4]: Aquí puedes ver un [cuadro comparativo](https://docs.google.com/spreadsheets/d/1qXi7zUSIh7F6UuSuhOryyFbHEy_LJuym3I3neAga_2s/edit?pli=1#gid=239466694) de las existencias, porcentaje de minado y otros guarismos entre bitcoin y monero. 

[^5]: [Tor](https://es.wikipedia.org/wiki/Tor_%28red_de_anonimato%29) es un sistema de anonimización en Internet.

[^6]: [RaspberryPi](https://www.raspberrypi.org/) es un "computador de placa simple" de bajo coste que surgió como un proyecto educativo y que se ha generalizado para diversos usos: domótica, estaciones metereológicas, robótica y otros. Además ha hecho crecer enormemente la cantida de proyectos similares. 

[^7]: Aquí hay una definición  de las técnicas de ["conocimento cero"](https://es.wikipedia.org/wiki/Prueba_de_conocimiento_cero) con un ejemplo para entenderlas mejor.   

