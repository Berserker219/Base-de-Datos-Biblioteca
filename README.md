# Sistema-Gestion-Biblioteca

Entidades: Libros, Autores, Usuarios, Préstamos, Categorías.
# Reglas de Negocio:
- Un libro puede tener múltiples autores.
- Un usuario puede prestar hasta 5 libros a la vez.
- Los libros deben devolverse en un plazo de 15 días.
- Los usuarios tienen un límite de 2 renovaciones por libro.
- Las categorías pueden ser jerárquicas (una categoría puede tener subcategorías).

# Entidades:
- Usuarios
- Libros
- Autores
- Categorías
- Préstamos
- Reservas
- Historial de Préstamos
- Multas
- Editoriales
- Ejemplares
- Sedes (si la biblioteca tiene varias ubicaciones)
- Personal (para gestionar los empleados de la biblioteca)

# Reglas de Negocio:

# Usuarios:
Cada usuario puede tener un máximo de 5 libros prestados al mismo tiempo.
Los usuarios deben devolver los libros en un plazo de 15 días, con la posibilidad de una renovación por libro.
Los usuarios que no devuelvan los libros a tiempo serán sancionados con una multa diaria.

# Libros:
Un libro puede estar asociado con múltiples autores y categorías.
Cada libro puede tener múltiples ejemplares distribuidos en diferentes sedes.
Los libros deben estar registrados con su editorial correspondiente.

# Autores:
Un autor puede estar relacionado con múltiples libros.
Los autores pueden tener seudónimos, y estos también deben ser registrados.

# Categorías:
Las categorías pueden ser jerárquicas, permitiendo la creación de subcategorías.
Un libro puede pertenecer a múltiples categorías simultáneamente.

# Préstamos:
Un préstamo se asocia a un usuario y a uno o más ejemplares de libros.
Los préstamos deben registrar la fecha de inicio y la fecha de devolución.
No se permite realizar un nuevo préstamo si el usuario tiene multas pendientes.

# Reservas:
Los usuarios pueden reservar libros que no estén disponibles.
Las reservas tienen una validez de 3 días después de que el libro esté disponible.
Solo se puede reservar un ejemplar de un libro por usuario.

# Historial de Préstamos:
Todos los préstamos y devoluciones deben ser registrados en un historial.
El historial debe incluir las fechas de préstamo y devolución, así como cualquier multa aplicada.

# Multas:
Las multas se calculan en función de los días de retraso en la devolución de libros.
Las multas deben ser pagadas antes de permitir nuevos préstamos o reservas.

# Editoriales:
Cada libro debe estar asociado con una editorial.
Las editoriales pueden estar relacionadas con múltiples libros.

# Ejemplares:
Cada libro puede tener múltiples ejemplares, identificados por un número único de ejemplar.
Los ejemplares pueden estar distribuidos en diferentes sedes de la biblioteca.

# Sedes:
Si la biblioteca tiene varias sedes, cada sede debe gestionar su inventario de ejemplares.
Los usuarios pueden realizar préstamos y devoluciones en cualquier sede.

# Personal:
El personal de la biblioteca puede gestionar préstamos, devoluciones, multas, y el inventario de libros.
Se deben registrar las acciones del personal para fines de auditoría.

