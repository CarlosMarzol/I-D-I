# Priorizador Humanitario Venezuela

Herramienta local para ordenar zonas afectadas por prioridad operativa usando datos de Copernicus EMS, reportes de terreno y criterio humanitario.

## Uso rápido

1. Abrir `index.html` en el navegador.
2. Reemplazar los datos de ejemplo con zonas reales.
3. Ajustar los pesos si cambia el criterio de decisión.
4. Exportar CSV para compartir el ranking.

## Campos

- `danio`: severidad física observada, 0-5.
- `aislamiento`: dificultad de acceso, vías cerradas o comunicaciones caídas, 0-5.
- `salud`: riesgo sanitario o presión sobre centros de salud, 0-5.
- `agua`: urgencia de agua, alimentos o suministros básicos, 0-5.
- `reportes`: número de reportes independientes.
- `verificado`: si la información fue confirmada por Copernicus, terreno o fuente confiable.

## Fuentes sugeridas

- Copernicus EMSR884: https://mapping.emergency.copernicus.eu/activations/EMSR884/
- Reportes de protección civil, alcaldías, hospitales y ONGs.
- OpenStreetMap y HDX/OCHA para carreteras, población e infraestructura.

Los datos de ejemplo no deben publicarse como evaluación real.
