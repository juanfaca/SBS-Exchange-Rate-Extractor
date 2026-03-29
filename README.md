💱 SBS Exchange Rate Extractor (USD/PEN)

Just a notebook with an API-interaction based Python code to extract exchange rate (USD/PEN) from the [**Superintendencia de Banca, Seguros y AFP (SBS) of Peru**](https://www.sbs.gob.pe/app/stats/tc-cv-historico.asp)

🚀 Why this project?

Interacting with the official SBS website can be inconsistent. Sometimes you can not access to the information because the number of requests surpass the server's capacity. This script automates the process, allowing financial analysts and economists to bypass manual exports and integrate data directly into their workflows.

🛠️ Technical Workflow

1. Session & Headers: Initializes a requests. Session with custom headers to handle cookies.
2. Request Handling: Sends a POST request with a specific payload to filter by date range.
3. Parsing: Uses BeautifulSoup4 to parse the HTML response and extract the relevant data.
4. (Optional) Data Processing: Pandas' fixes for reliability.
