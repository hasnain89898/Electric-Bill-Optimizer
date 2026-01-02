 ⚡ Electricity Bill Optimizer (Pakistan)

# Overview
A Python GUI app that estimates and optimizes monthly electricity bills in Pakistan.  
It uses **Tkinter** for the interface, **Matplotlib** for visualization, and a simple **Linear Regression model** for supervised ML predictions.

## Features
- Multi-appliance selection with auto-filled wattages  
- AM/PM input converted to 24-hour format  
- Peak-hour detection (5–11 PM) with smart suggestions  
- Appliance-wise monthly bill calculation  
- Pie chart visualization of cost distribution  
- ML-powered prediction of combined monthly bill  

## Installation
```bash
git clone https://github.com/your-username/Electric-Bill-Optimizer.git
cd Electric-Bill-Optimizer
pip install -r requirements.txt


## Usage
python electric_bill_optimizer.py

Functions Explained
- add_appliance() → Adds appliance details and calculates monthly cost
- calculate_total() → Computes total bill, predicts combined bill using ML, and gives suggestions
- show_pie_chart() → Displays appliance-wise bill share
- to_24h() → Converts AM/PM input to 24-hour format
- overlaps_peak() → Detects overlap with Pakistan’s peak hours
Machine Learning
A simple Linear Regression model predicts combined monthly bills based on total daily usage hours.
Future Work
- Mobile app version
- Cloud-based storage
- Advanced ML models for accuracy
