# ¿Hay varias criptomonedas?

Efectivamente hay varias centenas de ellas[^3] y en estos artículos nos centraremos solo en algunas de ellas. Elegimos las más famosas o las que nos parece que revisten mayor interés. En particular, tienen las características que te presentamos en el capítulo anterior: son **software libre**, funcionan como una **red distribuída** \(p2p\), generan una **cantidad finita** de unidades monetarias y se basan en un registro o libro contable llamado **blockchain**.

La primera y la más famosa hasta el momento es [Bitcoin](https://bitcoin.org/es/). Sin embargo debemos tener presente las otras criptomonedas, y sus diferentes propuestas tecnológicas o políticas; cada una con diferente grado de éxito o adpoción, pero hasta el momento de escribir estos artículo, todas a la sombre de Bitcoin. Aquí te presentamos un listado **no exahustivo y totalmente arbitrario** de las que nos resultan más interesantes.

## La primera: Bitcoin

Bitcoin fue la primer criptomoneda de éxito mundial y la más adoptada hasta el momento, veamos una explicación del sitio web de  [Bitcoin en Español: ](https://bitcoin.org/es/faq)

> "Bitcoin es la primera implementación de un concepto conocido como "moneda criptográfica", la cual fue descrita por primera vez en 1998 por Wei Dai en la lista de correo electónico "cypherpunks", donde propuso la idea de un nuevo tipo de dinero que utilizara la criptografía para controlar su creación y las transacciones, en lugar de que lo hiciera una autoridad centralizada. La primera especificación del protocolo Bitcoin y la prueba del concepto la publicó Satoshi Nakamoto en el 2009 en una lista de correo electrónico. Satoshi abandonó el proyecto a finales de 2010 sin revelar mucho sobre su persona. Desde entonces, la comunidad ha crecido de forma exponencial y cuenta con [numerosos desarrolladores](https://bitcoin.org/es/desarrollo) que trabajan en el protocolo Bitcoin".

Como ya se mencionó las criptomonedas deben ser un **bien escaso**, por eso existe un número limitado de bitcoins, que se ha fijado de forma arbitraria en **21 millones de unidades**. Lo mismo aplica para la amplia mayoría de las criptomonedas.

En el libro _"Bitcoin, la moneda del futuro"_ se resumen estas características de la siguiente forma:

> "A diferencia del dinero de curso forzoso, Bitcoin no puede ser controlado por ninguna autoridad debido a su naturaleza descentralizada. La expansión de la base monetaria está predeterminada por el software de Bitcoin y es conocida por todos, de modo que no es posible afectar el poder adquisitivo de los usuarios manipulando la cantidad de bitcoins en circulación".

Por último, cabe mencionar algunos elementos que se adelantaron en la sección de críticas y son elementos que esta criptomoneda debería mejorar:

1. La cuestión de la** privacidad,** ya que los metadatos de la transacción son públicos: fecha, hora, monto y otros. 
2. El **tamaño del blockchain**: para correr un nodo completo de bitcoin es necesario descargar el blockchain completo que al momento de escribir este texto pesa 156 GB[^1]. 
3. El **consumo** de recursos informáticos y por lo tanto energéticos que no suele ser amigable con el ambiente. La forma como valida las transacciones se denomina Proof-of-Work e implica un gran poder de cómputo. Esto ya lo mencionamos en un artículo anterior y lo veremos nuevamente más adelante. 

El software de Bitcoin está disponible para GNU/Linux, Android, Windows y Mac,  con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT) y veremos cómo instalarlo en siguientes artíclos.

Te recomendamos que leas todas las [preguntas frecuentes en español](https://bitcoin.org/es/faq): no tienen desperdicios.

## Litecoin, un intento de superar a Bitcoin

Está inspirada en Bitcoin y es técnicamente muy similar, con **3 diferencias principales**: **i\)** realiza el procesamiento de bloques de forma más rápida, **ii\)** el total de unidades en la red será 4 veces mayor que Bitcoin y **iii\)** usa la función "scrypt" en su mecanismo de Proof-of-Work que hace el minado más sencillo.

Un tema interesante a tener en cuenta, que se desprende de esas 3 diferencias planteadas y que impacta en la [instalación de "nodo completo"](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/crear-un-nodo-completo-de-bitcoin.html) por parte de los usuarios, es el** tamaño del blockhain**. Sin embargo hasta el momento, su adopción y su valorización **no se han popularizado**: tiene unas 8 veces menos transacciones diarias que Bitcoin o Ethereum.

En el artículo ["What is the Difference Between Litecoin and Bitcoin?"](https://www.coindesk.com/information/comparing-litecoin-bitcoin/) ofrecen una tabla comparativa entre ambas monedas, así como las diferencias en los algoritmos de minado y otros detalles técnicos.

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT).

Puedes seguir investigando en la [Web Oficial de Litecoin.](https://litecoin.org/)

## Faircoin, una forma "justa" de intercambio de valor

En su web oficial, se plantea como una **alternativa a las criptomonedas**, que funciona a través de la cooperación en vez de la competencia y que utiliza una prueba llamada Prueba-de-Cooperación \(Proof-of-Cooperation\)[^2].

Su versión 2 fue lanzada en diciembre de 2016 y desde entonces existen unas **53 millones** de _fair. _ A diferencia de las otras, la existencia de monedas _fair_ no varía por la creación de nuevos bloques. 

Para compensar el esfuerzo de correr un Nodo Colaborativo y Validado \(CVN\) se utiliza una pequeña comisión por cada transacción que se efectiviza en la creación de un bloque. El consumo de un CVN es tan bajo que puede correr en una RaspberryPi.

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT](https://es.wikipedia.org/wiki/Licencia_MIT).

Te recomendamos [esta comparativa entre bitcoin y faircoin](https://criptomonedasfavoritas.tumblr.com/post/165550463544/comparativa-bitcoin-faircoin) y además puedes profundizar en [su página web](https://fair-coin.org).

## El anonimato como problema: Zcash y Monero

Hay dos monedas que se disputan mejorar el sistema en cuanto a privacidad. Es que bitcoin ha demostrado no proteger la identidad de quienes intercambian valor. 

Para ello aparecen Monero en 2014 y Zcash en 2016. La primera surge en 2014 como y utiliza un protocolo diferente al de Bitcoin llamado [CryptoNote](https://en.wikipedia.org/wiki/CryptoNote). 

FIXME: continuar

## Chia, un abordaje para proteger al ambiente

[https://techcrunch.com/2017/11/08/chia-network-cryptocurrency/](https://techcrunch.com/2017/11/08/chia-network-cryptocurrency/)

## Ethereum, más allá de las monedas

asdf

En el artículo ["Pero, ¿cómo funcionan?"](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/pero-como-funcionan.html) presentamos una sección "Herramientas" donde encontrarás varias formas de comparar todas estas criptomonedas

[^1]: "Nodo completo" significa tener funcionando en tu propia computadora la versión oficial del software de bitcoin y la billetera bajo tu completo control. No es necesario que esto sea así para tener tus bitcoin, pero es la forma más soberana de tenerlo. Lo seguiremos desarrollando en futuros artículos. Puedes ver el [tamaño del blockchain aquí](https://blockchain.info/es/charts/blocks-size) en "tiempo real".

[^2]: Esto será retomado en el artículo ["Las diferentes pruebas".](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/pow-vs-pos.html)

[^3]: Aquí podrás acceder a un listado de más de mil criptomonedas: [https://coinmarketcap.com/all/views/all/](https://coinmarketcap.com/all/views/all/)

