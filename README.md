# Field Ops Web Tools

Utilidades de campo que funcionan en el navegador sin cuentas, servidor ni conexión permanente.

- [Field Notes](herramientas/field-notes/): observaciones geolocalizadas, fotografías opcionales, mapa, almacenamiento local y GeoJSON.
- [Measure Lab](herramientas/measure-lab/): conversiones, coordenadas DMS y distancias geodésicas.
- [Track Log](herramientas/track-log/): recorridos GPS con filtro de precisión, distancia, velocidad, mapa y exportación GeoJSON, GPX y CSV.

Las notas se guardan en `localStorage` del navegador. Exporta periódicamente el GeoJSON para conservar una copia fuera del navegador. Las capas de mapa son opcionales y proceden de OpenStreetMap mediante Leaflet; las observaciones no se envían a ningún servidor propio.
