# COVID-19 Data Analysis

This project involves the analysis of global COVID-19 data scraped from [Worldometer](https://www.worldometers.info/coronavirus/). The analysis explores the relationship between pandemic trends and public health indicators, as well as the effects of government interventions.

## 📊 Project Highlights

- 🕸 **Web Scraping**: Utilized `BeautifulSoup` to scrape real-time COVID-19 data from Worldometer and constructed a structured Pandas DataFrame.
- 🧹 **Data Cleaning**: Performed preprocessing using `Pandas`, `NumPy`, and `regex` to handle missing values, standardize formats, and prepare data for analysis.
- 📈 **Policy Impact Analysis**: Analyzed the impact of government measures—such as lockdowns and testing frequency—on daily COVID-19 case counts.
- 🧬 **Health Indicator Correlation**: Investigated the relationship between COVID-19 death rates and underlying health factors such as median age, obesity, and diabetes prevalence.
- 📉 **Visualization**: Created insightful plots using `Matplotlib` to highlight trends and correlations in the aggregated data.

## 🛠 Installation

To install all required Python packages:

```bash
pip install -r requirements.txt
```

## 📁 Project Structure

```
.
├── C_19_DataAnalysis.ipynb
├── requirements.txt
├── README.md
```

## 📌 Dependencies

- pandas
- numpy
- matplotlib
- requests
- beautifulsoup4
- re

## 📜 License

This project is licensed under the MIT License.
