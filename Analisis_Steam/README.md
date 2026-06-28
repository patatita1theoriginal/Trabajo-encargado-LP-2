
# Proyecto: Sistema de Análisis de Reseñas y Datos de Videojuegos

Este documento centraliza el código para el análisis de sentimientos y detección de texto generado por IA, así como la gestión de datos de **Steam**.

## 1. Código Integrado de Json (`analisis`)
```json
[
    {
        "medio": "Valak",
        "puntuacion": 100,
        "comentario": "67"
    },
    {
        "medio": "Minitheboss23",
        "puntuacion": 100,
        "comentario": "todo"
    },
    {
        "medio": "daviiidarroba",
        "puntuacion": 100,
        "comentario": "Juegazo con  o sin amigos te lo vas a pasar bien"
    },
    {
        "medio": "luquibru",
        "puntuacion": 100,
        "comentario": "juego muy copado y ademas con los mapas especiales se vuelve un jugo muy divertido (pero nescesitas saber pintar para sobrevivir)"
    },
    {
        "medio": "$LuK$",
        "puntuacion": 100,
        "comentario": "Me parece un buen juego pero con el único problema que veo es que tengas que buscar un servidor muy precariamente y no solo poner en búsqueda"
    },
    {
        "medio": "☠Nicolas☠",
        "puntuacion": 100,
        "comentario": "siu xd"
    },
    {
        "medio": "Richard Waterson",
        "puntuacion": 100,
        "comentario": "juegazo"
    },
    {
        "medio": "ferbon",
        "puntuacion": 0,
        "comentario": "muchos bugs en esta actualizacion"
    },
    {
        "medio": "ricardoarqui5",
        "puntuacion": 100,
        "comentario": "MARAVILLOSO"
    },
    {
        "medio": "Jefry",
        "puntuacion": 100,
        "comentario": "bien"
    },
    {
        "medio": "salvadormurcho",
        "puntuacion": 100,
        "comentario": "muy bueno"
    },
    {
        "medio": "Ryno",
        "puntuacion": 100,
        "comentario": "si"
    },
    {
        "medio": "danielpower42",
        "puntuacion": 100,
        "comentario": "Juego para GENIOOOS!!!! del escondite"
    },
    {
        "medio": "llucfabregat",
        "puntuacion": 100,
        "comentario": "Divertido para jugar con amigos pero hay algunos fallos y bugs"
    },
    {
        "medio": "BNG*******er",
        "puntuacion": 100,
        "comentario": "Mola"
    },
    {
        "medio": "AlvaroRUE",
        "puntuacion": 100,
        "comentario": "."
    },
    {
        "medio": "martinleonardo14",
        "puntuacion": 100,
        "comentario": "este juego es muy bueno para jugar con amigos y todos los que lo juegan es muy buen juego aunque algunas personas se dicen malas palabras jajaja"
    },
    {
        "medio": "imperio romano occidente",
        "puntuacion": 0,
        "comentario": "amigo si tu pc no tiene mas de 128 de ram no lo compres te va andar como la mierda"
    },
    {
        "medio": "mendezariel",
        "puntuacion": 100,
        "comentario": "b"
    },
    {
        "medio": "Matiasasoc",
        "puntuacion": 100,
        "comentario": "muy buen juego tiene mods gratis variedad de mapas y colores muy bueno"
    },
    {
        "medio": "antrusquireal901",
        "puntuacion": 0,
        "comentario": "juego mal creado cuando me meto me saca con un anuncio que dice as sido reportado y no deja jugar no lo descarguen es solo un mal gasto de dinero"
    },
    {
        "medio": "Derrygan",
        "puntuacion": 100,
        "comentario": "*Se camufla* fiu fiu"
    },
    {
        "medio": "tincho536",
        "puntuacion": 100,
        "comentario": "nasheardobuenardopolis"
    },
    {
        "medio": "pepito",
        "puntuacion": 100,
        "comentario": "ete jugo trata de ke eres un monito y te pintaaas y te camuflaas y y todo esooo pe pero pero cuando llega teniente yy se laba las manitas con aguita y jabon pinpon y y deja ciego a un tipo y se keda cieguito y le da mucha risita y y y nadie le le saluda cuando llega a el server y se enoja con su comunidad por no imterabtuar con eyos"
    },
    {
        "medio": "zvzvzvz",
        "puntuacion": 100,
        "comentario": "bkn"
    },
    {
        "medio": "luaydn",
        "puntuacion": 100,
        "comentario": "Es un juego muy entretenido para jugar con amigos, claro falta pulir las mecánicas del juego, pero por el precio lo vale todo."
    },
    {
        "medio": "m0NESY",
        "puntuacion": 100,
        "comentario": "buenjuego"
    },
    {
        "medio": "glitzale2016",
        "puntuacion": 100,
        "comentario": "es bueno pero se me queda trabado cuando entro"
    },
    {
        "medio": "reynolds",
        "puntuacion": 0,
        "comentario": "juego mal optimizado, me anda mejor el poppy playtime que esto"
    },
    {
        "medio": "kevinaso01",
        "puntuacion": 100,
        "comentario": "si"
    },
    {
        "medio": "s-gatito",
        "puntuacion": 100,
        "comentario": "no se :3"
    },
    {
        "medio": "pedritus_blanco",
        "puntuacion": 100,
        "comentario": "juegazo"
    },
    {
        "medio": "AngelSG0123",
        "puntuacion": 100,
        "comentario": "es muy chhulooo"
    },
    {
        "medio": "_k0jaku_",
        "puntuacion": 0,
        "comentario": "Tiene que arreglar la búsqueda de servidores, no se puede buscar por nombre y las etiquetas son inútiles. El juego es divertido pero he estado más rato en total buscando el server que ha creado mi colega que jugando con el. Cambiaré la reseña a positiva cuando lo arreglen."
    },
    {
        "medio": "maximogommar",
        "puntuacion": 100,
        "comentario": "Controles muy bien optimizados muchas opciones facil de entender idea original muy recomendable por el precio"
    },
    {
        "medio": "hugo.cano.tena",
        "puntuacion": 100,
        "comentario": "es la cabra"
    },
    {
        "medio": "Boogie APZ",
        "puntuacion": 100,
        "comentario": "Un juego bastante divertido para estar con los amigos un rato"
    },
    {
        "medio": "tiopaco_0",
        "puntuacion": 100,
        "comentario": "divertido"
    },
    {
        "medio": "tzyumiiwnl",
        "puntuacion": 100,
        "comentario": "AURA"
    },
    {
        "medio": "OH\\",
        "puntuacion": 100,
        "comentario": "muy bueno"
    },
    {
        "medio": "Yireh Seashell",
        "puntuacion": 100,
        "comentario": "libertad creativa a mil"
    },
    {
        "medio": "|   M1G   |",
        "puntuacion": 100,
        "comentario": "Está muy bueno el juego, como recomendación, deberían habilitar una opción dentro del pontado, para cambiar el tipo de pincel, hacer cosas como lineas finas, difuminandos, facilitar deegradado, etc."
    },
    {
        "medio": "Nitsu",
        "puntuacion": 100,
        "comentario": "nice"
    },
    {
        "medio": "jacoboga09",
        "puntuacion": 100,
        "comentario": "esta muy muy muy chulo"
    },
    {
        "medio": "Gamechip",
        "puntuacion": 100,
        "comentario": "muy bueno"
    },
    {
        "medio": "Fronta",
        "puntuacion": 100,
        "comentario": "67"
    },
    {
        "medio": "ñom",
        "puntuacion": 100,
        "comentario": "semen"
    },
    {
        "medio": "K4os9",
        "puntuacion": 100,
        "comentario": "Divertido para jugar con amigos, faltan pulir algunas cosas"
    },
    {
        "medio": "iVeRmA",
        "puntuacion": 100,
        "comentario": "Mucho rata de ponzoña"
    },
    {
        "medio": "swash",
        "puntuacion": 100,
        "comentario": "locuraa"
    },
    {
        "medio": "joeltebra",
        "puntuacion": 100,
        "comentario": "es god"
    },
    {
        "medio": "Campe",
        "puntuacion": 100,
        "comentario": "GRAN JUEGO, aca se define entre los que son grandes pintores y los que no ven nada y son cazadores"
    },
    {
        "medio": "Kujo03 (◕‿◕)",
        "puntuacion": 100,
        "comentario": "Un juego bastante entretenido y original. Me parece sublime que este tipo de mecánicas se implementen en juegos Indie. Una absoluta joya."
    },
    {
        "medio": "Salchipapa",
        "puntuacion": 100,
        "comentario": "goty"
    },
    {
        "medio": "LMNTRIX",
        "puntuacion": 100,
        "comentario": "Bueno para jugar con amigos,pero la optimizacion es pésima,ya que no todos en el grupo de amigos tiene una buena pc siempre hay uno con una pc papa pero fuera de eso es divertido"
    },
    {
        "medio": "adrianguallarcasasus",
        "puntuacion": 100,
        "comentario": "Muy divertido"
    },
    {
        "medio": "TheJhon1sS",
        "puntuacion": 100,
        "comentario": "la genialidad de la gente para esconderse es la hostia! jeje"
    },
    {
        "medio": "carlipey",
        "puntuacion": 100,
        "comentario": "good"
    },
    {
        "medio": "jmarquezd9",
        "puntuacion": 100,
        "comentario": "muy divertido"
    },
    {
        "medio": "LEAC2331",
        "puntuacion": 100,
        "comentario": "LOS CONTROLES SON DUROS"
    },
    {
        "medio": "mathy",
        "puntuacion": 0,
        "comentario": "ise crachea"
    },
    {
        "medio": "Xxp4ytonksxX",
        "puntuacion": 100,
        "comentario": "es muy bueno aun con mi laptop recomendado"
    },
    {
        "medio": "☭ Poleber",
        "puntuacion": 100,
        "comentario": "ta weno"
    },
    {
        "medio": "Dionmakx",
        "puntuacion": 100,
        "comentario": "very good"
    },
    {
        "medio": "Valyn",
        "puntuacion": 100,
        "comentario": "god"
    },
    {
        "medio": "Shinnosuke Nohara",
        "puntuacion": 100,
        "comentario": "Lo mejor del juego es cuando estás convencido de que hiciste el camuflaje perfecto y llevas como 3 minutos sin que nadie te encuentre... hasta que aparece un tipo, te mira medio segundo y te elimina como si tuviera rayos X. Es de esos juegos que siempre terminan con todos riéndose o echándole la culpa al mapa.♥♥3333"
    },
    {
        "medio": "tuupiin",
        "puntuacion": 100,
        "comentario": "muy muy muy buen juego no se por que la gente lo critica es muy divertido si lo juegas con tus amigos pasaras un buen rato"
    },
    {
        "medio": "LEON-TOILET-67",
        "puntuacion": 100,
        "comentario": "ESTA BUENO Y PESA 2 GIGABYTES"
    },
    {
        "medio": "EL_RUGBYER_VANN_27",
        "puntuacion": 100,
        "comentario": "es tremendo el juego"
    },
    {
        "medio": "YAKUZA",
        "puntuacion": 100,
        "comentario": "."
    },
    {
        "medio": "Elpachi29_Quilmes",
        "puntuacion": 100,
        "comentario": "esta buenisimo"
    },
    {
        "medio": "jokertoni1107",
        "puntuacion": 100,
        "comentario": "Es muy divertido"
    },
    {
        "medio": "👑 QueenDiana 👑",
        "puntuacion": 0,
        "comentario": "Sé que el juego para varios es bueno, pero esta es la última vez que me planteo conseguir un juego por el mero hecho de que es popular\n\nProp Hunt es un modo de juego que siempre me ha gustado muchísimo gracias a Garry's mod, pero como en este no había mucha gente jugando y hay otros juegos que son enteramente de este estilo pero nadie los juega, entonces fue como una lástima, ya que no encontraba donde jugar. Después salió esto, donde YouTube me recomendaba los vídeos y me entero del nombre, entonces lo compro, lo juego, me asqueo un poco y me voy\n\nMe pareció atractiva la mecánica de ser un monigote blanco y camuflarte pintándote la piel, pero la realidad es que el juego te agobia rápido. Te exige demasiada creatividad para decidir DÓNDE y CÓMO esconderte, así que al final, ver una silueta con brazos y piernas en una pared o un mueble es un Game Over asegurado porque resalta a la vista. Esos escondites perfectos donde nadie te encuentra parecen ideas que se te ocurren en un millón de años. Además, no puedes simplemente copiar los trucos de otros, porque aquí todo depende de tu habilidad con el pincel y el entorno. La clave está en lograr diseñar texturas complejas y \"romper\" tu silueta humana, algo que se vuelve muy difícil y estresante con la presión del cronómetro en contra\n\n[i]Mirá el tráiler y vas a notar cuan notorio es ser un monigote pintado sobre una superficie. Te cazo al instante[/i]\n\nPor último, el juego está muy mal optimizado gracias al Unreal Engine 5. He jugado fluidamente y con gráficos altos, títulos tales como Resident Evil 4 Remake, Devil May Cry 5, Dying Light 2, entre otros, pero sin embargo MECCHA CHAMELEON tiene caídas de FPS, se congela al cargar una partida y a veces me desconecta de los servidores. En principio pensé que era mi ordenador, hasta que leí más reseñas negativas y me enteré del motor gráfico que utiliza el juego\n\nEn fin... realmente prefiero volver a Garry's mod para jugar Prop Hunt. La compra fue mala y lo único que se podría corregir es el rendimiento, pero la muy alta habilidad que se te pide para jugar con otras personas, es estresante. Paso del juego, y de comprar títulos que se hacen de moda"
    },
    {
        "medio": "GuRuu",
        "puntuacion": 100,
        "comentario": "fun with friends"
    },
    {
        "medio": "JEFFREY DAHMER",
        "puntuacion": 100,
        "comentario": "me gusta pintar jajaj"
    },
    {
        "medio": "Laner",
        "puntuacion": 100,
        "comentario": "Es cutre pero es divertido con amigos"
    },
    {
        "medio": "ToCremoso",
        "puntuacion": 100,
        "comentario": "Pa pasalllla bien"
    },
    {
        "medio": "juanfran",
        "puntuacion": 100,
        "comentario": "está guapo"
    },
    {
        "medio": "lufeli07",
        "puntuacion": 0,
        "comentario": "no me deja cambiar a la posicion que yo quiero, selecciono una posicion y se pone la que quiere"
    },
    {
        "medio": "AaronchiFdez",
        "puntuacion": 100,
        "comentario": "10 de 10"
    },
    {
        "medio": "Toni pro",
        "puntuacion": 100,
        "comentario": "Un juego muy divertido que te hace sacar tus dotes artisticos para poder ganar. Lo de que se puedan descargar mapas tambien hace mas divertida la experiencia"
    },
    {
        "medio": "PiterPanda",
        "puntuacion": 0,
        "comentario": "Me lo baje por qué vi muchos videos divertidos y dije, este juego debe dar muchas risas! Pero la realidad es que no. Es el típico juego que es mas divertido verlo que jugarlo. La mecánica de pintar esta literalmente rota, el Angulo de cámara para mi gusto esta demasiado cerca, el sonido ambiental es malillo. Literalmente jugué 1h y vi que faltaba pulirlo mucho. Si esperabas un prophunt olvidate, no es ni de lejos tan divertido."
    },
    {
        "medio": "HeLLnWar",
        "puntuacion": 100,
        "comentario": "ess geniallllllll"
    },
    {
        "medio": "LA yorugua",
        "puntuacion": 100,
        "comentario": "ta copao, por los jajas... LIKE"
    },
    {
        "medio": "Lordsynth",
        "puntuacion": 100,
        "comentario": "Que risas de juego xD"
    },
    {
        "medio": "xo ツ",
        "puntuacion": 0,
        "comentario": "etsa bueno pero"
    },
    {
        "medio": "El Basoka",
        "puntuacion": 100,
        "comentario": "Excelente servicio"
    },
    {
        "medio": "istoleyourgastank002",
        "puntuacion": 100,
        "comentario": "ta bieeeeeeeeen chido"
    },
    {
        "medio": "Soy_Hombre",
        "puntuacion": 100,
        "comentario": "hifdhi dfhf wshfd dieb  b d"
    },
    {
        "medio": "Luatisha",
        "puntuacion": 100,
        "comentario": "me gustó"
    },
    {
        "medio": "10 | Zioshy ARG",
        "puntuacion": 100,
        "comentario": "Me gusta el juego y lo compre para saber que tan divertido es y si me llama la tencion con la ganas que tenia de jugar pero por el momento rechazo seguir jugando asta que el juego arregle los errores que algunas personas o la mayoria dicen mencionar algunas de ellas el cierra o crasheo o que pasa que a veces si no es la descarga de algun mod que puede ser imposible jugar BUGS Juegazo 8.6 ojala Un futuro el juego sea bueno y tenga Mas arreglos"
    },
    {
        "medio": "Cosuard",
        "puntuacion": 100,
        "comentario": "Muy divertido"
    },
    {
        "medio": "Jutta",
        "puntuacion": 100,
        "comentario": "se"
    },
    {
        "medio": "Cholitox",
        "puntuacion": 100,
        "comentario": "si"
    },
    {
        "medio": "Fꋪꋬꋊ✞ッ",
        "puntuacion": 100,
        "comentario": "es muy divertido lo reconmiendo mucho mas con jugar con amigos o jugar solo"
    },
    {
        "medio": "May Moon",
        "puntuacion": 100,
        "comentario": "Es divertido con amigos."
    },
    {
        "medio": "Sedi",
        "puntuacion": 100,
        "comentario": "ta chulo"
    },
    {
        "medio": "kick dieegoosg",
        "puntuacion": 100,
        "comentario": "god"
    },
    {
        "medio": "Mathyias",
        "puntuacion": 100,
        "comentario": "Si"
    },
    {
        "medio": "PamoZai",
        "puntuacion": 100,
        "comentario": "esta de pinga"
    }
]
```


## 2. `Analisis de la tabla para detectar si es AI `

| usuario_id | nombre_usuario | voto | horas_jugadas | review | indice_ia |
| --- | --- | --- | --- | --- | --- |
| 76561198791237314 | imperio romano occidente | No recomendado | 0.1333333333333333 | amigo si tu pc no tiene mas de 128 de ram no lo compres te va andar como la mierda | 5 |
| 76561197968703369 | PiterPanda | No recomendado | 0.9833333333333332 | Me lo baje por qué vi muchos videos divertidos y dije, este juego debe dar muchas risas! Pero la realidad es que no. Es el típico juego que es mas divertido verlo que jugarlo. La mecánica de pintar esta literalmente rota, el Angulo de cámara para mi gusto esta demasiado cerca, el sonido ambiental es malillo. Literalmente jugué 1h y vi que faltaba pulirlo mucho. Si esperabas un prophunt olvidate, no es ni de lejos tan divertido. | 5 |
| 76561199235865408 | antrusquireal901 | No recomendado | 0.6833333333333333 | juego mal creado cuando me meto me saca con un anuncio que dice as sido reportado y no deja jugar no lo descarguen es solo un mal gasto de dinero  | 5 |
| 76561198442321373 | reynolds | No recomendado | 0.2333333333333333 | juego mal optimizado, me anda mejor el poppy playtime que esto | 5 |
| 76561198864745072 | 👑 QueenDiana 👑 | No recomendado | 0.5833333333333334 | Sé que el juego para varios es bueno, pero esta es la última vez que me planteo conseguir un juego por el mero hecho de que es popular  Prop Hunt es un modo de juego que siempre me ha gustado muchísimo gracias a Garry's mod, pero como en este no había mucha gente jugando y hay otros juegos que son enteramente de este estilo pero nadie los juega, entonces fue como una lástima, ya que no encontraba donde jugar. Después salió esto, donde YouTube me recomendaba los vídeos y me entero del nombre, entonces lo compro, lo juego, me asqueo un poco y me voy  Me pareció atractiva la mecánica de ser un monigote blanco y camuflarte pintándote la piel, pero la realidad es que el juego te agobia rápido. Te exige demasiada creatividad para decidir DÓNDE y CÓMO esconderte, así que al final, ver una silueta con brazos y piernas en una pared o un mueble es un Game Over asegurado porque resalta a la vista. Esos escondites perfectos donde nadie te encuentra parecen ideas que se te ocurren en un millón de años. Además, no puedes simplemente copiar los trucos de otros, porque aquí todo depende de tu habilidad con el pincel y el entorno. La clave está en lograr diseñar texturas complejas y "romper" tu silueta humana, algo que se vuelve muy difícil y estresante con la presión del cronómetro en contra  [i]Mirá el tráiler y vas a notar cuan notorio es ser un monigote pintado sobre una superficie. Te cazo al instante[/i]  Por último, el juego está muy mal optimizado gracias al Unreal Engine 5. He jugado fluidamente y con gráficos altos, títulos tales como Resident Evil 4 Remake, Devil May Cry 5, Dying Light 2, entre otros, pero sin embargo MECCHA CHAMELEON tiene caídas de FPS, se congela al cargar una partida y a veces me desconecta de los servidores. En principio pensé que era mi ordenador, hasta que leí más reseñas negativas y me enteré del motor gráfico que utiliza el juego  En fin... realmente prefiero volver a Garry's mod para jugar Prop Hunt. La compra fue mala y lo único que se podría corregir es el rendimiento, pero la muy alta habilidad que se te pide para jugar con otras personas, es estresante. Paso del juego, y de comprar títulos que se hacen de moda | 5 |
| 76561199129152350 | "10  Zioshy ARG" | Recomendado | 2.1666666666666665 | Me gusta el juego y lo compre para saber que tan divertido es y si me llama la tencion con la ganas que tenia de jugar pero por el momento rechazo seguir jugando asta que el juego arregle los errores que algunas personas o la mayoria dicen mencionar algunas de ellas el cierra o crasheo o que pasa que a veces si no es la descarga de algun mod que puede ser imposible jugar BUGS Juegazo 8.6 ojala Un futuro el juego sea bueno y tenga Mas arreglos | 4 |
| 76561199833061048 | Toni pro | Recomendado | 3.866666666666666 | Un juego muy divertido que te hace sacar tus dotes artisticos para poder ganar. Lo de que se puedan descargar mapas tambien hace mas divertida la experiencia | 4 |
| 76561198047291558 | lufeli07 | No recomendado | 2.15 | no me deja cambiar a la posicion que yo quiero, selecciono una posicion y se pone la que quiere | 4 |
| 76561198902738700 | $LuK$ | Recomendado | 1.95 | Me parece un buen juego pero con el único problema que veo es que tengas que buscar un servidor muy precariamente y no solo poner en búsqueda | 4 |
| 76561199455323423 | tuupiin | Recomendado | 2.316666666666667 | muy muy muy buen juego no se por que la gente lo critica es muy divertido si lo juegas con tus amigos pasaras un buen rato | 4 |
| 76561198208211927 | Matiasasoc | Recomendado | 5.133333333333334 | muy buen juego tiene mods gratis variedad de mapas y colores muy bueno | 3 |
| 76561199112296536 | daviiidarroba | Recomendado | 5.183333333333334 | Juegazo con  o sin amigos te lo vas a pasar bien | 3 |
| 76561199811393394 | pepito | Recomendado | 6.383333333333334 | ete jugo trata de ke eres un monito y te pintaaas y te camuflaas y y todo esooo pe pero pero cuando llega teniente yy se laba las manitas con aguita y jabon pinpon y y deja ciego a un tipo y se keda cieguito y le da mucha risita y y y nadie le le saluda cuando llega a el server y se enoja con su comunidad por no imterabtuar con eyos  | 3 |
| 76561198889300779 | _k0jaku_ | No recomendado | 6.216666666666667 | Tiene que arreglar la búsqueda de servidores, no se puede buscar por nombre y las etiquetas son inútiles. El juego es divertido pero he estado más rato en total buscando el server que ha creado mi colega que jugando con el. Cambiaré la reseña a positiva cuando lo arreglen. | 3 |
| 76561198118938392 | TheJhon1sS | Recomendado | 4.1 | la genialidad de la gente para esconderse es la hostia! jeje  | 3 |
| 76561199610631755 | nan | Recomendado | 3.3 | Controles muy bien optimizados muchas opciones facil de entender idea original muy recomendable por el precio | 3 |
| 76561198405526415 | llucfabregat | Recomendado | 7.666666666666667 | Divertido para jugar con amigos pero hay algunos fallos y bugs | 3 |
| 76561199072496994 | nan | Recomendado | 8.9 | este juego es muy bueno para jugar con amigos y todos los que lo juegan es muy buen juego aunque algunas personas se dicen malas palabras jajaja | 3 |
| 76561199231682272 | glitzale2016 | Recomendado | 5.516666666666667 | es bueno pero se me queda trabado cuando entro | 3 |
| 76561198745660311 | luaydn | Recomendado | 10.15 | Es un juego muy entretenido para jugar con amigos, claro falta pulir las mecánicas del juego, pero por el precio lo vale todo. | 3 |
| 76561198383223394 | LMNTRIX | Recomendado | 7.716666666666667 | Bueno para jugar con amigos,pero la optimizacion es pésima,ya que no todos en el grupo de amigos tiene una buena pc siempre hay uno con una pc papa pero fuera de eso es divertido | 3 |
| 76561198239535094 | Boogie APZ | Recomendado | 6.016666666666667 | Un juego bastante divertido para estar con los amigos un rato | 3 |
| 76561198299706358 | |   M1G   | | Recomendado | 7.05 | Está muy bueno el juego, como recomendación, deberían habilitar una opción dentro del pontado, para cambiar el tipo de pincel, hacer cosas como lineas finas, difuminandos, facilitar deegradado, etc. | 3 |
| 76561199826373612 | Xxp4ytonksxX | Recomendado | 10.083333333333334 | es muy bueno aun con mi laptop recomendado | 3 |
| 76561198957792736 | Kujo03 (◕‿◕) | Recomendado | 4.766666666666667 | Un juego bastante entretenido y original. Me parece sublime que este tipo de mecánicas se implementen en juegos Indie. Una absoluta joya. | 3 |
| 76561199440194882 | K4os9 | Recomendado | 11.9 | Divertido para jugar con amigos, faltan pulir algunas cosas | 3 |
| 76561199848866800 | Fꋪꋬꋊ✞ッ | Recomendado | 3.883333333333333 | es muy divertido lo reconmiendo mucho mas con jugar con amigos o jugar solo | 3 |
| 76561198868555719 | ñom | Recomendado | 0.6166666666666667 | semen | 3 |
| 76561198104365867 | Lordsynth | Recomendado | 0.1833333333333333 | Que risas de juego xD | 3 |
| 76561198067678830 | Cosuard | Recomendado | 1.6 | Muy divertido | 2 |
| 76561199789516036 | LEAC2331 | Recomendado | 2.083333333333333 | LOS CONTROLES SON DUROS | 2 |
| 76561199217469348 | xo ツ | No recomendado | 1.6833333333333331 | etsa bueno pero | 2 |
| 76561198695581028 | istoleyourgastank002 | Recomendado | 2.3666666666666667 | ta bieeeeeeeeen chido | 2 |
| 76561199441433805 | tzyumiiwnl | Recomendado | 2.2 | AURA  | 2 |
| 76561199589048454 | ☠Nicolas☠ | Recomendado | 1.65 | siu xd | 2 |
| 76561198399183668 | Campe | Recomendado | 30.33333333333333 | GRAN JUEGO, aca se define entre los que son grandes pintores y los que no ven nada y son cazadores | 1 |
| 76561199135976030 | ferbon | No recomendado | 6.033333333333333 | muchos bugs en esta actualizacion | 1 |
| 76561199112646103 | Richard Waterson | Recomendado | 3.4166666666666665 | juegazo | 1 |
| 76561198402195986 | Ryno | Recomendado | 11.083333333333334 | si | 1 |
| 76561199075556486 | Minitheboss23 | Recomendado | 8.9 | todo   | 1 |
| 76561199860786390 | nan | Recomendado | 3.733333333333333 | juego muy copado y ademas con los mapas especiales se vuelve un jugo muy divertido (pero nescesitas saber pintar para sobrevivir)  | 1 |
| 76561198712194416 | nan | Recomendado | 10.766666666666667 | 67 | 1 |
| 76561198242753514 | mendezariel | Recomendado | 5.3 | b  | 1 |
| 76561198687069562 | nan | Recomendado | 5.083333333333333 | es la cabra  | 1 |
| 76561198921164361 | tincho536 | Recomendado | 5.066666666666666 | nasheardobuenardopolis  | 1 |
| 76561199107553730 | salvadormurcho | Recomendado | 3.816666666666667 | muy bueno | 1 |
| 76561199205712307 | Jefry | Recomendado | 3.283333333333333 | bien | 1 |
| 76561199783549242 | ricardoarqui5 | Recomendado | 6.7 | MARAVILLOSO   | 1 |
| 76561199060665318 | nan | Recomendado | 3.8333333333333335 | si | 1 |
| 76561198736290592 | AngelSG0123 | Recomendado | 7.916666666666667 | es muy chhulooo  | 1 |
| 76561199234991124 | s-gatito | Recomendado | 5.983333333333333 | no se :3 | 1 |
| 76561198762071010 | pedritus_blanco | Recomendado | 4.416666666666667 | juegazo | 1 |
| 76561198771519322 | nan | Recomendado | 3.966666666666667 | esta muy muy muy chulo | 1 |
| 76561198287692620 | danielpower42 | Recomendado | 3.033333333333333 | Juego para GENIOOOS!!!! del escondite | 1 |
| 76561198760369798 | BNG*******er | Recomendado | 5.95 | Mola | 1 |
| 76561198681707237 | nan | Recomendado | 7.033333333333333 | es god  | 1 |
| 76561199084363138 | Gamechip | Recomendado | 4.45 | muy bueno | 1 |
| 76561199445620686 | carlipey | Recomendado | 5.35 | good | 1 |
| 76561198762732889 | swash | Recomendado | 4.716666666666667 | locuraa | 1 |
| 76561198353189880 | iVeRmA | Recomendado | 4.066666666666666 | Mucho rata de ponzoña | 1 |
| 76561199387620525 | Salchipapa | Recomendado | 6.166666666666667 | goty | 1 |
| 76561198686242653 | nan | Recomendado | 6.566666666666666 | Muy divertido | 1 |
| 76561199239872640 | Fronta | Recomendado | 6.616666666666666 | 67 | 1 |
| 76561198179259754 | jmarquezd9 | Recomendado | 5.766666666666667 | muy divertido | 1 |
| 76561199636362975 | AlvaroRUE | Recomendado | 4.133333333333334 | . | 1 |
| 76561198355781331 | Derrygan | Recomendado | 7.733333333333333 | *Se camufla* fiu fiu | 1 |
| 76561199105744059 | zvzvzvz | Recomendado | 12.65 | bkn | 1 |
| 76561199138659510 | m0NESY | Recomendado | 5.633333333333334 | buenjuego  | 1 |
| 76561198788508396 | tiopaco_0 | Recomendado | 7.133333333333334 | divertido | 1 |
| 76561198757172768 | Yireh Seashell | Recomendado | 5.85 | libertad creativa a mil | 1 |
| 76561198742276078 | OH\ | Recomendado | 4.166666666666667 | muy bueno | 1 |
| 76561198253585634 | Nitsu | Recomendado | 6.05 | nice | 1 |
| 76561198709520695 | LEON-TOILET-67 | Recomendado | 6.866666666666666 | ESTA BUENO Y PESA 2 GIGABYTES  | 1 |
| 76561198343639313 | Shinnosuke Nohara | Recomendado | 3.316666666666667 | Lo mejor del juego es cuando estás convencido de que hiciste el camuflaje perfecto y llevas como 3 minutos sin que nadie te encuentre... hasta que aparece un tipo, te mira medio segundo y te elimina como si tuviera rayos X. Es de esos juegos que siempre terminan con todos riéndose o echándole la culpa al mapa.♥♥3333 | 1 |
| 76561198888903993 | Valyn | Recomendado | 7.516666666666667 | god | 1 |
| 76561198787969301 | Dionmakx | Recomendado | 4.066666666666666 | very good | 1 |
| 76561199234447708 | Laner | Recomendado | 3.966666666666667 | Es cutre pero es divertido con amigos | 1 |
| 76561198772398519 | JEFFREY DAHMER | Recomendado | 4.85 | me gusta pintar jajaj | 1 |
| 76561199345511250 | GuRuu | Recomendado | 3.0166666666666666 | fun with friends | 1 |
| 76561198000932738 | ToCremoso | Recomendado | 5.116666666666666 | Pa pasalllla bien | 1 |
| 76561199248248723 | mathy | No recomendado | 4.75 | ise crachea | 1 |
| 76561199385927333 | ☭ Poleber | Recomendado | 15.483333333333333 | ta weno  | 1 |
| 76561199177423551 | nan | Recomendado | 13.066666666666666 | Es muy divertido | 1 |
| 76561198683805654 | EL_RUGBYER_VANN_27 | Recomendado | 6.85 | es tremendo el juego  | 1 |
| 76561199481995316 | YAKUZA | Recomendado | 7.633333333333334 | . | 1 |
| 76561199764303852 | Elpachi29_Quilmes | Recomendado | 4.7 | esta buenisimo | 1 |
| 76561198860339323 | juanfran | Recomendado | 3.55 | está guapo | 1 |
| 76561198937456709 | AaronchiFdez | Recomendado | 17.183333333333334 | 10 de 10  | 1 |
| 76561198094211987 | nan | Recomendado | 13.433333333333334 | Excelente servicio | 1 |
| 76561197994194759 | HeLLnWar | Recomendado | 8.716666666666667 | ess geniallllllll | 1 |
| 76561198684950624 | Soy_Hombre | Recomendado | 11.383333333333333 | hifdhi dfhf wshfd dieb  b d | 1 |
| 76561199022401071 | LA yorugua | Recomendado | 9.083333333333334 | ta copao, por los jajas... LIKE | 1 |
| 76561199319307021 | Luatisha | Recomendado | 11.716666666666669 | me gustó  | 1 |
| 76561198089859358 | Jutta | Recomendado | 3.066666666666667 | se | 1 |
| 76561198415390096 | Cholitox | Recomendado | 4.416666666666667 | si | 1 |
| 76561199080581526 | May Moon | Recomendado | 5.1 | Es divertido con amigos. | 1 |
| 76561199653293459 | Sedi | Recomendado | 12.45 | ta chulo | 1 |
| 76561199548139643 | kick dieegoosg | Recomendado | 4.233333333333333 | god | 1 |
| 76561198172321051 | Mathyias | Recomendado | 5.583333333333333 | Si | 1 |
| 76561199849156785 | PamoZai | Recomendado | 15.083333333333334 | esta de pinga | 1 |
