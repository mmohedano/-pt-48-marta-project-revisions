# CLEAN CODE

El término clean code se atribuye al ingeniero de software **Robert Cecil Martin**, que lo utilizó en su libro *Clean Code: Refactoring, Patterns, Testing and Techniques for Clean Code* para referirse al código limpio.

Se trata de una serie de principios que ayudan a producir código intuitivo y fácil de modificar. En este contexto, intuitivo significa que cualquier desarrollador profesional pueda entenderlo de inmediato.

Entre las reglas y principios que se detallan en el libro destacaremos las siguientes:

**•	DRY PRINCIPLE**

Son la siglas de Don´t Repeat Yourself. Hay que evitar el código duplicado ya que es difícil de entender y mantener.
Generará posibles inconsistencias.
Debemos optar por la refactorización y la abstracción para conseguir alinearnos con este principio.
Lo contrario sería WET (We enjoy tiyping), lo que se resume en escribir código no necesario.

**•	THE PRINCIPLE OF LEAST SURPRISE** 

También llamado principle of least astonishment. 
Las funciones y clases deben hacer lo que se espera de ellas. En función de su nombre deben tener un comportamiento obvio.

**•	THE BOY SCOUT RULE**

HAce referencia a una de las reglas de los scouts “Deja el campamento más limpio de como te lo encontraste” que, aplicado al código sería “Deja las cosas mejor de como te las encontraste”.
En caso de encontrarnos nombres de variables confusos o erróneos, funciones duplicadas, etc., se deben corregir en vez de mirar para otro lado.

**•	SINGLE RESPONSIBILITY PRINCIPLE**

Esto aplica al diseño de clases, cada una de ellas debe tener una única responsabilidad.

**•	OPEN CLOSED PRINCIPLE**

Una clase debe estar abierta a extensiones pero cerrada a modificaciones.

**•	KISS**

Acrónimo de Keep It Simple Stupid. Lo que nos viene a decir es que el código debe ser lo más sencillo posible.

**•	YAGNI**

O You Aren´t Gonna Need It. Solo se deben añadir funciones al código cuando sea estrictamente necesario. 
El desarrollo paso a paso permite poder reaccionar a cada problema de una forma dinámica.

**•	LEGIBLE ANTES QUE CONCISO**

El código debe ser comprensible para otros desarrolladores. Los nombres de las variables y funciones siempre deben ser comprensibles.

**•	COMENTAR SOLO LO NECESARIO**

Se dice que “los comentarios mienten”. Esto se refiere a que cuando modificamos el código, a menudo los comentarios no se modifican por lo que tendremos unos comentarios que no se corresponden con las últimas versiones del código.

**•	FIRST**

En lo referente a los tests, estos deben de cumplir una serie de reglas que se engloban dentro del acrónimo FIRST:
-	FAST: Rapidez en la ejecución. Esto ayudará a que no nos dé pereza a ejecutarlos con frecuencia y por lo tanto tardemos menos en encontrar posibles complicaciones.
-	INDEPENDENT: Deben ser independientes unos de otros. El resultado de un test no debe condicionar el de los siguientes.
-	REPEATABLE: Deben poder ejecutarse en cualquier entorno, esto es desarrollo, pre producción, producción, etc.,
-	SELF -VALIDATING: Deben devolver una respuesta booleana. Pasan o no pasan.
-	TIMELY: Deben ser escritos antes que el código de producción.

Estos son algunos de las reglas y principios que recoge el libro, en el siguiente enlace se puede acceder a una guía con ejemplos y explicaciones más extensas.

[GUÍA](https://www.adictosaltrabajo.com/wp-content/uploads/2020/03/CLEAN-CODE.pdf)
