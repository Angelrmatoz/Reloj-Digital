# Reloj Digital

Este proyecto implementa un reloj digital simple utilizando HTML, CSS y JavaScript. El reloj muestra la hora actual (horas, minutos, segundos) y la fecha (día de la semana, día, mes, año) y presenta una sutil animación en cada actualización de segundo.

## Funcionalidad

El reloj se actualiza cada segundo para reflejar la hora actual. La hora y la fecha se formatean para una lectura clara. Se aplica una pequeña animación al contenedor del reloj en cada tic.

## Tecnologías Utilizadas

* **HTML:** Proporciona la estructura básica para mostrar el reloj.
* **CSS:** Estiliza la apariencia del reloj, incluyendo fuentes, colores y diseño. También maneja el efecto de animación.
* **JavaScript:** Implementa la lógica del reloj, incluyendo la obtención de la hora actual, su formateo y la actualización de la pantalla. La función `setInterval` asegura que el reloj se actualice cada segundo.

## Características Principales

* **Actualizaciones en Tiempo Real:** El reloj se actualiza cada segundo para mostrar la hora actual precisa.
* **Formato de Pantalla Claro:** La hora y la fecha se muestran en un formato claro y fácil de leer.
* **Animación Sutil:** Una sutil animación proporciona retroalimentación visual en cada actualización de segundo.

## Cómo Ejecutar

Simplemente abre el archivo `index.html` en tu navegador web para ver el reloj en funcionamiento.

## Explicación del Código

El código JavaScript utiliza el objeto incorporado `Date` para obtener la hora actual.  Las funciones auxiliares formatean los componentes de tiempo y fecha (por ejemplo, agregando ceros a la izquierda para horas, minutos y segundos de un solo dígito). La función `setInterval` llama a la función `mostrarReloj` cada 1000 milisegundos (1 segundo) para actualizar la hora mostrada y activar la animación. El CSS maneja el estilo y la animación del reloj.

Este proyecto sirve como un ejemplo básico de cómo construir un reloj digital utilizando tecnologías web.
