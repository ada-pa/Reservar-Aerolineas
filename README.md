# AeroGestión · Reservas

Prototipo de interfaz para la gestión de reservas y operaciones de una aerolínea. Está construido con HTML, CSS y JavaScript, sin dependencias ni proceso de compilación.

## Cómo ejecutarlo

Abre `index.html` directamente en un navegador moderno. También puedes servir la carpeta con cualquier servidor web estático; por ejemplo, desde la raíz del proyecto:

```bash
python3 -m http.server 8000
```

Luego visita [http://localhost:8000](http://localhost:8000).

## Funcionalidades

- Panel con resumen de la operación y actividad reciente.
- Consulta y filtrado de vuelos; formulario para programar vuelos durante la sesión.
- Creación de reservas con selección de pasajero, vuelo y asiento.
- Registro simulado de pagos y emisión de códigos de boleto de demostración.
- Consulta y registro básico de pasajeros.
- Validación de boleto y documento, check-in y registro de equipaje.
- Vistas informativas de rutas, tripulación y reportes.
- Diagrama de contexto y modelo entidad-relación en `diagramas_aerolinea.html`.

## Datos y alcance

La aplicación carga datos de ejemplo. Las reservas y sus cambios se conservan en `localStorage` del navegador actual; no se comparten entre usuarios o dispositivos. Los vuelos nuevos solo se mantienen en memoria durante la sesión. Los pagos son simulados: no se procesan transacciones reales. No hay servidor ni base de datos.

Para una descripción del flujo del prototipo y su modelo, consulta [`GUIA_PARA_SUSTENTAR.txt`](GUIA_PARA_SUSTENTAR.txt).
