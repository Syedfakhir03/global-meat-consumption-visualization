# 🌍 Global Meat Consumption & Production Visualization

An interactive data visualization project exploring **global meat consumption, production trends, regional differences, and the relationship between meat production and GDP per capita**.

The project combines multiple interactive visualizations into a single dashboard to help users explore how meat consumption and production vary across countries, continents, meat categories, and time.

## 📊 Project Overview

This project was created as an interactive data storytelling experience using **Vega-Lite, JavaScript, HTML, and CSS**.

It focuses on four main questions:

- Which countries consume the most meat per capita?
- How has global meat production changed over time?
- Which meat categories contribute most to total production?
- Is there a relationship between GDP per capita and meat production per person?

## ✨ Key Visualizations

### 🗺️ Global Meat Consumption Distribution

A choropleth world map showing **meat consumption per capita by country**.

The map makes it easy to compare consumption levels globally and identify countries with relatively high or low meat consumption.

### 🥩 Global Meat Production Breakdown

An interactive production chart that allows users to explore different meat categories, including:

- Bovine meat
- Fish and seafood
- Other meat
- Mutton and goat meat
- Pig meat
- Poultry meat

Users can filter the visualization by meat type to compare production trends.

### 📈 Global Meat Production by Continent

A time-series visualization covering **1961–2021**.

Users can filter by continent to explore long-term regional production patterns across:

- Asia
- Europe
- North America
- South America
- Africa
- Oceania

### 💰 GDP vs Meat Production per Capita

An interactive chart exploring the relationship between **GDP per capita** and **meat production per capita**.

Interactive controls include:

- Year selection
- Minimum GDP filter
- Continent filter
- Play / pause interaction for exploring changes over time

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**
- **Vega**
- **Vega-Lite**
- **Vega-Embed**
- **JSON**
- **GitHub Pages**

## 📁 Project Structure

```text
FIT3179_VIZ_2/
│
├── 5Ds Visualisation 2/
├── Data/
├── css/
├── js/
│
├── Bubblegraph.vg.json
├── StackedArea.vg.json
├── Stackedbar.vg.json
├── anotherone_bubble.vg.json
├── sybol_2_with.vg.json
│
└── index.html
```

The `.vg.json` files contain the Vega-Lite visualization specifications, while the `Data`, `css`, and `js` folders contain the supporting datasets, styling, and JavaScript used by the dashboard.

## 🎯 Key Features

- Interactive world map
- Dynamic filtering by meat category
- Continent-based filtering
- Year slider for temporal exploration
- GDP threshold filtering
- Interactive tooltips
- Multiple coordinated visualizations
- Data storytelling with written insights
- Web-based presentation
- Live deployment using GitHub Pages

## 💡 Insights Highlighted in the Dashboard

The dashboard is designed to help users identify patterns such as:

- Large differences in meat consumption per capita between countries
- Long-term growth in meat production across different regions
- Differences in production between meat categories
- Regional shifts in meat production over time
- Relationships between economic development and meat production per capita

## 🎓 Skills Demonstrated

This project demonstrates practical experience with:

- Data visualization
- Interactive dashboard development
- Data storytelling
- Exploratory data analysis
- Vega-Lite specification design
- Web development
- Filtering and interactive controls
- Communicating analytical findings to non-technical audiences

## 🚀 Running the Project Locally

Clone the repository:

```bash
git clone https://github.com/Syedfakhir03/FIT3179_VIZ_2.git
```

Open the project folder:

```bash
cd FIT3179_VIZ_2
```

Because the project loads local data and Vega-Lite specifications, it is best viewed through a local web server.

For example, with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

in your browser.

## 🔮 Possible Improvements

Future improvements could include:

- Updating the datasets with newer values
- Improving mobile responsiveness
- Adding richer hover interactions
- Adding more country-level drill-downs
- Adding downloadable chart data
- Improving accessibility and color contrast
- Reorganizing the codebase into a cleaner production-style structure

## 👤 Author

**Syed Fakhar Un Nabi**

- GitHub: [Syedfakhir03](https://github.com/Syedfakhir03)
- LinkedIn: [syed-fakhir](https://www.linkedin.com/in/syed-fakhir/)

---

⭐ If you found this project interesting, feel free to explore the live dashboard and repository.
