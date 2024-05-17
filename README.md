# SCRAPEAR_LEE
Este proyecto contiene un script en Python que permite extraer de manera masiva el índice multidimensional calculado disponible en el tablero de Power BI publicado por el Laboratorio de Economía de la Educación (LEE). La información incluye datos de colegios de los municipios de Colombia.

## Requisitos
Para poder ejecutar este script, necesitas tener instalados los siguientes programas y bibliotecas:
- Python 3.x
- Bibliotecas de Python:
  - `requests`
  - `BeautifulSoup`
  - `pandas`
  - `selenium`
  - `openpyxl`
 
 **Configuración del Web Scraper:**
- Abre el archivo `config.py` (o el archivo de configuración correspondiente) y asegúrate de que los parámetros estén configurados correctamente.
- Asegúrate de tener el navegador web compatible y el controlador (driver) de Selenium. Por ejemplo, para Chrome necesitarás [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/).

3. **Ejecutar el script:**
Ejecuta el script principal:
python scrapear_LEEE.py
