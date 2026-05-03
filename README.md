# :earth_americas: GDP Dashboard

An interactive global GDP data visualization dashboard — explore economic data across 200+ countries with comparisons, time series, and growth rate analysis.

Built to practice turning raw public datasets into something actually useful to look at.

## Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Setup Instructions](#-setup-instructions)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

## 🎯 Features

- **Interactive World Map:** Color-coded GDP by country for any selected year
- **Country Comparison:** Plot GDP trends for multiple countries on a single chart
- **Time Series View:** Track any country's GDP from 1960 to the present
- **Top N Rankings:** Surface the largest or smallest economies for any given year
- **Growth Rate Analysis:** Year-over-year GDP growth rate visualization
- **Per Capita Toggle:** Switch between total GDP and GDP per capita in one click

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Backend | Python |
| Data Processing | Pandas + NumPy |
| Visualization | Plotly + Streamlit |
| Data Source | World Bank API |

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/yatinbhalla/gdp-dashboard.git
cd gdp-dashboard
pip install -r requirements.txt

# Run the dashboard
python app.py
```

Then open [http://localhost:8050](http://localhost:8050) in your browser.

## 📋 Setup Instructions

### Prerequisites

- Python 3.8+
- pip or conda
- Internet connection (to fetch World Bank data)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yatinbhalla/gdp-dashboard.git
   cd gdp-dashboard
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

### Troubleshooting

- **Port already in use:** The app runs on port 8050 by default. You can change this in `app.py`
- **API timeout:** World Bank API may be slow on first load. Data is cached for subsequent runs
- **Missing dependencies:** Ensure you're using Python 3.8+

## 📖 Usage

1. **Select a year** on the left sidebar to filter the data
2. **Use the interactive map** to explore GDP by country
3. **Compare countries** by selecting multiple from the dropdown and clicking "Compare"
4. **Toggle per capita** view for normalized GDP comparisons
5. **Hover over charts** for detailed information

## 📁 Project Structure

```
gdp-dashboard/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── data/                  # Cached data files
├── utils/                 # Helper functions
└── README.md             # This file
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💼 Author

**Yatin Bhalla**

PM & AI builder | Managing retail businesses | PG Product Management @ BITS School of Management

🔗 [LinkedIn](https://linkedin.com/in/yatin-bhalla-834632238)
