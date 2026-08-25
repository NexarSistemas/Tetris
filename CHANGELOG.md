# Changelog

Todos los cambios relevantes de Tetris Deluxe se documentan en este archivo.

El proyecto sigue [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0] - 2026-08-24

### Added

- Música de fondo 8-bit original generada con Web Audio API durante la partida activa, sin dependencias ni archivos externos.
- Botón independiente de Música en la sección `Juego`, con persistencia local de la preferencia.

### Changed

- La música se pausa al pausar la partida, al ocultar la pestaña y en game over, y se reanuda al continuar si sigue habilitada.
- La configuración musical permanece fuera del guardado de partida y es independiente de los efectos de sonido.

## [0.3.0] - 2026-08-24

### Added

- Opción para mostrar u ocultar la sombra de caída desde la sección `Juego`.

### Changed

- La preferencia de la sombra de caída se guarda localmente en forma independiente de la partida.
- La sombra de caída permanece activada por defecto cuando no existe preferencia previa o el valor guardado es inválido.

## [0.2.2] - 2026-08-24

### Changed

- Mejora del layout responsive para mantener el juego completo en escritorio cuando hay espacio suficiente.
- Fallback con scroll vertical seguro en pantallas de poca altura para evitar contenido o controles cortados.
- Mejor compatibilidad con tablets y anchos intermedios, sin cambios en la lógica ni funcionalidades del juego.

## [0.2.1] - 2026-08-23

### Added

- Promociones internas y discretas de productos Nexar en estados no activos del juego.
- Nexar Sistemas en la pantalla inicial y al recuperar una partida.
- Nexar Comercio en pausa.
- Nexar Finanzas en game over.
- CTA `Conocer más →` hacia el sitio oficial de Nexar Sistemas.

### Changed

- Adaptación visual de Tetris a la identidad Nexar Play.
- Actualización de la interfaz principal, controles, temas y footer sin modificar la lógica del juego.
- La pausa reutiliza ahora el overlay principal para mantener una experiencia visual consistente.
- Las promociones permanecen fuera de la partida activa para no interferir con la jugabilidad.

## [0.2.0] - 2026-07-31

### Added

- Soporte optimizado para escritorio y dispositivos móviles.
- Controles táctiles.
- Vista de próxima pieza.
- Sistema HOLD para guardar piezas.
- Sistema de puntuación, récord, líneas, niveles y combos.
- Modos de dificultad: fácil, medio y difícil.
- Temas visuales Cyber, Retro y Ocean.
- Modo contrarreloj.
- Efectos de sonido opcionales.
- Guardado y recuperación automática de partidas mediante almacenamiento local.
- Sistema de logros.
- Soporte para áreas seguras en dispositivos móviles.
- Compatibilidad con orientación horizontal y vertical.
- Publicación como sitio independiente mediante GitHub Pages.

### Changed

- Rediseño completo de la interfaz.
- Mejora del layout responsive.
- Optimización del tamaño del tablero según pantalla y orientación.
- Mejora de controles de teclado y táctiles.
- Mejora de overlays de inicio, pausa y game over.
- Adaptación del proyecto para ejecutarse directamente desde `index.html`.
- Migración del proyecto al ecosistema oficial de Nexar Sistemas.

## [0.1.1] - 2024-05-22

### Changed

- Actualización de mantenimiento y correcciones menores.
- Incremento de versión para reflejar mejoras de estabilidad.

## [0.1.0] - 2024-05-20

### Added

- Estructura inicial del proyecto.
- Lógica básica de Tetris.
- Movimiento y rotación de piezas.
- Detección de colisiones.
- Eliminación de líneas.
- Sistema básico de puntuación.
