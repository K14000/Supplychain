# Supplychain
Supplychain Analytics
# Supply Chain Analytics System

A complete Python-based supply chain intelligence and automation platform for inventory optimization, demand planning, and supplier management.

## 🎯 Project Overview

This project demonstrates enterprise-grade data analytics capabilities applied to supply chain management. Built from scratch, it showcases data analysis, visualization, automation, and business intelligence skills.

**Status**: ✅ All features complete and tested

## 🚀 Features

### 1. **Basic Inventory Analysis** 
- Product-level inventory analysis
- Reorder point identification
- Supplier performance tracking
- File: `inventory_analysis.py`

### 2. **Advanced Analytics**
- Days of stock calculations
- Critical product identification
- Stockout risk analysis
- File: `advanced_analysis.py`

### 3. **Interactive Dashboard System**
- 7 professional charts with color-coding
- Real-time metrics summary
- Reorder recommendations
- Supplier importance ranking
- Stockout risk scoring
- File: `interactive_dashboard.py`
- Output: `supply_chain_advanced_dashboard.png`

### 4. **Excel Report Generation**
- Multi-sheet workbooks (5 sheets)
- Critical items sheet (urgent reorders)
- Low stock warnings
- Supplier analysis
- Executive summary
- File: `export_to_excel.py`

### 5. **Automated Alert System**
- Email-ready alerts for critical issues
- Daily inventory reports
- Professional formatting
- Supplier performance summaries
- File: `generate_alerts.py`

### 6. **Scenario Analysis**
- What-if simulations (5 scenarios)
- Safety stock optimization
- Demand surge preparation
- Cost reduction analysis
- Supplier negotiation impact
- File: `scenario_analysis.py`

## 📊 Current Business Metrics

**From Latest Analysis:**
- 💰 Total Inventory Value: **$95,750**
- 📦 Total Products: **10**
- 🏢 Total Suppliers: **7**
- ⏰ Average Days of Stock: **46.8 days**
- 📈 Total Daily Demand: **30.8 units/day**

### Top Insights
1. **Laptop** is highest value product ($36,000 | 37.6%)
2. **TechSupply Co** is most critical supplier (43.4% of inventory)
3. **USB Cable** is fastest-moving product (15 units/day)
4. ✅ **No critical stockouts** - all products well-stocked

## 🛠️ Technologies Used

- **Python 3.14** - Core programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Openpyxl** - Excel file generation
- **NumPy** - Numerical computations

## 📁 Project Structure
```
supply-chain-analytics/
├── supply_chain.csv                      # Sample inventory data
├── inventory_analysis.py                 # Basic analysis script
├── advanced_analysis.py                  # Advanced metrics
├── visualize_analysis.py                 # Initial dashboard
├── interactive_dashboard.py              # Professional dashboard
├── export_to_excel.py                   # Excel report generator
├── generate_alerts.py                   # Alert system
├── scenario_analysis.py                 # What-if analysis
├── supply_chain_advanced_dashboard.png  # Generated dashboard
└── README.md                            # This file
```

## 🚀 How to Use

### Prerequisites
```bash
pip install pandas matplotlib seaborn openpyxl
```

### Run Analysis Scripts

**Basic Analysis:**
```bash
python inventory_analysis.py
```

**Advanced Metrics:**
```bash
python advanced_analysis.py
```

**Interactive Dashboard (Recommended):**
```bash
python interactive_dashboard.py
```
Generates: `supply_chain_advanced_dashboard.png`

**Excel Reports:**
```bash
python export_to_excel.py
```
Generates: `supply_chain_report_[timestamp].xlsx`

**Alert System:**
```bash
python generate_alerts.py
```
Generates: `alert_[timestamp].txt` and `daily_report_[timestamp].txt`

**Scenario Analysis:**
```bash
python scenario_analysis.py
```

## 📈 Outputs Generated

Each script produces different outputs:

| Script | Output Type | Use Case |
|--------|------------|----------|
| interactive_dashboard.py | PNG image | Executive presentations |
| export_to_excel.py | XLSX file | Stakeholder reports |
| generate_alerts.py | TXT files | Email distribution |
| scenario_analysis.py | Console output | Decision support |

## 💡 Key Insights from Analysis

### Current State (✅ Healthy)
- All products have adequate stock (>14 days)
- Inventory value is optimized
- Supplier relationships are balanced
- No immediate stockout risks

### Strategic Recommendations

1. **Supplier Concentration Risk**
   - TechSupply Co supplies 43.4% of inventory
   - Recommendation: Negotiate better delivery terms or diversify

2. **Product Optimization**
   - USB Cable is cash cow (15 units/day)
   - Laptop is high-value ($36,000)
   - Monitor is valuable and stable
   - Recommendation: Ensure USB Cable never stockouts

3. **Cost Reduction Opportunity**
   - 10% cost reduction could save $9,575 annually
   - 15% inventory reduction could free up $14,362 in capital

4. **Demand Planning**
   - USB Cable: 15 units/day (monitor closely)
   - Prepare for 20% demand surge on top products

## 📊 Business Impact

This system enables supply chain managers to:
- ✅ **Prevent Stockouts** - Identify products at risk before shortage
- ✅ **Reduce Costs** - Optimize inventory levels and holding costs
- ✅ **Improve Efficiency** - Automate daily reporting and alerts
- ✅ **Make Data-Driven Decisions** - Scenario analysis and forecasting
- ✅ **Monitor Suppliers** - Track supplier performance and criticality
- ✅ **Plan for Growth** - Prepare for demand changes

## 🎓 Skills Demonstrated

### Data Analysis
- Pandas for data manipulation
- Inventory metrics calculation
- Demand pattern analysis
- Supplier performance evaluation

### Data Visualization
- Matplotlib for professional charts
- Seaborn for styled visualizations
- Color-coded risk indicators
- Executive dashboards

### Reporting & Automation
- Excel workbook generation
- Alert system creation
- Automated daily reports
- Professional formatting

### Business Intelligence
- Supply chain domain knowledge
- Inventory optimization
- Supplier analysis
- Scenario planning

### Problem Solving
- Debugging and troubleshooting
- Data quality issues
- File I/O operations
- Cross-platform compatibility

## 🔄 Next Steps / Roadmap

**Completed:**
- ✅ Data analysis and visualization
- ✅ Report generation
- ✅ Alert system
- ✅ Scenario analysis

**Future Enhancements:**
- [ ] SQL database integration
- [ ] Demand forecasting (ARIMA/Prophet)
- [ ] Interactive web dashboard (Streamlit/Dash)
- [ ] Real-time monitoring
- [ ] Machine learning predictions
- [ ] API integration

## 📝 Lessons Learned

- Importance of color-coding for quick insights
- Automation saves significant time
- Multiple output formats needed for different stakeholders
- Supply chain domain knowledge is crucial
- Data quality directly impacts decision-making

## 📧 Contact & Questions

For questions about this project:
- GitHub: github.com/K14000/supply-chain-analytics
- Email: [your-email]

## 📄 License

Open source - feel free to use and modify

---

**Project Status**: Active Development
**Last Updated**: March 22, 2026
**Version**: 1.0 - Feature Complete

*This portfolio project demonstrates professional-grade data analytics skills applied to real-world supply chain challenges.*
