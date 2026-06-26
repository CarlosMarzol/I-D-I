# Priorizador Humanitario Venezuela

Herramienta local/publicable para ordenar zonas afectadas por prioridad operativa usando solo datos trazables: Copernicus EMS, USGS, GDACS, autoridades, organismos humanitarios y reportes de terreno verificables.

## Uso rápido

1. Abrir `index.html` en el navegador.
2. Cargar zonas reales con fuente concreta y URL o referencia verificable.
3. Ajustar los pesos si cambia el criterio de decisión.
4. Revisar el estado `Publicable`, `Pendiente`, `Sin fuente` o `Falta contraste`.
5. Exportar CSV para compartir el ranking.

## Campos

- `danio`: severidad física observada, 0-5.
- `aislamiento`: dificultad de acceso, vías cerradas o comunicaciones caídas, 0-5.
- `salud`: riesgo sanitario o presión sobre centros de salud, 0-5.
- `agua`: urgencia de agua, alimentos o suministros básicos, 0-5.
- `reportes`: número de reportes independientes.
- `verificado`: si la información fue contrastada.
- `tipo_fuente`: Copernicus, GDACS, USGS, autoridad, ONG, terreno o medio verificado.
- `confirmaciones`: número de confirmaciones independientes.
- `fuente`: nombre concreto de la fuente.
- `url`: enlace o referencia verificable.

## Fuentes sugeridas

- Copernicus EMSR884: https://mapping.emergency.copernicus.eu/activations/EMSR884/
- USGS M7.5: https://earthquake.usgs.gov/earthquakes/eventpage/us6000t7zp
- GDACS M7.5: https://www.gdacs.org/report.aspx?eventid=1548377&eventtype=EQ
- GDACS M7.2: https://gdacs.org/report.aspx?episodeid=1714423&eventid=1548473&eventtype=EQ
- Reportes de protección civil, alcaldías, hospitales y ONGs.
- OpenStreetMap y HDX/OCHA para carreteras, población e infraestructura.

La herramienta no incluye zonas ficticias. No publiques una fila marcada como pendiente, sin fuente o sin contraste.
