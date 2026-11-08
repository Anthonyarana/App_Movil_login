# HolaMundo_IS2026_2

Tiene una pantalla principal y una pantalla de **Inicio de Sesión**. Las dos pantallas usan `ConstraintLayout` y componentes de Material Design.

<p align="center">
  <img src="capturas/pantalla_principal.png" width="280" alt="Pantalla principal">
  &nbsp;&nbsp;&nbsp;
  <img src="capturas/inicio_sesion.png" width="280" alt="Pantalla de Inicio Sesión">
</p>

## Características

### Pantalla principal (`MainActivity`)

- **Universidad:** imagen `universidad` en la parte superior.
- **Facultad:** imagen `facultad` debajo de la imagen de la universidad.
- **Botón Iniciar Sesión:** `MaterialButton` verde que abre la pantalla de inicio de sesión.

### Pantalla de Inicio Sesión (`inicioseccion`)

La interfaz usa componentes de Material Design (`TextInputLayout` con estilo *OutlinedBox*) e incluye:

- **Universidad:** encabezado con la imagen `universidad`.
- **Título:** texto "Inicio Sesión" en verde y negrita.
- **Correo electrónico:** campo de texto de tipo `textEmailAddress` con un ícono de sobre.
- **Contraseña:** campo de tipo `textPassword` con un ícono de candado y un botón para mostrar u ocultar la contraseña.
- **Botón Entrar:** `MaterialButton` verde con bordes redondeados.

## Detalles técnicos

- **Lenguaje:** Java.
- **Diseño de interfaz:** hecho en XML (`activity_main.xml` y `activity_inicioseccion.xml`).
- **Layout principal:** `ConstraintLayout` para ubicar los elementos unos respecto de otros.
- **Navegación:** un `Intent` abre la pantalla de inicio de sesión desde la pantalla principal.
- **Diseño de borde a borde:** `EdgeToEdge.enable(this)` con márgenes que se ajustan a las barras del sistema.
- **SDK:** `minSdk 24`, `targetSdk 37`.
