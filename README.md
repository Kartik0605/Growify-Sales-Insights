
# Growify Sales Insights

A comprehensive exploratory data analysis (EDA) project that uncovers key sales and return-rate patterns across brands, channels, and geographies for Growify’s Sales Data.

## 🚀 Table of Contents
1. [Project Description](#project-description)  
2. [Key Insights](#key-insights)  
3. [Dataset](#dataset)  
4. [Tech Stack & Dependencies](#tech-stack--dependencies)  
5. [Installation](#installation)  
6. [Usage](#usage)  
7. [Project Structure](#project-structure)  
8. [Contributing](#contributing)  
9. [License](#license)  

## 📝 Project Description  
This repository contains a Jupyter notebook (`dataanalysis_growify.ipynb`) and the raw sales dataset (`Sales Data_Test.xlsx`). Through data cleaning, aggregation, and visualization, we:

- Compute total sales and returns  
- Identify top-performing and underperforming brands  
- Analyze channel performance (Online, Wholesale, WhatsApp, etc.)  
- Map sales distribution by country  
- Detect anomalies in return rates  

All findings are presented with clear charts and markdown commentary.

## 🔍 Key Insights  
- **Total Sales:** ₹303 Cr across all records  
- **Top 5 Brands:** Drzya leads sales, while Shaira Fashion Dubai lags  
- **Channel Performance:**  
  - Highest: Online  
  - Zero sales observed via WhatsApp Marketing & Broadcast (potential data gap)  
- **Geographic Spread:**  
  - Largest market: India  
  - Smallest market: Canada  
- **Return Rate Anomaly:** Exceptionally high returns suggest data quality issues  

## 📂 Dataset  
- **`Sales Data_Test.xlsx`**  
  - Raw sales records with columns such as `Order Date`, `Brand`, `Channel`, `Country`, `Sales`, and `Returns`.  
  - Please ensure the file remains in the project root or update the notebook’s file path accordingly.

## 🛠️ Tech Stack & Dependencies  
- Python 3.8+  
- Jupyter Notebook  
- pandas  
- matplotlib  
- seaborn  

## ⚙️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/growify-sales-insights.git
   cd growify-sales-insights
   ```

2. **Create & activate a virtual environment**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage  

1. **Ensure** `Sales Data_Test.xlsx` is in the project root.  
2. **Open** the notebook:  
   ```bash
   jupyter notebook dataanalysis_growify.ipynb
   ```  
3. **Run cells sequentially** to reproduce the analysis and visualizations.  

## 📁 Project Structure  
```
├── dataanalysis_growify.ipynb   # Main exploratory notebook
├── Sales Data_Test.xlsx         # Raw sales data
├── requirements.txt             # Python dependencies
└── README.md                    # Project overview & instructions
```

## 🤝 Contributing  
Contributions are welcome! Please open an issue or submit a pull request with improvements, bug fixes, or new analyses (e.g., forecasting, segmentation).

1. Fork the repo  
2. Create your feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add YourFeature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

## 📄 License  
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute!  

*Happy analyzing!*
