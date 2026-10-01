# Los Tresmiles del Pirineo

Mapa navegable en relieve de los 212 tresmiles (lista UIAA) del Pirineo aragonés y del Pirineo catalán occidental. Cada cima tiene una ficha con foto, altitud, valles, refugios y rutas de acceso, y un modelo 3D que se puede girar para verla por todas sus caras.

**Ver el mapa:** https://rforcano.github.io/tresmiles-pirineo/

## Archivos

- `index.html`: la aplicación (mapa WebGL, índice de cimas, fichas y visor 3D).
- `datos-base.js`: relieve de 50 m, cobertura del suelo, ríos, lagos, glaciares, valles, cimas, rutas y fotos.
- `datos-relieve-1.js` y `datos-relieve-2.js`: relieve de 10 m de la alta montaña. Se cargan después de mostrar el mapa.

Es una web estática: funciona en GitHub Pages o en cualquier servidor de archivos. Las tipografías se cargan desde Google Fonts y el visor 3D usa three.js desde cdnjs.

## Datos y licencias

- Relieve: © Instituto Geográfico Nacional de España (MDT05 y MDT25, CC BY 4.0); IGN France, RGE ALTI (Licence Ouverte Etalab 2.0); Copernicus DEM GLO-30 (© DLR e.V. 2010-2014 y © Airbus Defence and Space GmbH 2014-2018, proporcionado en el marco de COPERNICUS por la Unión Europea y la ESA).
- Cobertura del suelo: © ESA WorldCover project 2021 (CC BY 4.0), con datos modificados de Copernicus Sentinel (2021).
- Ríos, lagos, glaciares, carreteras, pueblos y refugios: © colaboradores de OpenStreetMap (ODbL).
- Fotos: Wikimedia Commons. El autor y la licencia de cada foto aparecen en su ficha.
- Lista de cimas: lista UIAA de tresmiles del Pirineo (Buyse), a partir de Wikipedia y Viquipèdia.
- Visor 3D: three.js (licencia MIT). Tipografías Barlow, Barlow Condensed y Cormorant Garamond (SIL Open Font License).

Las rutas de acceso son orientativas. Antes de salir, consulta una guía actualizada y el estado de la montaña.
