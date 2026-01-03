<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,18,6&height=200&section=header&text=⚡%20Electricity%20Bill%20Optimizer&fontSize=45&fontColor=fff&animation=fadeIn&fontAlignY=38" />
</div>

<h3 align="center">Smart Energy Management for Pakistan | Save Money, Track Usage, Stay Efficient</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Tkinter-GUI-FF6B6B?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/ML-Linear_Regression-00D9FF?style=for-the-badge&logo=tensorflow&logoColor=white" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=FFD700&center=true&vCenter=true&width=600&lines=Calculate+Your+Bill+Instantly;Predict+Monthly+Costs+with+ML;Optimize+Peak+Hour+Usage;Visualize+Energy+Consumption" />
</p>

---

## 🌟 Why This App?

Electricity bills in Pakistan can be unpredictable and expensive, especially during peak hours. This intelligent application helps you:

<table>
<tr>
<td width="33%" align="center">

### 💰 Save Money
Track which appliances cost you the most and optimize usage during off-peak hours

</td>
<td width="33%" align="center">

### 📊 Visualize Usage
See exactly where your electricity budget goes with interactive pie charts

</td>
<td width="33%" align="center">

### 🤖 Predict Bills
Use machine learning to forecast your monthly costs before they arrive

</td>
</tr>
</table>

---

## ✨ Key Features

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🔌 Smart Appliance Management
- Pre-loaded wattage database for common appliances
- Multi-appliance selection and tracking
- Custom appliance addition support
- Real-time cost calculation per appliance

### ⏰ Intelligent Time Tracking
- AM/PM input with automatic 24-hour conversion
- Peak-hour detection (5 PM - 11 PM)
- Usage overlap analysis
- Smart usage recommendations

</td>
<td width="50%" valign="top">

### 📈 Visual Analytics
- Colorful pie chart breakdown
- Appliance-wise cost distribution
- Monthly bill projection
- Easy-to-understand insights

### 🧠 ML-Powered Predictions
- Linear Regression model for accuracy
- Combined monthly bill forecasting
- Usage pattern analysis
- Personalized savings suggestions

</td>
</tr>
</table>

</div>

---

## 🚀 Quick Start Guide

<div align="center">

### Step 1️⃣ Clone the Repository

</div>

```bash
git clone https://github.com/hasnain89898/Electric-Bill-Optimizer.git
cd Electric-Bill-Optimizer
```

<div align="center">

### Step 2️⃣ Install Dependencies

</div>

```bash
pip install -r requirements.txt
```

<div align="center">

### Step 3️⃣ Launch the Application

</div>

```bash
python electric_bill_optimizer.py
```

<div align="center">

### 🎉 You're All Set! Start Optimizing Your Bills

</div>

---

## 🎯 How It Works

<div align="center">

### Simple 4-Step Process

</div>

<table>
<tr>
<td align="center" width="25%">

**Step 1**

<img src="https://img.shields.io/badge/1-Select_Appliance-FFD700?style=for-the-badge" />

Choose from pre-loaded appliances or add custom ones

</td>
<td align="center" width="25%">

**Step 2**

<img src="https://img.shields.io/badge/2-Set_Usage_Time-FF6B6B?style=for-the-badge" />

Enter start and end times with AM/PM

</td>
<td align="center" width="25%">

**Step 3**

<img src="https://img.shields.io/badge/3-View_Analytics-00D9FF?style=for-the-badge" />

See cost breakdown and visualizations

</td>
<td align="center" width="25%">

**Step 4**

<img src="https://img.shields.io/badge/4-Get_Prediction-BB9AF7?style=for-the-badge" />

Receive ML-based monthly bill forecast

</td>
</tr>
</table>

---

## 🛠️ Technology Stack

<div align="center">

### Frontend & GUI

<img src="https://img.shields.io/badge/Tkinter-GUI_Framework-FF6B6B?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Modern_UI-Dark_Theme-1F2937?style=for-the-badge" />

### Data Visualization

<img src="https://img.shields.io/badge/Matplotlib-Charts-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
<img src="https://img.shields.io/badge/Pie_Charts-Interactive-FFD700?style=for-the-badge" />

### Machine Learning

<img src="https://img.shields.io/badge/scikit--learn-ML_Library-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/Linear_Regression-Prediction-00D9FF?style=for-the-badge" />

### Core Language

<img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />

</div>

---

## 💡 Core Functions Breakdown

<table>
<tr>
<td width="50%" valign="top">

### `add_appliance()`
**Purpose:** Adds appliance details and calculates monthly cost

**Process:**
- Retrieves appliance name and wattage
- Converts time to 24-hour format
- Calculates daily usage hours
- Computes monthly bill (30 days)
- Stores data for analysis

</td>
<td width="50%" valign="top">

### `calculate_total()`
**Purpose:** Computes total bill and provides ML predictions

**Process:**
- Sums all appliance costs
- Applies ML model for prediction
- Detects peak-hour usage
- Generates savings suggestions
- Displays comprehensive results

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `show_pie_chart()`
**Purpose:** Displays appliance-wise bill distribution

**Process:**
- Generates color-coded pie chart
- Shows percentage breakdown
- Highlights top consumers
- Provides visual insights

</td>
<td width="50%" valign="top">

### `overlaps_peak()`
**Purpose:** Detects overlap with Pakistan's peak hours

**Process:**
- Checks 5 PM - 11 PM window
- Analyzes usage patterns
- Flags high-cost periods
- Recommends optimizations

</td>
</tr>
</table>

---

## 🤖 Machine Learning Integration

<div align="center">

### Linear Regression Model

</div>

The application uses a supervised learning approach to predict monthly electricity bills based on usage patterns.

**Model Architecture**
- **Algorithm:** Linear Regression
- **Input Features:** Total daily usage hours across all appliances
- **Output:** Predicted combined monthly bill (PKR)
- **Training:** Historical usage data patterns

**Prediction Process**

```python
# Model predicts based on total usage hours
daily_hours = sum(all_appliance_usage_hours)
predicted_bill = model.predict([[daily_hours]])
```

**Accuracy Improvements**
- Considers appliance wattage variations
- Accounts for peak-hour multipliers
- Adapts to user-specific patterns

---

## 📊 Sample Output

<div align="center">

### Example Bill Breakdown

<table>
<tr>
<th>Appliance</th>
<th>Wattage</th>
<th>Daily Usage</th>
<th>Monthly Cost</th>
</tr>
<tr>
<td>Air Conditioner</td>
<td>1500W</td>
<td>8 hours</td>
<td>PKR 3,600</td>
</tr>
<tr>
<td>Refrigerator</td>
<td>150W</td>
<td>24 hours</td>
<td>PKR 1,080</td>
</tr>
<tr>
<td>LED TV</td>
<td>100W</td>
<td>6 hours</td>
<td>PKR 180</td>
</tr>
<tr>
<td colspan="3"><b>Total Calculated</b></td>
<td><b>PKR 4,860</b></td>
</tr>
<tr>
<td colspan="3"><b>ML Predicted</b></td>
<td><b>PKR 5,120</b></td>
</tr>
</table>

</div>

---

## 🎨 User Interface Preview

<div align="center">

### Modern Dark-Themed Interface

**Key UI Elements**
- Clean appliance selection dropdown
- Intuitive time input fields (AM/PM support)
- Real-time cost display
- Interactive pie chart visualization
- Clear prediction results
- Smart optimization tips

</div>

---

## 🌍 Pakistan-Specific Features

### Peak Hour Detection
Automatically identifies usage during Pakistan's high-tariff period (5 PM - 11 PM)

### Local Tariff Rates
Pre-configured with Pakistani electricity rates for accurate calculations

### Common Appliances
Database includes appliances typical in Pakistani households

---

## 🚀 Future Roadmap

<div align="center">

<table>
<tr>
<td align="center" width="33%">

### 📱 Mobile Version
React Native app for iOS and Android

**Features:**
- Push notifications
- Real-time tracking
- Bill reminders

</td>
<td align="center" width="33%">

### ☁️ Cloud Integration
Firebase backend for data persistence

**Features:**
- Multi-device sync
- Historical data storage
- Usage analytics

</td>
<td align="center" width="33%">

### 🧠 Advanced ML
Neural networks for better predictions

**Features:**
- Weather-based forecasting
- Seasonal adjustments
- Personalized tips

</td>
</tr>
<tr>
<td align="center" width="33%">

### 📊 Enhanced Analytics
More detailed insights and reports

**Features:**
- Weekly comparisons
- Cost trends
- Energy efficiency score

</td>
<td align="center" width="33%">

### 🏠 Smart Home Integration
IoT device connectivity

**Features:**
- Automatic tracking
- Remote control
- Voice commands

</td>
<td align="center" width="33%">

### 🌐 Multi-Region Support
Expand beyond Pakistan

**Features:**
- Currency conversion
- Regional tariffs
- Language options

</td>
</tr>
</table>

</div>

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

**Areas for Contribution**
- Add more appliances to the database
- Improve ML model accuracy
- Enhance UI/UX design
- Add new visualization types
- Implement additional features
- Fix bugs and optimize code

### How to Contribute

```bash
# Fork the repository
# Create your feature branch
git checkout -b feature/AmazingFeature

# Commit your changes
git commit -m 'Add some AmazingFeature'

# Push to the branch
git push origin feature/AmazingFeature

# Open a Pull Request
```

---

## 📝 Requirements

```txt
tkinter (included with Python)
matplotlib>=3.5.0
scikit-learn>=1.0.0
numpy>=1.21.0
```

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` file for details.

---

## 📞 Contact & Support

<div align="center">

<a href="https://www.linkedin.com/in/hasnain-naseer-a33036399" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:naseerhassnain981@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/hasnain89898" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://instagram.com/hasnain_naseer8" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=Instagram&logoColor=white" />
</a>

### Found This Helpful? Give it a ⭐ on GitHub!

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=16&pause=1000&color=FFD700&center=true&vCenter=true&width=500&lines=Save+Money+💰+Track+Usage+📊+Stay+Efficient+⚡" />

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,18,6&height=100&section=footer" />
</div>
