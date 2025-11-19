# 2024-Gloabl-Exconomy-GDP

**Description**:
Data Source: The code includes a built-in `gdpData` object containing IMF forecasts (in trillions of US dollars) for major economies in 2024.

Earth Rendering: Uses the `Globe.gl` library.

`polygonAltitude`: Calculates plate thickness based on GDP values; the higher the GDP, the higher the country appears on the Earth's surface.

`polygonCapColor`: Uses `d3-scale` to map GDP values ​​to colors (red represents high GDP, green/yellow represents medium to low GDP).

`GeoJSON`: Dynamically loads world country border data from a public repository on GitHub.
