# pad.github.io

# Pad Training

Tracker personal de entrenamiento de fútbol, entregado como **un solo archivo HTML autocontenido** — sin build, sin frameworks, sin dependencias externas ni conexión a internet. Pensado para usarse como PWA en iPhone/Safari, añadido a la pantalla de inicio.

## Uso rápido

1. Abre **`pad-training-v2.8.html`** (la versión vigente) en Safari, en el iPhone.
2. Toca **Compartir → Añadir a pantalla de inicio**. A partir de ahí funciona como una app normal, sin barra de Safari, con su propio icono.
3. Todos los datos se guardan localmente en el propio teléfono (`localStorage`). No hay servidor, no hay cuenta, no hay sincronización entre dispositivos.

No requiere instalar nada, ni Node, ni npm, ni ningún paso de compilación: es HTML/CSS/JS plano que corre directo en el navegador.

## Qué hace

- **Programas de entrenamiento**: soporta varios programas en paralelo (hasta 10), cada uno con sus propios días, bloques y ejercicios. Se puede crear un programa desde cero, duplicar uno existente, renombrarlo o borrarlo. El programa activo se puede cambiar en cualquier momento sin perder el histórico de los demás.
- **Registro de sesión**: cada ejercicio se registra según su tipo (carga, peso corporal, isométrico, distancia, pliométrico, sprint, técnica o solo casilla), con series añadibles/borrables, entrada uni o bilateral (izquierda/derecha, con cálculo de asimetría), y RPE por ejercicio.
- **Señal de carga**: un check-in previo a la sesión (sueño, dolor, energía, etc.) calcula una señal (verde/ámbar/rojo) con avisos concretos, incluyendo tres condiciones de lesión específicas que se muestran siempre que aplican (hernia umbilical operada, dolor de aductor, fascia plantar).
- **Progreso**: anillo semanal de sesiones completadas, histórico filtrable por programa.
- **Métricas propias**: el usuario puede crear sus propias métricas (nombre, unidad, cadencia de medición), renombrarlas, reordenarlas y verlas en una cuadrícula compacta de 3 columnas en la pantalla de Hoy.
- **Expectations**: módulo de tests físicos (peso, 1RM, Cooper, CMJ, squat jump, salto de longitud, sprint, etc.) con objetivos, retest y cálculos derivados (IMC, potencia, asimetría, velocidad máxima...).
- **Ajustes**: nombre del usuario, idioma, color de acento, tema claro/oscuro, elección de logo (dos variantes), PIN de acceso.
- **Copia de seguridad**: backup/restore completo en `.json` (incluye programas, histórico, ajustes y PIN) — es el único formato que permite restaurar todo sin pérdida.
- **Exportar datos en CSV**: además del backup, se puede exportar el histórico a 3 archivos `.csv` (sesiones, métricas, expectations) listos para abrir en Excel, Numbers o Google Sheets. Esta exportación es solo para ver/analizar: no sirve para restaurar datos.

## Idiomas

Español, inglés y polaco, seleccionables desde Ajustes. Todo el texto de la interfaz pasa por el diccionario `I18N` — no hay literales sin traducir.

## Datos y privacidad

- Todo vive en `localStorage`, bajo la clave `padtrain_v2`, en el propio teléfono.
- No hay backend, no hay analítica, no se manda nada a ningún servidor.
- Si se borra Safari o se cambia de teléfono, los datos se pierden a menos que se haya hecho un backup `.json` antes.

## Convención de versiones

Cada cambio sustancial se entrega como un **archivo nuevo** (`pad-training-vX.Y.html`), nunca sobreescribiendo el anterior — así siempre queda una versión funcional previa a la mano. Los arreglos pequeños dentro de la misma fase se aplican sobre el archivo vigente en curso.

La versión vigente y con la que se debe trabajar es siempre la de número más alto en el directorio. A la fecha: **`pad-training-v2.8.html`**.

Los archivos con número de versión menor (`pad-training-v2.1.html` … `pad-training-v2.7.html`) y los archivos más antiguos sin este esquema (`pad-training-tracker.html`, `pad-training-tracker_v0.html`, `pad-training-fase1.html`, `pad-training-v2.html`, `pad4training.html`) se conservan como historial, pero no reciben más cambios.

## Otros archivos del directorio

- `Verano_Programa_360_Ivan_con_Protocolo_Nutricion.xlsx`, `Plan_B_Casa_Ivan.xlsx` — hojas de cálculo originales de las que se derivaron los programas "Verano 360" y "Plan B — Casa" ya cargados en la app.
- `1.png`, `2.png` — las dos variantes del logo, embebidas en base64 dentro del HTML (splash, icono de pantalla de inicio, manifest PWA); estos archivos son solo la fuente original, la app no los lee en tiempo de ejecución.

## Restricciones técnicas del proyecto

- Un único archivo HTML, sin build ni CDN ni recursos externos.
- Sin `<input type="number">`: toda entrada numérica usa `type="text" inputmode="decimal"` y acepta coma o punto.
- Sin gestos: reordenar y borrar siempre con botones explícitos (↑↓, confirmación).
- Diseño mobile-first para iPhone/Safari.
