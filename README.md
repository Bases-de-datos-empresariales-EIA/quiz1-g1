# Gestión de Eventos y Conferencias

## Contexto del Negocio

Una empresa que organiza eventos y conferencias necesita un sistema para gestionar sus eventos, asistentes, ponentes, y las sesiones que componen cada evento. El objetivo es llevar un registro claro de los asistentes y ponentes, así como de las diferentes sesiones de cada evento.

## Descripción de los Elementos del Negocio

1. **Evento**:
   - **Descripción**: Los eventos o conferencias organizadas por la empresa.
   - **Atributos Clave**: Nombre del evento, fecha, sesiones.

2. **Asistente**:
   - **Descripción**: Las personas que asisten a los eventos.
   - **Atributos Clave**: Nombre del asistente, correo electrónico, eventos a los que asisten.

3. **Ponente**:
   - **Descripción**: Los ponentes que dan charlas en los eventos.
   - **Atributos Clave**: Nombre del ponente, identificación, sesiones en las que participa.

4. **Sesión**:
   - **Descripción**: Las sesiones son segmentos individuales dentro de un evento. Cada sesión se enfoca en un tema específico y puede incluir charlas, talleres, paneles de discusión, entre otros formatos. Una sesión tiene un horario definido y es impartida por un único ponente.
   - **Atributos Clave**: Título de la sesión, horario, evento asociado, ponente.

5. **Inscripción**:
   - **Descripción**: Los registros de inscripción de los asistentes a los eventos.
   - **Atributos Clave**: Fecha de inscripción, asistente asociado, evento asociado.

## Instruciones
- Construya en Figma o a mano el diagrama Entidad-Relación del negocio descrito anteriormente siguiendo el estándar explicado en clase (70%).
- Justifique la elección de cada tipo de relación (one-to-one, one-to-many, many-to-many) (10%).
- Justifique por qué cada tabla es transaccional o maestra (20%).
- Recuerde el estándar de construcción del diagrama E-R:
    - Entidades: PascalCase.
    - Campos: camelCase.
    - Cada relación `one` debe ser denotada en la fuente con un singular. Además, debe llevar un círculo en el destino.
    - Cada relación `many`  debe ser denotada en la fuente con un plural. Además, debe llevar un triángulo en el destino.
    - Cada entidad maestra es de color verde. Si el diagrama es dibujado a mano, el estudiante debe especificar que la entidad es de tipo maestra.
    - Cada entidad transaccional es de color púrpura. Si el diagrama es dibujado a mano, el estudiante debe especificar que la entidad es de tipo transaccional.

# Entrega
Enviar el diagrama Entidad-Relación y las justificaciones a `daniel.saldarriaga@eia.edu.co`.
