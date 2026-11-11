## Historial (punto 5)
Menú → Historial. Lista todas las entradas y salidas, de la más reciente a la más antigua.
Filtros: placa (búsqueda parcial en tiempo real), estado (Todos / Dentro / Ya salieron)
y rango de fecha y hora de entrada (DateTimePicker). Muestra cuántos registros hay y
cuánto suman sus ingresos.

## Reportes
Menú → Reportes.
- Ingresos por día: se agrupan por la fecha de salida (cuando se cobra).
- Ocupación por hora (bonificación): promedio de puestos ocupados en cada hora del día
  durante los últimos 7 días. La hora pico se marca en rojo.

## Bonificación: tarifa por minutos y horas pico
- Primeros 15 minutos gratis (se descuentan una sola vez por visita).
- Después: carro $70/min, moto $35/min, con tope por día (carro $20.000, moto $10.000).
- Si el vehículo pasa la noche, la visita se parte a la medianoche y cada día se cobra
  por separado con su propio tope.
- Se cobran minutos completos (los segundos se descartan).
- Cómo probarla: borrar datos/registros.txt para generar el historial de ejemplo;
  la placa NOCHE1 es una visita nocturna (cobra $26.650).
- Interruptor: Tarifa.COBRO_POR_MINUTOS = false vuelve al cobro por hora (punto 3).
