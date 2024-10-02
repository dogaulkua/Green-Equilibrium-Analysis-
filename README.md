# Green Equilibrium: A NASA Space Apps Challenge Project

**Green Equilibrium** is a data-driven project that analyzes the **impact of microplastic pollution** on human health, specifically focusing on **women and children**. This project utilizes **Fuzzy Logic** to model the effects of microplastics under changing climatic conditions, contributing to the **Sustainable Development Goals (SDGs)** for **Climate Change (SDG 13)** and **Gender Equality (SDG 5)**.

## 📑 Project Overview

Microplastic pollution is increasingly recognized as a significant environmental and public health concern. Green Equilibrium seeks to address this issue by:

- Modeling the **health impacts of microplastics** on vulnerable populations (women and children).
- Utilizing **Fuzzy Logic** to make predictions based on climatic and demographic data.
- Aligning solutions with **climate action** and **gender equality** goals.

## 🛠️ Installation & Requirements

To run this project locally, ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn skfuzzy
```

### How to run:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/GreenEquilibrium.git
   ```
2. Navigate into the project directory:
   ```bash
   cd GreenEquilibrium
   ```
3. Run the primary script that includes data preprocessing, fuzzy logic implementation, and visualization:
   ```bash
   python green_equilibrium.py
   ```

## 🚀 Features

- **Fuzzy Logic Model**: This project implements **Fuzzy Logic** to analyze the impact of **microplastics** on human health. It models environmental variables such as precipitation, temperature, and exposure to plastics to predict the health risks for women and children.
- **Data Visualization**: Using **matplotlib** and **seaborn**, the project generates graphs to visualize the correlations between microplastic pollution and health risks.
- **Sustainable Interventions**: The solution provides recommendations based on the predictions, aimed at mitigating microplastic impacts in high-risk areas, especially considering gender and climate vulnerabilities.

## 🌍 Datasets

This project makes use of several datasets, with key columns including:

- **Time**, **Latitude**, **Longitude**: Temporal and geographical data.
- **Microplastic Indicators**: Metrics such as R90P, R95P, R99P (precipitation thresholds), drydays, wetdays, and more.
- **Health Data**: Information about **plastic waste per capita** and demographic impacts, specifically focusing on women and children.

## 📊 Data Analysis

The project analyzes the following:

- **Microplastic-related health impacts**: Using fuzzy logic, the model predicts the likelihood of health issues caused by microplastics in various regions.
- **Correlation between environmental factors and microplastic exposure**: Identifying trends and patterns that highlight vulnerable populations.
  
### Key Model Functions:
1. **Fuzzy Logic Implementation**: 
   - Inputs include environmental and plastic waste data.
   - Outputs are risk levels for health impacts on women and children.
2. **Visualization**: Displays trends using **matplotlib** to highlight critical insights.

## 🤝 Contributing

To contribute to Green Equilibrium, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/NewFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add NewFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/NewFeature
   ```
5. Open a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



Bu README dosyası, kodunda kullanılan Bulanık Mantık modeline ve proje çözümüne odaklı bir yapı sunuyor.
