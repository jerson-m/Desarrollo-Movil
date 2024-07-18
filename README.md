Tipos de variables en kotlin:
 String , Int , Double , Float, y Boolean

CONSTANTES EN KOTLIN
en Kotlin se usan val para declarar variables inmutables que actúan como constantes y
companion object o enum class para agrupar constantes relacionadas. La palabra clave const
se usa dentro de companion object para definir constantes que son evaluadas en tiempo de compilación.

OPCIONES EN KOTLIN
Opciones como configuraciones o ajustes
Opciones en términos de selección o elección

MANEJO DE NULOS
Safe calls (Llamadas seguras): Se utilizan para llamar a un método o propiedad de un objeto que puede ser nulo. Si el objeto es nulo, la llamada se ignora y se devuelve un valor nulo.
Elvis operator (Operador Elvis): Se utiliza para proporcionar un valor predeterminado si el objeto es nulo.
Null checks (Verificaciones de nulos): Se utilizan para verificar si un objeto es nulo antes de acceder a sus propiedades o métodos.
Let (Let): Se utiliza para ejecutar un bloque de código solo si el objeto no es nulo.
