# Bitcon, Zcash, Faircoin ¿cuántas criptomonedas hay?

En las dos entregas anteriores, hablamos de [forma general de las criptomonedas](https://www.tedic.org/bitcoin-para-no-informaticos-entrega-1-que-son-las-criptomonedas/), y vimos alguna de las [críticas al sistema](https://www.tedic.org/bitcoin-para-no-informaticos-entrega-2-las-criticas-al-sistema/). Esta vez veremos algunas criptomonedas que nos parecen relevantes.

Comencemos respondiendo la pregunta del título, ¿cuántas criptomonedas hay? Hay **cientos de criptomonedas diferentes**: bitcoin fue solo la primera[^3]. De hecho deberás tener cuidado pues hay monedas con nombres muy similares: para evitar dudas, chequea dos veces que la moneda que vas a comprar sea la adecuada así como su **acrónimo que suele ser un código de 3 letras**, por ejemplo, **Bitcoin es BTC**, mientras que **Bitocoin Cash es BCH** y si bien tienen un origen común, hoy son dos programas y dos blockchains totalmente diferentes.

En este artículo, nos centraremos en solamente 3 o 4 de las centenas de criptomonedas que existen y que creemos que son las más importantes: por ser las más utilizadas, por alguna cuestión histórica o porque tienen alguna característica especial que las distingue de las otras.

Las que describimos abajo, tienen "las características" que desarrollamos en el capítulo anterior \[FIXME:enlace\]: son **software libre**, funcionan como una **red distribuida** \(p2p\), generan una **cantidad finita** de unidades monetarias y se basan en un registro o libro contable llamado **blockchain**.

Entonces veamos nuestro listado **no exhaustivo y totalmente arbitrario** de criptomonedas:

## La primera: Bitcoin

Bitcoin \(BTC\) fue la primer criptomoneda de éxito mundial y la más adoptada **hasta el momento**, veamos una explicación del sitio web de  [Bitcoin en Español: ](https://bitcoin.org/es/faq)

> "Bitcoin es la primera implementación de un concepto conocido como "moneda criptográfica", la cual fue descrita por primera vez en 1998 por Wei Dai en la lista de correo electrónico "cypherpunks", donde propuso la idea de un nuevo tipo de dinero que utilizara la criptografía para controlar su creación y las transacciones, en lugar de que lo hiciera una autoridad centralizada. La primera especificación del protocolo Bitcoin y la prueba del concepto la publicó Satoshi Nakamoto en el 2009 en una lista de correo electrónico. Satoshi abandonó el proyecto a finales de 2010 sin revelar mucho sobre su persona. Desde entonces, la comunidad ha crecido de forma exponencial y cuenta con [numerosos desarrolladores](https://bitcoin.org/es/desarrollo) que trabajan en el protocolo Bitcoin".

Como ya se mencionó las criptomonedas deben ser un **"bien" escaso**, por eso existe un número limitado de bitcoins, que se ha fijado de forma arbitraria en **21 millones de unidades**. Lo mismo aplica para la amplia mayoría de las criptomonedas.

En el libro _"Bitcoin, la moneda del futuro"_ se resumen estas características de la siguiente forma:

> "A diferencia del dinero de curso forzoso, Bitcoin no puede ser controlado por ninguna autoridad debido a su naturaleza descentralizada. La expansión de la base monetaria está predeterminada por el software de Bitcoin y es conocida por todos, de modo que no es posible afectar el poder adquisitivo de los usuarios manipulando la cantidad de bitcoins en circulación".

Veremos más adelante de que estas afirmaciones sobre la "gobernanza" del sistema, como por ejemplo "no es controlado" y "conocida por todos" se ha expresado recientemente en algunos cambios y bifurcaciones, conocidos como **"hardforks"** con diversas implicaciones políticas y económicas. Lo retomaremos en futuras entregas.

Por último, cabe mencionar algunos elementos que se adelantaron en la sección de "críticas", que esta criptomoneda debería mejorar:

1. La cuestión de la** privacidad,** ya que los metadatos de la transacción son públicos: fecha, hora, monto y otros. También existen métodos de asociar dirección IP con usuarios, en caso que no se use en conjunto con Tor[^5]
2. El **tamaño del blockchain**: para correr un "nodo completo" de Bitcoin es necesario descargar el blockchain completo que al momento de escribir este texto pesa 160 GB[^1]
3. El **consumo** de recursos informáticos y energéticos que no suele ser amigable con el ambiente. La forma como valida las transacciones se denomina Proof-of-Work \(PoW\) e impulsa la creación y puesta en funcionamiento de computadoras más poderosas con mayor consumo energético. 

El software de Bitcoin está disponible para GNU/Linux, Android, Windows y Mac,  con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT) y veremos cómo instalarlo en siguientes artículos.

Te recomendamos que leas **todas** las [preguntas frecuentes de Bitcoin en español](https://bitcoin.org/es/faq): no tienen desperdicios.

## Litecoin, un intento de superar a Bitcoin

Litecoin \(LTC\) surgió en 2011 inspirada en Bitcoin y como intento de superarla. Es tecnicamente muy similar, con **3 diferencias principales**: **i\)** realiza el **procesamiento de bloques** de forma más rápida, **ii\)** el total de **unidades** en la red será 4 veces mayor que Bitcoin y **iii\)** usa la función **"scrypt"** en su mecanismo de Proof-of-Work \(PoW\) que hace el minado más sencillo.

Un tema interesante a tener en cuenta, que se desprende de esas 3 diferencias planteadas y que impacta en la [instalación de "nodo completo"](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/crear-un-nodo-completo-de-bitcoin.html) por parte de los usuarios, es el** tamaño del blockhain**. Sin embargo hasta el momento, su adopción y su valorización **no se han popularizado**: tiene unas 8 veces menos transacciones diarias que Bitcoin o Ethereum.

En el artículo ["What is the Difference Between Litecoin and Bitcoin?"](https://www.coindesk.com/information/comparing-litecoin-bitcoin/) ofrecen una tabla comparativa entre ambas monedas, así como las diferencias en los algoritmos de minado y otros detalles técnicos.

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT/X11](https://es.wikipedia.org/wiki/Licencia_MIT).

Puedes seguir investigando en la [Web Oficial de Litecoin.](https://litecoin.org/)

## Faircoin, una forma "justa" de intercambio de valor

Faircoin \(FAIR\) se plantea como una **alternativa a las criptomonedas**, que funciona a través de la cooperación en vez de la competencia y que utiliza una prueba llamada Prueba-de-Cooperación \(Proof-of-Cooperation\)[^2]. Según su página web esto la hace más democrática que el resto además de más amigable con el ambiente.

Su versión 2 fue lanzada en julio de 2017 y desde entonces existen unas **53 millones** de _fair. _ A diferencia de las otras, la existencia de monedas _fair_ no varía por la creación de nuevos bloques.

Para compensar el esfuerzo de correr un **Nodo Colaborativo y Validado** \(CVN\) se utiliza una pequeña comisión por cada transacción que se efectiviza en la creación de un bloque. El consumo de un CVN es tan bajo que puede correr en una RaspberryPi[^6].

A diferencia de las otras que presentamos, esta es la única en que el **precio de la moneda es fijo**, y está fijado por una asamblea de miembros de su comunidad cooperativa \([FairCoop](https://fair.coop)\). Además se ha generado un ecosistema, principalmente en Europa, de [tiendas tanto físicas](https://use.fair-coin.org/) como [online](https://market.fair.coop) para el intercambio de valores y servicios utilizando FAIR. En este [video promocional](https://vimeo.com/253953965) se muestra a través de un ejemplo real, cómo una persona [pagar un taxi con FAIRs](https://use.fair-coin.org/listings/taxi-en-valencia/).

El **precio actual de faircoin es de 1,2 €** y probablemente sea muy similar cuando leas este artículo ya que no varía demasiado en el tiempo a diferencia de las monedas que se manejan a precio de mercado.

Su software, está disponible para GNU/Linux, Android, Windows y Mac, con una [licencia MIT](https://github.com/faircoin/faircoin/blob/master/COPYING).

Te recomendamos [esta comparativa entre bitcoin y faircoin](https://criptomonedasfavoritas.tumblr.com/post/165550463544/comparativa-bitcoin-faircoin) y además puedes profundizar en [su página web](https://fair-coin.org).

## La privacidad por diseño: Zcash y Monero

Hay otras 2 monedas que se disputan **mejorar la privacidad** del sistema: sus creadores han aplicado el principio de** "privacidad por diseño".** Buscan "superar" bitcoin con diversas técnicas de anonimización y ocultamiento de metadatos, pues identifican que dirección de origen, destino y montos **pueden poner en riesgo** la identidad de los usuarios.

### Monero

Monero \(XMR\) aparece en 2014 y no es una "derivada de bitcoin" sino que utiliza un código completamente diferente y un protocolo llamado [CryptoNote](https://en.wikipedia.org/wiki/CryptoNote), además de un algoritmo de minado llamado _CryptoNight._ A su vez tiene 3 componentes tecnológicos que permiten **mantener las transacciones confidenciales**:_ ring signatures,_ _ring confidential transactions_ \(RingCT\) y _stealth address_. Como resultado la información acerca de quién envía, quien recibe y los montos de cada transacción queda oculta, es decir, todas las transacciones de la red son privadas "por mandato" y no hay forma de hacer una transacción transparente.

En cuanto a las existencias, en mayo de 2024, se llegará a un total de **18,4 millones **de monedas y luego tendrá una inflación de 1% anual que irá reduciéndose paulatínamente[^4].

Su software, está disponible para GNU/Linux, Android, Windows, Mac y otros sistemas, con una [licencia específica](https://github.com/monero-project/monero-gui/blob/master/LICENSE).

Puedes seguir profundizando sobre Monero en su [página web](https://getmonero.org/) que también tiene una sección de [preguntas frecuentes](https://getmonero.org/get-started/faq/).

### Zcash

Zcash \(ZEC\) por su parte, surge en 2016 y también aplica el principio de "privacidad por diseño". El surgimiento tardío le dio el beneficio de aprender de los errores del pasado, presentándose como una mejora de bitcoin, que utiliza parte de su protocolo y de su código, pero con mucha innovación y nuevas funcionalidades. El algoritmo de Zcash se llama [Equihash](https://blog.z.cash/es/why-equihash/) y es resistente al minado con "ASIC" \(es hardware diseñado específicamente para minar Bitcoin u otra crypto\). Esto significa que no es **económicamente viable** minar Zcash con este tipo de tecnologías. Las implicaciones políticas de esto las discutiremos en un futuro artículo sobre minería.

En cuanto a la privacidad de los usuarios, las **transacciones pueden ser "transparentes" **como las de Bitcoin, o **"blindadas"**. En este último caso, Zcash utiliza un algoritmo de ocultamiento llamado zk-SNARKs[^10] que es una "prueba de conocimiento cero"[^7]. De esta forma se ocultan los detalles de las transacciones como monto, remitente y destinatario. En el blog de Zcash puedes leer una explicación en español acerca de [Cómo Funcionan Las Transacciones Entre Direcciones Blindadas](https://z.cash/es/blog/zcash-private-transactions.html).

La cantidad de monedas será como máximo de **21 millones** y la generación de un bloque se da en promedio cada 2 minutos y medio. Los detalles del blockchain de Zcash los podrás ver en [Zchain](https://explorer.zcha.in/).

Puedes seguir investigando en la [web de Zcash](https://z.cash/) que también tiene una sección de [preguntas frecuentes](https://z.cash/support/faq.html).

## Chia, un abordaje para proteger al ambiente

Chia es un proyecto de criptomoneda que en momentos de escribir este artículo aún no está en funcionamiento. Según su web y algunos [artículos de prensa](https://techcrunch.com/2017/11/08/chia-network-cryptocurrency/), buscará ser una alternativa amigable con el ambiente en contraposición con los problemas que tienen las criptomonedas estilo Bitcoin y que ya mencionamos en el artículo anterior.

Sus pruebas criptográficas combinarían el espacio en disco duro "ProofOfSpace" y de tiempo de uso "ProofOfTime". Explicaremos los detalles en un futuro artículo específico sobre las "pruebas criptográficas".

Puedes investigar más en la [web de Chia](https://chia.network) y en su sección de [preguntas frecuentes](https://chia.net/faq/).

## Ethereum, más allá de las monedas

En al último de los artículos discutiremos otros usos de las tecnologías de blockchain, más allá de las criptomonedas, sin embargo adelantaremos algo hablando de Ethereum \(ETH\), que es una plataforma que combina una **criptomoneda** \(ether\) ara el intercambio y almacenamiento de valor, con un innovador concepto de **contratos inteligentes **ente pares \(o "smart contracts"\). Esto sumado a su lenguage de programación permite la creación de aplicaciones descentralizadas \(Daps\). Por lo tanto Ethereum es una criptomoneda, un protocolo, un lenguaje de programación y una plataforma de aplicaciones.

El proyecto comenzó a funcionar en 2015 y se financió a través de financiación colectiva o "crowdfunding", obteniendo unos 15 millones de dólares en 2014. A pesar de tener ya 3 años de desarrollo, el proyecto aún se considera en fase beta. Si bien su prueba algorítmica utiliza ProofOfWork \(PoW\), se supone que pronto cambiará a ProofOfStake \(PoS, prueba de participación\).

El **total de monedas** en momentos de escribir este artículo es de unas **100 millones**[^8], que irá creciendo cada año en una especie de inflación controlada decreciente[^9].

En cuanto a los **contratos inteligentes**, estos son unidades programables en la red ethereum en las que dadas ciertas condiciones iniciales, aseguran que al cumplirse, se ececuta cierta transacción, y todo esto utilizando el blockchain. Estos contratos pueden interactuar con otros, para ejecutar aplicaciones más complejas.

Es importante aclarar que para comprender y utilizar esta plataforma en todo su potencial, sí se requieren conocimientos en informática y probablemente de programación. Puedes seguir leyendo en la [Web de Ethereum](https://ethereum.org/) y sobre todo en sus [Preguntas Frecuentes](https://www.ethereum.org/ether).

## Otras

Otras monedas que te recomendamos revisar:

* [Dash](https://www.dash.org/) \(DASH\): con privacidad por diseño \(no confundir con dashcoin\)
* [Gridcoin](https://www.gridcoin.us/) \(GRC\): pon tu poder de computo al servicio de la investigación científica
* [CreativeCoin](https://www.creativechain.org/) \(CREA\): para el intercambio de bienes creativos
* Revisa los hardforks de Bitcoin [aquí](https://coincentral.com/the-upcoming-bitcoin-hard-forks-what-you-need-to-know/) o [aquí](http://list.wiki/Bitcoin_Hard_Forks) \(sobre todo si compraste bitcoin antes de 2017\)

Esperemos que te haya gustado el artículo, y que te sea de utilidad para comprender estos procesos que serán de vital importancia en el futuro. No dudes en comentar abajo o escribirnos en nuestro formulario de contacto.

---

**En próximos artículos presentaremos varias formas de adquirir y utilizar estas y otras criptomonedas.**

---

[^1]: "Nodo completo" significa tener funcionando en tu propia computadora la versión oficial del software de bitcoin y la billetera bajo tu completo control. No es necesario que esto sea así para tener tus bitcoin, pero es la forma más soberana de tenerlo. Lo seguiremos desarrollando en futuros artículos. Puedes ver el [tamaño del blockchain de Bitcoin](https://blockchain.info/es/charts/blocks-size) en "tiempo real".

[^2]: Esto será retomado en el artículo ["Las diferentes pruebas".](https://lupa18.gitbooks.io/bitcoin-para-no-informaticos/pow-vs-pos.html)

[^3]: Aquí podrás acceder a un listado de más de mil criptomonedas: [https://coinmarketcap.com/all/views/all/](https://coinmarketcap.com/all/views/all/)

[^4]: Aquí puedes ver un [cuadro comparativo](https://docs.google.com/spreadsheets/d/1qXi7zUSIh7F6UuSuhOryyFbHEy_LJuym3I3neAga_2s/edit?pli=1#gid=239466694) de las existencias, porcentaje de minado y otros guarismos entre bitcoin y monero. 

[^5]: [Tor](https://es.wikipedia.org/wiki/Tor_%28red_de_anonimato%29) es un sistema de anonimización en Internet.

[^6]: [RaspberryPi](https://www.raspberrypi.org/) es un "computador de placa simple" de bajo coste que surgió como un proyecto educativo y que se ha generalizado para diversos usos: domótica, estaciones meteoreológicas, robótica y otras [miles de posibilidades](https://www.hackster.io/raspberry-pi). Además ha hecho crecer enormemente la cantida de proyectos similares. 

[^7]: Para comprender mejor las pruebas de conocimiento cero, puedes ver la definición y ejemplos en el artículo de Wikipedia: ["Prueba de conocimento cero"](https://es.wikipedia.org/wiki/Prueba_de_conocimiento_cero).   

[^8]: Puedes verlo [aquí: https://etherscan.io/stat/supply](https://etherscan.io/stat/supply)

[^9]: Puedes leer interesante hilo de discusión en el [foro de ethereum: https://forum.ethereum.org/discussion/46/total-supply-of-eth](https://forum.ethereum.org/discussion/46/total-supply-of-eth)

[^10]:  Este protocolo ha sido adoptado recientemente por Ethereum: [https://z.cash/es/blog/ethereum-snarks.html](https://z.cash/es/blog/ethereum-snarks.html)

