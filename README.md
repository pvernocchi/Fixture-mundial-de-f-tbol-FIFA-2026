# ⚽ Fixture Mundial de Fútbol FIFA 2026

## 📌 Propósito del archivo

Este repositorio contiene un archivo de Excel (`Fixture mundial 2026.xlsx`) diseñado para **seguir el torneo completo de la Copa Mundial FIFA 2026** de forma práctica y visual.

Su objetivo principal es:

- 🗓️ Organizar todos los partidos del torneo (fase de grupos y eliminación directa).
- 📊 Calcular automáticamente posiciones, estadísticas y clasificaciones.
- 🏆 Mostrar el avance del campeonato hasta la final.

---

## 🧾 ¿Qué incluye el archivo Excel?

El libro está compuesto por varias hojas con funciones específicas:

- **Dashboard**: resumen general del torneo, métricas clave y próximos partidos.
- **Standings**: tablas de posiciones por grupo y ranking de mejores terceros.
- **Matches**: carga y seguimiento de partidos de fase de grupos.
- **Standings Data**: base de datos de soporte para cálculos de posiciones.
- **Knockout**: cuadro de eliminación directa (desde dieciseisavos hasta final).
- **Knockout Data**: datos auxiliares para cruces y resultados eliminatorios.
- **Teams**: listado de selecciones y su grupo correspondiente.
- **Settings**: parámetros generales del torneo (fechas, formato y reglas de puntos).

---

## ⚙️ Funcionamiento

El archivo está preparado para que ingreses resultados y el resto se actualice automáticamente:

1. ✍️ Cargar resultados (goles) en las columnas de resultado de las hojas:
   - `Matches` (fase de grupos)
   - `Knockout` (eliminación directa)
2. 🔄 El sistema recalcula:
   - puntos y diferencia de gol
   - posición por grupo
   - clasificación de terceros
   - cruces de rondas eliminatorias
3. 📈 Visualizar el estado general en `Dashboard`.

> 💡 Recomendación: editar solo las celdas de entrada marcadas para resultados (las columnas amarillas indicadas en el archivo) para no romper fórmulas.

---

## 🧠 Lógica del torneo modelada en esta plantilla

- Formato configurado en el archivo: **48 equipos divididos en 12 grupos de 4**.
- Clasificación configurada en la plantilla:
  - ✅ Los 2 primeros de cada grupo.
  - ✅ Los 8 mejores terceros.
- Total de partidos modelados en este archivo: **104** (72 en fase de grupos + 32 en eliminación directa).
- Sistema de puntaje:
  - Victoria: 3 puntos
  - Empate: 1 punto
  - Derrota: 0 puntos

---

## 🚀 Cómo usarlo rápidamente

1. Abrir `Fixture mundial 2026.xlsx` en Microsoft Excel de escritorio (el archivo está optimizado para este entorno; en otras suites como Excel Online o LibreOffice pueden variar algunas fórmulas/formatos).
2. Ir a `Matches` y completar resultados.
3. Continuar con `Knockout` cuando inicie la fase eliminatoria.
4. Revisar `Standings` y `Dashboard` para ver clasificación y progreso.

---

## 🎯 Alcance de este repositorio

Este proyecto está enfocado en:

- 📚 Centralizar la planificación y seguimiento del Mundial 2026.
- 🛠️ Ofrecer una plantilla funcional reutilizable para simulaciones o seguimiento real.
- 👥 Facilitar el uso por parte de aficionados, analistas o creadores de contenido deportivo.

---

## 📄 Archivo principal

- `Fixture mundial 2026.xlsx`
