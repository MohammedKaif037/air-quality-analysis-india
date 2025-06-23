# Air Quality Analysis in Indian Cities

A comprehensive Python-based analysis tool for examining air quality data across Indian cities, focusing on key pollutants like PM2.5, NO2, and SO2.

## 🌟 Features

- **Multi-pollutant Analysis**: Analyze PM2.5, NO2, SO2, and other air quality indicators
- **City Comparison**: Compare air quality metrics across different Indian cities
- **WHO Guidelines Integration**: Automatic comparison with WHO air quality guidelines
- **Correlation Analysis**: Examine relationships between different pollutants
- **Interactive Visualizations**: Generate comprehensive charts and heatmaps
- **Health Impact Assessment**: Categorize pollution levels and health implications

## 📊 Key Visualizations

- Top 20 cities by PM2.5 levels
- Pollutant correlation heatmaps
- PM2.5 vs NO2 scatter plots with trend lines
- Air quality category distribution
- Box plots for pollution distribution analysis

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MohammedKaif037/air-quality-analysis-india.git
cd air-quality-analysis-india
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

### Usage

1. Prepare your air quality dataset in CSV format with the following columns:
   - `city`: City name
   - `last_update`: Date and time (format: DD-MM-YYYY HH:MM:SS)
   - `pollutant_id`: Pollutant identifier (PM2.5, NO2, SO2, etc.)
   - `pollutant_avg`: Average pollutant concentration

2. Update the CSV filename in the script:
```python
df = pd.read_csv('air-quality-data.csv')
```

3. Run the analysis:
```bash
python air_quality_analysis.py
```

## 📁 Project Structure

```
air-quality-analysis-india/
│
├── air_quality_analysis.py    # Main analysis script
├── requirements.txt           # Python dependencies
├── README.md                 # Project documentation
├── data/                     # Data directory (add your CSV files here)

```

## 📈 Analysis Features

### 1. Data Preprocessing
- Automatic datetime conversion
- Missing value handling
- Data pivoting for multi-pollutant analysis
- Numeric data validation

### 2. Statistical Analysis
- **PM2.5 Analysis**: Average levels across cities with WHO guideline comparison
- **City Rankings**: Identification of most polluted cities by different pollutants
- **Correlation Analysis**: Relationship strength between pollutants
- **Health Categorization**: Classification based on pollution severity

### 3. Visualizations
- **Bar Charts**: Top polluted cities
- **Scatter Plots**: Pollutant relationships with trend lines
- **Heatmaps**: Correlation matrices
- **Box Plots**: Distribution analysis
- **Category Charts**: Health impact visualization

## 📊 Sample Output

The analysis provides:
- Dataset overview with shape and statistical summary
- Average PM2.5 levels compared to WHO guidelines (15 μg/m³)
- City with highest NO2 levels
- Top 3 most polluted cities by PM2.5
- Pollutant correlation coefficients with strength interpretation
- Comprehensive visualizations
- Health implications summary

## 🎯 Key Metrics Analyzed

- **PM2.5**: Fine particulate matter (μg/m³)
- **NO2**: Nitrogen dioxide levels (μg/m³)
- **SO2**: Sulfur dioxide concentration (μg/m³)
- **Correlation Coefficients**: Statistical relationships between pollutants

## 🏥 Health Categories

The analysis categorizes air quality into:
- **Good**: PM2.5 ≤ 30 μg/m³
- **Moderate**: PM2.5 31-60 μg/m³
- **Unhealthy for Sensitive**: PM2.5 61-90 μg/m³
- **Unhealthy**: PM2.5 91-120 μg/m³
- **Very Unhealthy**: PM2.5 > 120 μg/m³

## 📋 Requirements

See `requirements.txt` for detailed package versions.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- World Health Organization (WHO) for air quality guidelines
- Indian air quality monitoring networks for data sources
- Python data science community for excellent libraries

## 📞 Contact

Mohammed Kaif - kaifmohammed037@gmail.com
Project Link: https://github.com/MohammedKaif037/air-quality-analysis-india

## 🔄 Future Enhancements

- [ ] Real-time data integration
- [ ] Seasonal trend analysis with multi-temporal data
- [ ] Geographic mapping with latitude/longitude
- [ ] Machine learning predictions for air quality forecasting
- [ ] API integration for automated data updates
- [ ] Dashboard development with interactive web interface
