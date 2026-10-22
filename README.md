# Intendentas de Entre Ríos (2019-2023 y 2023-2027)

Mapa interactivo de los 84 municipios de Entre Ríos según el género de la autoridad municipal en dos períodos.

**Ver el mapa:** https://julianatentorcarmody-lang.github.io/intendentas-entre-rios/

Al pasar el cursor (o tocar) un municipio se ven su población (Censo 2022), sus autoridades y partidos en ambos períodos, y si hubo continuidad o cambio. Incluye una vista del cambio entre períodos, un buscador y una tabla con los 84 municipios.

En los 84 municipios, las intendentas pasaron de 9 (2019-2023) a 15 (2023-2027).

## Archivo
Todo el mapa está en un único archivo, `index.html`, con los datos incluidos. Funciona sin servidor: también se puede abrir con doble clic.

## Notas de método
- Se muestran los 84 municipios vigentes en 2026, con el polígono de su jurisdicción (ejido). Comunas, juntas de gobierno y zonas sin gobierno local quedan como contexto.
- Sauce Montrull era comuna en 2019-2023 y es municipio desde el 1 de enero de 2026 (Ley 11.233). Para 2023-2027 se registra la autoridad vigente a octubre de 2026.
- Las jurisdicciones grandes y poco pobladas (por ejemplo, Victoria con sus islas) pesan visualmente más que su población. La tabla permite leer cada municipio por igual.

## Fuentes
- Límites de gobiernos locales: ATER, Catastro de Entre Ríos (servicio WFS `sit_catastro`, 2026).
- Departamentos, ríos y espejos de agua: Instituto Geográfico Nacional (IGN).
- Autoridades 2019-2023: DataGénero (relevamiento de 2023, Carolina Glasserman Apicella).
- Autoridades 2023-2027: base de la autora, con correcciones registradas.
- Población: INDEC, Censo Nacional de Población, Hogares y Viviendas 2022.
- Mapa base: © [colaboradores de OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL). La página incluye las teselas de zoom 7 a 9; al acercarse más, las pide en vivo a `tile.openstreetmap.org`.

Elaboración: Juliana Tentor Carmody (UNER).
