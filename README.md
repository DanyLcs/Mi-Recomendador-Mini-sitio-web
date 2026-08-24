# Laboratorio: Mini-sitio-web-con-apoyo-de-IA
# Objetivo: Construir un sitio web sencillo utilizando HTML, CSS, Bootstrap y JavaScript, utilizando una herramienta de Inteligencia Artificial como apoyo durante el proceso.

1. Nombre del proyecto: 
BIBOU: La France t'attend

2. Descripción: 
    * ¿Qué voy a recomedar? Lugares turísticos atípicos para visitar en Francia.
    * ¿A quién va dirigida la página? Para las personas que les gusta viajar y conocer nuevos lugares.
    * ¿Qué información tendrá cada recomendación? El nombre del lugar, una pequeña descripción sobre él y un enlace para conocer más sobre el lugar y las actividades que se pueden hacer.
    * ¿Qué quiero que suceda cuando el usuario interactué con mi página? Quiero que se lleva una experiencia agradable y sobretodo que se pueda informar sobre que lugares puede visitar durante su viaje a Francia, quiero que el sitio les sirva de inspiración para ir a descubrir nuevos lugares distintos y diferentes a los lugares populares que ya se conocen por películas o series. 
    * ¿Qué hace mi recomendador? Dar recomendaciones de lugares poco comunes de Francia para visitar. 

3. Tecnologías:
    * HTML
    * CSS
    * Bootstrap
    * JavaScript
    * Git
    * GitHub
    * IA utilizada

4. Proceso con IA: 
    a. Planificar página: 
        * ¿Qué necesitaba?: Planificar página.
        * Prompt: Actúa como tutor de desarrollo web para principiantes. Estoy creando un sitio web llamado "BIBOU: La France t'attend" utilizando HTML, CSS, Bootstrap y variables básicas de JavaScript. Mi tema es lugares turísticos para visitar en Francia. Ya conozco HTML, CSS, Bootstrap y variables en JavaScript, pero todavía no conozco funciones, ciclos ni manipulación del DOM. Ayúdame a dividir el proyecto en pasos pequeños. No generes todo el código del proyecto.
        * ¿Qué respondio?: Me hizo una ruta dividida en pasos pequeños y manejables, también me dio ideas de los componentes que podría agregar al HTML, así como detalles en los que me tenía que fijar como la parte de las columnas para que la página tuviera responsive. 
        * ¿Qué utilice?: De lo que me recomendo para el HTML use el container solamente, del CSS no use nada y la parte de JavaScript tampoco use nada al principio. 
        * ¿Qué aprendí?: Aprendí a usar el container, creció mi conocimiento sobre la navbar (cambiar el fondo) y las cards (cambiar el fondo, ajustar el tamaño y centrarlas) y la propiedad style. 

    b. HTML y Bootstrap: 
        * ¿Qué necesitaba?: Cambiar el color de fondo de la navbar, las cards y el grid.
        * Prompt: Si quiero cambiarle el color a las cards, pero de que quiero que cada tarjeta tenga un color distinto, lo hago con una class?
        * ¿Qué respondio?: Opción A: Usar la propiedad style directamente en el HTML. Es la forma más rápida y directa de sobreescribir cualquier color de Bootstrap sin fallar.
        * ¿Qué utilice?: Solo use la propiedad style en todos los componentes que quería de un color distinto al que Bootstrap me proponia y los colores los decidó yo. 
        * ¿Qué aprendí?: Que la propiedas style es TOP porque de esa forma muchísimo más sencillo cambiarle el color a los componentes sin necesidad de usar una clase y que pueda no funcionar. Es super útil, me encanto y como se puede ver en mi código lo use en todos lados. 

    c. CSS: 
        * ¿Qué necesitaba?: Cambiar el tamaño del container.
        * Prompt: Tengo este código para el conteiner y esto en la página, el asunto es que quiero que la imagen cubra la parte blanca de arriba y todo lo largo que falta y que lo que se ve de slogan y eso se vea en la imagen, me podrías decir en que tendría que fijarme antes de darme el código
        * ¿Qué respondio?: Me felicito, me dio opciones que podrían ayudarme y posteriormente me ayudo a generar el código de CSS para poder lograr mi objetivo
        * ¿Qué utilice?: Utilicé solo la parte que genero en la cuál venía el código para adecuar el tamaño del container.
        * ¿Qué aprendí?: Como cambiar el tamaño del container. 

    d. JavaScript: 
        * ¿Qué necesitaba?: Agregar JS a mi proyecto.
        * Prompt: Para la parte de javascript debo agregar algunas variables, pero no sé cuáles podría agregar. 
        * ¿Qué respondio?: Me dió la idea de añadir las variables que se ven en el sitio web.
        * ¿Qué utilice?: Solo use las ideas que me dio de variables y solo las que considere relevantes. 
        * ¿Qué aprendí?: Aprendí a tener cuidado con el orden en el cual pongo las variables, el alert y los const.log porque hubo un momento en el que se repetía todo o no se ejecutaban y ahí andaba acomodando todo porque no salía como yo quería. 
    
5. Código generado vs Código propio: 
    a. Esa parte de código (como se ve en los comentarios) cambia el color de la navbar por uno distinto al que se propone en Bootstrap y se mantienen las letras en un tono claro, lo utilizo para darle un aspecto más personalizado y acordé a la paleta de colores que decidí utilizar. La parte de navbar-dark viene explicada en la documentación de Bootstrap y la parte de style si me lo genero la IA ya que yo intenté hacerlo utilizando la clase, pero no me funcionaba y lo forcé, pero después la IA me dijo que podía utilizar lo propiedad style para hacerlo de una forma más sencilla y lo que modifiqué o agregué fue el color. 

    b. Este segundo fragmento cambia el tamaño de las tarjetas, las centra y cambia fondo de cada una. Lo utilizo para que la página se vea más estética con colores y todo centrado. Este fragmento lo generé yo con ayuda de la documentación de Bootstrap y usando la propiedad que me dio anteriormente la IA para el fondo. Lo que modifiqué fue el tamaño y el color. 

    c. El último fragmento me ayuda a poner el grid del tamaño de la página y que no haya ningún espacio blanco a los lados. Se utilizo para que no se viera un espacio blanco a los lados en el footer y mejorará el aspecto de la página. Para este fragmento fue mitad documentación de Bootstrap, mitad IA, ya que en la documentación viene el componente de container-fluid, pero no decía la función como tal solo se mencionaba así que le pregunté a la IA. Finalmente, lo único que hice fue agregar la palabra fluid al código y listo. 