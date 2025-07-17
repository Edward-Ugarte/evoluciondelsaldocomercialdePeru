# evoluciondelsaldocomercialdePeru
Modelo ARLA (Balanza Comercial) — Gretl 2025b

NOMBRE DEL MODELO:
ARLA — Dinámica del saldo comercial peruano, 2022:07–2025:06

OBJETIVO:
Estimar la evolución mensual del saldo comercial (exportaciones − importaciones) de Perú, detectar patrones de persistencia y sensibilidad ante shocks externos.

DESCRIPCIÓN DEL MODELO:
Se utiliza un modelo ARMA(1) sobre la serie Balanza para capturar:
- Inercia en el superávit o déficit comercial
- Reacción ante variaciones en flujos internacionales
- Posibilidad de proyección con escenarios alternativos (commodities, demanda externa, tipo de cambio)

VARIABLES IMPLICADAS:
- Exportaciones
- Importaciones
- Balanza comercial (serie derivada)

RESULTADOS ESPERADOS:
✔ Identificación de ciclos y shocks externos
✔ Cuantificación de efectos temporales sobre la balanza
✔ Proyecciones hasta 2026 bajo supuestos personalizados

NOTAS TÉCNICAS:
- Frecuencia mensual, 36 observaciones
- Serie construida y modelada en el mismo script
- Puede extenderse a VAR con tipo de cambio, reservas o actividad real

AUTOR:
Edward Ugarte — Economista
